###  Bind, Live, Delegate and On

```Javascript
	
	//Bind
	$('button').bind('click', function(){
		var cloned = $(this).clone()
		cloned.appendTo('body')
	});
	// Live
	$("button").live("click", function(){
		// do someting
	})

	// Replacement using ON
	$(document).on("click", 'button', function(){
  		// gobs of code
	});

	// Delegate 
	$('#context').delegate('button', 'click', function(){
		var cloned = $(this).clone()
		cloned.appendTo('#context')
	});

	// Replacement using ON
	$('#context').on('click', 'button', function(){
	 	var cloned = $(this).clone()
	 	cloned.appendTo('#context')
	});

```
