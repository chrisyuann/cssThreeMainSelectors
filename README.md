# cssThreeMainSelectors

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <h1>Hey</h1>
    <div class="Test1">
      <header>What's Poppin</header>
      <header>ay</header>
      <header>f</header>
      <header>k</header>
    </div>
    <div id="Test2">
      <p>new drip O_O /////////////////////////////////////////////////////</p>
    </div>
    <script src="script.js"></script>
  </body>
</html>

/*THREE MAIN SELECTORS ARE ELEMENT, CLASS, AND ID*/
* {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}


h1 {
  text-align: center;
}
/*THIS SELECTOR IS ELEMENT: any html element could be used for this selector*/

.Test1 {
  background-color: black;
  color: whitesmoke;
}
/*THIS SELECTOR IS CLASS: This selector could have multiple classes within the selector*/

#Test2 {
  text-align: justify;
  background-color: gold;
}
/*THIS SELECTOR IS ID: it's basically the same as class but for id, you can't have two id's with the same name*/

body {
  background-color: aliceblue;
}
