<script>
    import '../app.css'
    import logo from "../assets/logo-NB.png"
</script>

<section class="sec">
    <video muted autoplay loop playsinline disablepictureinpicture>
        <source src="/pnphomevideo.webm" type="video/webm" />
    </video>
    <img src={logo} alt="logo" id="logo"/>
    <a href="./landing">Enter</a>
</section>

<style>
    section{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between; 
        height: 100vh;
        width:100vw;
        position: relative;
        overflow: hidden;
    }
    video{
        position: absolute;
        min-height:100%;
        object-fit: cover;
    }
    #logo{
        z-index: 1;
        padding-top: 25px;
    }
    a{
        z-index: 1;
        margin-bottom: 25px;
        color: white;
        background-color: transparent;
        border: none;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-weight: bold;
        letter-spacing: 1px;
    }
</style>