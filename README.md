<!DOCTYPE html> 
theme: midnight 
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CatPhotoApp</title>
</head>
<body>
  <main>
<section>
  <h1>CatPhotoApp</h1>
  <h2>Cat Photos</h2> 
  <!-- TODO: Add more links to cat photos -->
  <p>See more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a> in our gallery</p>
  
  <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back"></a> 
</section>
<section>
  <h2>Cat Lists</h2>
  <h3>Things cats love:</h3>
  <ul>
    <li>cat nip</li>
    <li>laser pointer</li>
    <li>lasagna</li>
  </ul>
 <figure>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate"> 
  <figcaption>Cats <em>love</em> lasagna</figcaption> 
</figure>
<h3>Top 3 things cats hate</h3>
<ol>
  <li>flea teeatment</li>
  <li>thunder</li>
  <li>other cats</li>
</ol>
<figure>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Fivee cats looking around a field.">
  <figcaption>Cats <strong>hate</strong> other cats</figcaption>
</figure>
</section>
<section>
  <h2>Cat Form</h2>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
  <fieldset>
   <legend>Is your cat and indoor or outdoor cat?</legend>
    <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor">Indoor</label>
    <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor">Outdoor</label>
  </fieldldset>
  <fieldset>
   <legend> What's your cat's personality?</legend>
   <input id="loving" type="checkbox" name="personality" value="loving"> <label for="loving">Loving</label>
   <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
   <input id="energetic" type="checkbox" name="persobnakity" value="energetic"> <label for="energetic">Energetic</label>
  </fieldset>
    <input type="text" name="catphotourl" placeholder="cat photo url" required>
  </form>
  <button type="submit">Submit</button>
</section>
  </main>
  <footer>
    <p>No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</p></a>
  </footer>
