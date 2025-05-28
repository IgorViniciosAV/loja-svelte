<script>
	import Cabecalho from "./Cabecalho.svelte";
	import Produto from "./produto/Produto.svelte";

</script>
<div class="flex flex-col h-screen w-screen p-5">
    <Cabecalho />
    <main class="flex flex-col gap-5">
        <Produto />
        <Produto />
        <Produto />
        <slot></slot>
    </main>
</div>