<script lang="ts">
    import MetaMap from '$lib/meta-map/MetaMap.svelte';
    import type { PageData } from './$types.js';

    let { data }: { data: PageData } = $props();
</script>

<MetaMap />