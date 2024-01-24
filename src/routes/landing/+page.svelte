<script>
    import logo from "../../assets/logo-NB.png"
    import Mantra from "../../components/mantra.svelte";
</script>

<section class="page">
    <div>
        <img src={logo} alt="logo" id="logo"/>
    </div>
    <div class="slide">
        <Mantra />
    </div>
    <div class="menu">
        <p>menu</p>
        <p>menu</p>        
    </div>
</section>

<style>
    .page{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        
        height: 100vh;
        background-color: black;
    }
    #logo{
        margin-top: 25px;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
    }
    .slide{
        margin-left: auto;
        margin-right: auto;
        width: 50%;
        text-align: center;
    }
    .menu{
        display: flex;
        justify-content: space-between;
    }
    p{
        color: red;
    }
</style>