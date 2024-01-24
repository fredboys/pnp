<script>
    import logo from "../../assets/logo-NB.png"
    import Quote from "../../components/quote.svelte";
    import Menu from "../../components/menu.svelte";
</script>

<section class="page">
    <div>
        <img src={logo} alt="logo" id="logo"/>
    </div>
    <div class="slide">
        <Quote />
    </div>
    <div class="menu">
          <Menu />      
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
        margin: 20px 40px;
    }
    p{
        color: red;
    }
</style>