<script lang="ts">
  let isActive = true;
  let isGreen = true;
  let meow = isActive ? (isGreen ? "./src/mascot.png" : "./src/mascot.png") : "./src/mascot.png";
  </script>

<div class="content">
    
    <h1> peptune: an indie creative studio </h1>
      <p>coming soon... </p>
</div>  

<style>

  .content{ 
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    height: 30vh;
    text-align: right; 
    color: rgb(179, 0, 0);
    margin-top: 10rem;
    }

  h1 {
    font-size:5rem;
    margin-left: 10vw;
    margin-right: 1vw;

  }
  p {
    margin-top: 2rem;
    font-size: 2rem;
    margin-left: 2vw;
    font-family: 'Pixel';

  }
</style>