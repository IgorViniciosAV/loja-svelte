<script lang="ts">
	export let nome: string = "Produto Indefinido";
	export let precoUni: number = 0;
	export let precoTot: number = 0;
	export let quantidade: number = 1;
</script>

<div class="relative flex flex-col gap-1 border-b border-zinc-200 py-3">
	<span class="font-semibold">{nome}</span>
	<div class="flex gap-4">
		<span class="font-semibold text-amber-700">{quantidade}x</span>
		<span class="font-medium text-zinc-400">@ ${precoUni}</span>
		<span class="font-semibold text-amber-900/55">${precoTot}</span>
	</div>
	<button class="absolute top-8 right-0 p-0.5 border-2 border-amber-800/40 rounded-full">
		<img src="./src/assets/images/icon-remove-item.svg" alt="" class="min-w-2" />
	</button>
</div>
