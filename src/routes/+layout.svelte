<!-- src/routes/+layout.svelte -->
<header>
    <nav class = "menu">
        <ul>
            <h1>My Portfolio</h1>
        </ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/performance">Performance</a></li>
        <li><a href="/contact">Contact</a></li>
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
    .menu li{
        /* text-align: right; */
        /* text-decoration: none; */
        /* align-items: right; */
    }
    .menu ul{
        display:block;
        justify-content: start;
    }
</style>
<main>
    <slot></slot>
</main>