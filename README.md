# My first project on my own with html


<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="style.css" />
    <link
      href="https://fonts.googleapis.com/css?family=Open+Sans"
      rel="stylesheet"
    />
    <title>Form A Story!</title>
  </head>
  <body>
    <section id="top">
      <img
        src="https://content.codecademy.com/courses/learn-html-forms/formAStoryLogo.svg"
        alt="Form A Story Logo"
      />
    </section>

    
    
      
        <section id="main">
      <h1>
        Complete the Form -<br />
        Complete the Story!
      </h1>
      <hr />
      <form action="story.html" method="GET">
        <label for="animal-1">Animal:</label>
        <input id="animal-1" type="text" name="animal-1" required placeholder="e.g., lion" />
        <br />
        <label for="animal-2">Another Animal:</label>
        <input id="animal-2" name="animal-2" type="text" required placeholder="e.g., tiger"/>
        <br />
        <label for="animal-3">One More Animal:</label>
        <input type="text" id="animal-3" name="animal-3" required />
        <br />
        <label for="adj-1">Adjective (ends in -ed):</label>
        <input type="text" name="adj-1" id="adj-1" required />
        <br />
        <label for="verb-1">Verb (ends in -ing):</label>
        <input type="text" name="verb-1" id="verb-1" required />
        <br />
        <label for="num-1">Number:</label>
        <input type="number" name="num-1" id="num-1" required min="1" />
        <br />
        <span>Yes or No:</span>
        <input id="yes" type="radio" name="answer" value="yes" required />
        <label for="yes">Yes</label>
        <input id="no" type="radio" name="answer" value="no" required />
        <label for="no">No</label>
        <br />
        <label for="speed">Relative speed:</label>
        <select id="speed" name="speed" required>
        <option value="fastest">Fastest</option>
        <option value="faster">Faster</option>
        <option value="slowest">Slowest</option>
        <option value="slower">Slower</option>
        </select>
        <br />
        <label for="quote">Motivational Quote:</label>
        <input id="quote" name="quote" type="text" required list="quote-choices" />
        <datalist id="quote-choices">
          <option value=" 1st place winner gets tickets to the movies"></option>
          <option value="2nd place gets 5 dollar gift certificate"></option>
          <option value="3rd place gets a free candy bar"></option>
        </datalist>
        <br />
        <label for="message">Meaningful Message:</label>
        <textarea id="message" name="message" required rows="8" cols=40></textarea>
        <br /><br />
        <input type="submit" value="Form My Story!" />
      </form>
    </section>
  </body>
</html>
