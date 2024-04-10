<script>
    export default {
        name: 'AppJumbotron'
}
</script>

<template>
    <div class="container-fluid">
        <div class="jumbotron-div">
            <div>
                <h1>Hello VITE</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum neque, modi hic itaque officiis laudantium iste repellat vero ea, porro quo vitae, tenetur unde. Iure impedit quae ea aliquid eius.</p>
            </div>
            <img src="../assets/vue.svg" alt="" class="logo">
        </div>
    </div>
</template>

<style>
    .container-fluid{
        max-width: 700px;
        margin: 0 auto;
        padding: 20px;
        border-bottom: 1px solid rgb(198, 198, 198);
    }

    h1{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-size: 3rem;
    }

    p{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }

    .jumbotron-div{
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .logo{
        width: 400px;

    }

</style>