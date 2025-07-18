<!-- src/routes/+layout.svelte -->
<header>
    <nav class = "menu">
        <ul>
            <h1>Portfolio</h1>
        </ul>
        <nav class = "nav-links">
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
            <li><a href="/performance">Performance</a></li>
            <li><a href="/contact">Contact</a></li>
        </nav>
    </nav>
    <nav class = "logo">
            
    </nav>
</header>
<style>
    .menu{
        display: flex;
        justify-content:space-between;
        align-items: center;
        margin: 40px;
        list-style: none;
    }
    .menu h1{
        display: flex;
        margin: 0;
        font-size: 40px;
    }
    
    .nav-links {
        display: flex;
        gap: 180px;
        list-style: none;
        margin: 0;
        padding: 0;
    }
    
    .nav-links li a {
        text-decoration: none;
        color: inherit;
    }
    .menu ul{
        display: flex;
        justify-content: start;
    }
</style>
<main>
    <slot></slot>
</main>