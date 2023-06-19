<template>
    <!-- new arrival section -->
    <section class="new-arrivals-section">
        <p class="new-arrival-text">New arrivals</p>
        <h2 class="new-arrival-head-header">Where Modern Meets Luxury</h2>
        <div class="suits-parent-grids">
            <div class="suit-grid-item">
                <div class="card-img-wrapper">
                    <img src="~/assets/images/coat-only.png" class="new-coat" alt="new suit">            
                    <!--Default: show only Label for product -->
                    <div class="absolute position-top product-default-label ">
                        <div>
                            <!-- <img src="~/assets/images/like-icon.png" class="like" alt="like this product"> -->
                        </div>
                        <p class="label-new">NEW</p>
                    </div>
                    
                    <!-- Hover effect: both label and Like icon-->
                    <div class="absolute position-top product-hover-label ">
                        <p class="label-new">NEW</p>
                        <div>
                            <img src="~/assets/images/like-icon.png" class="like" alt="like this product">
                        </div>
                    </div>
                    
                    <!-- next and previous button -->
                    <div class="absolute position-middle show-next-previous-but ">
                        <div>
                            <img src="~/assets/images/previous-icon.png" width="25" class="like" alt="previous product button">
                        </div>
                        <div>
                            <img src="~/assets/images/next-icon.png" width="25" class="like" alt="next product button">
                        </div>
                    </div>
                </div>
                <!-- card caption text -->
                <div class="grid-text-capture">
                    <p class="suit-capture">Dotted jacquard, half double breasted</p>
                    <p class="suit-price">N300,000.00</p>
                </div>
            </div>
            <div class="suit-grid-item">
                <div class="card-img-wrapper">
                    <img src="~/assets/images/coat-only.png" class="new-coat" alt="new suit">            
                    <!--Default: ahow only Label for product -->
                    <div class="absolute position-top product-default-label ">
                        <div>
                            <!-- <img src="~/assets/images/like-icon.png" class="like" alt="like this product"> -->
                        </div>
                        <p class="label-new">NEW</p>
                    </div>
                    
                    <!-- Hover effect: both label and Like icon-->
                    <div class="absolute position-top product-hover-label ">
                        <p class="label-new">NEW</p>
                        <div>
                            <img src="~/assets/images/like-icon.png" class="like" alt="like this product">
                        </div>
                    </div>
                    
                    <!-- next and previous button -->
                    <div class="absolute position-middle show-next-previous-but ">
                        <div>
                            <img src="~/assets/images/previous-icon.png" width="25" class="like" alt="previous product button">
                        </div>
                        <div>
                            <img src="~/assets/images/next-icon.png" width="25" class="like" alt="next product button">
                        </div>
                    </div>
                </div>
                <!-- card caption text -->
                <div class="grid-text-capture">
                    <p class="suit-capture">Dotted jacquard, half double breasted</p>
                    <p class="suit-price">N300,000.00</p>
                </div>
            </div>
            <div class="suit-grid-item">
                <div class="card-img-wrapper">
                    <img src="~/assets/images/coat-only.png" class="new-coat" alt="new suit">            
                    <!--Default: ahow only Label for product -->
                    <div class="absolute position-top product-default-label ">
                        <div>
                            <!-- <img src="~/assets/images/like-icon.png" class="like" alt="like this product"> -->
                        </div>
                        <p class="label-new">NEW</p>
                    </div>
                    
                    <!-- Hover effect: both label and Like icon-->
                    <div class="absolute position-top product-hover-label ">
                        <p class="label-new">NEW</p>
                        <div>
                            <img src="~/assets/images/like-icon.png" class="like" alt="like this product">
                        </div>
                    </div>
                    
                    <!-- next and previous button -->
                    <div class="absolute position-middle show-next-previous-but ">
                        <div>
                            <img src="~/assets/images/previous-icon.png" width="25" class="like" alt="previous product button">
                        </div>
                        <div>
                            <img src="~/assets/images/next-icon.png" width="25" class="like" alt="next product button">
                        </div>
                    </div>
                </div>
                <!-- card caption text -->
                <div class="grid-text-capture">
                    <p class="suit-capture">Dotted jacquard, half double breasted</p>
                    <p class="suit-price">N300,000.00</p>
                </div>
            </div>
            <div class="suit-grid-item">
                <div class="card-img-wrapper">
                    <img src="~/assets/images/coat-only.png" class="new-coat" alt="new suit">            
                    <!--Default: ahow only Label for product -->
                    <div class="absolute position-top product-default-label ">
                        <div>
                            <!-- <img src="~/assets/images/like-icon.png" class="like" alt="like this product"> -->
                        </div>
                        <p class="label-new">NEW</p>
                    </div>
                    
                    <!-- Hover effect: both label and Like icon-->
                    <div class="absolute position-top product-hover-label ">
                        <p class="label-new">NEW</p>
                        <div>
                            <img src="~/assets/images/like-icon.png" class="like" alt="like this product">
                        </div>
                    </div>
                    
                    <!-- next and previous button -->
                    <div class="absolute position-middle show-next-previous-but ">
                        <div>
                            <img src="~/assets/images/previous-icon.png" width="25" class="like" alt="previous product button">
                        </div>
                        <div>
                            <img src="~/assets/images/next-icon.png" width="25" class="like" alt="next product button">
                        </div>
                    </div>
                </div>
                <!-- card caption text -->
                <div class="grid-text-capture">
                    <p class="suit-capture">Dotted jacquard, half double breasted</p>
                    <p class="suit-price">N300,000.00</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
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
</style>

<script>

</script>