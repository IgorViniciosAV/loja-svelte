<script lang="ts">
	export let quantidaItem: any = 0;
</script>

<div class="rounded-lg bg-white p-5 shadow shadow-amber-50">
    <span class="text-2xl font-black text-amber-700">Your Cart ({quantidaItem})</span>
    <slot></slot>
</div>
