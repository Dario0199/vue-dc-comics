<template>
    <header>
        <div>
            <a href="/">
                <img src="../assets/dc-logo.png" alt="dc comics">
            </a>
            <nav>
                <ul>
                    <li v-for="(link, index) in menuLink" :key="`link-${index}`">
                        <a :class="{active: link.current}" :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
            </nav>

        </div>
    </header>
</template>

<script>
export default {
    name: 'header',
    data() {
        return{
            menuLink: [
                {
                    text: 'character',
                    url: '/',
                    current: false
                },
                {
                    text: 'comics',
                    url: '/',
                    current: true
                },
                {
                    text: 'movie',
                    url: '/',
                    current: false
                },
                {
                    text: 'tv',
                    url: '/',
                    current: false
                },
                {
                    text: 'games',
                    url: '/',
                    current: false
                },
                {
                    text: 'collectibles',
                    url: '/',
                    current: false
                },
                {
                    text: 'videos',
                    url: '/',
                    current: false
                },
                {
                    text: 'fans',
                    url: '/',
                    current: false
                },
                {
                    text: 'news',
                    url: '/',
                    current: false
                },
                {
                    text: 'shop',
                    url: '/',
                    current: false
                },
            ],
        }
    },
}
</script>

<style scoped lang="scss">
$primary-color: #0c7cec;
$default-color: black;
div{
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 80%;
    height: auto;
    margin: 0 auto;
    
    img{
        width: 70px;
    }

    ul{
        display: flex;
        justify-content: flex-end;

        li{
            list-style: none;

            a{
                text-decoration: none;
                margin: 0 1rem;
                padding-bottom: 25px;
                text-transform: uppercase;
                font-size: 0.60rem;
                font-weight: 700;
                color: $default-color;
                &.active,
                &:hover{
                    color: $primary-color;
                    border-bottom: 4px solid $primary-color;
                }
            }
        }
    }
}
 
</style>