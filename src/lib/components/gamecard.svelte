<script lang="ts">
    interface Props {
        title: string;
        image: string;
    }
    let { title, image }: Props = $props()

</script>

<div class="aspect-square rounded-lg overflow-clip group/game relative">
    <span class="invisible group-hover/game:visible z-10 absolute">{title}</span>
    <div class="bg-cover bg-center w-full h-full group-hover/game:opacity-30 z-0 absolute" style={`background-image: url("${image}")`}></div>
</div>
