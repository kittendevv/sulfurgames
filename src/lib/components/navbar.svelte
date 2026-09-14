<script lang="ts">
    import FlaskIcon from "phosphor-svelte/lib/FlaskIcon";

    import HouseIcon from "phosphor-svelte/lib/HouseIcon";
    import PopcornIcon from "phosphor-svelte/lib/PopcornIcon";
    import GearIcon from "phosphor-svelte/lib/GearIcon";
</script>

<div class="flex bg-base-200 m-2 rounded-full px-4 py-2 items-center">
	<div class="flex-1 flex items-center gap-1 text-primary font-bold">
        <FlaskIcon weight="fill" />
        Sulfur
    </div>
	<div class="flex-0">
        <ul class="flex gap-2">
            <li class="btn-primary">
                <HouseIcon weight="fill" />
                Home
            </li>
            <li class="btn-ghost">
                <PopcornIcon weight="fill" />
                Movies
            </li>
            <li class="btn-ghost">
                <GearIcon weight="fill" />
                Settings
            </li>
        </ul>
    </div>
</div>
