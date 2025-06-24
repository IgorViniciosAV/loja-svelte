<script>
	import CabecalhoOrdem from "./CabecalhoOrdem.svelte";

</script>
<div class="fixed bg-white flex flex-col h-11/12 w-screen z-50 left-0 bottom-0 p-5 rounded-t-xl shadow-top animate-aparecer">
    <CabecalhoOrdem />
</div>

<style>
    .shadow-top {
        box-shadow: 0px 0px 0px 100vh rgba(0, 0, 0, 0.6);
    }
    .animate-aparecer {
        animation: aparecer .5s ease-out forwards;
    }

    @keyframes aparecer {
        from {
            height: 0;
        }
        to {
            height: 90vh;
        }
    }
</style>