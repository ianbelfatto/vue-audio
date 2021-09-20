<template>
  <div class="home">
    <div class="logo">
      <br />
      <br />
      <img src="../assets/relaxrlogo.png" alt="" />
    </div>
    <br />
    <br />
    <table>
      <tbody>
        <tr>
          <td>
            <div>
              <div class="title"><img src="../assets/bushes.png" alt="" /></div>
              <audio controls loop class="audio-display">
                <source src="../assets/bush-rustling-sound-effect.mp3" type="audio/mpeg" />
                Your browser does not support the audio element.
              </audio>
            </div>
          </td>
          <td>
            <div>
              <div class="title"><img src="../assets/keyboard.png" alt="" /></div>
              <audio controls loop class="audio-display">
                <source src="../assets/keyboard-typing-sound.mp3" type="audio/mpeg" />
                Your browser does not support the audio element.
              </audio>
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div>
              <div class="title"><img src="../assets/citystreet.png" alt="" /></div>
              <audio controls loop class="audio-display">
                <source src="../assets/city-street.mp3" type="audio/mpeg" />
                Your browser does not support the audio element.
              </audio>
            </div>
          </td>
          <td>
            <div>
              <div class="title"><img src="../assets/ocean.png" alt="" /></div>
              <audio controls loop class="audio-display">
                <source src="../assets/ocean-waves.mp3" type="audio/mpeg" />
                Your browser does not support the audio element.
              </audio>
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div>
              <div class="title"><img src="../assets/fire.png" alt="" /></div>
              <audio controls loop class="audio-display">
                <source src="../assets/Fire-sound.mp3" type="audio/mpeg" />
                Your browser does not support the audio element.
              </audio>
            </div>
          </td>
        </tr>
        <td></td>
      </tbody>
    </table>

    <!-- <div>
      <div class="title"><img src="../assets/bushes.png" alt="" /></div>
      <audio controls loop class="audio-display">
        <source src="../assets/bush-rustling-sound-effect.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div>
      <div class="title"><img src="../assets/keyboard.png" alt="" /></div>
      <audio controls loop class="audio-display">
        <source src="../assets/keyboard-typing-sound.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div>
      <div class="title"><img src="../assets/citystreet.png" alt="" /></div>
      <audio controls loop class="audio-display">
        <source src="../assets/city-street.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div>
      <div class="title"><img src="../assets/ocean.png" alt="" /></div>
      <audio controls loop class="audio-display">
        <source src="../assets/ocean-waves.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div>
      <div class="title"><img src="../assets/fire.png" alt="" /></div>
      <audio controls loop class="audio-display">
        <source src="../assets/Fire-sound.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div> -->
    <br />
    <br />
    <!-- NOTES -->
    <div>
      <p>
        Relaxr (an audio relaxation web app),
        <br />
        built by Ian Belfatto
      </p>
    </div>
    <div>
      <p>
        using:
        <i>
          Vue.js, HTML, CSS,
          <br />
          Photoshop, FreeSoundLibrary
        </i>
      </p>
      <p>
        Message me on
        <a
          class="social-link"
          href="https://www.linkedin.com/in/ianbelfatto/"
          style="color: blue; opacity: 100%"
          target="_blank"
        >
          Linkedin
          <br />
        </a>
        to suggest new sounds!
      </p>
    </div>
    <br />
    <!-- SOCIAL LINKS -->
    <div>
      <a class="social-link" href="https://github.com/ianbelfatto" style="color: black" target="_blank">My GitHub</a>
    </div>
  </div>
</template>

<style>
@media only screen and (max-width: 548px) {
  /* Mobile Phones */
  [class*="audio-display"] {
    height: 50px;
    width: 150px;
    align-content: center;
    margin-bottom: 8px;
  }
}

@media only screen and (max-width: 321px) {
  /* Mobile Phones */
  [class*="logo"] {
    height: 50px;
    width: 325px;
    display: block;
    align-content: center;
    margin-bottom: 30px;
  }
}

@media only screen and (max-width: 321px) {
  /* Mobile Phones */
  [class*="title"] {
    height: 50px;
    width: 325px;
    display: block;
    align-content: center;
    margin-bottom: 2px;
  }
}

p {
  font-family: "SF Mono", sans-serif;
  font-weight: 800;
  font-size: 12px;
  opacity: 50%;
}

table {
  margin-left: auto;
  margin-right: auto;
}

audio {
  width: 150px;
  height: 50px;
}

audio::-webkit-media-controls-panel {
  background-color: none;
}

audio::-webkit-media-controls-play-button {
  background-color: whitesmoke;
  border-radius: 100%;
}

audio::-webkit-media-controls-timeline {
  display: none;
}

audio::-webkit-media-controls-current-time-display,
audio::-webkit-media-controls-time-remaining-display {
  display: none;
}

.social-link {
  padding-left: 4px;
  padding-right: 4px;
  font-family: "SF Mono";
  font-size: 12px;
  font-weight: 800;
  /* text-decoration: none; */
}
</style>
