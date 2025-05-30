<script>
	import BotaoConfirmar from "./BotaoConfirmar.svelte";
	import CarrinhoItem from "./CarrinhoItem.svelte";
	import PrecoTotal from "./PrecoTotal.svelte";
	import TopoCarrinho from "./TopoCarrinho.svelte";
	import ZeroCarbono from "./ZeroCarbono.svelte";

</script>

<TopoCarrinho>
    <CarrinhoItem />
    <CarrinhoItem />
    <CarrinhoItem />

    <PrecoTotal />
    <ZeroCarbono />
    <BotaoConfirmar />
</TopoCarrinho>