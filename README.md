<h1> Create my own profile card </h1>
Profile card, is een visitekaartje waarmee ik mijzelf presenteerd op het world web!
In het visitekaartje maak ik duidelijk wie ik ben en wat mijn ambitities zijn. De contactgegevens staan overzichtelijk bij elkaar op de achterkant. 

<h2>Dit project is opgebouwd met behulp van de volgende tools::</h2>

* MacOS Monterey versie 12.5.1 
* Visual code
* Git
* HTML 
* CSS

<h2>Opbouw</h2>

1️⃣ Eerst gebruik je de toolkit "Emmet" om snel de basis HTML opmaak te maken. 
Vergeet niet om de Link "style.css toe te voegen. om HTML aan CSS te koppelen. 

```
<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="styles/style.css">
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile card</title>
</head>
<body>
</body>
</html>
```

2️⃣ Maak een .div. met een class .card. Dit wordt gebruikt om het matglazen effect weer te geven. Vervolgens voeg je een .div. met een class .content. Hierin wordt de overlappende schaduw met inhoud weergegeven. daaropvolgend voeg een .h1. en .p. in de .div's. elementen toe om tekst weer te geven. De icon libarary zorgt ervoor dat het icon wordt gelinkt aan het desbetreffende social media kanaal.

```
<div class="card">
 <div class="content">
  <h1>Hi, my name is Michelle</h1>
  <p>wie ben je? wat zijn je ambities?</p>
<!-- icon library  -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<!-- font icons -->
<a href="https://codepen.io/your-work/" class="fa fa-codepen"></a>
<a href="https://github.com/mcphendriks" class="fa fa-github"></a>
<a href="https://twitter.com/Michell44434706" class="fa fa-twitter"></a>
<a href="https://www.linkedin.com/in/michelle-hendriks-5a874b180/" class="fa fa-linkedin"></a>

  </div>
  </div>
```

3️⃣ Maak een achtergrondafbeelding op het body-element. Op deze achtergrond dien je te bouwen. Voeg .background-attachment. toe, om ervoor te zorgen dat de  achtergrond op volledige grootte blijft. Onderstaand zorgt ervoor dat alles in het midden wordt weergegeven. Vervolgens voeg je een .font. element toe om de tekst te voorzien van lettertype. 

```
body {
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background: #EEEEEE;
  font-family: young;
  background: url(https://media.istockphoto.com/photos/abstract-background-mock-up-scene-geometry-shape-podium-for-product-picture-id1296735563?b=1&k=20&m=1296735563&s=170667a&w=0&h=DsOkmxKp6DHOneq8WfzTTPi35vQnvtaYHlQc6uDjpOA=) no-repeat;
background-attachment: fixed;
background-size: cover;
}
```

4️⃣ Voeg het .card. element toe om ervoor de zorgen dat de positie in stand houdt. De ".box.shadow. & .backdrop-filter." pseudo-elementen geven een matglazen effect.

```
.card {
  position:relative;
  width:330px;
  height:412px;
  border-radius: 15px;
  transition:0.5s ease-out;
  box-shadow: 20px 20px 20px rgba(0, 0, 0, 0.5);
  background: rgb(128, 128, 128, .1);
  backdrop-filter: blur(5px)
}
```

5️⃣ 
```
.card .content {
  position:absolute;
  bottom:0;
  width:100%;
  height:60px;
  background: rgba(255,255,255, 0.3);
  box-sizing:border-box;
  transition: 0.5s cubic-bezier(.22,.68,0,1.71);
  transition:0.3s ease-out;
  overflow:hidden;
  padding:12px;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius:15px;
}
```

6️⃣
```
.card:hover .content {
  width:100%;
  height:60%;
  text-align:center;
  }
.card:hover {
  transform: scale(1.1);
}
```
7️⃣

```
h1 {
  font-size:18px;
  text-align:left;
  color: rgba(128, 128, 128);
  text-shadow: 0px 0px 30px #0a0909;
}

p {
  text-align:left;
  font-size: 14px;
  padding: 10px 10px;
  color: rgba(128, 128, 128)
}

p, h1 {
  margin: 0px;
  padding: 10px;
}
```
8️⃣
```
.fa {
  padding: 10px 10px;
  font-size: 10px;
  width: 15px;
  min-height: 15px;
  text-decoration: none;
  border-radius: 4px;
  margin: 10px;
}

.fa:hover {
  opacity: 0.7;
  color: rgb(255, 255, 255)
}
```

9️⃣
```
/* codepen */
.fa-codepen { 
  background: rgba(255, 255, 255, 0.5);
  color: rgb(128, 128, 128);
}
/* github */
.fa-github { 
  background: rgba(255, 255, 255, 0.5);
  color: rgb(128, 128, 128);
}
/* Twitter */
.fa-twitter {
  background: rgba(255, 255, 255, 0.5);
  color: rgb(128, 128, 128);
}

/* linkedin */
.fa-linkedin {
  background: rgba(255, 255, 255, 0.5);
  color: rgb(128, 128, 128);
}

```

<h2> THANKYOU FOR YOUR TIME AND LET'S CONTACT! </h2>
