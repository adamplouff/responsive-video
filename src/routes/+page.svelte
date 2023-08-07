<!-- https://github.com/metonym/sveltekit-gh-pages -->

<script>
  import { base } from "$app/paths";
  import ResponsiveVideo from "../lib/ResponsiveVideo.svelte";
</script>

<main>
  <ResponsiveVideo />

  <!-- <video src="{ base }/video/desktop_landscape.mp4" loop autoplay muted playsinline></video> -->
</main>

<style>
  :global(body) {
    top: 0;
    padding: 0;
    margin: 0;
  }
</style>