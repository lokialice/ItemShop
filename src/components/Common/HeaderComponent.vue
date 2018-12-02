<template>
    <header class="nk-header nk-header-opaque">

        <!-- START: Top Contacts -->
        <div class="nk-contacts-top">
            <div class="container">
                <div class="nk-contacts-right">
                    <ul class="nk-contacts-icons">

                        <li>
                            <a href="#" data-toggle="modal" data-target="#modalSearch">
                                <span class="fa fa-search"></span>
                            </a>
                        </li>

                        <li>
                            <a href="store-personal.html" >
                                <span class="fa fa-user"></span>
                            </a>
                        </li>

                        <li>
                            <span class="nk-cart-toggle">
                        <span class="fa fa-shopping-cart"></span>
                            <span class="nk-badge">27</span>
                            </span>
                            <div class="nk-cart-dropdown">

                                <div class="nk-widget-post">
                                    <a href="store-product.html" class="nk-post-image">
                                        <img src="https://cdn-html.nkdev.info/goodgames/assets/images/product-5-xs.jpg" alt="In all revolutions of">
                                    </a>
                                    <h3 class="nk-post-title">
                                <a href="#" class="nk-cart-remove-item"><span class="ion-android-close"></span></a>
                                <a href="store-product.html">In all revolutions of</a>
                            </h3>
                                    <div class="nk-gap-1"></div>
                                    <div class="nk-product-price">Price:  23 IST</div>
                                </div>

                                <div class="nk-widget-post">
                                    <a href="store-product.html" class="nk-post-image">
                                        <img src="https://cdn-html.nkdev.info/goodgames/assets/images/product-7-xs.jpg" alt="With what mingled joy">
                                    </a>
                                    <h3 class="nk-post-title">
                                <a href="#" class="nk-cart-remove-item"><span class="ion-android-close"></span></a>
                                <a href="store-product.html">With what mingled joy</a>
                            </h3>
                                    <div class="nk-gap-1"></div>
                                    <div class="nk-product-price">  14 IST</div>
                                </div>

                                <div class="nk-gap-2"></div>
                                <div class="text-center">
                                    <a href="store-checkout.html" class="nk-btn nk-btn-rounded nk-btn-color-main-1 nk-btn-hover-color-white">Proceed to Checkout</a>
                                </div>
                            </div>
                        </li>

                    </ul>
                </div>
            </div>
        </div>

        <nav class="nk-navbar nk-navbar-top nk-navbar-sticky nk-navbar-autohide">
            <div class="container">
                <div class="nk-nav-table">

                    <a href="store.html" class="nk-nav-logo">
                        <img src="@/assets/images/ex-final.png" alt="GoodGames" width="250">
                    </a>

                    <ul class="nk-nav nk-nav-right d-none d-lg-table-cell" data-nav-mobile="#nk-nav-mobile">
                            
                        <li data-toggle="dropdown">
                            <a href="" class="dropdown-toggle" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Category
                            </a>
                            <ul class=" dropdown-menu" aria-labelledby="dropdownMenu2">
                                    <li class="dropdown-item"><a href="store-gallery.html">Dota 2</a></li>
                                    <li class="dropdown-item" ><a href="store-gallery.html">CS Go</a></li>
                                    <li class="dropdown-item"><a href="store-gallery.html">League Of Legend</a></li>
                            </ul>
                        </li>
                        <li class=" nk-drop-item">
                            <a href="tournaments.html">
                Helps

            </a>                            
                        </li>
                        <li class="active nk-drop-item">
                            <a href="store.html">
                Store

            </a>                           
                        </li>
                    </ul>
                    <ul class="nk-nav nk-nav-right nk-nav-icons">

                        <li class="single-icon d-lg-none">
                            <a href="#" class="no-link-effect" data-nav-toggle="#nk-nav-mobile">
                                <span class="nk-icon-burger">
                                    <span class="nk-t-1"></span>
                                <span class="nk-t-2"></span>
                                <span class="nk-t-3"></span>
                                </span>
                            </a>
                        </li>

                    </ul>
                </div>
            </div>
        </nav>
        <!-- END: Navbar -->

    </header>
</template>

<script>
export default {
    name:"HeaderComponent"
}
</script>
