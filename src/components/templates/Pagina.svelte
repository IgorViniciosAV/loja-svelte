<script>
	import Cabecalho from "./Cabecalho.svelte";
	import Produto from "./produto/Produto.svelte";
	import SeuCarrinhoCheio from "./seu-carrinho/SeuCarrinhoCheio.svelte";
	import SeuCarrinhoVazio from "./seu-carrinho/SeuCarrinhoVazio.svelte";

</script>
<div class="flex flex-col min-h-screen w-screen p-5 bg-rose-50">
    <Cabecalho />
    <main class="flex flex-col gap-5">
        <Produto />
        <slot></slot>
        <SeuCarrinhoCheio />
    </main>
</div>