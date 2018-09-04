<template>
    <section pt-5 id="Testimonials">
        <div class="container">
            <div class="row">
                <div class="column-block col-12">
                    <div class="column-block-inner">
                        <div class="column-block-wrap">
                            <div class="header-text">
                                <h3 class="special-heading-1 text-center">
                                    Get an inside look at <strong>SKIPT</strong>
                                </h3>
                            </div>
                            <hr>
                            <div class="vc-carousel" @mousemove="stopPlay()" @mouseout="autoPlay()">
                                <div class="carousel-wrap mx-auto">
                                        <div class="carousel-inner" >
                                            <div class="c-item" v-show="isShow">
                                                <div class="mb-4">
                                                    <span class="item-head">SKIPT is awesome</span>
                                                </div>
                                                <div class="mb-4">
                                                    <img src="../assets/testimonial1.png" alt="">
                                                </div>
                                                <div>
                                                    <span >Rick</span>
                                                    <span class="red-txt">Johosan</span>
                                                    <p>happer app user</p>
                                                </div>
                                            </div>
                                            <div class="c-item" v-show="!isShow">
                                                <div class="mb-4">
                                                    <span class="item-head">Cool app! Love this</span>
                                                </div>
                                                <div class="mb-4">
                                                    <img src="../assets/testimonial2.png" alt="">
                                                </div>
                                                <div>
                                                    <span>kim</span>
                                                    <span class="red-txt">willims</span>
                                                    <p>happer app user</p>
                                                </div>
                                            </div>
                                        </div>
                                </div>
                                <div class="carousel-btn text-center">
                                    <a href="javascript:;" @click="goto()">
                                        <i class="zi zi_forLeft" zico="左指"></i>
                                    </a>
                                    <a href="javascript:;" @click="goto()">
                                        <i class="zi zi_forRight" zico="右指"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                isShow: true,

            }
        },
        computed: {
            
        },
        methods: {
            goto() {
                this.isShow = this.isShow === true ? false : true;
            },
            autoPlay() {
                this.timer = setInterval(() => {
                    this.goto()
                }, 2000);
            },
            stopPlay() {
                clearInterval(this.timer);
            }
        },
        mounted() {
            this.autoPlay();
        }
    }

</script>

<style scoped>
section {
    background: url(../assets/parallax-two.jpg);
    background-color: rgb(9, 24, 39);
    padding-top: 100px;
    padding-bottom: 100px;
    background-position: 13% -48px;
}
.vc-carousel {
    overflow: hidden;
    margin-top: 40px;
}
.carousel-wrap {
    position: relative;
    top: auto;
    right: auto;
    bottom: auto;
    left: auto;
    width: 100%;
    height: 229px;
    overflow: hidden;
    cursor: move;
}
.carousel-inner {
    text-align:left;
    width: 100%;
    height: 229px;
}
.c-item {
    text-align: center;
    width: 100%;
    transition: all .3s;
}
.c-item span {
    color: #fff;
}
.c-item .item-head {
    font-size: 20px;
    font-weight: 100;
    margin-bottom: 40px;
}
.c-item .red-txt {
    color: #db6f6a;
}
.c-item p {
    color: #eee;
    opacity: .8;
    font-size: .85rem;
}
.carousel-btn a {
    display: inline-block;
    height: 25px;
    width: 25px;
    padding: 0;
    margin: 20px 4px 0;
    background-color: #db6f6a;
    text-align: center;
    border-radius: 2px;
    transition: all .3s ease-in-out;
}
.carousel-btn a i {
    color: #fff;
    font-size: .9rem;
}
.carousel-btn a:hover {
    background-color: #000;
}
</style>
