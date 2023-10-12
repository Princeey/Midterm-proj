<template>
  <div class="container">
      <h2>Prince Paul Banquil</h2>
      <h4>Buttons</h4>
      <div class="buttons">
          <div class="reg">
          <RegularB style="flex: 1; text-align: center" title="Regular" type="regular" />
      </div>
      <div class="hap">
          <RegularB style="flex: 1; text-align: center" title="Happy" type="happy" />
      </div>
          <div class="sad">
          <RegularB style="flex: 1; text-align: center" title="Sad" type="sad" />
      </div>
          <div class="ang">
          <RegularB style="flex: 1; text-align: center" title="Angry" type="angry" />
      </div>
      </div>

      <div class="message-box">
          <div class="top-messages">
          <RegularB title="Regular Message" type="regM" />
          <RegularB title="Sad Message" type="hapM" />
      </div>
          <div class="bottom-messages">
          <RegularB title="Happy Message" type="sadM" />
          <RegularB title="Angry Message" type="angM" />
      </div>
      </div>
      <h4>Cards</h4>
      <div class="cards">
          <div class="first">
            <div class="cardd">
              <img src="" alt="">
<div class="card__content">
  <p class="card__title"></p>
  <p class="card__description"></p>
</div>
</div>

          <!-- <h1 style="text-align: center;">Like</h1> -->
      </div>
      <div class="second">
        <div class="main">
<div class="currentplaying">
  <svg height="50px" width="50px" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" class="spotify"><radialGradient gradientUnits="userSpaceOnUse" gradientTransform="translate(0 -534)" r="43.888" cy="572.064" cx="33.34" id="ipdIa4~cOclR8yt_ClW93a"><stop stop-color="#f4e9c3" offset="0"></stop><stop stop-color="#f8eecd" offset=".219"></stop><stop stop-color="#fdf4dc" offset=".644"></stop><stop stop-color="#fff6e1" offset="1"></stop></radialGradient><path d="M51.03,37.34c0.16,0.98,1.08,1.66,2.08,1.66h5.39c2.63,0,4.75,2.28,4.48,4.96	C62.74,46.3,60.64,48,58.29,48H49c-1.22,0-2.18,1.08-1.97,2.34c0.16,0.98,1.08,1.66,2.08,1.66h8.39c1.24,0,2.37,0.5,3.18,1.32	C61.5,54.13,62,55.26,62,56.5c0,2.49-2.01,4.5-4.5,4.5h-49c-1.52,0-2.9-0.62-3.89-1.61C3.62,58.4,3,57.02,3,55.5	C3,52.46,5.46,50,8.5,50H14c1.22,0,2.18-1.08,1.97-2.34C15.81,46.68,14.89,44,13.89,44H5.5c-2.63,0-4.75-2.28-4.48-4.96	C1.26,36.7,3.36,35,5.71,35H8c1.71,0,3.09-1.43,3-3.16C10.91,30.22,9.45,29,7.83,29H4.5c-2.63,0-4.75-2.28-4.48-4.96	C0.26,21.7,2.37,20,4.71,20H20c0.83,0,1.58-0.34,2.12-0.88C22.66,18.58,23,17.83,23,17c0-1.66-1.34-3-3-3h-1.18	c-0.62-0.09-1.43,0-2.32,0h-9c-1.52,0-2.9-0.62-3.89-1.61S2,10.02,2,8.5C2,5.46,4.46,3,7.5,3h49c3.21,0,5.8,2.79,5.47,6.06	C61.68,11.92,60.11,14,57.24,14H52c-2.76,0-5,2.24-5,5c0,1.38,0.56,2.63,1.46,3.54C49.37,23.44,50.62,24,52,24h6.5	c3.21,0,5.8,2.79,5.47,6.06C63.68,32.92,61.11,35,58.24,35H53C51.78,35,50.82,36.08,51.03,37.34z" fill="url(#ipdIa4~cOclR8yt_ClW93a)"></path><linearGradient gradientUnits="userSpaceOnUse" gradientTransform="translate(0 -534)" y2="590.253" y1="530.096" x2="32" x1="32" id="ipdIa4~cOclR8yt_ClW93b"><stop stop-color="#42d778" offset="0"></stop><stop stop-color="#3dca76" offset=".428"></stop><stop stop-color="#34b171" offset="1"></stop></linearGradient><path d="M57,32c0,12.837-9.663,23.404-22.115,24.837C33.942,56.942,32.971,57,32,57	c-1.644,0-3.25-0.163-4.808-0.471C15.683,54.298,7,44.163,7,32C7,18.192,18.192,7,32,7S57,18.192,57,32z" fill="url(#ipdIa4~cOclR8yt_ClW93b)"></path><path d="M41.683,44.394c-0.365,0-0.731-0.181-1.096-0.365c-3.471-2.009-7.674-3.105-12.24-3.105	c-2.559,0-5.116,0.364-7.491,0.912c-0.365,0-0.914,0.183-1.096,0.183c-0.914,0-1.461-0.732-1.461-1.462	c0-0.913,0.547-1.463,1.279-1.643c2.923-0.732,5.846-1.096,8.951-1.096c5.116,0,9.866,1.276,13.885,3.655	c0.548,0.364,0.914,0.73,0.914,1.642C43.145,43.847,42.414,44.394,41.683,44.394z M44.241,38.181c-0.547,0-0.912-0.18-1.279-0.364	c-3.835-2.375-9.135-3.839-15.163-3.839c-2.924,0-5.664,0.366-7.674,0.916c-0.549,0.18-0.731,0.18-1.096,0.18	c-1.096,0-1.827-0.912-1.827-1.826c0-1.096,0.549-1.645,1.461-2.009c2.74-0.73,5.481-1.279,9.317-1.279	c6.213,0,12.241,1.463,16.991,4.384c0.73,0.364,1.096,1.096,1.096,1.826C46.069,37.269,45.337,38.181,44.241,38.181z M47.165,30.876	c-0.548,0-0.731-0.182-1.279-0.364c-4.385-2.559-10.961-4.021-17.356-4.021c-3.289,0-6.577,0.366-9.5,1.096	c-0.366,0-0.731,0.182-1.279,0.182c-1.279,0.183-2.193-0.912-2.193-2.192c0-1.279,0.731-2.009,1.644-2.192	c3.471-1.096,7.125-1.462,11.327-1.462c6.943,0,14.25,1.462,19.731,4.567c0.73,0.366,1.278,1.096,1.278,2.193	C49.357,29.961,48.442,30.876,47.165,30.876z" fill="#fff"></path></svg>
  <p class="heading">Currently Playing</p>
