<template>
    <footer>
        <div class="container">
            <div class="left">
                <div class="side-left">
                    <h3>dc comics</h3>
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
                            <a href="/">videos</a>
                        </li>
                        <li>
                            <a href="/">news</a>
                        </li>
                    </ul>
                    <h3>shop</h3>
                    <ul>
                        <li>
                            <a href="/">Shop DC</a>
                        </li>
                        <li>
                            <a href="/">Shop DC Collectibles</a>
                        </li>
                    </ul>
                </div>
                <div class="center">
                    <h3>dc</h3>
                    <ul>
                        <li>
                            <a href="/">Terms of use</a>
                        </li>
                        <li>
                            <a href="/">Privacy policy (New)</a>
                        </li>
                        <li>
                            <a href="/">Ad Choices</a>
                        </li>
                        <li>
                            <a href="/">Advertising</a>
                        </li>
                        <li>
                            <a href="/">Jobs</a>
                        </li>
                        <li>
                            <a href="/">Subscriptions</a>
                        </li>
                        <li>
                            <a href="/">Talent Workshop</a>
                        </li>
                        <li>
                            <a href="/">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="/">Ratings</a>
                        </li>
                        <li>
                            <a href="/">Shop Help</a>
                        </li>
                        <li>
                            <a href="/">Contact Us</a>
                        </li>
                    </ul>
                </div>
                <div class="side-right">
                    <h3>sites</h3>
                    <ul>
                        <li>
                            <a href="/">DC</a>
                        </li>
                        <li>
                            <a href="/">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="/">DC Kids</a>
                        </li>
                        <li>
                            <a href="/">DC Universe</a>
                        </li>
                        <li>
                            <a href="/">DC Power Vista</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="right">
                <img src="../assets/dc-logo-bg.png" alt="dc logo footer">
            </div>
        </div>
        <div class="contact">
            <div class="container footer-bar">
                <div class="button">
                    <button>sign-up now!</button>
                </div>
                <div class="social">
                    <ul>
                        <li>
                            <h2>follow us</h2>
                        </li>
                        <li>
                            <a href="/">
                                <img src="../assets/footer-facebook.png" alt="facebook">
                            </a>
                        </li>
                        <li>
                            <a href="/">
                                <img src="../assets/footer-twitter.png" alt="twitter">
                            </a>
                        </li><li>
                            <a href="/">
                                <img src="../assets/footer-youtube.png" alt="you tube">
                            </a>
                        </li><li>
                            <a href="/">
                                <img src="../assets/footer-pinterest.png" alt="pinterest">
                            </a>
                        </li><li>
                            <a href="/">
                                <img src="../assets/footer-periscope.png" alt="periscope">
                            </a>
                        </li>
                    </ul>
                </div>
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
        max-height: 700px;
        background-image: url('../assets/footer-bg.jpg');
        background-size: cover;
        padding: 20px 0;
    
        .container{
            display: flex;
            width: 80%;
            margin: 0 auto;
                
                .left{
                    display: flex;
                    padding-top: 110px;

                    .side-left,
                    .center,
                    .side-right{
                        width: calc(100% / 3);
                        
                        h3{
                            color: white;
                            text-transform: uppercase;
                            margin: 1rem 0;
                        }
                        ul{
                            list-style: none;
                        
                            li{
                                margin-bottom: 4px;

                                a{
                                    text-decoration: none;
                                    color:gray;
                                    font-size: 0.70rem;
                            }
                            }
                        }
                        
                    }
                    
                }


                .left{
                    width: 30%;
                }
                .right{
                    width: 70%;
                    img{
                        width: 550px;
                    }
                }

                .right{
                    display: flex;
                    justify-content: flex-end;
                }
        }
        .contact{
            background: rgb(41, 41, 41);
            padding: 50px 0;
            
            .footer-bar{
                display: flex;
                justify-content: space-between;
            }

                button{
                    padding: 15px;
                    background: rgb(41, 41, 41);
                    color: white;
                    border: 3px solid #0c7cec;
                    text-transform: uppercase;
                }

                .social{
                    display: flex;
                    align-items: center;

                    ul{
                    display: flex;
                    align-items: center;
                    list-style: none;

                    li{
                        margin-left: 15px;

                        h2{
                            text-transform: uppercase;
                            color: #0c7cec;
                        }
                    }
                }
                }

                

        }

    }

        
       


</style>