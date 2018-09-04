<template>
    <section class="mb-3" id="home">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-sm-12 left-col">
                    <div class="left-col-wrapper">
                        <div class="lc-icon">
                            <span>
                                <i class="zi zi_house"></i>
                            </span>
                        </div>
                        <div class="lc-heading">
                            <h3 class="special-heading-1">Skip the Line with
                                 <strong>SKIPT.</strong>
                            </h3>
                        </div>
                        <div class="lc-heading mb-3">
                            <div>Any line. Any time. Anywhere.</div>
                        </div>
                        <div class="lc-btn-box">
                            <div>
                                <a href="">
                                    <img src="../assets/available_app_store-1.png" alt="">
                                </a>
                            </div>
                            <div class="mt-2">
                                <a href="">
                                    <img src="../assets/google_play.png" alt="">
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-sm-12">
                    <div class="right-col-wrapper">
                        <img src="../assets/new_slider-2.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
</script>
<style scoped>
    section {
        background-image: url(../assets/header-app-image.jpg);
        background-color: #091827;
        padding-top: 200px;
    }
    .row .left-col {
        color: #fff;
        padding-top: 4%;
        padding-bottom: 30px;
    }
    .left-col-wrapper {
        position: relative;
        box-sizing: border-box;
        padding: 0 15px;
        width: 100%;
    }
    .lc-icon {
        margin-left: -5%;
    }
    .lc-icon span {
        border-radius: 50%;
        background-color: #db6f6a;
        border-width: 2px;
        border-color: #db6f6a;
        border-style: solid;
        display: block;
        width: 60px;
        height: 60px;
        position: relative;
    }
    .lc-icon span i {
        font-size: 2rem;
        position:absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    .lc-btn-box a {
        transition: all .3s ease-in-out;
    }
    .lc-btn-box a:hover {
        opacity: 0.8;
    }

    .right-col-wrapper {
        padding: 0 15px;
        width: 100%;
    }
    .right-col-wrapper img {
        height: auto;
        max-width: 100%;
        vertical-align: top;
    }
</style>

