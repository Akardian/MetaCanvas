<Navigation />

<script lang="ts">
    import type { Snippet } from 'svelte';
    import type { LayoutData } from './$types';
    import Navigation from '$lib/navigation/Navigation.svelte';

    let { data, children }: { data: LayoutData, children: Snippet } = $props();
</script>

{@render children()}