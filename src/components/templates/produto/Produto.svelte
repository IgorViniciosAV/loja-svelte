<script>
	import ImgemProduto from './ImgemProduto.svelte';
	import InfoProduto from './InfoProduto.svelte';
	import { dados } from '../../../functions/dados';
	import Carrinho from './Carrinho.svelte';
	
</script>

{#each dados as dado}
	<div class="flex w-full flex-col">
		<ImgemProduto imagem={dado.image.mobile} />
		<InfoProduto categoria={dado.category} nome={dado.name} preco="${dado.price}" />
		<Carrinho />
	</div>
{/each}
