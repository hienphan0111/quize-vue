<template>
  <div class="container">
    <header>
      <h1>Quizes</h1>
      <input type="text" placeholder="search...">
    </header>
    <div class="options-container">
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsA0injQVaDOgOuEUFbm43VNAKpv65Wkcd5A&usqp=CAU" alt="">
        <div class="card-text">
          <h2>Math</h2>
          <p class="card-text">15 questions</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .container {
    max-width: 1000px;
    margin: 0 auto;
  }

  header {
    margin-bottom: 10px;
    margin-top: 30px;
    display: flex;
    align-items: center;
  }

  header h1 {
    font-weight: bold;
    margin-right: 30px;
  }

  header input {
    border: none;
    background-color: rgba(128, 128, 128, 0.1);
    padding: 10px;
    border-radius: 5px;
  }


  .options-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 40px;
  }

  .card {
    width: 310px;
    overflow: hidden;
    border-radius: 2%;
    box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 35px;
    margin-right: 20px;
    cursor: pointer;
  }

  .card img {
    width: 100%;
    height: 200px;
    margin: 0;
  }

  .card card-text {
    padding: 0 2px;
  }
</style>