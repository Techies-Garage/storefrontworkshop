<template>
    <nav class="nav-container">
        <div class="top-nav-wrapper hide-for-mobile">
            <nav class="top-nav-items-wrapper nav-items-states">
                <a href="#"> Men </a>
                <a href="#"> Women</a>
                <a href="#"> kids </a>
            </nav>
            <div><img src="~/assets/images/StoreFront Logo.svg" alt=""></div>
            <form action="" class="search-form">
                <div class="search-bar">
                    <img class="search-icon" src="~/assets/images/Icon.svg" alt="">
                    <input onclick="handleClick()" id="search-input" class="search-field" type="search" placeholder="Search clothes and accessories">
                </div>
            </form>
        </div>
        <hr class="hide-for-mobile">
        <div class="primary-nav-bar hide-for-mobile">
           <nav class="primary-nav-items-wrapper nav-items-states">
                <a href="#" class="nav-item1">Brands</a>
                <a href="#" class="nav-item2"> Suits</a>
                <a href="#" class="nav-item3"> Shirts</a>
                <a href="#" class="nav-item4">Senators</a>
                <a href="#" class="nav-item5">Natives</a>
                <a href="#" class="nav-item6">Coats & Jackets</a>
           </nav>
           <div class="cart-like-login">
                <img src="~/assets/images/like-icon.png" alt="like a product" class="like-icon">
                <img src="~/assets/images/cart-icon.png" alt="items added to cart" class="cart-icon">
                <div role="button" id="login" class="login-button">Login</div>
            </div>
        </div>

        <!-- mobile navigation section  -->
        <nav class="hide-for-desktop show-for-mobile">
           <div class="top-nav-wrapper">
               <div>
                    <img src="~/assets/images/menu.png" alt="open menu items" title="open nav items">
                </div>

                <div><img src="~/assets/images/StoreFront Logo.svg" alt=""></div>
                
                <div class="cart-like-login">
                    <img src="~/assets/images/like-icon.png" alt="like a product" class="like-icon">
                    <img src="~/assets/images/cart-icon.png" alt="items added to cart" class="cart-icon">
                </div>
            </div>
            <hr>
            <div class="primary-nav-bar">
                <form action="" class="search-form">
                    <div class="search-bar">
                        <img class="search-icon" src="~/assets/images/Icon.svg" alt="">
                        <input onclick="handleClick()" class="search-field" id="search-input" type="search" placeholder="Search clothes and accessories">
                    </div>
                </form>
            </div>
        </nav>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
.hide-for-desktop {
    display: none;
}
.nav-container {
    font-family: var(--Inter-font-family);
    padding-block: 10px;
    padding-inline: 7.4%;
    display: flex;
    flex-direction: column;
}
.primary-nav-bar,
.top-nav-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.nav-items-states {
    display: flex;
    column-gap: 1.5rem;
}
.nav-items-states a {
    text-decoration-line: none;
    color: #737373; 
    padding-block: 14px;
    padding-inline: 5px;
}
.nav-items-states a:hover {
    color: #404040;
    text-decoration-line: underline;
    text-underline-offset: 5px;
}
.nav-items-states a:focus {
    color: #404040;
    text-underline-offset: 3px;
    font-weight :var(--fw-600);
}
.search-form {
    border: 1px solid;
    background: #FAFAFA;
    border: 1px solid #E5E5E5;
    box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05);
}
.search-bar {
    display: flex;
    align-items: center;
    justify-content: start;
    flex-grow: 1;
}
.search-icon {
    padding-inline: 17px;
    padding-block: 15px;
}
.search-field {
    padding-inline: 5px;
    padding-block: 14px;
    border: none;
    flex-grow: 1;
    font-size: 14px;
    background: #FAFAFA;
    font-family: 'Inter', sans-serif;
}
.primary-nav-bar {
    height: 48px;
}
.cart-like-login {
    display: flex;
    align-items: center;
    gap: 2rem;
}
.cart-like-login .cart-icon,
.cart-like-login .like-icon,
.cart-like-login .login-button {
    padding-block: 14px;
    padding-inline: 5px;
}
hr {
    margin-block: 5px;
}



/* New arrival section styles ************/
.new-arrivals-section {
    font-family: var(--Manrope-font-family);
    padding-inline: 1rem;
    margin-block-end: 8rem; /*128px*/
}
.new-arrival-head-header,
.new-arrival-text {
    text-transform: uppercase;
    text-align: center;
}
.new-arrival-text {
    color: #1F2937;
    font-family: var(--Inter-font-family);
    margin-block: 4px;
}
.new-arrival-head-header {
    font-size: 2rem;
    font-weight: var(--fw-600);
    color: #404040;
    margin-block-end: 48px;
}
.suits-parent-grids {
    display: grid;
    row-gap: 5rem;
    /* column-gap: 3rem; */
    grid-template-columns: repeat(auto-fit, minmax(auto, 366px));
    justify-content: center;
    align-items: center;
}
.suit-grid-item {
    width: 366px;
    font-size: 24px;
    color: #262626;
    position: relative;
}

.suit-grid-item:hover {
    background: #FFFFFF;
}
.suit-grid-item img.new-coat {
    width: 100%;
    object-fit: contain;
}
.suit-capture {
    margin-block-start: 14px;
    margin-block-end: 20px;
}
.suit-price {
    font-weight: var(--fw-500);
}
.label-new {
    font-weight: 500;
    font-size: 16px;
    line-height: 44px;
    background: #FFFFFF;
    padding: 5px 15px;
    color: #262626;
    border-radius: 2px;    
}
.suit-grid-item:hover .label-new{
    background: rgba(238, 238, 238, 0.95);
}
.absolute {
    position: absolute;
}
.position-top {
    left: 10px;
    right: 10px;
    top: 4px;
}
.position-middle {
    left: 10px;
    right: 10px;
    top: 40%;
}
.product-default-label {
    display: flex;
    justify-content: space-between;       
    align-items: center;
}
.suit-grid-item:hover .product-default-label {
    display: none;
}
.show-next-previous-but,
.product-hover-label{
    display: none;
}
.suit-grid-item:hover .show-next-previous-but,
.suit-grid-item:hover .product-hover-label {
    display: flex;
    justify-content: space-between;       
    align-items: center;
}


/*  shopping section ********************/
.shopping-banner-section {
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

    /* navigation css styles  *******************/
    .hide-for-mobile {
        display: none;
    }
    .show-for-mobile {
        display: block;
    }
    .primary-nav-bar {
        width: 100%;
    }
    .search-form {
        display: flex;
        flex: 1;
    }
    .search-bar {
        display: flex;
        align-items: center;
    }
    
    

    /* shopping guide banner section ****************/
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
    
    
    @media (max-width: 425px) {
        
       
    }
}
</style>