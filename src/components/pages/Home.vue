<template>
    <div id="home" class="animate__animated animate__fadeInUpBig">
        <h1>サンプル株式会社</h1>
        <p>~明日の未来を作る~</p>
    </div>
</template>

<script>
export default {
    name: "Home",
}
</script>

<style scoped>
    #home {
        height: 100vh;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        text-shadow: 0px 0px 13px rgba(0, 0, 0, 0.9);
    }
    h1 {
        font-size: 5.5rem;
    }
    p {
        font-size: 4.5rem;
    }

@media(max-width: 768px){
    h1 {
        font-size: 2.5rem;
    }
    p {
        font-size: 1.5rem;
    }
}
</style>