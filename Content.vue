<template>
  <div class="container">
      <h1>Prince Paul Banquil</h1>
      <h2>Buttons</h2>
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
          <RegularB title="Regular Message" type="regM"/>
          <RegularB title="Sad Message" type="hapM" />
      </div>
          <div class="bottom-messages">
          <RegularB title="Happy Message" type="sadM" />
          <RegularB title="Angry Message" type="angM" />
      </div>
      </div>
      <h2>Cards</h2>
      
      <div class="card-container">
      <div class="card">
        <img src="https://images.pexels.com/photos/2399840/pexels-photo-2399840.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Image 1" />
        <div class="card-info">
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1534196511436-921a4e99f297?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8aW5zcGlyYXRpb25hbCUyMG1lc3NhZ2UlMjBpbiUyMHByb2dyYW1taW5nfGVufDB8fDB8fHww&auto=format&fit=crop&w=600&q=60" alt="Image 2" />
        <div class="card-info">
        </div>
      </div>

      <div class="card">
        <img src="https://i.pinimg.com/474x/18/f5/42/18f542294802c4fb94d81498a9cb5a37.jpg" alt="Image 3" />
        <div class="card-info">
        </div>
      </div>

      <div class="card">
        <img src="https://i.pinimg.com/474x/f8/96/92/f896924dde6e6b2fc39526ecc88b7869.jpg" alt="Image 4" />
        <div class="card-info">
        </div>
      </div>
    </div>

  <br>
  <a href="/" class="bn5">Button</a>
    
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
h1 {
  border-bottom: 3px solid #000000;
  background-color: #618264;
}
.buttons {
  display: flex;
  gap: 4px;
  padding: 20px;
}
.reg {
  width: 100px;
  /* margin-left: 50px;
  margin-right: 50px; */
  padding-left: 100px;

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
  background-color: #79AC78;
}
.message-box {
display: flex;
margin-left: 40px;
}
/* Add styles for the card container */
  .card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    gap: 20px;
    height: 100px;
  }

  /* Style for each card */
  .card {
    width: calc(25% - 20px); /* Adjust the card width as needed */
    border: 1px solid #e0e0e0;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
    height: 200px;
  }

  /* Card hover effect */
  .card:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
  }

  /* Style for card images */
  .card img {
    width: 200%;
    border-radius: 10px 10px 0 0;
    height:100px;
    
  }

  /* Style for card info */
  .card-info {
    padding: 20px;
  }

  .card-info p {
    font-size: 1rem;
    color: #555;
  }

  /* Responsive styling for smaller screens */
  @media (max-width: 768px) {
    .card {
      width: calc(50% - 20px); /* Adjust for two cards per row on smaller screens */
    }
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
height: 100px;
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

.bn5 {
  padding: 0.6em 2em;
  border: none;
  outline: none;
  color: rgb(255, 255, 255);
  background: #f6ebeb;
  cursor: pointer;
  position: relative;
  z-index: 0;
  border-radius: 10px;
}

.bn5:before {
  content: "";
  background: linear-gradient(
    45deg,
    #ff0000,
    #ff7300,
    #fffb00,
    #48ff00,
    #00ffd5,
    #002bff,
    #7a00ff,
    #ff00c8,
    #ff0000
  );
  position: absolute;
  top: -2px;
  left: -2px;
  background-size: 400%;
  z-index: -1;
  filter: blur(5px);
  width: calc(100% + 4px);
  height: calc(100% + 4px);
  animation: glowingbn5 20s linear infinite;
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
  border-radius: 10px;
}

@keyframes glowingbn5 {
  0% {
    background-position: 0 0;
  }
  50% {
    background-position: 400% 0;
  }
  100% {
    background-position: 0 0;
  }
}

.bn5:active {
  color: #000;
}

.bn5:active:after {
  background: transparent;
}

.bn5:hover:before {
  opacity: 1;
}

.bn5:after {
  z-index: -1;
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: #191919;
  left: 0;
  top: 0;
  border-radius: 10px;
}

</style>