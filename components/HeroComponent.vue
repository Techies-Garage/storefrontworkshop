<template>
    <!-- banner(hero) section -->
    <section class="main-banner">    
        <div class="hero-wrapper">
            <img src="~/assets/images/Hero-banner-desktop.png" alt="hero banner" class="hero-banner">
        </div>
        <div class="banner-text-wrapper">
            <h1 class="banner-head-text">
                Discover the Essence of Nigerian Fashion 
            </h1>
            <p class="banner-para-text">
                From the sleek and intuitive interface to the curation 
                of the finest high-end fashion brands, 
                our platform is designed to cater to your every need. 
            </p>
        </div>        
    </section>
</template>

<script>

</script>

<style>
html {
    font-size: 16px;
}

body {
    font-family: var(--Manrope-font-family); 
}
.hide-for-desktop {
    display: none;
}
.hide {
    display: none;
}

/* Bannner section **********************/
.main-banner {
    position: relative;
    margin-block-end: 66px;
}
.hero-wrapper {
    height: 569px;
    min-height: 569px;
}
.hero-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.banner-text-wrapper {
    color: #FFFFFF;
    position: absolute;
    bottom: 60px /*10.54%*/;
    left: 7.4%;
}
.banner-head-text {
    width: 50.45%;
    font-weight: var(--fw-500);
    text-transform: uppercase;
    font-size: 56px;
    line-height: 57.46px;
    margin-block-end: 0.5rem;
}
.banner-para-text {
    font-size: 20px;
    font-family: var(--Inter-font-family);
    width: 43.492%;
    line-height: 24.2px;
}

@media (max-width: 900px) {
    /* Hero section *************************/
    .hero-wrapper {
        height: 573px;
        min-height: 573px;
        -webkit-transform: scaleX(-1);
        transform: scaleX(-1);
    }
    .banner-text-wrapper {
        color: #FFFFFF;
        position: absolute;
        bottom: 60px /*10.54%*/;
        left: 7.4%;
    }
    .banner-head-text {
        font-weight: var(--fw-600);
        text-transform: uppercase;
        font-size: 32px;
        line-height: 34.75px;
        width: 82.442%;
    }
    .banner-para-text {
        font-size: 14px;
        font-family: var(--Inter-font-family);
        width: 92.277%;
        line-height: 16.94px;
    }
}
</style>