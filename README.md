A jQuery templating plugin - created for demonstration purposes.

    $("#sometmpl")
	    .tmpl( dataObject ) // Returns a LI with all the data filled in
	    .appendTo("ul");
    
    $("#sometmpl")
	    .tmpl( arrayOfDataObjects ) // Returns multiple LIs with data filled in
	    .appendTo("ul");
    
    // Appends one LI, filled with data, into the UL
    $("ul").append( tmpl, dataObject );

    // Appends multiple LI, filled with data, into the UL
    $("ul").append( tmpl, arrayOfDataObjects );
