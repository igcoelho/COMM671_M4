<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Profession WebDeveloper</title>
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <a href="./home.html">
            <li>Home</li>
          </a>
          <a href="./photos.html">
            <li>Photos</li>
          </a>
          <a href="./trips.html">
            <li>Trips</li>
          </a>
          <a href="./contacts.html" target="_blank">
            <li>Contacts</li>
          </a>
        </ul>
      </nav>
    </header>
    <main>
      <h1>Initial Structure</h1>
      <h2>Main Information</h2>
      <div class="first" id="red">
        <label for="email">E-m@il</label>
        <form action="./index.html">
          <input
            style="display: block"
            id="e-mail"
            type="text"
            name="email"
            placeholder="Enter a valid e-mail"
          />
          <label for="email">Password</label>
          <input
            style="display: block"
            id="password"
            type="password"
            name="email"
            placeholder="Enter your password"
          />
          <label for="text">Phrase</label>
          <input
            style="display: block"
            id="text"
            type="text"
            name="email"
            placeholder="Enter your favorite Phrase"
          />
          <label for="CheckBox">Checkbox</label>
          <input
            style="display: block"
            id="checkbox"
            type="CheckBox"
            name="email"
          />
          <label for="radio">Male</label>
          <input
            style="display: block"
            id="radio"
            type="radio"
            name="genre"
            value="male"
          />
          <label for="radio">Female</label>
          <input
            style="display: block"
            id="radio"
            type="radio"
            name="genre"
            value="female"
          />
          <label for="range">Range</label>
          <input
            style="display: block"
            id="range"
            type="range"
            name="range"
            placeholder="Enter a valid e-mail"
          />
          <label for="number">Number</label>
          <input
            style="display: block"
            id="number"
            type="text"
            name="email"
            placeholder="Enter a number"
          />
          <label for="file">File</label>
          <input
            style="display: block"
            id="file"
            type="text"
            name="email"
            placeholder="Add the File"
          />
          <label for="date">Date</label>
          <input
            style="display: block"
            id="date"
            type="text"
            name="email"
            placeholder="Enter a valid date"
          />
          <select style="display: block" name="Weekday" id="">
            <option value="Sunday">Sunday</option>
            <option value="Monday">Monday</option>
            <option value="Tuesday">Tuesday</option>
            <option value="Wednesday">Wednesday</option>
            <option value="Thursday">Thursday</option>
            <option value="Friday">Friday</option>
            <option value="Saturday">Saturday</option>
          </select>
          <textarea
            style="display: block"
            name="message"
            id="message"
            rows="5"
          >
          </textarea>

          <button>Submit</button>
        </form>
      </div>

      <div class="first">
        <span> <b>La</b> <i>Passion!</i> </span>
        <img
          src="./media/Gigi D'Agostino - La Passion.jpg"
          style="display: flex"
          alt=""
        />

        <audio controls id="playerAudio2" style="display: flex">
          <source
            src="./audios/Gigi D'Agostino - La Passion.mp3"
            type="audio/mp3"
          />
          Your navigator doesn't support this type of media.
        </audio>

        <button onclick="document.getElementById('playerAudio2').play()">
          Play
        </button>
        <button onclick="document.getElementById('playerAudio2').pause()">
          Pause
        </button>

        <video
          controls
          id="playerVideo2"
          style="display: flex; width: 50%; border-radius: 10px"
        >
          <source
            src="./videos/Gigi D'Agostino - La Passion.mp4"
            type="video/mp4"
          />
          Your navigator doesn't support this type of media.
        </video>

        <button onclick="document.getElementById('playerVideo2').play()">
          Play
        </button>
        <button onclick="document.getElementById('playerVideo2').pause()">
          Pause
        </button>

        <iframe style="display: block" src="./contacts.html">CONTACTS</iframe>
    </main>

    <aside></aside>

    <footer>
      <div id="div1" style="display: block">
        <div id="div2" style="display: block">Son</div>
      </div>
      
      <div id="div3" style="display: block">

      </div>

      <div id="div4" style="display: block">

      </div>

      <div id="div5" style="display: block">
        <div id="div55" style="display: block">

        </div>

      </div>

      <div id="div6" style="display: block">

      </div>

    </footer>

    <script>
      alert('It is a JS code');
    </script>
  </body>
</html>
