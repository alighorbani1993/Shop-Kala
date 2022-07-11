<template>
  <div>
    <Head>
      <Title>صفحه اصلی</Title>
    </Head>
    <!-- start of mini-slider -->
    <div class="mini-slider-container mb-5">
      <!-- Slider main container -->
      <div class="swiper mini-single-swiper-slider">
        <!-- Additional required wrapper -->
        <div class="swiper-wrapper">
          <!-- Slides -->
          <div class="swiper-slide">
            <a href="#">
              <img src="/images/slider/mini/01.jpg" alt="" />
            </a>
          </div>
          <div class="swiper-slide">
            <a href="#">
              <img src="/images/slider/mini/02.jpg" alt="" />
            </a>
          </div>
          <div class="swiper-slide">
            <a href="#">
              <img src="/images/slider/mini/03.jpg" alt="" />
            </a>
          </div>
          <div class="swiper-slide">
            <a href="#">
              <img src="/images/slider/mini/04.jpg" alt="" />
            </a>
          </div>
        </div>
        <div class="slider-handler">
          <div class="swiper-button-prev"></div>
          <div class="swiper-pagination"></div>
          <div class="swiper-button-next"></div>
        </div>
      </div>
    </div>
    <!-- end of mini-slider -->
    <!-- start of box => categories-slider -->
    <div class="ui-box mb-5">
      <div class="ui-box-title">دسته بندی محصولات</div>
      <div class="ui-box-content">
        <div class="categories-container">
          <!-- Slider main container -->
          <div class="swiper category-swiper-slider pb-5">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper">
              <!-- Slides -->
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/01.jpg" class="category-img" alt="" />
                    <span class="category-title">گوشی موبایل</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/02.jpg" class="category-img" alt="" />
                    <span class="category-title">لوازم جانبی گوشی موبایل</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/03.jpg" class="category-img" alt="" />
                    <span class="category-title">کامپیوترهای All-in-One</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/04.jpg" class="category-img" alt="" />
                    <span class="category-title">کنسول بازی</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/05.jpg" class="category-img" alt="" />
                    <span class="category-title">پخش کننده خانگی</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/06.jpg" class="category-img" alt="" />
                    <span class="category-title">لوازم شست و شو و نظافت</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/07.jpg" class="category-img" alt="" />
                    <span class="category-title">لباس مردانه</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/08.jpg" class="category-img" alt="" />
                    <span class="category-title">لباس زنانه</span>
                  </a>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="category-item">
                  <a href="#">
                    <img src="/images/categories/03.jpg" class="category-img" alt="" />
                    <span class="category-title">کامپیوترهای All-in-One</span>
                  </a>
                </div>
              </div>
            </div>
            <!-- If we need pagination -->
            <div class="swiper-pagination"></div>

            <!-- If we need navigation buttons -->
            <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
          </div>
        </div>
      </div>
    </div>
    <!-- end of box => categories-slider -->
    <!-- start of box -->
    <div class="ui-box bg-white border-0 pb-0">
      <div class="ui-box-title">منتخب محصولات</div>
    </div>
    <!-- start of nav-tabs -->
    <ul
      class="nav nav-pills nav-tabs align-items-center justify-content-center mb-4"
      id="sort-tab"
      role="tablist"
    >
      <li class="nav-item" role="presentation">
        <button
          class="nav-link active"
          id="most-visited-tab"
          data-bs-toggle="tab"
          data-bs-target="#most-visited"
          type="button"
          role="tab"
          aria-controls="most-visited"
          aria-selected="true"
        >
          پربازدید ترین
        </button>
      </li>
      <li class="nav-item" role="presentation">
        <button
          class="nav-link"
          id="best-selling-tab"
          data-bs-toggle="tab"
          data-bs-target="#best-selling"
          type="button"
          role="tab"
          aria-controls="best-selling"
          aria-selected="false"
        >
          پرفروش ترین
        </button>
      </li>
      <li class="nav-item" role="presentation">
        <button
          class="nav-link"
          id="most-popular-tab"
          data-bs-toggle="tab"
          data-bs-target="#most-popular"
          type="button"
          role="tab"
          aria-controls="most-popular"
          aria-selected="false"
        >
          محبوب ترین
        </button>
      </li>
    </ul>
    <!-- end of nav-tabs -->
    <!-- start of tab-content -->
    <div class="tab-content mb-5" id="sort-tabContent">
      <!-- start of tab-pane -->
      <div
        class="tab-pane fade show active"
        id="most-visited"
        role="tabpanel"
        aria-labelledby="most-visited-tab"
      >
        <div class="ui-box pt-3 pb-0 px-0 mb-4">
          <div class="ui-box-content">
            <div class="row mx-0">
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/01.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 13 A2634 دو سیم‌ کارت ظرفیت 128
                        گیگابایت و رم 4 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">26,900,000</del>
                        <span class="discount ms-2">%2</span>
                      </div>
                      <span class="price-now"
                        >26,249,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/02.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل 11 lite 5G NE 2109119DG دو سیم‌ کارت
                        ظرفیت 256 گیگابایت و رم 8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >8,239,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/03.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Redmi Note 10 pro M2101K6G دو سیم‌ کارت
                        ظرفیت 128 گیگابایت و رم 6</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >7,599,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/04.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Z Flip3 5G ظرفیت 256 گیگابایت و رم
                        8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >22,499,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/05.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 12 Pro Max A2412 دو سیم‌ کارت ظرفیت
                        256 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >36,300,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/06.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Mi 11i 5G M2012K11G دو سیم‌ کارت ظرفیت
                        256 گیگابایت و 8 گیگابایت رم</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >16,199,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/07.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy S9 Plus دو سیم کارت ظرفیت 64
                        گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >12,890,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/08.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Note 20 5G SM-N981B/DS دو سیم کارت
                        ظرفیت 256 گیگابایت و رم 8</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">23,570,000</del>
                        <span class="discount ms-2">%3</span>
                      </div>
                      <span class="price-now"
                        >22,799,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/01.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 13 A2634 دو سیم‌ کارت ظرفیت 128
                        گیگابایت و رم 4 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">26,900,000</del>
                        <span class="discount ms-2">%2</span>
                      </div>
                      <span class="price-now"
                        >26,249,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/02.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل 11 lite 5G NE 2109119DG دو سیم‌ کارت
                        ظرفیت 256 گیگابایت و رم 8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >8,239,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/03.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Redmi Note 10 pro M2101K6G دو سیم‌ کارت
                        ظرفیت 128 گیگابایت و رم 6</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >7,599,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/04.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Z Flip3 5G ظرفیت 256 گیگابایت و رم
                        8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >22,499,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- end of tab-pane -->
      <!-- start of tab-pane -->
      <div
        class="tab-pane fade"
        id="best-selling"
        role="tabpanel"
        aria-labelledby="best-selling-tab"
      >
        <div class="ui-box pt-3 pb-0 px-0 mb-4">
          <div class="ui-box-content">
            <div class="row mx-0">
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/05.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 12 Pro Max A2412 دو سیم‌ کارت ظرفیت
                        256 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >36,300,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/06.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Mi 11i 5G M2012K11G دو سیم‌ کارت ظرفیت
                        256 گیگابایت و 8 گیگابایت رم</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >16,199,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/01.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 13 A2634 دو سیم‌ کارت ظرفیت 128
                        گیگابایت و رم 4 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">26,900,000</del>
                        <span class="discount ms-2">%2</span>
                      </div>
                      <span class="price-now"
                        >26,249,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/02.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل 11 lite 5G NE 2109119DG دو سیم‌ کارت
                        ظرفیت 256 گیگابایت و رم 8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >8,239,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/03.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Redmi Note 10 pro M2101K6G دو سیم‌ کارت
                        ظرفیت 128 گیگابایت و رم 6</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >7,599,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/04.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Z Flip3 5G ظرفیت 256 گیگابایت و رم
                        8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >22,499,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/07.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy S9 Plus دو سیم کارت ظرفیت 64
                        گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >12,890,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/08.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Note 20 5G SM-N981B/DS دو سیم کارت
                        ظرفیت 256 گیگابایت و رم 8</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">23,570,000</del>
                        <span class="discount ms-2">%3</span>
                      </div>
                      <span class="price-now"
                        >22,799,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/01.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 13 A2634 دو سیم‌ کارت ظرفیت 128
                        گیگابایت و رم 4 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">26,900,000</del>
                        <span class="discount ms-2">%2</span>
                      </div>
                      <span class="price-now"
                        >26,249,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/02.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل 11 lite 5G NE 2109119DG دو سیم‌ کارت
                        ظرفیت 256 گیگابایت و رم 8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >8,239,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/03.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Redmi Note 10 pro M2101K6G دو سیم‌ کارت
                        ظرفیت 128 گیگابایت و رم 6</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >7,599,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/04.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Z Flip3 5G ظرفیت 256 گیگابایت و رم
                        8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >22,499,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- end of tab-pane -->
      <!-- start of tab-pane -->
      <div
        class="tab-pane fade"
        id="most-popular"
        role="tabpanel"
        aria-labelledby="most-popular-tab"
      >
        <div class="ui-box pt-3 pb-0 px-0 mb-4">
          <div class="ui-box-content">
            <div class="row mx-0">
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/05.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 12 Pro Max A2412 دو سیم‌ کارت ظرفیت
                        256 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >36,300,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/06.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Mi 11i 5G M2012K11G دو سیم‌ کارت ظرفیت
                        256 گیگابایت و 8 گیگابایت رم</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >16,199,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/01.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 13 A2634 دو سیم‌ کارت ظرفیت 128
                        گیگابایت و رم 4 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">26,900,000</del>
                        <span class="discount ms-2">%2</span>
                      </div>
                      <span class="price-now"
                        >26,249,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/02.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل 11 lite 5G NE 2109119DG دو سیم‌ کارت
                        ظرفیت 256 گیگابایت و رم 8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >8,239,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/03.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Redmi Note 10 pro M2101K6G دو سیم‌ کارت
                        ظرفیت 128 گیگابایت و رم 6</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >7,599,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/08.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Note 20 5G SM-N981B/DS دو سیم کارت
                        ظرفیت 256 گیگابایت و رم 8</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">23,570,000</del>
                        <span class="discount ms-2">%3</span>
                      </div>
                      <span class="price-now"
                        >22,799,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/01.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل اپل مدل iPhone 13 A2634 دو سیم‌ کارت ظرفیت 128
                        گیگابایت و رم 4 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #d4d4d4"></span>
                      <span class="color" style="background-color: #e86841"></span>
                      <span class="color" style="background-color: #b82c32"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <div class="d-flex align-items-center">
                        <del class="price-old">26,900,000</del>
                        <span class="discount ms-2">%2</span>
                      </div>
                      <span class="price-now"
                        >26,249,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/04.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Z Flip3 5G ظرفیت 256 گیگابایت و رم
                        8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >22,499,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/07.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy S9 Plus دو سیم کارت ظرفیت 64
                        گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >12,890,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/02.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل 11 lite 5G NE 2109119DG دو سیم‌ کارت
                        ظرفیت 256 گیگابایت و رم 8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #4d5b63"></span>
                      <span class="color" style="background-color: #57415f"></span>
                      <span class="color" style="background-color: #984638"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >8,239,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/03.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل شیائومی مدل Redmi Note 10 pro M2101K6G دو سیم‌ کارت
                        ظرفیت 128 گیگابایت و رم 6</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >7,599,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <!-- start of product-card -->
                <div class="product-card product-card-horizontal">
                  <div class="product-thumbnail">
                    <a href="#">
                      <img src="/images/products/04.jpg" alt="product title" />
                    </a>
                  </div>
                  <div class="product-card-body">
                    <h2 class="product-title">
                      <a href="#"
                        >گوشی موبایل سامسونگ مدل Galaxy Z Flip3 5G ظرفیت 256 گیگابایت و رم
                        8 گیگابایت</a
                      >
                    </h2>
                    <div class="product-variant">
                      <span class="color" style="background-color: #24476e"></span>
                      <span class="color" style="background-color: #12505b"></span>
                      <span class="color" style="background-color: #e4a793"></span>
                      <span>+</span>
                    </div>
                    <div class="product-price fa-num">
                      <span class="price-now"
                        >22,499,000 <span class="currency">تومان</span></span
                      >
                    </div>
                  </div>
                  <div class="product-card-footer">
                    <div
                      class="d-flex align-items-center justify-content-between mt-2 py-2"
                    >
                      <div class="product-actions">
                        <ul>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به سبد خرید"
                              aria-label="افزودن به سبد خرید"
                              ><i class="ri-shopping-cart-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="مشاهده سریع"
                              aria-label="مشاهده سریع"
                              data-remodal-target="quick-view-modal"
                              ><i class="ri-search-line"></i
                            ></a>
                          </li>
                          <li>
                            <a
                              href="#"
                              data-bs-toggle="tooltip"
                              data-bs-placement="top"
                              title=""
                              data-bs-original-title="افزودن به علاقمندی"
                              aria-label="افزودن به علاقمندی"
                              ><i class="ri-heart-3-line"></i
                            ></a>
                          </li>
                        </ul>
                      </div>
                      <div class="product-rating fa-num">
                        <i class="ri-star-fill star"></i>
                        <strong>۴.۴</strong>
                        <span>(۴۳۶)</span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- end of product-card -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- end of tab-pane -->
    </div>
    <!-- end of tab-content -->
    <!-- end of box -->
    <div class="ads-container">
      <!-- start of nav-tabs -->
      <nav>
        <div class="nav nav-tabs justify-content-center" id="nav-tab" role="tablist">
          <button
            class="nav-link active"
            id="nav-1-tab"
            data-bs-toggle="tab"
            data-bs-target="#nav-1"
            type="button"
            role="tab"
            aria-controls="nav-1"
            aria-selected="true"
          >
            زیبایی و سلامت
          </button>
          <button
            class="nav-link"
            id="nav-2-tab"
            data-bs-toggle="tab"
            data-bs-target="#nav-2"
            type="button"
            role="tab"
            aria-controls="nav-2"
            aria-selected="false"
          >
            مردانه
          </button>
          <button
            class="nav-link"
            id="nav-3-tab"
            data-bs-toggle="tab"
            data-bs-target="#nav-3"
            type="button"
            role="tab"
            aria-controls="nav-3"
            aria-selected="false"
          >
            زنانه
          </button>
          <button
            class="nav-link"
            id="nav-4-tab"
            data-bs-toggle="tab"
            data-bs-target="#nav-4"
            type="button"
            role="tab"
            aria-controls="nav-4"
            aria-selected="false"
          >
            بچگانه
          </button>
        </div>
      </nav>
      <!-- end of nav-tabs -->
      <!-- start of tab-content -->
      <div class="tab-content" id="nav-tabContent">
        <!-- start of tab-pane -->
        <div
          class="tab-pane py-4 fade show active"
          id="nav-1"
          role="tabpanel"
          aria-labelledby="nav-1-tab"
        >
          <div class="row">
            <div class="col-12 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">لوازم آرایشی</span>
                  <img src="/images/banner/01.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">لوازم بهداشتی</span>
                  <img src="/images/banner/02.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">لوازم شخصی برقی</span>
                  <img src="/images/banner/03.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">عطر</span>
                  <img src="/images/banner/04.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">ابزار سلامت</span>
                  <img src="/images/banner/05.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
          </div>
        </div>
        <!-- end of tab-pane -->
        <!-- start of tab-pane -->
        <div
          class="tab-pane py-4 fade"
          id="nav-2"
          role="tabpanel"
          aria-labelledby="nav-2-tab"
        >
          <div class="row">
            <div class="col-12 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">لباس مردانه</span>
                  <img src="/images/banner/06.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">کفش مردانه</span>
                  <img src="/images/banner/07.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">اکسسوری مردانه</span>
                  <img src="/images/banner/08.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">ورزشی مردانه</span>
                  <img src="/images/banner/09.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
          </div>
        </div>
        <!-- end of tab-pane -->
        <!-- start of tab-pane -->
        <div
          class="tab-pane py-4 fade"
          id="nav-3"
          role="tabpanel"
          aria-labelledby="nav-3-tab"
        >
          <div class="row">
            <div class="col-12 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">لباس زنانه</span>
                  <img src="/images/banner/010.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">کفش زنانه</span>
                  <img src="/images/banner/011.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">اکسسوری زنانه</span>
                  <img src="/images/banner/012.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">ورزشی زنانه</span>
                  <img src="/images/banner/013.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
          </div>
        </div>
        <!-- end of tab-pane -->
        <!-- start of tab-pane -->
        <div
          class="tab-pane py-4 fade"
          id="nav-4"
          role="tabpanel"
          aria-labelledby="nav-4-tab"
        >
          <div class="row">
            <div class="col-12 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">نوزاد</span>
                  <img src="/images/banner/014.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">دخترانه</span>
                  <img src="/images/banner/015.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
            <div class="col-lg-6 mb-4">
              <!-- start of banner -->
              <div class="banner-container">
                <a href="#">
                  <span class="banner-text">پسرانه</span>
                  <img src="/images/banner/016.jpg" class="banner-image" alt="" />
                </a>
              </div>
              <!-- end of banner -->
            </div>
          </div>
        </div>
        <!-- end of tab-pane -->
      </div>
      <!-- end of tab-content -->
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
