<template>
    <header :class="{isSticky: isSticky}">
        <nav class="navbar navbar-expand-md container py-0 clearfix">
            <a href="" class="navbar-brand">
                <img src="../assets/logo-2.png" alt="">
            </a>
            <button class="navbar-toggler ml-auto" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
                <span class="navbar-toggler-icon">
                    <i :class="{'bar-white': !isSticky, 'bar-dark': isSticky}" class="zi zi_bars" zico="栅栏" id="bars"></i>
                </span>
            </button>
            <div class="collapse navbar-collapse" id="collapsibleNavbar">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a :class="{'a-color-while-isSticky': isSticky, 'a-white': !isSticky}" class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a :class="{'a-color-while-isSticky': isSticky, 'a-white': !isSticky}" class="nav-link" href="#overview">Overview</a>
                    </li>
                    <li class="nav-item">
                        <a :class="{'a-color-while-isSticky': isSticky, 'a-white': !isSticky}" class="nav-link" href="#benefits">Benefits</a>
                    </li> 
                    <li class="nav-item">
                        <a :class="{'a-color-while-isSticky': isSticky, 'a-white': !isSticky}" class="nav-link" href="#screenshots">Screenshots</a>
                    </li>
                    <li class="nav-item">
                        <a :class="{'a-color-while-isSticky': isSticky, 'a-white': !isSticky}" class="nav-link" href="#Testmonials">Testmonials</a>
                    </li>
                    <li class="nav-item">
                        <a :class="{'a-color-while-isSticky': isSticky, 'a-white': !isSticky}" class="nav-link" href="#FAQ">FAQs</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<script>
export default {
    data() {
        return {
            isSticky: false
        }
    },
    methods: {
        hasScroll() {
            this.isSticky = window.scrollY > 0;
        }
    },
    created() {
        window.addEventListener('scroll', this.hasScroll);
    }
}
</script>

<style scoped>
header {
    z-index: 1000;
    position: absolute;
    top: 0;
    background-color: transparent;
    width: 100%;
}
.isSticky {
    position: fixed;
    top: 0;
    background: #fff;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.19);
}
.bar-white {
    color: #fff;
}
.bar-dark {
    color: #999;
}
#collapsibleNavbar .a-white {
    color: #fff;
}
.a-color-while-isSticky {
    color: #777;
}
#collapsibleNavbar a:hover {
    color: #fa8322;
}
</style>



