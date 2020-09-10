<script>
  import Notification from "./components/Notification.svelte";
  import LoginScreen from "./routes/LoginScreen.svelte";

  let isLogin = false;
</script>

<main>
  {#if isLogin === true}
    <Notification />
  {:else if isLogin === false}
    <LoginScreen />
  {/if}
</main>
