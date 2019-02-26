---
title: Spell Search
---

<table>
<tr>
	<td>Name</td>
	<td><input type="text" name="SpellName"></td>
</tr>
<tr>
	<td colspan="2">
		<button type="button" onclick="SearchSpells()">Search</button>
	</td>
</tr>
</table>

<script>
function SearchSpells() {
	var SpellName = $("input[name=SpellName]").value();
	alert(SpellName);
}


$(document).ready(function(){
	$("button").button();
});
</script>
