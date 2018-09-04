<template>
    <footer>
        <div class="widgets-area">
            <div class="container">
                <div class="row">
                    <div class="col-sm-12 col-md-4">
                        <div class="widget-text">
                            <h4>THE SKIPT APP</h4>
                            <p>SKIPT enables users to buy and sell any spot, in any line by giving users the opportunity to find one another based on their location. With SKIPT, you decide how to spend your time. Any line. Any time. Any where.</p>
                            <p>
                                <a href="#overview">Back to overview»</a>
                            </p>
                        </div>
                    </div>
                    <div class="col-sm-12 col-md-4">
                        <h4>CONTACT</h4>
                        <p>
                            <a href="#">iloveSKIPT@theskiptapp.com</a>
                        </p>
                    </div>
                    <div class="col-sm-12 col-md-4">
                        <h4>SOCLAL</h4>
                        <div class="widget-icon" >
                            <a href="#">
                                <div class="icon-wrap" style="border-color:#00aced;">
                                    <span style="background-color:#00aced;border-color:#00aced;">
                                        <i class="zi zi_tmTwittersquare" zico="twittersquare"></i>
                                    </span>
                                </div>
                            </a>
                            <a href="#">
                                <div class="icon-wrap" style="border-color:#517fa4;">
                                    <span style="background-color:#517fa4;border-color:#517fa4;">
                                        <i class="zi zi_tmInstagram" zico="instagram"></i>
                                    </span>
                                </div>
                            </a>
                            <a href="#">
                                <div class="icon-wrap" style="border-color:#3b5998;">
                                    <span style="background-color:#3b5998;border-color:#3b5998;">
                                        <i class="zi zi_tmFacebookf" zico="facebookf"></i>
                                    </span>
                                </div>
                            </a>
                            <a href="#">
                                <div class="icon-wrap" style="border-color:#cb2027;">
                                    <span style="background-color:#cb2027;border-color:#cb2027;">
                                        <i class="zi zi_tmGoogle" zico="google"></i>
                                    </span>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="bottom-band">
            <div class="container">
                <div class="row">
                    <div class="col-md-6 col-sm-12 copy-info">
                        @
                        <a href="">The Skipt App</a>
                         All Rights Reserved 2018			        
                    </div>
                    <div class="col-md-6 col-sm-12">
                        <nav class="footer-menu">
                            <ul>
                                <li>
                                    <a href="#home">Home</a>
                                </li>
                                <li>
                                    <a href="#overview">Overview</a>
                                </li>
                                <li><a href="#benefits">Benefits</a></li>
                                <li><a href="#screenshots">Screenshots</a></li>
                                <li><a href="#testimonials">Testimonials</a></li>
                                <li><a href="#FAQ">FAQ</a></li>
                            </ul>
                        </nav>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
</script>

<style scoped>
footer {
  background-color: #2b2b2b;
  color: #999;
  font-size: 12px;
}
.widgets-area {
  padding: 56px 0 28px 0;
  min-height: 300px;
}
.widgets-area h4 {
  font-size: 15px;
  color: #ccc;
}
.widgets-area p a {
  color: #db6f6a;
}
.widgets-area p a:hover {
  text-decoration: underline;
}

.widget-icon .icon-wrap {
  border: 1px solid #fa8322;
  display: inline-block;
  margin: 0 5px 5px 0;
  padding: 3px;
}
.widget-icon .icon-wrap span {
  display: block;
  position: relative;
  text-align: center;
  transition: all 0.2s ease-in-out;
  width: 26px;
  height: 26px;
}
.widget-icon .icon-wrap span:hover {
    opacity: .8;
}
.widget-icon .icon-wrap i {
  font-size: 14px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  line-height: 1;
  color: #fff;
}

.bottom-band {
    background-color: #242424;
    color: #666;
    border-top: 1px solid #222;
    padding: 17px 0;
    font-size: 11px;
}
.bottom-band a {
    color: #888;
}
.bottom-band a:hover {
    color: #db6f6a;
    text-decoration: underline;
}
.footer-menu ul {
    list-style: none;
    text-align: right;
    overflow: hidden;
}
.footer-menu ul li {
    display: inline-block;
    padding: 0 8px 0 5px;
    border-right: 1px solid;
}
.footer-menu ul li:last-child {
    border: none;
}
</style>
