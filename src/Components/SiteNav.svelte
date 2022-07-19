<script>
    import CompanyLogo from "./CompanyLogo.svelte"
</script>

<style>
    #site-nav {
        width: 100%;
        height: 300px;
        position: sticky;
        left: 0; 
        top: 0;
        display: flex;
        align-items: flex-end;
        justify-content: space-between;
        background-color: #222222;
        clip-path: polygon(0 0, 0 100%, 100% calc(100% - 50px), 100% 0);
    }
    nav {
        width: 50%;
        display: flex;
        justify-content: center;
        height: 100%;
    }
    button {
        padding: 0 50px;
        height: 100%;
        border: none;
        color: white;
        background-color: inherit;
    }
    button:hover {
        color: #888888;
    }
    button:active {
        color: #000000;
    }
</style>

<div id="site-nav">
    <CompanyLogo/>
    <nav>
        <a href="./"><button>
            <h2>Home</h2>
            </button></a>
        <a href="./projects.html"><button>
            <h2>Projects</h2>
            </button></a>
        <a href="./contact.html"><button>
            <h2>Contact</h2>
            </button></a>
    </nav>
</div>