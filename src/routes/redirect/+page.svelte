<script>
    import { onMount } from "svelte";
    import { goto } from "$app/navigation";

    onMount(() => {
        goto("/");
    });
</script>

<div class="max-w-[65ch] m-auto prose prose-blue">
    Redirecting <a href="/">to main page</a>...
</div>
