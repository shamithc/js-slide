##  Load()

```Javascript

	var loadUrl = "ajax/load.php";  
    $("#load_basic").click(function(){  
        $("#result").html(ajax_load).load(loadUrl);  
    });

    // Get - Pass parameter
    $("#load_get").click(function(){  
        $("#result")  
            .html(ajax_load)  
            .load(loadUrl, "language=php&version=5");  
    });

    // Post data
    $("#load_post").click(function(){  
    	$("#result")  
        	.html(ajax_load)  
        	.load(loadUrl, {language: "php", version: 5});  
	});     

```

