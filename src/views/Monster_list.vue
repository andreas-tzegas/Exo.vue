<script setup>
import TheNav from '../components/TheNav.vue';
import TheFooter from '../components/TheFooter.vue';
</script>


<template>
       <div class="container">
        <TheNav>
        </TheNav>

        <div class="container py-5">
        <div class="row">
            <!-- Monster list Start -->
            <div class="col">
                <div class="mb-5">
                    <h3 class="text-uppercase border-start border-5 border-primary ps-3 mb-4">Every Monsters</h3>
                    <div class="d-flex overflow-hidden mb-3 bg-light">
                        <img class="img-fluid" src="https://botw-compendium.herokuapp.com/api/v3/compendium/entry/guardian_stalker/image" style="width: 100px; height: 100px; object-fit: cover;" alt="">
                        <a href="monster-detail.html" class="h5 d-flex align-items-center bg-light px-3 mb-0">guardian stalker
                        </a>
                    </div>
                    <div class="d-flex overflow-hidden mb-3 bg-light">
                        <img class="img-fluid" src="https://botw-compendium.herokuapp.com/api/v3/compendium/entry/guardian_stalker/image" style="width: 100px; height: 100px; object-fit: cover;" alt="">
                        <a href="monster-detail.html" class="h5 d-flex align-items-center  px-3 mb-0">guardian stalker
                        </a>
                    </div>
                    <div class="d-flex overflow-hidden mb-3 bg-light">
                        <img class="img-fluid" src="https://botw-compendium.herokuapp.com/api/v3/compendium/entry/guardian_stalker/image" style="width: 100px; height: 100px; object-fit: cover;" alt="">
                        <a href="" class="h5 d-flex align-items-center bg-light px-3 mb-0">guardian stalker
                        </a>
                    </div>
                    <div class="d-flex overflow-hidden mb-3 bg-light">
                        <img class="img-fluid" src="https://botw-compendium.herokuapp.com/api/v3/compendium/entry/guardian_stalker/image" style="width: 100px; height: 100px; object-fit: cover;" alt="">
                        <a href="" class="h5 d-flex align-items-center bg-light px-3 mb-0">guardian stalker
                        </a>
                    </div>
                    <div class="d-flex overflow-hidden mb-3 bg-light">
                        <img class="img-fluid" src="https://botw-compendium.herokuapp.com/api/v3/compendium/entry/guardian_stalker/image" style="width: 100px; height: 100px; object-fit: cover;" alt="">
                        <a href="" class="h5 d-flex align-items-center bg-light px-3 mb-0">guardian stalker
                        </a>
                    </div>
                </div>
            </div>
            <!-- Monster list End -->

          
        </div>
    </div>
        
        <TheFooter>
        </TheFooter>
       </div>
</template>

<style>
</style>