</div>
<div class="loader">
  <div class="song">
    <p class="name">About You</p>
    <p class="artist">The 1975</p>
  </div>
  <div class="albumcover"></div>
  <div class="loading">
    <div class="load"></div>
    <div class="load"></div>
    <div class="load"></div>
    <div class="load"></div>
  </div>
</div>
<div class="loader">
  <div class="song">
    <p class="name">Sino</p>
    <p class="artist">Unique Salonga</p>
  </div>
  <div class="albumcover"></div>
  <div class="play"></div>
</div>
<div class="loader">
  <div class="song">
    <p class="name">Robbers</p>
    <p class="artist">The 1975</p>
  </div>
  <div class="albumcover"></div>
  <div class="play"></div>
</div>
</div>
      </div>
      <div class="third">
        <div class="task" draggable="true">
<div class="tags">
  <span class="tag">Draggable</span>
  <button class="options">
    <svg xml:space="preserve" viewBox="0 0 41.915 41.916" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" id="Capa_1" version="1.1" fill="#000000"><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"> <g> <g> <path d="M11.214,20.956c0,3.091-2.509,5.589-5.607,5.589C2.51,26.544,0,24.046,0,20.956c0-3.082,2.511-5.585,5.607-5.585 C8.705,15.371,11.214,17.874,11.214,20.956z"></path> <path d="M26.564,20.956c0,3.091-2.509,5.589-5.606,5.589c-3.097,0-5.607-2.498-5.607-5.589c0-3.082,2.511-5.585,5.607-5.585 C24.056,15.371,26.564,17.874,26.564,20.956z"></path> <path d="M41.915,20.956c0,3.091-2.509,5.589-5.607,5.589c-3.097,0-5.606-2.498-5.606-5.589c0-3.082,2.511-5.585,5.606-5.585 C39.406,15.371,41.915,17.874,41.915,20.956z"></path> </g> </g> </g></svg>
  </button>
</div>
<p>"It's okay not to be okay, as long as you are not giving up. You don't have to be strong all the time." - Mitsuha Miyamizu (Your Name) </p>
<div class="stats">
  <div>
    <div><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"> <path stroke-linecap="round" stroke-width="2" d="M12 8V12L15 15"></path> <circle stroke-width="2" r="9" cy="12" cx="12"></circle> </g></svg>Feb 24</div>
    <div><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"> <path stroke-linejoin="round" stroke-linecap="round" stroke-width="1.5" d="M16 10H16.01M12 10H12.01M8 10H8.01M3 10C3 4.64706 5.11765 3 12 3C18.8824 3 21 4.64706 21 10C21 15.3529 18.8824 17 12 17C11.6592 17 11.3301 16.996 11.0124 16.9876L7 21V16.4939C4.0328 15.6692 3 13.7383 3 10Z"></path> </g></svg>18</div>
    <div><svg fill="#000000" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="-2.5 0 32 32"><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"> <g id="icomoon-ignore"> </g> <path fill="#000000" d="M0 10.284l0.505 0.36c0.089 0.064 0.92 0.621 2.604 0.621 0.27 0 0.55-0.015 0.836-0.044 3.752 4.346 6.411 7.472 7.060 8.299-1.227 2.735-1.42 5.808-0.537 8.686l0.256 0.834 7.63-7.631 8.309 8.309 0.742-0.742-8.309-8.309 7.631-7.631-0.834-0.255c-2.829-0.868-5.986-0.672-8.686 0.537-0.825-0.648-3.942-3.3-8.28-7.044 0.11-0.669 0.23-2.183-0.575-3.441l-0.352-0.549-8.001 8.001zM1.729 10.039l6.032-6.033c0.385 1.122 0.090 2.319 0.086 2.334l-0.080 0.314 0.245 0.214c7.409 6.398 8.631 7.39 8.992 7.546l-0.002 0.006 0.195 0.058 0.185-0.087c2.257-1.079 4.903-1.378 7.343-0.836l-13.482 13.481c-0.55-2.47-0.262-5.045 0.837-7.342l0.104-0.218-0.098-0.221-0.031 0.013c-0.322-0.632-1.831-2.38-7.498-8.944l-0.185-0.215-0.282 0.038c-0.338 0.045-0.668 0.069-0.981 0.069-0.595 0-1.053-0.083-1.38-0.176z"> </path> </g></svg>7</div>
  </div>
  <div class="viewer">
    <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"> <path stroke-width="2" stroke="#ffffff" d="M17 8C17 10.7614 14.7614 13 12 13C9.23858 13 7 10.7614 7 8C7 5.23858 9.23858 3 12 3C14.7614 3 17 5.23858 17 8Z"></path> <path stroke-linecap="round" stroke-width="2" stroke="#ffffff" d="M3 21C3.95728 17.9237 6.41998 17 12 17C17.58 17 20.0427 17.9237 21 21"></path> </g></svg></span>
    <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"> <path stroke-width="2" stroke="#ffffff" d="M17 8C17 10.7614 14.7614 13 12 13C9.23858 13 7 10.7614 7 8C7 5.23858 9.23858 3 12 3C14.7614 3 17 5.23858 17 8Z"></path> <path stroke-linecap="round" stroke-width="2" stroke="#ffffff" d="M3 21C3.95728 17.9237 6.41998 17 12 17C17.58 17 20.0427 17.9237 21 21"></path> </g></svg></span>
    <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"> <path stroke-width="2" stroke="#ffffff" d="M17 8C17 10.7614 14.7614 13 12 13C9.23858 13 7 10.7614 7 8C7 5.23858 9.23858 3 12 3C14.7614 3 17 5.23858 17 8Z"></path> <path stroke-linecap="round" stroke-width="2" stroke="#ffffff" d="M3 21C3.95728 17.9237 6.41998 17 12 17C17.58 17 20.0427 17.9237 21 21"></path> </g></svg></span>
    <span>+20</span>
</div>
</div>

</div>
      </div>
      <div class="fourth">
        <div class="cardd">
<div class="top">
  <div class="pfp">
    <div class="playing">
      <div class="greenline line-1"></div>
      <div class="greenline line-2"></div>
      <div class="greenline line-3"></div>
      <div class="greenline line-4"></div>
      <div class="greenline line-5"></div>
    </div>
  </div>
  <div class="texts">
    <p class="title-1">I Wanna Be Yours</p>
    <p class="title-2">Arctic Monkeys</p>
  </div>
