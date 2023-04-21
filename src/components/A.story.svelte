<script lang="ts">
  import type { Hst } from '@histoire/plugin-svelte'
  export let Hst: Hst

  import A from './A.svelte';
</script>

<Hst.Story> <!-- Typed! -->
  <A />
</Hst.Story>
