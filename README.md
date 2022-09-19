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
2️⃣ Maak een .div. met een class .card. Dit wordt gebruikt om het matglazen effect weer te geven. Vervolgens voeg je een .div. met een class .content. Hierin wordt de overlappende schaduw met inhoud weergegeven. daaropvolgend voeg een .h1. en .p. in de .div's. elementen toe om tekst weer te geven. 

```
<div class="card">
 <div class="content">
  <h1>Hi, my name is Michelle</h1>
  <p>Jezelf voorstellen, wie ben je?</p>
```

3️⃣ Maak een achtergrondafbeelding op het body-element. Op deze achtergrond dien je te bouwen. 

```
 background: url(https://images.unsplash.com/photo-1544306094-e2dcf9479da3) no-repeat;
  /* Keep the inherited background full size. */
  background-attachment: fixed; 
  background-size: cover;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  font-family: sans-serif;
```




<h2>BEDANKT VOOR JE TIJD EN VOEL JE VRIJ OM CONTACT OP TE NEMEN! </h2>
