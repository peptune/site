<script lang="ts">
  import DotField from '$lib/components/svelte-bits/DotField.svelte';
  import LiquidChrome from '$lib/components/svelte-bits/LiquidChrome.svelte';

</script>


<div style="width: 100%; height: 600px; position: relative;">
  <LiquidChrome
    baseColor={[1, 0.1, 0.1]}
    speed={0.2}
    amplitude={0.5}
    interactive={true}
  />
</div>