---
title: Spell Search
---


<table>
<tr>
	<td>Name</td>
	<td><input type="text" name="SpellName" /></td>
</tr>
<tr>
	<td colspan="2">
		<button type="button" onclick="SearchSpells()">Search</button>
	</td>
</tr>
</table>

<div id="SpellSearchResults">
</div>

<script>
var SpellList

function SearchSpells() {
	var SpellName = $("input[name=SpellName]").val().trim();
	$("input[name=SpellName]").val(SpellName);

	var html = "";

	if (
		SpellName == ""
		|| SpellName.length < 3
	) {
		$("#SpellSearchResults").html("");
		alert("Please enter a value of at least length 3 to search for");
		return
	}

	$(SpellList).find("Spell").each(function(){
		if ($(this).find("Name").text().toLowerCase().includes(SpellName.toLowerCase()) == false) {
			return
		}

		html += "<hr>"
			+ "<table>"
			+ "<tr><td>Category</td><td>" + $(this).find("Category").text() + "</td></tr>"
			+ "<tr><td>Name</td><td>" + $(this).find("Name").text() + "</td></tr>"
			+ "<tr><td>Effects</td><td>" + $(this).find("Effects").text() + "</td></tr>"
			+ "<tr><td>Type</td><td>" + $(this).find("Type").text() + "</td></tr>"
			+ "<tr><td>Range</td><td>" + $(this).find("Range").text() + "</td></tr>"
			+ ($(this).find("Damage").text() != "" ? "<tr><td>Damage</td><td>" + $(this).find("Damage").text() + "</td></tr>" : "")
			+ "<tr><td>Duration</td><td>" + $(this).find("Duration").text() + "</td></tr>"
			+ "<tr><td>Drain</td><td>" + $(this).find("Drain").text() + "</td></tr>"
			+ "<tr><td>Source</td><td>" + $(this).find("Source").text() + "</td></tr>"
			+ "<tr><td>Text</td><td>" + $(this).find("Text").text() + "</td></tr>"
			+ "</table>";
	});

	$("#SpellSearchResults").html(html);
}


$(document).ready(function(){
	//Get SpellList Data
	$.get(
		"SpellList.xml"
		,function(data){
			SpellList = $(data).find("Spells");
		}
	);

	$("button").button();
	$("input[type=text]").addClass("ui-widget ui-widget-content ui-corner-all")
});
</script>
