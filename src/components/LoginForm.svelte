<style>
  .flex-container {
    margin: 2rem;
    display: flex;
    padding: 2rem;
    background-color: white;
    border-radius: 0.8rem;
    min-height: 10rem;
    align-items: center;
    flex-direction: column;
  }

  .input {
    border-bottom: 2px solid#c5c3f7;
  }

  .input-field {
    width: 100%;
    height: 100%;
    background-color: inherit;
    border: none;
    outline-style: none;
    color: #4f26e1;
  }

  h4 {
    font-size: 2.5vh;
    font-weight: 600;
    padding: 0;
    margin: 0;
    margin-bottom: 5vh;
  }

  form {
    width: 100%;
  }

  .login-btn {
    background-color: #4f26e1;
    color: white;
    border: none;
    outline-style: none;
    width: 60px;
    height: 20px;
    font-size: 2vh;
  }

  a {
    font-size: 1.8vh;
  }
</style>

<div class="flex-container">
  <div>
    <h4>Welcome back! CECian</h4>
  </div>
  <form>
    <div class="input grid-item">
      <input class="input-field" type="text" placeholder="Username" />
    </div>
    <br />
    <div class="input grid-item">
      <input class="input-field" type="password" placeholder="Password" />
    </div>
    <br />
    <div>
      <a href="./">Dont have a account?</a>
      <button class="login-btn">Login</button>
    </div>
  </form>
</div>
