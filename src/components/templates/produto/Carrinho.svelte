<script lang="ts">
	import Produto from "./Produto.svelte";
	import { dados } from '../../../functions/dados';
	export let nome: string = 'null';
	
	function adicionarAoCarrinho() {
		alert(nome)
	}
</script>

<button on:click={adicionarAoCarrinho}
	class="flex justify-center gap-2 rounded-full border-1 bg-white px-6 py-1.5 hover:border-amber-700 hover:text-amber-700"
>
	<img src="./src/assets/images/icon-add-to-cart.svg" alt="Carrinho" />
	<span class="text-lg font-semibold">Add to Cart</span>
</button>
