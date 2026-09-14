<script lang="ts">
    import Navbar from "$lib/components/navbar.svelte";
    import Gamecard from "$lib/components/gamecard.svelte";

    import Vex from "$lib/assets/images.jpg"
</script>

<Navbar />

<div class="grid grid-cols-8 mx-2 gap-2">
    <Gamecard title="Steal a brainrot" image={Vex} />
    <Gamecard title="Steal a brainrot" image={Vex} />
    <Gamecard title="Steal a brainrot" image={Vex} />
</div>
