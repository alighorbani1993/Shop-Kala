<template>
  <div>
    <Head>
      <Title>سبد خرید</Title>
    </Head>
    <header class="page-header d-md-block d-none">
      <!-- start of page-header-top -->
      <div class="page-header--top">
        <div class="container">
          <div class="d-flex align-items-center justify-content-between">
            <div class="page-header--top-right">
              <div class="notification-container notification-light">
                <div class="swiper notification-swiper-slider mb-5">
                  <!-- Additional required wrapper -->
                  <div class="swiper-wrapper">
                    <!-- Slides -->
                    <div class="swiper-slide">
                      <div class="notification-item">
                        <div class="notification-item--text">خوش آمدید 👋</div>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="notification-item">
                        <div class="notification-item--text">
                          زمستان امسال با تخفیفات ويژه 😍
                        </div>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="notification-item">
                        <div class="notification-item--text">
                          به باشگاه مشتریان ما بپیوندید 😎
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="page-header--top-left">
              <ul class="nav nav-light justify-content-end">
                <li class="nav-item">
                  <a class="nav-link" href="#">وبلاگ</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">پرسش های متداول</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">تماس با ما</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">درباره ما</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <!-- end of page-header-top -->
      <!-- start of page-header-middle -->
      <div class="page-header--middle">
        <div class="container">
          <div class="row align-items-center py-4">
            <div class="col-4">
              <div class="user-options">
                <div class="user-option user-option--account">
                  <a href="#" class="user-option-btn user-option-btn--account">
                    <i class="ri-user-fill icon"></i>
                    <i class="ri-arrow-down-s-fill icon fs-7 text-muted"></i>
                  </a>
                  <div class="user-option--dropdown user-option--dropdown-right">
                    <div class="profile-user-info ui-box">
                      <div class="profile-detail">
                        <div class="d-flex align-items-center">
                          <div class="profile-avatar me-3">
                            <img src="/images/avatar/default.png" alt="avatar" />
                          </div>
                          <div class="profile-info">
                            <a
                              href="#"
                              class="text-decoration-none text-dark fw-bold mb-2"
                              >جلال بهرامی راد</a
                            >
                            <div class="text-muted fs-7 fw-bold">۰۹xxxxxxxxx</div>
                          </div>
                        </div>
                        <div class="user-options">
                          <ul>
                            <li>
                              <span class="label">کیف پول</span>
                              <span class="detail">
                                <span class="d-block"
                                  >۰
                                  <span class="currency fs-7 fw-bold">تومان</span></span
                                >
                                <a
                                  href="#"
                                  class="link border-bottom-0 text-info fs-7 fw-bold"
                                  >افزایش موجودی <i class="ri-arrow-left-s-line"></i
                                ></a>
                              </span>
                            </li>
                            <li>
                              <span class="label">باشگاه مشتریان</span>
                              <span class="detail">
                                <span class="d-block"
                                  >۰
                                  <span class="score text-muted fs-7">امتیاز</span></span
                                >
                              </span>
                            </li>
                          </ul>
                        </div>
                      </div>
                      <ul class="nav nav-items-with-icon flex-column">
                        <li class="nav-item">
                          <a class="nav-link" href="#"
                            ><i class="nav-link-icon ri-file-list-3-line"></i> سفارش های
                            من</a
                          >
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#"
                            ><i class="nav-link-icon ri-copper-coin-fill"></i> باشگاه
                            مشتریان</a
                          >
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#"
                            ><i class="nav-link-icon ri-logout-box-r-line"></i> خروج</a
                          >
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
                <div class="user-option">
                  <a href="#" class="user-option-btn user-option-btn--account">
                    <i class="ri-heart-3-fill icon"></i>
                    <span class="counter">۲</span>
                  </a>
                </div>
                <div class="user-option user-option--cart">
                  <a href="#" class="user-option-btn user-option-btn--cart">
                    <i class="ri-shopping-bag-2-fill icon"></i>
                    <span class="user-item-text">
                      <span class="title">سبد خرید شما</span>
                      <span class="value fa-num"
                        >83,678,000 <span class="currency">تومان</span></span
                      >
                    </span>
                    <span class="counter">۴</span>
                  </a>
                  <div class="mini-cart mini-cart-dropdown-right">
                    <div class="mini-cart-header">
                      <span class="mini-cart-products-count fa-num">4 کالا</span>
                      <a href="#" class="btn btn-link px-0"
                        >مشاهده سبد خرید <i class="ri-arrow-left-s-fill"></i
                      ></a>
                    </div>
                    <div class="mini-cart-products do-simplebar">
                      <div class="mini-cart-product">
                        <div class="mini-cart-product-thumbnail">
                          <a href="#"><img src="/images/products/01.jpg" alt="" /></a>
                        </div>
                        <div class="mini-cart-product-detail">
                          <div class="mini-cart-product-brand"><a href="#">apple</a></div>
                          <div class="mini-cart-product-title">
                            <a href="#"
                              >گوشی موبایل اپل مدل iPhone 13 A2634 دو سیم‌ کارت ظرفیت 128
                              گیگابایت و رم 4 گیگابایت</a
                            >
                          </div>
                          <div class="mini-cart-purchase-info">
                            <div class="mini-cart-product-meta">
                              <span class="fa-num">1 عدد</span>
                              <span
                                class="color"
                                style="background-color: #d4d4d4"
                              ></span>
                            </div>
                            <div class="mini-cart-product-price fa-num">
                              26,249,000 <span class="currency">تومان</span>
                            </div>
                          </div>
                          <button class="mini-cart-product-remove"></button>
                        </div>
                      </div>
                      <div class="mini-cart-product">
                        <div class="mini-cart-product-thumbnail">
                          <a href="#"><img src="/images/products/02.jpg" alt="" /></a>
                        </div>
                        <div class="mini-cart-product-detail">
                          <div class="mini-cart-product-brand">
                            <a href="#">xiaomi</a>
                          </div>
                          <div class="mini-cart-product-title">
                            <a href="#"
                              >گوشی موبایل شیائومی مدل 11 lite 5G NE 2109119DG دو سیم‌
                              کارت ظرفیت 256 گیگابایت و رم 8 گیگابایت</a
                            >
                          </div>
                          <div class="mini-cart-purchase-info">
                            <div class="mini-cart-product-meta">
                              <span class="fa-num">1 عدد</span>
                              <span
                                class="color"
                                style="background-color: #d4d4d4"
                              ></span>
                            </div>
                            <div class="mini-cart-product-price fa-num">
                              8,239,000 <span class="currency">تومان</span>
                            </div>
                          </div>
                          <button class="mini-cart-product-remove"></button>
                        </div>
                      </div>
                      <div class="mini-cart-product">
                        <div class="mini-cart-product-thumbnail">
                          <a href="#"><img src="/images/products/05.jpg" alt="" /></a>
                        </div>
                        <div class="mini-cart-product-detail">
                          <div class="mini-cart-product-brand"><a href="#">apple</a></div>
                          <div class="mini-cart-product-title">
                            <a href="#"
                              >گوشی موبایل اپل مدل iPhone 12 Pro Max A2412 دو سیم‌ کارت
                              ظرفیت 256 گیگابایت</a
                            >
                          </div>
                          <div class="mini-cart-purchase-info">
                            <div class="mini-cart-product-meta">
                              <span class="fa-num">1 عدد</span>
                              <span
                                class="color"
                                style="background-color: #d4d4d4"
                              ></span>
                            </div>
                            <div class="mini-cart-product-price fa-num">
                              36,300,000 <span class="currency">تومان</span>
                            </div>
                          </div>
                          <button class="mini-cart-product-remove"></button>
                        </div>
                      </div>
                      <div class="mini-cart-product">
                        <div class="mini-cart-product-thumbnail">
                          <a href="#"><img src="/images/products/07.jpg" alt="" /></a>
                        </div>
                        <div class="mini-cart-product-detail">
                          <div class="mini-cart-product-brand">
                            <a href="#">samsung</a>
                          </div>
                          <div class="mini-cart-product-title">
                            <a href="#"
                              >گوشی موبایل سامسونگ مدل Galaxy S9 Plus دو سیم کارت ظرفیت 64
                              گیگابایت</a
                            >
                          </div>
                          <div class="mini-cart-purchase-info">
                            <div class="mini-cart-product-meta">
                              <span class="fa-num">1 عدد</span>
                              <span
                                class="color"
                                style="background-color: #d4d4d4"
                              ></span>
                            </div>
                            <div class="mini-cart-product-price fa-num">
                              12,890,000 <span class="currency">تومان</span>
                            </div>
                          </div>
                          <button class="mini-cart-product-remove"></button>
                        </div>
                      </div>
                    </div>
                    <div class="mini-cart-footer">
                      <div class="mini-cart-total">
                        <span class="mini-cart-total-label">مبلغ قابل پرداخت:</span>
                        <span class="mini-cart-total-value fa-num"
                          >83,678,000 <span class="currency">تومان</span></span
                        >
                      </div>
                      <a href="#" class="btn btn-primary">ورود و ثبت سفارش</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-4">
              <div class="logo-container">
                <NuxtLink to="/" class="logo">
                  <img src="/images/logo-dark.svg" class="mb-0" width="120" alt="" />
                </NuxtLink>
              </div>
            </div>
            <div class="col-4">
              <div class="user-options justify-content-end">
                <div class="user-option">
                  <a href="#" class="user-option-btn user-option-btn--search">
                    <i class="ri-search-2-fill icon"></i>
                  </a>
                </div>
              </div>
              <div class="mega-search-container">
                <div class="mega-search-box">
                  <form action="#">
                    <input type="text" placeholder="جستجو کنید..." />
                    <i class="ri-search-2-line mega-search-form-icon"></i>
                    <button type="button" class="mega-search-box-close">
                      <i class="ri-close-line"></i>
                    </button>
                  </form>
                  <div class="mega-search-result-container">
                    <ul class="most-searched">
                      <li><a href="#">گل</a></li>
                      <li><a href="#">گلدان</a></li>
                      <li><a href="#">گیاه زینتی</a></li>
                      <li><a href="#">کود</a></li>
                    </ul>
                    <ul class="search-result do-simplebar">
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                      <li><a href="#">گیاه سانسوریا</a></li>
                    </ul>
                    <!-- <div class="search-result-not-found">
                                    <div class="search-result-not-found-icon">
                                        :)
                                    </div>
                                    <div class="search-result-not-found-text">
                                        نتیجه ای برای جستجوی شما پیدا نشد..
                                    </div>
                                </div> -->
                  </div>
                </div>
                <div class="mega-search-overlay"></div>
              </div>
            </div>
            <div class="d-flex align-items-center flex-grow-1 pe-3"></div>
          </div>
        </div>
      </div>
      <!-- end of page-header-middle -->
      <!-- start of page-header-bottom -->
      <div class="page-header--bottom">
        <div class="container">
          <ul class="nav justify-content-center">
            <li class="nav-item mega-menu-btn">
              <a class="nav-link" href="#">زنانه</a>
              <ul class="mega-menu mega-menu-3-col">
                <li class="nav-item-parent"><a href="#">لباس</a></li>
                <li><a href="#">سویشرت و هودی</a></li>
                <li><a href="#">ژاکت و پلیور</a></li>
                <li><a href="#">تی شرت و پولوشرت</a></li>
                <li><a href="#">لباس راحتی و خواب</a></li>
                <li><a href="#">شلوار و سرهمی</a></li>
                <li><a href="#">جین</a></li>
                <li><a href="#">دامن</a></li>
                <li><a href="#">لباس زیر</a></li>
                <li><a href="#">شلوارک</a></li>
                <li class="nav-item-parent"><a href="#">کیف</a></li>
                <li><a href="#">کوله پشتی</a></li>
                <li><a href="#">کیف پول و لوازم آرایش</a></li>
                <li><a href="#">ست کیف و کفش</a></li>
                <li class="nav-item-parent"><a href="#">کفش</a></li>
                <li><a href="#">نیم بوت</a></li>
                <li><a href="#">بوت</a></li>
                <li><a href="#">کالج</a></li>
                <li><a href="#">صندل</a></li>
                <li class="nav-item-parent"><a href="#">لباس</a></li>
                <li><a href="#">سویشرت و هودی</a></li>
                <li><a href="#">ژاکت و پلیور</a></li>
                <li><a href="#">تی شرت و پولوشرت</a></li>
                <li><a href="#">لباس راحتی و خواب</a></li>
                <li><a href="#">شلوار و سرهمی</a></li>
                <li><a href="#">جین</a></li>
                <li><a href="#">دامن</a></li>
                <li><a href="#">لباس زیر</a></li>
                <li><a href="#">شلوارک</a></li>
              </ul>
            </li>
            <li class="nav-item mega-menu-btn">
              <a class="nav-link" href="#">مردانه</a>
              <ul class="mega-menu mega-menu-2-col">
                <li class="nav-item-parent"><a href="#">لباس</a></li>
                <li><a href="#">سویشرت و هودی</a></li>
                <li><a href="#">ژاکت و پلیور</a></li>
                <li><a href="#">تی شرت و پولوشرت</a></li>
                <li><a href="#">لباس راحتی و خواب</a></li>
                <li><a href="#">شلوار و سرهمی</a></li>
                <li><a href="#">جین</a></li>
                <li><a href="#">دامن</a></li>
                <li><a href="#">لباس زیر</a></li>
                <li><a href="#">شلوارک</a></li>
                <li class="nav-item-parent"><a href="#">کیف</a></li>
                <li><a href="#">کوله پشتی</a></li>
                <li><a href="#">کیف پول و لوازم آرایش</a></li>
                <li><a href="#">ست کیف و کفش</a></li>
                <li class="nav-item-parent"><a href="#">کفش</a></li>
                <li><a href="#">نیم بوت</a></li>
                <li><a href="#">بوت</a></li>
                <li><a href="#">کالج</a></li>
                <li><a href="#">صندل</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">بچگانه</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">زیبایی و سلامت</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">وبلاگ</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">پرسش های متداول</a>
            </li>
          </ul>
        </div>
      </div>
      <!-- end of page-header-bottom -->
    </header>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
