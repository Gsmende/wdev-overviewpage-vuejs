<template>
    <main>
        <div class="text-top">
            Vídeo novo toda <b>quinta-feria</b> as <b>20hrs</b>
        </div>

        <a href="https://youtube.com/wdevoficial" target="_blank">
            <img id="subscribe" alt="Increva-se" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg">
        </a>

        <div class="text-bottom">
            youtube.com/wdevoficial 
        </div>
    </main>
</template>

<script>
    export default{
        name: 'Home'
    }
</script>

<style scoped>
    main{
        background-color: var(--color-background-home);
        justify-content: center;
        align-items: center;
    }

    .text-top{
        color: var(--color-text-light);
        font-size: 22px;
        margin-bottom: 20px;
    }

    #subscribe{
        width: 350px;
    }

    .text-bottom{
        color: var(--color-text-light);
        font-size: 22px;
        margin-top: 20px;
    }

    @media (min-width: 700px){
        #subscribe{
            width: 400px;
        }
    }
</style>