<!-- <script>
    import '../app.css'
    import logo from "../assets/logo-NB.png"
  </script>

<div>
    <video muted autoplay loop>
        <source src="/static/20240113_210908.mp4" type="video" />
    </video>
    <img src={logo} alt="logo" id="logo"/>
    <button id="enter-btn">Enter</button>   
</div>

<style>
    div{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;        
        width: 100vw;
        height: 100vh;
    }
    #logo {
        padding-top: 30px;
    }
    #enter-btn{
        margin-bottom: 30px;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        color: white;
        font-weight: bold;
        background-color: Transparent;
        border: 1px solid #ffffff;
        padding: 3px 5px;
    }

</style> -->

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
    }
    video{
        position: absolute;
        height:100vh;
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