</div>

<div class="controls">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" height="20" width="24" class="volume_button">
    <path clip-rule="evenodd" d="M11.26 3.691A1.2 1.2 0 0 1 12 4.8v14.4a1.199 1.199 0 0 1-2.048.848L5.503 15.6H2.4a1.2 1.2 0 0 1-1.2-1.2V9.6a1.2 1.2 0 0 1 1.2-1.2h3.103l4.449-4.448a1.2 1.2 0 0 1 1.308-.26Zm6.328-.176a1.2 1.2 0 0 1 1.697 0A11.967 11.967 0 0 1 22.8 12a11.966 11.966 0 0 1-3.515 8.485 1.2 1.2 0 0 1-1.697-1.697A9.563 9.563 0 0 0 20.4 12a9.565 9.565 0 0 0-2.812-6.788 1.2 1.2 0 0 1 0-1.697Zm-3.394 3.393a1.2 1.2 0 0 1 1.698 0A7.178 7.178 0 0 1 18 12a7.18 7.18 0 0 1-2.108 5.092 1.2 1.2 0 1 1-1.698-1.698A4.782 4.782 0 0 0 15.6 12a4.78 4.78 0 0 0-1.406-3.394 1.2 1.2 0 0 1 0-1.698Z" fill-rule="evenodd"></path>
  </svg>
  <div class="volume">
    <div class="slider">
      <div class="green"></div>
    </div>
    <div class="circle"></div>
  </div>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" height="24" width="24">
    <path clip-rule="evenodd" d="M12 21.6a9.6 9.6 0 1 0 0-19.2 9.6 9.6 0 0 0 0 19.2Zm.848-12.352a1.2 1.2 0 0 0-1.696-1.696l-3.6 3.6a1.2 1.2 0 0 0 0 1.696l3.6 3.6a1.2 1.2 0 0 0 1.696-1.696L11.297 13.2H15.6a1.2 1.2 0 1 0 0-2.4h-4.303l1.551-1.552Z" fill-rule="evenodd"></path>
  </svg>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" height="24" width="24">
    <path clip-rule="evenodd" d="M21.6 12a9.6 9.6 0 1 1-19.2 0 9.6 9.6 0 0 1 19.2 0ZM8.4 9.6a1.2 1.2 0 1 1 2.4 0v4.8a1.2 1.2 0 1 1-2.4 0V9.6Zm6-1.2a1.2 1.2 0 0 0-1.2 1.2v4.8a1.2 1.2 0 1 0 2.4 0V9.6a1.2 1.2 0 0 0-1.2-1.2Z" fill-rule="evenodd"></path>
  </svg>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" height="24" width="24">
    <path clip-rule="evenodd" d="M12 21.6a9.6 9.6 0 1 0 0-19.2 9.6 9.6 0 0 0 0 19.2Zm4.448-10.448-3.6-3.6a1.2 1.2 0 0 0-1.696 1.696l1.551 1.552H8.4a1.2 1.2 0 1 0 0 2.4h4.303l-1.551 1.552a1.2 1.2 0 1 0 1.696 1.696l3.6-3.6a1.2 1.2 0 0 0 0-1.696Z" fill-rule="evenodd"></path>
  </svg>
  <div class="air"></div>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="2" stroke-linejoin="round" stroke-linecap="round" class="heart" stroke="currentColor" fill="none" height="20" width="24">
    <path d="M3.343 7.778a4.5 4.5 0 0 1 7.339-1.46L12 7.636l1.318-1.318a4.5 4.5 0 1 1 6.364 6.364L12 20.364l-7.682-7.682a4.501 4.501 0 0 1-.975-4.904Z">
    </path>
  </svg>
</div>
<div class="song-time">
  <p class="timetext time_now">1:31</p>
  <div class="time">
    <div class="elapsed"></div>
  </div>
  <p class="timetext time_full">3:46</p>
</div>
</div>
      </div>
  </div>
  <br>
  <div class="but">
  <a href="#"><button>Button
<div class="star-1">
  <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53" style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd" version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><defs></defs><g id="Layer_x0020_1"><metadata id="CorelCorpID_0Corel-Layer"></metadata><path d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z" class="fil0"></path></g></svg>
</div>
<div class="star-2">
  <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53" style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd" version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><defs></defs><g id="Layer_x0020_1"><metadata id="CorelCorpID_0Corel-Layer"></metadata><path d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z" class="fil0"></path></g></svg>
</div>
<div class="star-3">
  <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53" style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd" version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><defs></defs><g id="Layer_x0020_1"><metadata id="CorelCorpID_0Corel-Layer"></metadata><path d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z" class="fil0"></path></g></svg>
</div>
<div class="star-4">
  <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53" style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd" version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><defs></defs><g id="Layer_x0020_1"><metadata id="CorelCorpID_0Corel-Layer"></metadata><path d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z" class="fil0"></path></g></svg>
</div>
<div class="star-5">
  <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53" style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd" version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><defs></defs><g id="Layer_x0020_1"><metadata id="CorelCorpID_0Corel-Layer"></metadata><path d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z" class="fil0"></path></g></svg>
</div>
<div class="star-6">
  <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53" style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd" version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><defs></defs><g id="Layer_x0020_1"><metadata id="CorelCorpID_0Corel-Layer"></metadata><path d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z" class="fil0"></path></g></svg>
</div></button></a>
</div>
<div class="main">
<div class="card">
  <svg class="instagram" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0,0,256,256" width="30px" height="30px" fill-rule="nonzero"><g fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><g transform="scale(8,8)"><path d="M11.46875,5c-3.55078,0 -6.46875,2.91406 -6.46875,6.46875v9.0625c0,3.55078 2.91406,6.46875 6.46875,6.46875h9.0625c3.55078,0 6.46875,-2.91406 6.46875,-6.46875v-9.0625c0,-3.55078 -2.91406,-6.46875 -6.46875,-6.46875zM11.46875,7h9.0625c2.47266,0 4.46875,1.99609 4.46875,4.46875v9.0625c0,2.47266 -1.99609,4.46875 -4.46875,4.46875h-9.0625c-2.47266,0 -4.46875,-1.99609 -4.46875,-4.46875v-9.0625c0,-2.47266 1.99609,-4.46875 4.46875,-4.46875zM21.90625,9.1875c-0.50391,0 -0.90625,0.40234 -0.90625,0.90625c0,0.50391 0.40234,0.90625 0.90625,0.90625c0.50391,0 0.90625,-0.40234 0.90625,-0.90625c0,-0.50391 -0.40234,-0.90625 -0.90625,-0.90625zM16,10c-3.30078,0 -6,2.69922 -6,6c0,3.30078 2.69922,6 6,6c3.30078,0 6,-2.69922 6,-6c0,-3.30078 -2.69922,-6 -6,-6zM16,12c2.22266,0 4,1.77734 4,4c0,2.22266 -1.77734,4 -4,4c-2.22266,0 -4,-1.77734 -4,-4c0,-2.22266 1.77734,-4 4,-4z"></path></g></g></svg>
