<template>
    <nav>
        <p>
            <router-link to="/">
                <i class="fa-solid fa-star"><span>Example Inc.</span></i>         
            </router-link>
        </p>
        <ul>
            <li>
                <router-link to="/">Home</router-link>
            </li>
            <li>
                <router-link to="/about">About</router-link>
            </li>         
            <li>
                <router-link to="/contact">Contact</router-link>
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: "header",

}
</script>

<style scoped>
    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 75px;
        width: 100%;
        font-family: 'M PLUS Rounded 1c', sans-serif;
        position: absolute;
    }
    p {
        font-size: 2.0rem;
        margin-left: 20px;
    }

    li {
        font-size: 1.3rem;
        display: inline-block;
        margin-right: 20px;
    }

</style>