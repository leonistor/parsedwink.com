<script lang="ts">
  import eye from '$lib/assets/eye.png'
</script>

<div class="container mx-auto min-h-screen w-full p-8">
  <div class="flex-col items-center justify-center">
    <h1 class="text-center text-3xl font-bold text-gray-900">Parsed Wink</h1>

    <p class="text-center text-xl font-light text-gray-700">Mobile apps development.</p>

    <img src={eye} alt="Parsed Wink" class="mx-auto w-64" />

    <p class="text-center font-light leading-tight text-gray-600">
      <strong>Contact</strong><br />leo.nistor at gmail.com<br />Mircea cel Batran 39<br />Brasov,
      Romania
    </p>
  </div>
</div>

<style lang="postcss">
  :global(html) {
    background-color: #03c9e3;
  }
</style>
