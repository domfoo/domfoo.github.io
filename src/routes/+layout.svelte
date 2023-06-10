<script>
    // global css
    import 'normalize.css';
    import './styles.css';

    import Navbar from "../lib/Navbar.svelte";

    let brand = "domfoo";
</script>

<Navbar {brand}></Navbar>
<slot></slot>