</div>
<div class="card">
  <svg class="twitter" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" width="30px" height="30px"><path d="M42,12.429c-1.323,0.586-2.746,0.977-4.247,1.162c1.526-0.906,2.7-2.351,3.251-4.058c-1.428,0.837-3.01,1.452-4.693,1.776C34.967,9.884,33.05,9,30.926,9c-4.08,0-7.387,3.278-7.387,7.32c0,0.572,0.067,1.129,0.193,1.67c-6.138-0.308-11.582-3.226-15.224-7.654c-0.64,1.082-1,2.349-1,3.686c0,2.541,1.301,4.778,3.285,6.096c-1.211-0.037-2.351-0.374-3.349-0.914c0,0.022,0,0.055,0,0.086c0,3.551,2.547,6.508,5.923,7.181c-0.617,0.169-1.269,0.263-1.941,0.263c-0.477,0-0.942-0.054-1.392-0.135c0.94,2.902,3.667,5.023,6.898,5.086c-2.528,1.96-5.712,3.134-9.174,3.134c-0.598,0-1.183-0.034-1.761-0.104C9.268,36.786,13.152,38,17.321,38c13.585,0,21.017-11.156,21.017-20.834c0-0.317-0.01-0.633-0.025-0.945C39.763,15.197,41.013,13.905,42,12.429"></path></svg>
</div>
<div class="card">
  <svg class="dribble" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40 40" width="30px" height="30px"><path d="M20,38.5C9.799,38.5,1.5,30.201,1.5,20S9.799,1.5,20,1.5S38.5,9.799,38.5,20S30.201,38.5,20,38.5z"></path><path fill="#ea4c89" d="M20,2c9.925,0,18,8.075,18,18s-8.075,18-18,18S2,29.925,2,20S10.075,2,20,2 M20,1 C9.507,1,1,9.507,1,20s8.507,19,19,19s19-8.507,19-19S30.493,1,20,1L20,1z"></path><path fill="none" stroke="#ea4c89" stroke-miterlimit="10" d="M28.352 36.914c0 0-3.032-21.087-15.63-34.292M1.269 17.848c0 0 24.2 2.117 32.075-11.102M7.804 34.152c0 0 8.624-19.807 31.058-12.194"></path></svg>
</div>
<div class="card">
  <svg class="codepen" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50" width="30px" height="30px"><path d="M 25 4 L 4 17.34375 L 4 32.652344 L 25 46 L 46 32.65625 L 46 17.34375 Z M 25 29.183594 L 19.066406 25.070313 L 25 21.023438 L 30.933594 25.070313 Z M 27 17.605469 L 27 9.949219 L 40.429688 18.484375 L 34.410156 22.65625 Z M 23 17.605469 L 15.589844 22.65625 L 9.570313 18.484375 L 23 9.949219 Z M 12.09375 25.042969 L 8 27.832031 L 8 22.203125 Z M 15.570313 27.453125 L 23 32.605469 L 23 40.050781 L 9.589844 31.527344 Z M 27 32.605469 L 34.429688 27.453125 L 40.410156 31.527344 L 27 40.050781 Z M 37.90625 25.042969 L 42 22.203125 L 42 27.832031 Z"></path></svg>
</div>
<div class="card">
  <svg class="uiverse" width="23px" height="23px" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <path d="M38.0481 4.82927C38.0481 2.16214 40.018 0 42.4481 0H51.2391C53.6692 0 55.6391 2.16214 55.6391 4.82927V40.1401C55.6391 48.8912 53.2343 55.6657 48.4248 60.4636C43.6153 65.2277 36.7304 67.6098 27.7701 67.6098C18.8099 67.6098 11.925 65.2953 7.11548 60.6663C2.37183 56.0036 3.8147e-06 49.2967 3.8147e-06 40.5456V4.82927C3.8147e-06 2.16213 1.96995 0 4.4 0H13.2405C15.6705 0 17.6405 2.16214 17.6405 4.82927V39.1265C17.6405 43.7892 18.4805 47.2018 20.1605 49.3642C21.8735 51.5267 24.4759 52.6079 27.9678 52.6079C31.4596 52.6079 34.0127 51.5436 35.6268 49.4149C37.241 47.2863 38.0481 43.8399 38.0481 39.0758V4.82927Z" fill="url(#paint0_linear_501_142)"></path>
  <path d="M86.9 61.8682C86.9 64.5353 84.9301 66.6975 82.5 66.6975H73.6595C71.2295 66.6975 69.2595 64.5353 69.2595 61.8682V4.82927C69.2595 2.16214 71.2295 0 73.6595 0H82.5C84.9301 0 86.9 2.16214 86.9 4.82927V61.8682Z" fill="url(#paint1_linear_501_142)"></path>
  <path d="M2.86102e-06 83.2195C2.86102e-06 80.5524 1.96995 78.3902 4.4 78.3902H83.6C86.0301 78.3902 88 80.5524 88 83.2195V89.1707C88 91.8379 86.0301 94 83.6 94H4.4C1.96995 94 0 91.8379 0 89.1707L2.86102e-06 83.2195Z" fill="url(#paint2_linear_501_142)"></path>
  <defs>
  <linearGradient id="paint0_linear_501_142" x1="0" y1="0" x2="96.1684" y2="87.6201" gradientUnits="userSpaceOnUse">
  <stop stop-color="#BF66FF"></stop>
  <stop offset="0.510417" stop-color="#6248FF"></stop>
  <stop offset="1" stop-color="#00DDEB"></stop>
  </linearGradient>
  <linearGradient id="paint1_linear_501_142" x1="0" y1="0" x2="96.1684" y2="87.6201" gradientUnits="userSpaceOnUse">
  <stop stop-color="#BF66FF"></stop>
  <stop offset="0.510417" stop-color="#6248FF"></stop>
  <stop offset="1" stop-color="#00DDEB"></stop>
  </linearGradient>
  <linearGradient id="paint2_linear_501_142" x1="0" y1="0" x2="96.1684" y2="87.6201" gradientUnits="userSpaceOnUse">
  <stop stop-color="#BF66FF"></stop>
  <stop offset="0.510417" stop-color="#6248FF"></stop>
  <stop offset="1" stop-color="#00DDEB"></stop>
  </linearGradient>
  </defs>
  </svg>
