<script>
    import logo from "../../assets/logo-NB.png"
    import Quote from "../../components/quote.svelte";
    import Menu from "../../components/menu.svelte";

    function changeToQuote(){
        
    }
</script>

<section class="page">
    <div>
        <img src={logo} alt="logo" id="logo"/>
    </div>
    <div class="slide">
        <div id="display"><Quote/></div>
        <div class="btns">
            <button onclick="changeToQuote"></button>
            <button onclick="changeToSets"></button>
        </div>
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
    .btns{
        margin: 15px;
    }
    .btns button{
        padding: 25px;
    }
</style>