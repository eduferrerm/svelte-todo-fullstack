<script>
  import Header from "$lib/header.svelte";
  import "../app.css";
  const pages = ['login', 'signin'];
</script>
<Header pageBrand={'Organizer'} pages={pages}/>
<main class="p-5">
  <div class="max-w-6xl mx-auto">
    <slot />
  </div>
</main>