</div>
<div class="card">
  <svg class="discord" height="30px" width="30px" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg"><path d="M40,12c0,0-4.585-3.588-10-4l-0.488,0.976C34.408,10.174,36.654,11.891,39,14c-4.045-2.065-8.039-4-15-4s-10.955,1.935-15,4c2.346-2.109,5.018-4.015,9.488-5.024L18,8c-5.681,0.537-10,4-10,4s-5.121,7.425-6,22c5.162,5.953,13,6,13,6l1.639-2.185C13.857,36.848,10.715,35.121,8,32c3.238,2.45,8.125,5,16,5s12.762-2.55,16-5c-2.715,3.121-5.857,4.848-8.639,5.815L33,40c0,0,7.838-0.047,13-6C45.121,19.425,40,12,40,12z M17.5,30c-1.933,0-3.5-1.791-3.5-4c0-2.209,1.567-4,3.5-4s3.5,1.791,3.5,4C21,28.209,19.433,30,17.5,30z M30.5,30c-1.933,0-3.5-1.791-3.5-4c0-2.209,1.567-4,3.5-4s3.5,1.791,3.5,4C34,28.209,32.433,30,30.5,30z"></path></svg>
</div>
<div class="card">
  <svg class="github" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30" width="30px" height="30px"><path d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051 c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526 c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769 c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098 c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9 c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594 c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734 c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z"></path></svg>
</div>
<div class="card">
  <svg class="telegram" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" width="30px" height="30px"><path d="M24 4A20 20 0 1 0 24 44A20 20 0 1 0 24 4Z"></path><path fill="#fff" d="M33.95,15l-3.746,19.126c0,0-0.161,0.874-1.245,0.874c-0.576,0-0.873-0.274-0.873-0.274l-8.114-6.733 l-3.97-2.001l-5.095-1.355c0,0-0.907-0.262-0.907-1.012c0-0.625,0.933-0.923,0.933-0.923l21.316-8.468 c-0.001-0.001,0.651-0.235,1.126-0.234C33.667,14,34,14.125,34,14.5C34,14.75,33.95,15,33.95,15z"></path><path fill="#b0bec5" d="M23,30.505l-3.426,3.374c0,0-0.149,0.115-0.348,0.12c-0.069,0.002-0.143-0.009-0.219-0.043 l0.964-5.965L23,30.505z"></path><path fill="#cfd8dc" d="M29.897,18.196c-0.169-0.22-0.481-0.26-0.701-0.093L16,26c0,0,2.106,5.892,2.427,6.912 c0.322,1.021,0.58,1.045,0.58,1.045l0.964-5.965l9.832-9.096C30.023,18.729,30.064,18.416,29.897,18.196z"></path></svg>
</div>
<div class="card">
  <svg class="reddit" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="30" height="30" viewBox="0 0 256 256" xml:space="preserve">
  <defs>
  </defs>
  <g style="stroke: none; border-radius:50%; stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-linejoin: miter; stroke-miterlimit: 10; fill: none; fill-rule: nonzero; opacity: 1;" transform="translate(1.4065934065934016 1.4065934065934016) scale(2.81 2.81)">
    <circle cx="45" cy="45" r="45" style="stroke: none; stroke-width: 0; stroke-dasharray: none; stroke-linecap: butt; stroke-linejoin: miter; stroke-miterlimit: 10; fill-rule: nonzero; opacity: 1;" transform="matrix(1 0 0 1 0 0)"></circle>
    <path d="M 75.011 45 c -0.134 -3.624 -3.177 -6.454 -6.812 -6.331 c -1.611 0.056 -3.143 0.716 -4.306 1.823 c -5.123 -3.49 -11.141 -5.403 -17.327 -5.537 l 2.919 -14.038 l 9.631 2.025 c 0.268 2.472 2.483 4.262 4.955 3.993 c 2.472 -0.268 4.262 -2.483 3.993 -4.955 s -2.483 -4.262 -4.955 -3.993 c -1.421 0.145 -2.696 0.973 -3.4 2.204 L 48.68 17.987 c -0.749 -0.168 -1.499 0.302 -1.667 1.063 c 0 0.011 0 0.011 0 0.022 l -3.322 15.615 c -6.264 0.101 -12.36 2.025 -17.55 5.537 c -2.64 -2.483 -6.801 -2.36 -9.284 0.291 c -2.483 2.64 -2.36 6.801 0.291 9.284 c 0.515 0.481 1.107 0.895 1.767 1.186 c -0.045 0.66 -0.045 1.32 0 1.98 c 0 10.078 11.745 18.277 26.23 18.277 c 14.485 0 26.23 -8.188 26.23 -18.277 c 0.045 -0.66 0.045 -1.32 0 -1.98 C 73.635 49.855 75.056 47.528 75.011 45 z M 30.011 49.508 c 0 -2.483 2.025 -4.508 4.508 -4.508 c 2.483 0 4.508 2.025 4.508 4.508 s -2.025 4.508 -4.508 4.508 C 32.025 53.993 30.011 51.991 30.011 49.508 z M 56.152 62.058 v -0.179 c -3.199 2.405 -7.114 3.635 -11.119 3.468 c -4.005 0.168 -7.919 -1.063 -11.119 -3.468 c -0.425 -0.515 -0.347 -1.286 0.168 -1.711 c 0.447 -0.369 1.085 -0.369 1.544 0 c 2.707 1.98 6.007 2.987 9.362 2.83 c 3.356 0.179 6.667 -0.783 9.407 -2.74 c 0.492 -0.481 1.297 -0.47 1.779 0.022 C 56.655 60.772 56.644 61.577 56.152 62.058 z M 55.537 54.34 c -0.078 0 -0.145 0 -0.224 0 l 0.034 -0.168 c -2.483 0 -4.508 -2.025 -4.508 -4.508 s 2.025 -4.508 4.508 -4.508 s 4.508 2.025 4.508 4.508 C 59.955 52.148 58.02 54.239 55.537 54.34 z" style="stroke: none; stroke-width: 1; stroke-dasharray: none; stroke-linecap: butt; stroke-linejoin: miter; stroke-miterlimit: 10; fill-rule: nonzero; opacity: 1;" transform="matrix(1 0 0 1 0 0)" stroke-linecap="round"></path>
  </g>
  </svg>
