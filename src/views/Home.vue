<template>
  <div class="home">
    <div class="logo">
      <img src="../assets/relaxrlogot.png" alt="" />
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
</style>
