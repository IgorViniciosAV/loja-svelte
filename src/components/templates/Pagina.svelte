<script>
	import Cabecalho from './Cabecalho.svelte';
	import ConfirmarOrdem from './confirmar-ordem/ConfirmarOrdem.svelte';
	import Produto from './produto/Produto.svelte';
	import SeuCarrinhoCheio from './seu-carrinho/SeuCarrinhoCheio.svelte';
	import SeuCarrinhoVazio from './seu-carrinho/SeuCarrinhoVazio.svelte';
	import { dados } from '../../functions/dados';
</script>

<div class="flex min-h-screen w-screen flex-col bg-rose-50 p-5">
	<Cabecalho />
	<main class="flex flex-col gap-5">
		<!-- <ConfirmarOrdem /> -->
		<Produto />
		<slot></slot>
		<SeuCarrinhoCheio />
	</main>
</div>