</div>
<p class="text">Social<br><br>Media<br><br>Accounts</p>

</div>
      </div>
</template>

<script>
import RegularB from './RegularB.vue';

export default {
  props: {
      person: Object
  },
  components: {
      RegularB,
  }
}

</script>

<style scoped>
img {
  width: 100%;
}
h2 {
  border-bottom: 1px solid black;
}
.buttons {
  display: flex;
  gap: 4px;
  padding: 20px;

  /* margin-left: 250px; */
}
.reg {
  width: 100px;
  /* margin-left: 50px;
  margin-right: 50px; */
  padding-left: 200px;

}
.hap {
  width: 100px;
  padding-left: 100px;
}
.hap:hover {
  cursor: pointer;
  transform: scale(1.1);
 
}
.sad {
  width: 100px;
  margin-left: 50px;
}
.sad:hover {
  cursor: pointer;
  transform: scale(1.1);
}
.ang {
  width: 100px;
  padding-left: 150px;
}
.ang:hover {
  cursor: pointer;
  transform: scale(1.1);
}
.reg:hover {
  cursor: pointer;
  transform: scale(1.1);
}
.container {
  max-width: 80%;
  border: 1px solid #888;
  padding: 12px;
  border-radius: 8px;
  box-shadow: 0px 0px 5px #888;
  margin: 16px 0;
  height: 100%;
  margin-left: 150px;
}
.message-box {
display: flex;
margin-left: 40px;
}
.cards {
  display: flex;
}
.first, .second, .third, .fourth{
width: 300px; /* Set the width of the card as needed */
height: 400px; /* Set the height of the card as needed */
border: 1px solid #ccc; /* Add border or other styling as needed */
border-radius: 10px;
overflow: hidden; /* Ensure the images stay within the card boundaries */
position: relative; /* For absolute positioning of the image container */
}
.but {

}
.cardd {
position: relative;
width: 300px;
height: 100%;
background-color: #f2f2f2;
border-radius: 10px;
display: flex;
align-items: center;
justify-content: center;
overflow: hidden;
perspective: 1000px;
box-shadow: 0 0 0 5px #ffffff80;
transition: all 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}

.cardd svg {
width: 48px;
fill: #333;
transition: all 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}

.cardd:hover {
transform: scale(1.05);
box-shadow: 0 8px 16px rgba(255, 255, 255, 0.2);
}

.card__content {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
padding: 20px;
box-sizing: border-box;
background-color: #f2f2f2;
transform: rotateX(-100deg);
transform-origin: bottom;
transition: all 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}

.cardd:hover .card__content {
transform: rotateX(0deg);
}

.card__title {
margin: 0;
font-size: 24px;
color: #333;
font-weight: 900;
}

.cardd:hover svg {
scale: 0;
}

.card__description {
margin: 90px 0 0;
font-size: 14px;
color: #777;
line-height: 1.4;
}
.main {
background-color: rgb(255, 255, 255);
padding: 0 2em;
border-radius: 15px;

width: 100%;
height: 100%;
}

.loader {
display: flex;
flex-direction: row;
height: 4em;
padding-left: 1em;
padding-right: 1em;
transform: rotate(180deg);
justify-content: right;
border-radius: 10px;
transition: .4s ease-in-out;
}

.loader:hover {
cursor: pointer;
background-color: lightgray;
}

.currentplaying {
display: flex;
margin: 1em;
}

.spotify {
width: 50px;
height: 50px;
margin-right: 0.6em;
}

.heading {
color: black;
font-size: 1em;
font-weight: bold;
align-self: center;
}

.loading {
display: flex;
margin-top: 1em;
margin-left: 0.3em;
}

.load {
width: 2px;
height: 33px;
background-color: limegreen;
animation: 1s move6 infinite;
border-radius: 5px;
margin: 0.1em;
}

.load:nth-child(1) {
animation-delay: 0.2s;
}

.load:nth-child(2) {
animation-delay: 0.4s;
}

.load:nth-child(3) {
animation-delay: 0.6s;
}

.play {
position: relative;
left: 0.35em;
height: 1.6em;
width: 1.6em;
clip-path: polygon(50% 50%, 100% 50%, 75% 6.6%);
background-color: black;
transform: rotate(-90deg);
align-self: center;
margin-top: 0.7em;
justify-self: center;
}

.albumcover {
position: relative;
margin-right: 1em;
height: 40px;
width: 40px;
background-color: rgb(233, 232, 232);
align-self: center;
border-radius: 5px;
}

.song {
position: relative;
transform: rotate(180deg);
margin-right: 1em;
color: black;
align-self: center;
}

.artist {
font-size: 0.6em;
}

@keyframes move6 {
0% {
  height: 0.2em;
}

25% {
  height: 0.7em;
}

50% {
  height: 1.5em;
}

100% {
  height: 0.2em;
}
}
.task {
position: relative;
color: #2e2e2f;
cursor: move;
background-color: #fff;
padding: 1rem;
border-radius: 8px;
box-shadow: rgba(99, 99, 99, 0.1) 0px 2px 8px 0px;
margin-bottom: 1rem;
border: 3px dashed transparent;
max-width: 350px;
height: 100%;
}

.task:hover {
box-shadow: rgba(99, 99, 99, 0.3) 0px 2px 8px 0px;
border-color: rgba(162, 179, 207, 0.2) !important;
}

.task p {
font-size: 18px;
margin: 5rem 0;
}

.tag {
border-radius: 100px;
padding: 4px 13px;
font-size: 12px;
color: #ffffff;
background-color: #1389eb;
}

.tags {
width: 100%;
display: flex;
align-items: center;
justify-content: space-between;
}

.options {
background: transparent;
border: 0;
color: #c4cad3;
font-size: 17px;
}

.options svg {
fill: #9fa4aa;
width: 20px;
}

.stats {
position: relative;
width: 100%;
color: #9fa4aa;
font-size: 12px;
display: flex;
align-items: center;
justify-content: space-between;
}

.stats div {
margin-right: 1rem;
height: 100%;
display: flex;
align-items: center;
cursor: pointer;
}

