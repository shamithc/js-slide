###  Basics
1. $(document).ready(function()
2.						 DOM and Querying the DOM


```javascript
<!-- html -->

<ul id="notes">
	<li></li>
	<li></li>
	<ul>
		<li></li>
	</ul>
</ul>

$('#notes').find('li');  // [li, li, li]
$('#notes').children('li');  // [li, li]

// parent()
// closest()
// next()
// prev()


```