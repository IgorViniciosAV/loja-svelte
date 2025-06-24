<script lang="ts">
	import BotaoConfirmar from "./BotaoConfirmar.svelte";
	import CarrinhoItem from "./CarrinhoItem.svelte";
	import PrecoTotal from "./PrecoTotal.svelte";
	import TopoCarrinho from "./TopoCarrinho.svelte";
	import ZeroCarbono from "./ZeroCarbono.svelte";
	import { dados } from "../../../functions/dados";

</script>

<TopoCarrinho>
    

    <PrecoTotal />
    <ZeroCarbono />
    <BotaoConfirmar />
</TopoCarrinho>