<!DOCTYPE html>
<html>
<head>
      <meta name='author' content='Atpail'>
    <meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Module 2 Assignment</title>
<style>
* {
  box-sizing: border-box;
}


.box {
  float: right;
  width: 28%;
  padding: 40px;
  border: 1px solid black;
  margin-left: 62;
  margin-right: 62px;
  height: 220px;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}


@media screen and (max-width: 992px) {
  .box {
    width: 100%;
  }
}


</style>
</head>
<body>

<h1 class="title-container" style="text-align: center">Our Menu</h1>


<div class="row">
  <div class="box" style="background-color:#bbb;">
      <div class='menu-title' align="right" id="Sushi" style="color: blue">Sushi</div>
    <p class='text'>Sushi is traditionally made with medium-grain white rice, though it can be prepared with brown rice or short-grain rice. It is very often prepared with seafood, such as squid, eel, yellowtail, salmon, tuna or imitation crab meat.</p>
  </div>
  <div class="box" style="background-color:#bbb;">
    <div class='menu-title' align="right" id="Beef"style="color: crimson">Beef</div>
    <p class='text'>Beef is the culinary name for meat from cattle, particularly skeletal muscle. Humans have been eating beef since prehistoric times. Beef is a source of protein and nutrients. Meat from younger cows (calves) is called veal.</p>
  </div>
  <div class="box" style="background-color:#bbb;">
    <div class='menu-title' align="right" id="Chicken"style="color: darkgreen">Chicken</div>
    <p class='text'>Chickens are one of the most common and widespread domestic animals, with a total population of 23.7 billion as of 2018, up from more than 19 billion in 2011. There are more chickens in the world than any other bird.</p>
  </div>
</div>

</body>
</html>
