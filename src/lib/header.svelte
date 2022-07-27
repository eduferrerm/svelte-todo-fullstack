<script lang="ts">
  export let pageBrand: String;
  export let pages: Array<String>;
</script>

<nav class="w-full max-w-6xl mx-auto flex justify-between p-3">
  <a href="/">{pageBrand}</a>
  <ul class="flex">
    {#each pages as page, i}
      <li class="capitalize p-1"><a href="/{page}">{page}</a></li>
    {/each}
  </ul>
</nav>