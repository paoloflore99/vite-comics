<script>

export default {

}
</script>



<!------------------------------------------->


<template>
    <footer>
        <div class="sfondo">
            <div class="opacita">
                <div class="container p-5 ">
                    <div class="row d-flex">
                        <div class="col-2">
                        <ul  class="lista text-white ">
                            <li><strong>DC COMICS</strong></li>
                            <li><a href="#">charater</a></li>
                            <li><a href="#">comics</a></li>
                            <li><a href="#">Movis</a></li>
                            <li><a href="#">Tv</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <ul  class="lista text-white">
                            <li><strong>SHOP</strong></li>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">shop DC Collectibles</a></li>
                        </ul>
                        </div>

                        <div class="col-2">
                        <ul  class="lista text-white">
                            <li><strong>DC COMICS</strong></li>
                            <li><a href="#">charater</a></li>
                            <li><a href="#">comics</a></li>
                            <li><a href="#">Movis</a></li>
                            <li><a href="#">Tv</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <ul   class="lista text-white">
                            <li><strong>SHOP</strong></li>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">shop DC Collectibles</a></li>
                        </ul>
                        </div>

                        <div class="col-2">
                        <ul  class="lista text-white">
                            <li><strong>DC COMICS</strong></li>
                            <li><a href="#">charater</a></li>
                            <li><a href="#">comics</a></li>
                            <li><a href="#">Movis</a></li>
                            <li><a href="#">Tv</a></li>
                            <li><a href="#">Games</a></li>
                        </ul>

                        </div>



                    </div>
                </div>
            </div>
        </div>

        <div class="finale bg-dark">
    <div class="container">
        <div class="row custom-row">
            <div class="col-md-6">
                <button class="btn-personale border-5 border-primary bg-dark text-white">SING-UP NOW!</button>
            </div>

            <div class="col-md-6">
                <div class="follow-us">
                    <h3 class="text-info">FOLLOW US</h3>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
            </div>
        </div>
    </div>
</div>

    </footer>
</template>



<!------------------------------------------->
<style lang="scss" scoped>
.sfondo {
    /* background-color: black;
    opacity: 0.9; */
    background-image: url(../assets/img/footer-bg.jpg);
    /* height: 800px; */
    /* filter: grayscale(var(--value, 100%)); */

}
.finale {
    height: 200px;
    padding: 2rem;
}

.btn-personale {
    width: 180px;
    height: 50px;
    
}

a {
    color: grey;
}

/* .opacita {
    background-color: black;
    opacity: 0.9;
    height: 800px;
} */

.custom-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.follow-us {
    display: flex;
    align-items: center;
    gap: 10px;
}

li {
    list-style: none;
}

a {
    text-decoration: none;
}
</style>
