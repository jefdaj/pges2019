---
title: Organizers
...

<!-- TODO move to CSS and unify with all pages -->
<!-- TODO and make this a template -->
<div style="max-width: 750px;">
<ul class="personList">
$for(people)$
$partial("templates/person.html")$
$endfor$
</ul>
</div>