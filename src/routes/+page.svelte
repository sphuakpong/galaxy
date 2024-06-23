<script lang="ts">
  import * as dat from "lil-gui";
  import { onMount } from "svelte";

  onMount(() => {
    /**
     * Base
     */
    // Debug
    const gui = new dat.GUI();

    // Canvas
    const canvas = document.querySelector("canvas.webgl") as HTMLElement;
  });
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
