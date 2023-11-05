<script>
  import "../app.postcss";
  import Header from "./Header.svelte";
  import "./styles.css";
</script>

<div class="app">
  	<Header />
	<slot />  
</div>
