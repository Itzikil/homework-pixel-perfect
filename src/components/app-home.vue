<template>
    <!-- <div class="background"> -->
        <section class="home flex justify-center align-items column full main-layout">
            <div class="page-intro flex column align-center">
            <img src="../assets/imgs/illustration-intro.png" alt="">
            <h2 class="text-center">All your files in one secure location, accessible anywhere.</h2>
            <p class="intro-text text-center">Flyo stores all your most important files on one secure location.
                Access them wherever you need, share and collaborate with
                friends family, and co-workers</p>
            <button class="btn">Get Started</button>
        </div>
        <div class="main-page full main-layout">
            <mainFeatures />
            <stayProductive/>
            <profileCards/>
            <signUp/>
        </div>
    </section>
<!-- </div> -->
</template>

<script>
import stayProductive from './stay-productive.vue';
import profileCards from './profile-cards.vue'
import mainFeatures from './main-features.vue'
import signUp from './sign-up.vue';
export default {

    components: {
        stayProductive,
        profileCards,
        mainFeatures,
        signUp
    }
}
</script>