# demo<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blinkit clone</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.rtl.min.css"
        integrity="sha384-Xbg45MqvDIk1e563NLpGEulpX6AvL404DP+/iCgW9eFa2BqztiwTexswJo2jLMue" crossorigin="anonymous">
    <link rel="stylesheet" href="blinkit.css">
    <link rel="stylesheet" href="blinkit media.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.0/css/all.min.css">
</head>

<body>
    <!-- Header Secrion  -->
    <div class="conatainer-fluid">
        <header>
            <div class="headerLaft">
                <a href="#">
                    <div class="logo"><svg width="134" height="30" viewBox="0 0 114 30" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M14.3342 7.186C16.2619 7.186 17.9832 7.66644 19.4978 8.62732C21.0262 9.57447 22.2242 10.9197 23.0917 12.663C23.9316 14.3377 24.3516 16.3075 24.3516 18.5724C24.3516 20.7687 23.9316 22.7316 23.0917 24.4612C22.2517 26.1908 21.0675 27.5429 19.5391 28.5175C17.9969 29.5058 16.2619 30 14.3342 30C12.9297 30 11.6078 29.7117 10.3685 29.1352C9.12927 28.5587 8.06901 27.7488 7.18775 26.7056V29.4852H0V0H7.18775V10.4598C8.06901 9.41661 9.12927 8.61359 10.3685 8.05079C11.6078 7.47426 12.9297 7.186 14.3342 7.186ZM12.1861 24.0494C13.2051 24.0494 14.1139 23.8161 14.9125 23.3493C15.7112 22.8826 16.3377 22.2306 16.7921 21.3933C17.2465 20.5697 17.4737 19.6294 17.4737 18.5724C17.4737 17.5429 17.2465 16.6095 16.7921 15.7721C16.3377 14.9348 15.7112 14.2828 14.9125 13.8161C14.1139 13.3493 13.2051 13.116 12.1861 13.116C11.2223 13.116 10.3617 13.3493 9.60432 13.8161C8.84699 14.269 8.2549 14.9073 7.82804 15.731C7.40118 16.5683 7.18775 17.5154 7.18775 18.5724C7.18775 19.6294 7.40118 20.5765 7.82804 21.4139C8.2549 22.2375 8.84699 22.8826 9.60432 23.3493C10.3617 23.8161 11.2223 24.0494 12.1861 24.0494Z"
                                fill="#F8CB46"></path>
                            <path d="M25.3356 29.4852V0H32.5233V29.4852H25.3356Z" fill="#F8CB46"></path>
                            <path d="M34.5607 29.4852V7.68016H41.7071V29.4852H34.5607Z" fill="#F8CB46"></path>
                            <path
                                d="M57.2319 7.186C58.7603 7.186 60.1372 7.5429 61.3627 8.25669C62.5882 8.95676 63.5521 9.94509 64.2544 11.2217C64.9291 12.512 65.2664 13.9739 65.2664 15.6074V29.4852H58.4092V17.2135C58.4092 16.4173 58.2508 15.7104 57.9341 15.0927C57.6312 14.4612 57.1974 13.9739 56.6329 13.6307C56.0821 13.2876 55.4349 13.116 54.6914 13.116C53.9891 13.116 53.3419 13.2876 52.7498 13.6307C52.1577 13.9602 51.6965 14.4132 51.366 14.9897C51.0218 15.5388 50.8496 16.1839 50.8496 16.9252L50.8083 29.4852H43.6619V7.68016H50.8083V10.1716C51.483 9.23816 52.3849 8.51064 53.5141 7.98902C54.6432 7.45367 55.8824 7.186 57.2319 7.186Z"
                                fill="#F8CB46"></path>
                            <path
                                d="M81.0597 17.2135L89.1769 29.4852H81.0597L76.3091 21.7639L74.1198 24.2965V29.4852H66.932V0H74.1198V16.2869L81.0184 7.68016H89.1356L81.0597 17.2135Z"
                                fill="#F8CB46"></path>
                            <path d="M34.5569 0.00232667H41.7267V5.59207H34.5569V0.00232667Z" fill="#F8CB46"></path>
                            <path d="M90.3176 29.4198V7.61479H97.464V29.4198H90.3176Z" fill="#54B226"></path>
                            <path
                                d="M112.575 23.2634L114 27.855C113.353 28.4727 112.534 28.9737 111.542 29.3581C110.564 29.7424 109.607 29.9346 108.671 29.9346C107.322 29.9346 106.117 29.6395 105.057 29.0492C103.996 28.4452 103.17 27.6079 102.578 26.5372C101.986 25.494 101.69 24.2929 101.69 22.9339V13.3183H98.819V7.61479H101.69V0.00241089H108.547V7.61479H113.071V13.3183H108.547V21.6161C108.547 22.3162 108.733 22.8859 109.105 23.3251C109.477 23.7644 109.952 23.984 110.53 23.984C110.943 23.984 111.329 23.9223 111.687 23.7987C112.045 23.6752 112.341 23.4967 112.575 23.2634Z"
                                fill="#54B226"></path>
                            <path d="M90.2609 0.00241089H97.4307V5.59215H90.2609V0.00241089Z" fill="#54B226"></path>
                        </svg></div>
                </a>
                <div class="headerText">
                    <h3>Delivery in 8 minutes</h3>
                    <p>121, AB Rd, Bhopal Square, Radhaganj, Itawa, </p>
                </div>
            </div>
            <form class="searchBox">
                <button class="sbbtn"><i class="fa-solid fa-magnifying-glass"></i></button>
                <input type="text">
                
            </form>
            <div class="headerBtn">
                <button class="b1">Log in </button>
                <button class="b2"> <i class="fa-solid fa-cart-shopping"></i> My Cart </button>
            </div>
        </header>
    </div>
    <!-- Header Secrion And  -->

    <!-- bennerSection   -->
    <div class="container">
        <div class="bannerSection-1">
            <img src="banner.webp" alt="">
        </div>
        <div class="bannerSection">

            <div class="banner-items"><img src="m1.avif" alt=""></div>
            <div class="banner-items"><img src="m2.avif" alt=""></div>
            <div class="banner-items"><img src="m3.avif" alt=""></div>
        </div>
    </div>
    <!-- bennerSection And  -->
    <!-- Card Section -->

    <div class="container">
        <div class="cards-Item ">
            <div class="cards"><a href="#"></a><img src="cm1.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm2.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm3.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm4.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm5.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm6.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm7.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm8.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm9.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm10.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm11.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm12.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm13.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm14.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm15.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm16.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm17.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm18.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm19.avif"></div>
            <div class="cards"><a href="#"></a><img src="cm20.avif"></div>
        </div>
    </div>
    <!-- Card Section And -->

    <!-- product section  -->
    

    <!-- first Slider  container -->
    <div class="container">
    <div class="head1">
        <h2>Dairy, Bread & Eggs</h2>
        <button><h1> see all </h1></button>
    </div>
        <div class="swiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper d-flex">
                <!-- Slides -->
                                 <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>

                                <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                
            </div>

            <!-- Navigation buttons -->
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>
    </div>

 <div class="container">
    <div class="hedder">
    <div class="head1">
        <h2>Dairy, Bread & Eggs</h2>
        <button><h1> see all </h1></button>
    </div>
    
    <div class="secCards">
                    <div class="swiper-slide">
                    <img src="sc1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹200
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="sc2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹200
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="sc3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹188
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="sc4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹399
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="sc5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹399
                    <button>ADD</button></div>
                </div>
            </div>


    </div>
    </div>



        <div class="container">
    <div class="head1">
        <h2>Snacks & Munchies</h2>
        <button><h1> see all </h1></button>
    </div>
        <div class="swiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper d-flex">
                <!-- Slides -->
                                 <div class="swiper-slide">
                    <img src="2s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹69
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹350
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹99
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹99
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹139
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹161
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s12.avif" alt="">
                    <div class="title">GNB 65 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹65
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹90
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹100
                    <button>ADD</button></div>
                </div>

                                                 <div class="swiper-slide">
                    <img src="2s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹69
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹350
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹99
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹99
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹139
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹161
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">70
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s12.avif" alt="">
                    <div class="title">GNB 65 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹65
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹90
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="2s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹100
                    <button>ADD</button></div>
                </div>



                
            </div>

            <!-- Navigation buttons -->
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>
    </div>

        <div class="container">
    <div class="head1">
        <h2>Mouth fresheners</h2>
        <button><h1> see all </h1></button>
    </div>
        <div class="swiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper d-flex">
                <!-- Slides -->
                                 <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>

                                <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                
            </div>

            <!-- Navigation buttons -->
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>
    </div>
    
        <div class="container">
    <div class="head1">
        <h2>Cold Drinks & Juices</h2>
        <button><h1> see all </h1></button>
    </div>
        <div class="swiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper d-flex">
                <!-- Slides -->
                                 <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>

                                <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                
            </div>

            <!-- Navigation buttons -->
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>
    </div>
    
        <div class="container">
    <div class="head1">
        <h2>Candies & Gums</h2>
        <button><h1> see all </h1></button>
    </div>
        <div class="swiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper d-flex">
                <!-- Slides -->
                                 <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>

                                <div class="swiper-slide">
                    <img src="s1.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s2.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s3.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s4.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s5.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s6.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s7.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s8.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s9.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s10.avif" alt="">
                    <div class="title">Amul Pure Milk Cheese Slices</div>
                    <div class="price">₹149
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s11.avif" alt="">
                    <div class="title">Modern Family Special White Bread</div>
                    <div class="price">₹35
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s12.avif" alt="">
                    <div class="title">GNB 365 Premium White Bread</div>
                    <div class="price">₹45
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s13.avif" alt="">
                    <div class="title">Sanchi Gold Full Cream Milk</div>
                    <div class="price">₹34
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s14.avif" alt="">
                    <div class="title">Sanchi Plain Pouch Curd</div>
                    <div class="price">₹32
                    <button>ADD</button></div>
                </div>
                <div class="swiper-slide">
                    <img src="s15.avif" alt="">
                    <div class="title">Sanchi Standard Fresh Milk</div>
                    <div class="price">₹31
                    <button>ADD</button></div>
                </div>
                
            </div>

            <!-- Navigation buttons -->
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
        </div>
    </div>



    <!-- Swiper JS -->
    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

    <script>
        const swiper = new Swiper('.swiper', {
            spaceBetween: 16,
            loop: true,
            //   autoplay: {
            //     delay: 2000,
            //     disableOnInteraction: false,
            //   },
            navigation: {
                nextEl: '.swiper-button-next',
                prevEl: '.swiper-button-prev',
            },
            breakpoints: {
                // Mobile
                0: {
                    slidesPerView: 1.2, // थोड़ा हिस्सा दिखेगा next slide का
                },
                // Small Tablets
                480: {
                    slidesPerView: 2.2,
                },
                // Tablets
                768: {
                    slidesPerView: 3.2,
                },
                // Laptops
                1024: {
                    slidesPerView: 4.2,
                },
                // Large screens
                1280: {
                    slidesPerView: 5.2,
                }
            }
        });
    </script>
</body>

</html>
