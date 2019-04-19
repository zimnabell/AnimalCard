<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>Cat Trading Cards</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <div id="container">
<h1>Cat</h1>

<img src="cat.jpeg" alt="Cat">
<div id="card" class="animal-info">
  <p id="interesting-fact" class="animal-info">Cats have flexible bodies and teeth adapted for hunting small animals such as mice and rats.</p>
  <ul id="facts">
    <li>
      <span>Scientific Name</span>: Felis catus
    </li>
    <li>
      <span>Average Length</span>: 46 cm
    </li>
    <li>
      <span>Average Lifespan</span>: 15 years
    </li>
    <li>
      <span>Mass</span>: 10 kg
    </li>
  </ul>
  <p id="summary">Cats are beautiful creatures, some are pet and some are non-pets, cats are brought up for their ability to catch mice, cats eat dry food, drink milk and water, I love cats ♥
  </p>
</div>
  </div>
</body>

</html>


/* add your CSS here */
html {
   font-family: Arial,  Helvatica, sans-serif;
}
.animal-info, #facts {
	font-style: italic;
}
span {
	font-weight: bold;
	font-style: normal;
}
li {
	list-style-type: none;
}
img, #card{
	border: 1px solid gray;
	margin: 5px;
}
#container {
	width: 320px;
	border: 1px solid gray;
	padding: 5px 5px 5px;
	margin: 5px;
}
#card {
	padding: 5px 5px 5px;
}
#summary {
	list-style-type: none;
    font-style: normal;
}