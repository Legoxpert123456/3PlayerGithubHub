<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<div class="row">
  <div class="column" style="background-color:#aaa;">
    <p>Game 1</p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <p>Game 2</p>
  </div>
  <div class="column" style="background-color:#ccc;">
    <p>Game 3</p>
  </div>
</div>

</body>
</html>
