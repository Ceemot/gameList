<script lang="ts">
  const handleFetch = async () => {};
</script>

<div class="container">
  <div class="header">
    <h1>Game List</h1>
    <div class="input-container">
      <input type="text" class="input" />
      <button class="button" on:click={handleFetch}>Button</button>
    </div>
  </div>

  <div class="photos">
    <img src={"src/Images/test.png"} alt={""} class={"image"} />
    <img src={"src/Images/test.png"} alt={""} class={"image"} />
    <img src={"src/Images/test.png"} alt={""} class={"image"} />
    <img src={"src/Images/test.png"} alt={""} class={"image"} />
    <img src={"src/Images/test.png"} alt={""} class={"image"} />
    <img src={"src/Images/test.png"} alt={""} class={"image"} />
  </div>
</div>

<style>
  :root {
    color-scheme: dark light;
  }
  .image {
    width: 400px;
    height: 250px;
    margin: 5px;
  }
  .photos {
    display: flex;
    flex-wrap: wrap;
  }
  .container {
    width: 1230px;
    margin: 0 auto;
  }
  .header {
    text-align: center;
    font-size: 20px;
  }
  .input {
    padding: 10px;
    width: 400px;
    border-radius: 10px;
    outline: none;
    border: 1px solid gray;
    font-size: 20px;
  }
  .button {
    padding: 10px;
    font-size: 20px;
    background-color: orangered;
    border-radius: 10px;
    border: none;
    color: blanchedalmond;
  }
  .input-container {
    margin-bottom: 40px;
  }
</style>
