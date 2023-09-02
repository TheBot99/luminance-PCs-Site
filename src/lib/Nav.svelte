<script>

    
    import { page } from '$app/stores';  
    let currentPage = $page.url.pathname;
    var isHomeNavElement = false;
    var isPCNavElement = false;
    var isPeripheralsNavElement = false;
    if (currentPage == "/") {
        isHomeNavElement = true;
    };
    if (currentPage == "/listings/PCs") {
        isPCNavElement = true;
    };
    if (currentPage == "/listings/Peripherals") {
        isPeripheralsNavElement = true;
    };
    
    

    
    

    
    
</script>





<div class="container  flex justify-between items-center">
    <h1 class = "text-left my-2 mx-2 text-gray-500 text-4xl font-semibold"><a href="/">Luminance PCs & Tech</a></h1>
    <ul class=" text-gray-500 flex justify-center space-x-28 text-2xl mx-auto">
        <li class="hover:text-white transition hover:underline duration-500 ease-in-out hover:scale-105 font-semibold {isHomeNavElement ? 'active' : ''}"><a href="/">Home</a></li>
        <li class="hover:text-white transition hover:underline duration-500 ease-in-out hover:scale-105 font-semibold {isPCNavElement ? 'active' : ''}"><a href="/listings/PCs">PCs</a></li>
        <li class="hover:text-white transition hover:underline duration-500 ease-in-out hover:scale-105 font-semibold {isPeripheralsNavElement ? 'active' : ''}"><a href="/listings/Peripherals">Peripherals</a></li>
    </ul>
</div>




<style>
    @import "../app.css";
    .active {
      color: white;
        text-decoration: underline;


    }
</style>