.stats svg {
margin-right: 5px;
height: 100%;
stroke: #9fa4aa;
}

.viewer span {
height: 30px;
width: 30px;
background-color: rgb(28, 117, 219);
margin-right: -10px;
border-radius: 50%;
border: 1px solid #fff;
display: grid;
align-items: center;
text-align: center;
font-weight: bold;
color: #fff;
padding: 2px;
}

.viewer span svg {
stroke: #fff;
}
/* Spotify music card made by: csozi | Website: www.csozi.hu*/

.cardd {
margin-top: 90px;
position: relative;
min-width: 250px;
min-height: 120px;
background: #191414;
border-radius: 10px;
padding: .8rem;
display: flex;
flex-direction: column;
gap: .5rem;
box-shadow: 0 10px 40px -25px rgba(100, 100, 100, .5);

}

.top {
position: relative;
width: 100%;
display: flex;
align-items: center;
gap: 10px;
margin-block-end: .5rem;
}

.pfp {
position: relative;
height: 40px;
width: 40px;
background-color: white;
border-radius: 5px;
display: flex;
justify-content: center;
align-items: center;
}

.title-1 {
color: white;
font-size: 1.25rem;
font-weight: 900;
}

.title-2 {
color: white;
font-size: .75rem;
opacity: .8;
}

/* new */
.song-time {
width: 100%;
margin-inline: auto;
position: relative;
display: flex;
align-items: center;
gap: .3rem;
}

.time {
width: 90%;
background-color: #5e5e5e;
height: .35rem;
border-radius: 3px;
}

.elapsed {
width: 42%;
background-color: #1db954;
height: 100%;
border-radius: 3px;
}

.controls {
color: white;
display: flex;
justify-content: space-evenly;
align-items: center;
width: 100%;
}

.volume {
height: 100%;
width: 48px;
}

.air {
height: 100%;
width: 48px;
}

.controls svg {
cursor: pointer;
transition: 0.1s;
}

.controls svg:hover {
color: #1db954;
}

.controls .heart:hover {
color: pink;
}

.volume {
opacity: 0;
position: relative;
transition: 0.2s;
}

.volume .slider {
height: 4px;
background-color: #5e5e5e;
width: 80%;
border-radius: 2px;
margin-left: .3rem;
}

.volume .slider .green {
background-color: #1db954;
height: 100%;
width: 80%;
border-radius: 3px;
}

.volume .circle {
background-color: white;
height: 6px;
width: 6px;
border-radius: 3px;
position: absolute;
right: 20%;
top: 50%;
transform: translateY(-50%);
}

.volume_button:hover ~ .volume {
opacity: 1;
}

.timetext {
color: white;
}

.time_now {
font-size: .8rem;
background-color: #00000060;
padding: .5rem;
border-radius: .5rem;
background-blend-mode: multiply;
}

.time_full {
font-size: .8rem;
background-color: #00000060;
padding: .5rem;
border-radius: .5rem;
background-blend-mode: multiply;
}

.playing {
display: flex;
position: relative;
justify-content: center;
gap: 1px;
width: 30px;
height: 20px;
}

.greenline {
background-color: #1db954;
height: 20px;
width: 2px;
position: relative;
transform-origin: bottom;
}

.line-1 {
animation: infinite playing 1s ease-in-out;
animation-delay: 0.2s;
}

.line-2 {
animation: infinite playing 1s ease-in-out;
animation-delay: 0.5s;
}

.line-3 {
animation: infinite playing 1s ease-in-out;
animation-delay: 0.6s;
}

.line-4 {
animation: infinite playing 1s ease-in-out;
animation-delay: 0s;
}

.line-5 {
animation: infinite playing 1s ease-in-out;
animation-delay: 0.4s;
}

@keyframes playing {
0% {
  transform: scaleY(0.1);
}

33% {
  transform: scaleY(0.6);
}

66% {
  transform: scaleY(0.9);
}

100% {
  transform: scaleY(0.1);
}
}
button {
position: relative;
padding: 12px 35px;
background: #7C81AD;
font-size: 17px;
font-weight: 500;
color: #181818;
border: 3px solid #4B527E;
border-radius: 8px;
box-shadow: 0 0 0 #7C81AD;
transition: all .3s ease-in-out;
width: 100%;
}

