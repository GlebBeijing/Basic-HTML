<!DOCTYPE html>
<html>
    <head>
      <h2>CatPhotoApp</h2>
    </head>
  <main>
    <p>Click here to view more <a href="#">cat photos</a>.</p>
    <body>
      <p>Things cats love:</p>
      <ul>
        <li>cat nip</li>
        <li>laser pointers</li>
        <li>lasagna</li>
      </ul>
      <p>Top 3 things cats hate:</p>
      <ol>
        <li>flea treatment</li>
        <li>thunder</li>
        <li>other cats</li>
      </ol>
      <form action="https://www.freecatphotoapp.com/submit-cat-photo">
        <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor"> Indoor</label>
        <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor"> Outdoor</label><br>
        <label for="loving"><input id="loving" type="checkbox" name="personality"> Loving</label>
        <label for="lazy"><input id="lazy" type="checkbox" name="personality"> Lazy</label>
        <label for="energetic"><input id="energetic" type="checkbox" name="personality"> Energetic</label><br>
        <input type="text" placeholder="cat photo URL" required>
        <button type="submit">Submit</button>
      </form>
    </body>
  </main>
</html>
