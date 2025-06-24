<script>
	import Carrinho from "./Carrinho.svelte";
    
    export let imagem
</script>
<div class="relative flex justify-center">
    <img src={imagem} alt="Foto Produto" class="w-full rounded-lg">
    <div class="absolute -bottom-5">
    </div>
</div>


<!-- "./src/assets/images/image-waffle-mobile.jpg" -->