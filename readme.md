Autocolor is a simple way to autocomplete some common colors and display the color instantly in the input field.
Example1:
'''html
<html>
 <head>
    <link rel="stylesheet" href="http://code.jquery.com/ui/1.11.3/themes/smoothness/jquery-ui.css">
    <script src="http://code.jquery.com/jquery-1.10.2.js"></script>
    <script src="http://code.jquery.com/ui/1.11.3/jquery-ui.js"></script>
    <script src="jquery.autocolor.js"></script>
    <script>
    $(function() {
      $( "#example" ).autocolor();
      });
    </script>
</head>
<body>
  <div>
      <label for="example">Enter one color:</label>
      <input type="text" id="example" value=""/>
  </div>
</body>
</html>
'''
See [Demo here](http://jsfiddle.net/Leq8w12y/14/).
