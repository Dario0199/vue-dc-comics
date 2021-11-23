<template>
    <footer>
        <div class="container">
            <div class="left">
                left
            </div>
            <div class="right">
                <img src="../assets/dc-logo-bg.png" alt="dc logo footer">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped lang="scss">
    footer{
        max-width: 100%;
        background-image: url('../assets/footer-bg.jpg');
        background-size: cover;
        padding: 20px 0;
    
        .container{
        display: flex;
        width: 80%;
        margin: 0 auto;

            .left,
            .right{
                width: 50%;
                img{
                    width: 450px;
                }
            }

            .right{
                display: flex;
                justify-content: flex-end;
            }
        }

    }

        
       


</style>