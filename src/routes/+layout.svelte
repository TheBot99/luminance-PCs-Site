<!-- First navbar -->




<div class="navbar">
    <div class="logo">
        <h1><a href="/">Luminance PCs & Tech</a></h1>
    </div>
    <div class="menu">
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="listings/PCs">PCs</a></li>
        </ul>
    </div>

    <div></div>
</div>




<style>
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: rgb(31, 30, 30);
        color: #b4b4b4;
        padding: 10px;
    }

    .logo {
        font-size: 2rem;
    }

    .menu ul {
        display: flex;
        justify-content: space-between;
        list-style: none;
    }

    .menu ul li a {
        color: #b4b4b4;
        text-decoration: none;
        padding: 15px;
        transition: all 0.3s ease;
        font-size: 1.2rem;
        
    }

    .menu ul li a:hover {
        color: #fff;
        
    }

    .menu ul li a.active {
        color: #fff;
    }
</style>



<script>
    import "../app.css";
</script>




<slot></slot>