<!DOCTYPE html>

<html lang="en">
  <head>
    <link rel ="stylesheet" href="project3.css"> <!--using css-->
    <title>Hiro's Page</title>
  </head>
  <body>
    <main>
      <h1>Hiro's Page</h1>
      <section>
        <h2>Hiro Photos</h2>
        <!-- TODO: Add link to cat photos -->
        <p>See more <a target="_blank" href="HIRO3IMG_.jpeg">Hiro photos</a> in our gallery.</p>
        
        <img src="hiro1IMG_2981.JPG"
        width="200"   
        height="300">  <!--This is how i adjusted the picture size-->
        
      </section>
      <section>
        <h2>List</h2>
        <h3>Things Hiro loves:</h3>
        <ul>
          <li>Treats</li>
          <li>Toys</li>
          <li>Food</li>
          <li>Hiking</li>
        </ul>
        <figure>
          <img src="HIRO3IMG_.jpeg"
          width="250"   
        height="300"
         alt="A slice of lasagna on a plate.">
          <figcaption>He <em>loves</em> walks.</figcaption>  
        </figure>
        <h3>Top 3 things he can do:</h3>
        <ol>
          <li>Sit</li>
          <li>recall when called</li>
          <li>lay down</li>
        </ol>
        <figure>
          <img src="hiro2IMG.jpeg"
          width="200"   
          height="300" 
          alt="Dog chewing on a bone.">
          <figcaption>He <strong>loves</strong> milkbones.</figcaption>  
        </figure>
      </section>
      <section>
        <h2>Cat Form</h2>
        
          <fieldset>
            <legend>Is your dog  an indoor or outdoor dog?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
          </fieldset>
          <fieldset>
            <legend>What's your dog's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
          </fieldset>
          <button type="submit">Submit</button>
        </form>
      </section>
    </main>
    <footer>
      <p>
      </p>
    </footer>
  </body>
</html>
