<template>
    <header>
        <div>
            <a href="/">
                <img src="../assets/dc-logo.png" alt="dc comics">
            </a>
            <nav>
                <ul>
                    <li>
                        <a href="/">character</a>
                    </li>
                    <li>
                        <a href="/">comics</a>
                    </li>
                    <li>
                        <a href="/">movie</a>
                    </li>
                    <li>
                        <a href="/">tv</a>
                    </li>
                    <li>
                        <a href="/">games</a>
                    </li>
                    <li>
                        <a href="/">collectibles</a>
                    </li>
                    <li>
                        <a href="/">videos</a>
                    </li>
                    <li>
                        <a href="/">fans</a>
                    </li>
                    <li>
                        <a href="/">news</a>
                    </li>
                    <li>
                        <a href="/">shop</a>
                    </li>
                </ul>
            </nav>

        </div>
    </header>
</template>

<script>
export default {
    name: 'header',
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

                &:hover{
                    color: $primary-color;
                    border-bottom: 4px solid $primary-color;
                }
            }
        }
    }
}
 
</style>