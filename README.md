# Bootstrap Rating

Bootstrap Rating is a jQuery plugin that creates a rating control that uses Bootstrap [glyphicons](http://glyphicons.com/) for rating symbols.

## Dependencies

Bootstrap Rating depends on [jQuery](http://jquery.com/) and Bootstrap for the rating symbols. Actually, it depends on the glyphs in font format that Bootstrap provides. 

    <link href="dist/css/bootstrap.css" rel="stylesheet">
    <script type="text/javascript" src="dist/js/jquery-1.10.2.js"></script>
    <script type="text/javascript" src="bootstrap-rating.js"></script>  

## Usage

Bootstrap Rating uses a text input to keep the rating value. This value corresponds to the 0-based index of the selected rating.

    <input type="text" class="rating"/>

Any rating plugin is implicitly initialized if the *bootstrap-rating.js* is loaded after the *rating* inputs:

    <body>
        <input type="text" class="rating"/>
        <script type="text/javascript" src="bootstrap-rating.js"></script>
    </body>

Also it can be explicitly initialized just calling *.rating()* on the desired input:

    $('input[type=text].rating').rating()

