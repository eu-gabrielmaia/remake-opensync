<script lang="ts">

</script>

<div class="descripition">
    <div>
        <h1>Image hosting service</h1>
        <h1 class="detalhe">At your home, for free.</h1>
    </div>
    

    <p>Lightweight, fast, open source and multiplatform self-hosted image backup platform</p>

    <div class="ancoras">
        <a href="">Quickstart</a>
        <a href="">Learn More</a>
    </div>
</div>

<style>

    .descripition{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
        font-weight: bold;
        margin: 15px 20px;
    }

    h1{
        font-size: 2.5em;
        text-shadow: 0px 0px 30px #000;
    }

    p{
        margin: 20px 20px;
        font-size: 1.5em;
        text-shadow: 0px 0px 30px #000;
    }

    .detalhe{
        color: var(--cor-principal);
        text-shadow: 1px 0px 30px;
    }

    .ancoras{
        display: flex;
        justify-content: space-around;
        gap: 50px;
    }

    .ancoras a{
        font-weight: 400;
        font-size: 1.5em;
        padding: 15px 40px;
        border-radius: 15px;
        background: var(--fundo2);
        box-shadow: 0px 0px 20px #000;
    }

    .ancoras a:hover{
        transform: scale(1.25);
        transition-duration: 1.2s;
        border: 1px solid #000;
        box-shadow: var(--cor-principal);
    }
</style>