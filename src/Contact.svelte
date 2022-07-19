<script>
    export let name;
    import SiteNav from "./Components/SiteNav.svelte"
    import PageHeader from "./Components/PageHeader.svelte"
  </script>
  
  <main>
    <SiteNav/>
    <PageHeader name={name}/>
  </main>
