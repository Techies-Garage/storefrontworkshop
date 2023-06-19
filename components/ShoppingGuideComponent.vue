<template>
    <!-- shopping guide section -->
    <section class="shopping-banner-section">    
        <div class="shopping-wrapper">
            <!-- <img src="~/assets/images/shopping guide.png" alt="shopping banner" class="shopping-banner"> -->
        </div>
        <div class="shopping-banner-text-wrapper">
            <p class="shopping-storefront-concierge">StoreFront Concierge</p>
            <h1 class="shopping-head-text">
                Unparalleled Luxury Shopping Experience 
            </h1>
            <p class="shopping-para-text">
                From bespoke suits to designer senators, 
                each piece in our carefully curated selection 
                embodies the very essence  
            </p>
            <button class="shopping-guide-button">
                Shopping Guide
            </button>
        </div>        
    </section>
</template>

<style scoped>
    /*  shopping section ********************/
.shopping-banner-section {
    font-family: var(--Manrope-font-family);
    position: relative;
    margin-block-end: 66px;
}
.shopping-wrapper {
    height: 414px;
    min-height: 414px;
    background: linear-gradient(84.21deg, rgba(0, 0, 0, 0.72) 0.81%, rgba(34, 24, 24, 0.424) 67.63%, rgba(75, 53, 53, 0.296) 92.2%, rgba(255, 183, 183, 0.192) 129.86%);
}
.shopping-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.shopping-banner-text-wrapper {
    color: #FFFFFF;
    position: absolute;
    bottom: 90px /*10.54%*/;
    left: 7.4%;
    width: 560.36px;
    /* border: solid 1px red; */
}
.shopping-storefront-concierge {
    font-size: 14px;
    line-height: 17px;
    font-family: var(--Inter-font-family);
    margin-block-end: 0.25rem;
    text-transform: uppercase;
}
.shopping-head-text {
    /* width: 50.45%; */
    /* font-weight: var(--fw-500); */
    text-transform: uppercase;
    font-size: 40px;
    line-height: 49px;
    margin-block-end: 0.25rem;
}
.shopping-para-text {
    font-size: 18px;
    font-family: var(--Inter-font-family);
    line-height: 22px;
    margin-block-end: 33px;
}
.shopping-guide-button {
    padding-inline: 43.5px;
    padding-block: calc(6px + 6px);
    font-size: 12px;
    line-height: 20px;
    font-weight: var(--fw-500);
    color: #F9FAFB;
    background: linear-gradient(84.21deg, rgba(0, 0, 0, 0.72) 0.81%, rgba(34, 24, 24, 0.424) 67.63%, rgba(75, 53, 53, 0.296) 92.2%, rgba(255, 183, 183, 0.192) 129.86%);
    border: solid 1px #F9FAFB;
}

@media (max-width: 900px) {
    .shopping-wrapper {
        height: 433px;
        min-height: 433px;
        /* background: linear-gradient(84.21deg, rgba(0, 0, 0, 0.72) 0.81%, rgba(34, 24, 24, 0.424) 67.63%, rgba(75, 53, 53, 0.296) 92.2%, rgba(255, 183, 183, 0.192) 129.86%); */
    }
    .shopping-head-text {
        font-size: 32px;
        line-height: 39px;
        margin-block-end: 0.25rem;
    }
    .shopping-para-text {
        font-size: 14px;
        font-family: var(--Inter-font-family);
        line-height: 17px;
        margin-block-end: 33px;
    }

    .shopping-banner-text-wrapper {
        width: 90%;
        color: #FFFFFF;
        bottom: 90px /*10.54%*/;
        left: 16px;
        right: 16px;
    }
    .shopping-guide-button {
        width: 100%;
    }
}
</style>