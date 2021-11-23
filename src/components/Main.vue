<template>
    <section>
        <div>
            <h1>vue dc comics</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Esse, ex nobis tempore cumque eos nulla dicta! Labore mollitia totam dolore esse blanditiis quae! Nisi accusantium soluta sapiente harum ipsam rem!</p>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Main'
}
</script>

<style scoped lang="scss">
$default-color: black;

section{
    width: 100%;
    background: $default-color;

    div{
        max-width: 80%;
        margin: 0 auto;
        color: white;
        padding: 40px 0;

        h1{
            margin-bottom: 15px;
            text-transform: uppercase;
        }
    }
}
</style>