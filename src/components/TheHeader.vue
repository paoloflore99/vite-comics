<script>

export default {
    data(){
        return {
            cardlist : [
            {},
            {}
            ]
        }
    }
};
</script>

 

<!------------------------------------------->


<template>
    <header>
        <div class=" container">
            <nav class="d-flex justify-content-center">
                <div class=" d-flex">

                    <div>
                        <img class="p-2 logo" src="../assets/img/dc-logo.png" alt="">
                    </div>

                    <div>
                        <ul class="nav nav-pills text-black p-2">
                            <li class="nav-item"><a href="#" class="nav-link">CHARACTER</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">COMICS</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">MOVIES</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">TV</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">GAME</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">COLLECTIBLES</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">VIDEOS</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">FANS</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">NEWS</a></li>
                            <li class="nav-item"><a href="#" class="nav-link">SHOP</a></li>
                        </ul>
                    </div>

                </div>
            </nav>

        </div>

        <div class="sfondo-seconda-parte"></div>



        <secondaparte></secondaparte>




    </header>
</template>



<!------------------------------------------->
<style lang="scss" scoped>

@use "../styles/partials/_variables" as *;

.centratura {
    align-items: centere;
}

.logo {
    width: 100px;
    margin-left: -220px;

}

.nav-link {
    color: black;
}

.sfondo-seconda-parte {
    background-image: url(../assets/img/jumbotron.jpg);
    min-height: 450px;
}
    .btn-centrato {
        
        width: 150px;
    }

.film-sala {

    color: white;
}

</style>