.star-1 {
position: absolute;
top: 20%;
left: 20%;
width: 25px;
height: auto;
filter: drop-shadow(0 0 0 #ffe100);
z-index: -5;
transition: all 1s cubic-bezier(0.05, 0.83, 0.43, 0.96);
}

.star-2 {
position: absolute;
top: 45%;
left: 45%;
width: 15px;
height: auto;
filter: drop-shadow(0 0 0 #f6e350);
z-index: -5;
transition: all 1s cubic-bezier(0, 0.4, 0, 1.01);
}

.star-3 {
position: absolute;
top: 40%;
left: 40%;
width: 5px;
height: auto;
filter: drop-shadow(0 0 0 #f9df18);
z-index: -5;
transition: all 1s cubic-bezier(0, 0.4, 0, 1.01);
}

.star-4 {
position: absolute;
top: 20%;
left: 40%;
width: 8px;
height: auto;
filter: drop-shadow(0 0 0 #ffe203);
z-index: -5;
transition: all .8s cubic-bezier(0, 0.4, 0, 1.01);
}

.star-5 {
position: absolute;
top: 25%;
left: 45%;
width: 15px;
height: auto;
filter: drop-shadow(0 0 0 #f8db05);
z-index: -5;
transition: all .6s cubic-bezier(0, 0.4, 0, 1.01);
}

.star-6 {
position: absolute;
top: 5%;
left: 50%;
width: 50px;
height: auto;
filter: drop-shadow(0 0 0 #f0d404);
z-index: -5;
transition: all .8s ease;
}

button:hover {
background: #363062;
color: #D0BFFF;
box-shadow: 0 0 25px #D0BFFF;
}

button:hover .star-1 {
position: absolute;
top: -80%;
left: -30%;
width: 70px;
height: auto;
filter: drop-shadow(0 0 10px #f7db07);
z-index: 2;
}

button:hover .star-2 {
position: absolute;
top: -25%;
left: 10%;
width: 50px;
height: auto;
filter: drop-shadow(0 0 10px #e2ea08);
z-index: 2;
}

button:hover .star-3 {
position: absolute;
top: 55%;
left: 25%;
width: 30px;
height: auto;
filter: drop-shadow(0 0 10px #f1d922);
z-index: 2;
}

button:hover .star-4 {
position: absolute;
top: 30%;
left: 80%;
width: 20px;
height: auto;
filter: drop-shadow(0 0 10px #eed832);
z-index: 2;
}

button:hover .star-5 {
position: absolute;
top: 25%;
left: 115%;
width: 15px;
height: auto;
filter: drop-shadow(0 0 10px #ffe100);
z-index: 2;
}

button:hover .star-6 {
position: absolute;
top: 5%;
left: 60%;
width: 15px;
height: auto;
filter: drop-shadow(0 0 10px #ffe100);
z-index: 2;
}

.fil0 {
fill: #f0d404
}
.main_back {
position: absolute;
border-radius: 10px;
transform: rotate(90deg);
width: 11em;
height: 11em;
background: linear-gradient(270deg, #03a9f4, #cc39a4, #ffb5d2);
z-index: -2;
box-shadow: inset 0px 0px 180px 5px #ffffff;
}

.main {
display: flex;
flex-wrap: wrap;
width: 14em;
align-items: center;
justify-content: center;
z-index: -1;
}

.card {
width: 60px;
height: 60px;
border-top-left-radius: 10px;
background: lightgrey;
transition: .4s ease-in-out, .2s background-color ease-in-out, .2s background-image ease-in-out;
background: rgba(255, 255, 255, 0.596);
backdrop-filter: blur(5px);
border: 1px solid transparent;
-webkit-backdrop-filter: blur(5px);
display: flex;
align-items: center;
justify-content: center;
}

.card .instagram {
opacity: 0;
transition: .2s ease-in-out;
fill: #cc39a4;
}

.card:nth-child(2) {
border-radius: 0px;
}

.card:nth-child(2) .twitter {
opacity: 0;
transition: .2s ease-in-out;
fill: #03A9F4;
}

.card:nth-child(3) {
border-top-right-radius: 10px;
border-top-left-radius: 0px;
}

.card:nth-child(3) .dribble {
opacity: 0;
transition: .2s ease-in-out;
fill: #ffb5d2;
}

.card:nth-child(4) {
border-radius: 0px;
}

.card:nth-child(4) .codepen {
opacity: 0;
transition: .2s ease-in-out;
fill: black;
}

.card:nth-child(5) {
border-radius: 0px;
}

.card:nth-child(5) .uiverse {
position: absolute;
margin-left: 0.2em;
margin-top: 0.2em;
opacity: 0;
transition: .2s ease-in-out;
}

.card:nth-child(6) {
border-radius: 0px;
}

.card:nth-child(6) .discord {
opacity: 0;
transition: .2s ease-in-out;
fill: #8c9eff;
}

.card:nth-child(7) {
border-bottom-left-radius: 10px;
border-top-left-radius: 0px;
}

.card:nth-child(7) .github {
opacity: 0;
transition: .2s ease-in-out;
fill: black;
}

.card:nth-child(8) {
border-radius: 0px;
}

.card:nth-child(8) .telegram {
opacity: 0;
transition: .2s ease-in-out;
fill: #29b6f6;
}

.card:nth-child(9) {
border-bottom-right-radius: 10px;
border-top-left-radius: 0px;
}

.card:nth-child(9) .reddit {
opacity: 0;
transition: .2s ease-in-out;
}

.main:hover {
width: 14em;
cursor: pointer;
}

.main:hover .main_back {
opacity: 0;
}

.main:hover .card {
margin: .2em;
border-radius: 10px;
box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
border: 1px solid rgba(255, 255, 255, 0.3);
background: rgba(255, 255, 255, 0.2);
}

.main:hover .card:nth-child(5) {
border: transparent;
}

.main:hover .text {
opacity: 0;
z-index: -3;
}

.main:hover .instagram {
opacity: 1;
}

.main:hover .twitter {
opacity: 1;
}

.main:hover .dribble {
opacity: 1;
}

.main:hover .codepen {
opacity: 1;
}

.main:hover .uiverse {
opacity: 1;
}

.main:hover .discord {
opacity: 1;
}

.main:hover .github {
opacity: 1;
}

.main:hover .telegram {
opacity: 1;
}

.main:hover .reddit {
opacity: 1;
}

.card:nth-child(1):hover {
background-color: #cc39a4;
}

.card:nth-child(1):hover .instagram {
fill: white;
}

.card:nth-child(2):hover {
background-color: #03A9F4;
}

.card:nth-child(2):hover .twitter {
fill: white;
}

.card:nth-child(3):hover {
background-color: #ffb5d2;
}

.card:nth-child(3):hover .dribble {
fill: white;
}

.card:nth-child(4):hover {
background-color: #1E1F26;
}

.card:nth-child(4):hover .codepen {
fill: white;
}

.card:nth-child(5):hover {
animation: backgroundIMG .1s;
animation-fill-mode: forwards;
}

.card:nth-child(5):hover .uiverse #paint0_linear_501_142 stop {
stop-color: white;
}

.card:nth-child(5):hover .uiverse #paint1_linear_501_142 stop {
stop-color: white;
}

.card:nth-child(5):hover .uiverse #paint2_linear_501_142 stop {
stop-color: white;
}

@keyframes backgroundIMG {
100% {
  background-image: linear-gradient(#BF66FF,#6248FF,#00DDEB);
}
}

.card:nth-child(6):hover {
background-color: #8c9eff;
}

.card:nth-child(6):hover .discord {
fill: white;
}

.card:nth-child(7):hover {
background-color: black;
}

.card:nth-child(7):hover .github {
fill: white;
}

.card:nth-child(8):hover {
background-color: #29b6f6;
}

.card:nth-child(8):hover .telegram > path:nth-of-type(1) {
fill: white;
}

.card:nth-child(8):hover .telegram > path:nth-of-type(2) {
fill: #29b6f6;
}

.card:nth-child(8):hover .telegram > path:nth-of-type(3) {
fill: #29b6f6;
}

.card:nth-child(9):hover {
background-color: rgb(255,69,0);
}

.card:nth-child(9) .reddit > g circle {
fill: rgb(255,69,0);
}

.card:nth-child(9) .reddit > g path {
fill: white;
}

.text {
position: absolute;
font-size: 0.7em;
transition: .4s ease-in-out;
color: black;
text-align: center;
font-weight: bold;
letter-spacing: 0.33em;
z-index: 3;
}

</style>