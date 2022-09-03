<script setup>
import { Head, Link } from "@inertiajs/inertia-vue3";
import GuestLayout from "@/Layouts/Guest.vue";

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    <Head title="Forms Living" />

    <GuestLayout>
        <div class="index">
            <div class="cta">
                <div class="container-fluid left-side">
                    <div class="row align-items-center">
                        <div class="col-12 col-lg-6 cta-text mb-4 mb-lg-0">
                            <h5 class="cta-subtitle" data-aos="fade-right">
                                Selamat datang di FORMS Living
                            </h5>
                            <h1
                                class="cta-title"
                                data-aos="fade-right"
                                data-aos-delay="400"
                            >
                                Representasi gaya hidup millenials dalam satu
                                genggaman
                            </h1>
                            <p
                                class="cta-desc"
                                data-aos="fade-right"
                                data-aos-delay="600"
                            >
                                Lorem ipsum dolor sit amet consectetur
                                adipisicing elit. Accusantium ullam soluta
                                laudantium at, minima temporibus sapiente!
                            </p>
                            <div
                                class="actions"
                                data-aos="fade-right"
                                data-aos-delay="600"
                            >
                                <button type="button" class="btn btn-primary">
                                    Jelajahi Sekarang
                                </button>
                                <button
                                    type="button"
                                    class="btn btn-blank-primary"
                                >
                                    <img
                                        src="../../images/ic-play-fill.png"
                                        alt=""
                                    />
                                    <span>Tonton Video</span>
                                </button>
                            </div>
                            <div
                                class="sponsor"
                                data-aos="fade-right"
                                data-aos-delay="600"
                                data-aos-offset="0"
                            >
                                <p>Trusted by</p>
                                <div class="logos">
                                    <div class="item">
                                        <img
                                            src="../../images/logo-tidar-gray.png"
                                            alt=""
                                        />
                                    </div>
                                    <div class="item">
                                        <img
                                            src="../../images/logo-project2b.png"
                                            alt=""
                                        />
                                    </div>
                                    <div class="item">
                                        <img
                                            src="../../images/logo-project3b.png"
                                            alt=""
                                        />
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div
                            class="col-12 col-lg-6 cta-img pe-0"
                            data-aos="fade-left"
                            data-aos-delay="400"
                        >
                            <div class="image-sliders">
                                <div>
                                    <img
                                        src="../../images/img-splash-screen.png"
                                        class="w-100"
                                        alt=""
                                    />
                                </div>
                                <div>
                                    <img
                                        src="../../images/img-cluster-large1.png"
                                        class="w-100"
                                        alt=""
                                    />
                                </div>
                                <div>
                                    <img
                                        src="../../images/img-cluster-large2.png"
                                        class="w-100"
                                        alt=""
                                    />
                                </div>
                            </div>
                            <div class="text-blur-bg text-sliders">
                                <div>
                                    <h5>Apartemen</h5>
                                    <small
                                        >Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit. Sed dignissim interdum
                                        neque vel euismod.
                                    </small>
                                </div>
                                <div>
                                    <h5>Mall</h5>
                                    <small
                                        >Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit. Sed dignissim interdum
                                        neque vel euismod.
                                    </small>
                                </div>
                                <div>
                                    <h5>Hotel</h5>
                                    <small
                                        >Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit. Sed dignissim interdum
                                        neque vel euismod.
                                    </small>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="mobile-only">
                <div class="cta-mobile">
                    <div class="container">
                        <div class="sliders-mobile">
                            <a href="/greenland.html" class="item">
                                <div class="logo">
                                    <img
                                        src="../../images/logo-tidar-white.png"
                                        alt=""
                                    />
                                </div>
                                <div class="item-img">
                                    <img
                                        src="../../images/mobile-sliders1.png"
                                        alt=""
                                    />
                                </div>
                                <div class="float-button">
                                    Miliki Unit <i class="bi-chevron-right"></i>
                                </div>
                            </a>
                            <div class="item">
                                <div class="logo">
                                    <img
                                        src="../../images/logo-project2b.png"
                                        alt=""
                                    />
                                </div>
                                <div class="item-img">
                                    <img
                                        src="../../images/img-greenland2.png"
                                        alt=""
                                    />
                                </div>
                                <div class="float-button">
                                    Miliki Unit <i class="bi-chevron-right"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="search-unit">
                    <div class="container">
                        <ul class="nav nav-tabs" id="myTab" role="tablist">
                            <li class="nav-item" role="presentation">
                                <button
                                    class="nav-link active"
                                    id="semua-tab"
                                    data-bs-toggle="tab"
                                    data-bs-target="#semua-tab-pane"
                                    type="button"
                                    role="tab"
                                    aria-controls="semua-tab-pane"
                                    aria-selected="true"
                                >
                                    Semua
                                </button>
                            </li>
                            <li class="nav-item" role="presentation">
                                <button
                                    class="nav-link"
                                    id="perumahaan-tab"
                                    data-bs-toggle="tab"
                                    data-bs-target="#perumahaan-tab-pane"
                                    type="button"
                                    role="tab"
                                    aria-controls="perumahaan-tab-pane"
                                    aria-selected="false"
                                >
                                    Perumahaan
                                </button>
                            </li>
                            <li class="nav-item" role="presentation">
                                <button
                                    class="nav-link"
                                    id="apartemen-tab"
                                    data-bs-toggle="tab"
                                    data-bs-target="#apartemen-tab-pane"
                                    type="button"
                                    role="tab"
                                    aria-controls="apartemen-tab-pane"
                                    aria-selected="false"
                                >
                                    Apartemen
                                </button>
                            </li>
                        </ul>
                        <div class="tab-content" id="myTabContent">
                            <div
                                class="tab-pane fade show active"
                                id="semua-tab-pane"
                                role="tabpanel"
                                aria-labelledby="semua-tab"
                                tabindex="0"
                            >
                                <div class="units">
                                    <a href="/greenland.html" class="item">
                                        <div class="item-img">
                                            <img
                                                src="../../images/img-greenland.png"
                                                alt=""
                                            />
                                        </div>
                                        <h6>Greenland</h6>
                                        <p>
                                            Lorem ipsum dolor sit amet,
                                            consectetur adipiscing elit.
                                        </p>
                                    </a>
                                    <a href="#" class="item">
                                        <div class="item-img">
                                            <img
                                                src="../../images/img-apartement.png"
                                                alt=""
                                            />
                                        </div>
                                        <h6>Austinville</h6>
                                        <p>
                                            Lorem ipsum dolor sit amet,
                                            consectetur adipiscing elit.
                                        </p>
                                    </a>
                                    <a href="/greenland.html" class="item">
                                        <div class="item-img">
                                            <img
                                                src="../../images/img-hotel.png"
                                                alt=""
                                            />
                                        </div>
                                        <h6>Project B</h6>
                                        <p>
                                            Lorem ipsum dolor sit amet,
                                            consectetur adipiscing elit.
                                        </p>
                                    </a>
                                    <a href="/greenland.html" class="item">
                                        <div class="item-img">
                                            <img
                                                src="../../images/img-hotel.png"
                                                alt=""
                                            />
                                        </div>
                                        <h6>Project B</h6>
                                        <p>
                                            Lorem ipsum dolor sit amet,
                                            consectetur adipiscing elit.
                                        </p>
                                    </a>
                                </div>
                            </div>
                            <div
                                class="tab-pane fade"
                                id="perumahaan-tab-pane"
                                role="tabpanel"
                                aria-labelledby="perumahaan-tab"
                                tabindex="0"
                            >
                                <div class="no-unit">
                                    <img
                                        src="../../images/img-illustration5.svg"
                                        alt=""
                                    />
                                </div>
                            </div>
                            <div
                                class="tab-pane fade"
                                id="apartemen-tab-pane"
                                role="tabpanel"
                                aria-labelledby="apartemen-tab"
                                tabindex="0"
                            >
                                <div class="no-unit">
                                    <img
                                        src="../../images/img-illustration5.svg"
                                        alt=""
                                    />
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="projects">
                <div class="container">
                    <h5 class="subtitle">Projects</h5>
                    <h2 class="title">Proyek Proyek Kami</h2>
                    <div class="row items">
                        <div class="col-12 col-lg-6">
                            <div class="item" data-aos="fade-right">
                                <img
                                    src="../../images/img-greenland.png"
                                    alt=""
                                />
                                <div class="item-text">
                                    <h4>Greenland</h4>
                                    <p>
                                        Lorem ipsum dolor sit, amet consectetur
                                        adipisicing elit. Expedita impedit quas
                                        at inventore, aperiam esse animi.
                                    </p>
                                    <a href="/greenland.html" class="more">
                                        Learn More
                                        <i class="bi bi-chevron-right"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-lg-6">
                            <div class="item" data-aos="fade-left">
                                <img
                                    src="../../images/img-apartement.png"
                                    alt=""
                                />
                                <div class="item-text">
                                    <h4>Project B</h4>
                                    <p>
                                        Lorem ipsum dolor sit, amet consectetur
                                        adipisicing elit. Expedita impedit quas
                                        at inventore, aperiam esse animi.
                                    </p>
                                    <div class="more">
                                        Learn More
                                        <i class="bi bi-chevron-right"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-lg-6">
                            <div class="item" data-aos="fade-right">
                                <img src="../../images/img-hotel.png" alt="" />
                                <div class="item-text">
                                    <h4>Project C</h4>
                                    <p>
                                        Lorem ipsum dolor sit, amet consectetur
                                        adipisicing elit. Expedita impedit quas
                                        at inventore, aperiam esse animi.
                                    </p>
                                    <div class="more">
                                        Learn More
                                        <i class="bi bi-chevron-right"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-lg-6">
                            <div class="item" data-aos="fade-left">
                                <img src="../../images/img-mall.png" alt="" />
                                <div class="item-text">
                                    <h4>Project D</h4>
                                    <p>
                                        Lorem ipsum dolor sit, amet consectetur
                                        adipisicing elit. Expedita impedit quas
                                        at inventore, aperiam esse animi.
                                    </p>
                                    <div class="more">
                                        Learn More
                                        <i class="bi bi-chevron-right"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="d-flex justify-content-center">
                                <button type="button" class="btn btn-primary">
                                    Tampilkan Semua
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="sliders-index container-fluid" data-aos="zoom-in">
                <div class="sliders">
                    <div class="slider-item">
                        <div class="slider-img">
                            <img
                                src="../../images/slider-1.png"
                                class="w-100"
                                alt=""
                            />
                        </div>
                        <div class="slider-content">
                            <h1 class="title">
                                Lorem ipsum dolor sit amet consectetur.
                            </h1>
                            <div class="desc">
                                <div class="text questrial">
                                    Lorem ipsum dolor sit amet, consectetur
                                    adipiscing elit. Sed dignissim interdum
                                    neque vel euismod.
                                </div>
                                <div class="more">
                                    Learn More
                                    <i class="bi bi-chevron-right"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="slider-item">
                        <div class="slider-img">
                            <img
                                src="../../images/slider-1.png"
                                class="w-100"
                                alt=""
                            />
                        </div>
                        <div class="slider-content">
                            <h1 class="title">
                                Lorem ipsum dolor sit amet consectetur.
                            </h1>
                            <div class="desc questrial">
                                <div class="text">
                                    Lorem ipsum dolor sit amet, consectetur
                                    adipiscing elit. Sed dignissim interdum
                                    neque vel euismod.
                                </div>
                                <div class="more">
                                    Learn More
                                    <i class="bi bi-chevron-right"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div
                class="promotions"
                data-aos="zoom-right"
                data-aos-offset="0"
                data-aos-duration="500"
            >
                <div class="container">
                    <h5 class="subtitle">Promotions</h5>
                    <h2 class="title">Promo untung banget</h2>
                    <div class="row items">
                        <div class="col-12 col-sm-6 col-lg-4 mb-3 mb-lg-0">
                            <div class="item brown">
                                <div class="cashback">
                                    <div class="text-cashback">
                                        <h5>Cashback</h5>
                                        <h1>15%</h1>
                                        <p>
                                            Lorem ipsum dolor sit amet
                                            consectetur adipisicing elit
                                        </p>

                                        <div class="mobile-only">
                                            <small
                                                >Berlaku hingga: 15 Mei
                                                2022</small
                                            >
                                            <button
                                                type="button"
                                                class="btn btn-white"
                                            >
                                                Salin Kode
                                                <img
                                                    class="ms-2"
                                                    src="../../images/ic-copy.png"
                                                    alt=""
                                                />
                                            </button>
                                        </div>
                                    </div>

                                    <div class="bg-cashback">
                                        <img
                                            src="../../images/img-promo.png"
                                            alt=""
                                        />
                                    </div>

                                    <div class="promo-date">
                                        <div class="date-text questrial">
                                            <i class="bi-clock"></i>
                                            20 Mei 2022
                                        </div>
                                    </div>
                                </div>
                                <div class="line">
                                    <img
                                        src="../../images/line-coupon.png"
                                        alt=""
                                    />
                                </div>
                                <div class="qr">
                                    <div class="qr-img">
                                        <img
                                            src="../../images/qr-code.png"
                                            alt=""
                                        />
                                    </div>
                                    <p>Scan QR Code or Copy the code</p>
                                    <button type="button" class="btn btn-white">
                                        Salin Kode
                                        <img
                                            class="ms-2"
                                            src="../../images/ic-copy.png"
                                            alt=""
                                        />
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-sm-6 col-lg-4 mb-3 mb-lg-0">
                            <div class="item grey">
                                <div class="cashback">
                                    <div class="text-cashback">
                                        <h5>Cashback</h5>
                                        <h1>20%</h1>
                                        <p>
                                            Lorem ipsum dolor sit amet
                                            consectetur adipisicing elit
                                        </p>
                                        <div class="mobile-only">
                                            <small
                                                >Berlaku hingga: 15 Mei
                                                2022</small
                                            >
                                            <button
                                                type="button"
                                                class="btn btn-white"
                                            >
                                                Salin Kode
                                                <img
                                                    class="ms-2"
                                                    src="../../images/ic-copy.png"
                                                    alt=""
                                                />
                                            </button>
                                        </div>
                                    </div>

                                    <div class="bg-cashback">
                                        <img
                                            src="../../images/img-promo.png"
                                            alt=""
                                        />
                                    </div>

                                    <div class="promo-date">
                                        <div class="date-text questrial">
                                            <i class="bi-clock"></i>
                                            20 Mei 2022
                                        </div>
                                    </div>
                                </div>
                                <div class="line">
                                    <img
                                        src="../../images/line-coupon.png"
                                        alt=""
                                    />
                                </div>
                                <div class="qr">
                                    <div class="qr-img">
                                        <img
                                            src="../../images/qr-code.png"
                                            alt=""
                                        />
                                    </div>
                                    <p>Scan QR Code or Copy the code</p>
                                    <button type="button" class="btn btn-white">
                                        Salin Kode
                                        <img
                                            class="ms-2"
                                            src="../../images/ic-copy.png"
                                            alt=""
                                        />
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-sm-6 col-lg-4 mb-3 mb-lg-0">
                            <div class="item green">
                                <div class="cashback">
                                    <div class="text-cashback">
                                        <h5>Cashback</h5>
                                        <h1>20%</h1>
                                        <p>
                                            Lorem ipsum dolor sit amet
                                            consectetur adipisicing elit
                                        </p>
                                        <div class="mobile-only">
                                            <small
                                                >Berlaku hingga: 15 Mei
                                                2022</small
                                            >
                                            <button
                                                type="button"
                                                class="btn btn-white"
                                            >
                                                Salin Kode
                                                <img
                                                    class="ms-2"
                                                    src="../../images/ic-copy.png"
                                                    alt=""
                                                />
                                            </button>
                                        </div>
                                    </div>

                                    <div class="bg-cashback">
                                        <img
                                            src="../../images/img-promo.png"
                                            alt=""
                                        />
                                    </div>

                                    <div class="promo-date">
                                        <div class="date-text questrial">
                                            <i class="bi-clock"></i>
                                            20 Mei 2022
                                        </div>
                                    </div>
                                </div>
                                <div class="line">
                                    <img
                                        src="../../images/line-coupon.png"
                                        alt=""
                                    />
                                </div>
                                <div class="qr">
                                    <div class="qr-img">
                                        <img
                                            src="../../images/qr-code.png"
                                            alt=""
                                        />
                                    </div>
                                    <p>Scan QR Code or Copy the code</p>
                                    <button type="button" class="btn btn-white">
                                        Salin Kode
                                        <img
                                            class="ms-2"
                                            src="../../images/ic-copy.png"
                                            alt=""
                                        />
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="apps" data-aos="fade-up" data-aos-offset="0">
                <div class="container">
                    <div class="ornament one">
                        <img src="../../images/img-ornament3.png" alt="" />
                    </div>
                    <div class="ornament two">
                        <img src="../../images/img-ornament1.png" alt="" />
                    </div>
                    <div class="row">
                        <div class="col-5 col-lg-6">
                            <div class="apps-preview">
                                <div class="first">
                                    <img
                                        src="../../images/phone-1.png"
                                        alt=""
                                    />
                                </div>
                                <div class="second">
                                    <img
                                        src="../../images/phone-2.png"
                                        alt=""
                                    />
                                </div>
                            </div>
                        </div>

                        <div class="col-7 col-lg-6">
                            <h2>Percayalah, hidup itu hanya butuh jari</h2>
                            <p>
                                Bayar iuran bulanan? Butuh perbaikan rumah?
                                Cleaning service?Ada ular? Panggil ambulan?
                                Keluhan? dan seabreg kebutuhan lainnya? Tenang,
                                semua ada di aplikasi One Property.
                            </p>

                            <div class="logos">
                                <div class="me-3">
                                    <img
                                        src="../../images/img-app-store.png"
                                        alt="App Store"
                                    />
                                </div>
                                <div>
                                    <img
                                        src="../../images/img-google-play.png"
                                        alt="Google Play"
                                    />
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="navbar-mobile active">
                <a href="/index.html" class="item active">
                    <svg
                        width="20"
                        height="20"
                        viewBox="0 0 20 20"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M2.5 7.49999L10 1.66666L17.5 7.49999V16.6667C17.5 17.1087 17.3244 17.5326 17.0118 17.8452C16.6993 18.1577 16.2754 18.3333 15.8333 18.3333H4.16667C3.72464 18.3333 3.30072 18.1577 2.98816 17.8452C2.67559 17.5326 2.5 17.1087 2.5 16.6667V7.49999Z"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                        <path
                            d="M7.5 18.3333V10H12.5V18.3333"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                    </svg>
                    <p>Home</p>
                </a>
                <a href="/search.html" class="item">
                    <svg
                        width="20"
                        height="20"
                        viewBox="0 0 20 20"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M9.16667 15.8333C12.8486 15.8333 15.8333 12.8486 15.8333 9.16667C15.8333 5.48477 12.8486 2.5 9.16667 2.5C5.48477 2.5 2.5 5.48477 2.5 9.16667C2.5 12.8486 5.48477 15.8333 9.16667 15.8333Z"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                        <path
                            d="M17.5 17.5L13.875 13.875"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                    </svg>
                    <p>Cari</p>
                </a>
                <div class="item">
                    <svg
                        width="20"
                        height="20"
                        viewBox="0 0 20 20"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M17.5 12.5C17.5 12.942 17.3244 13.366 17.0118 13.6785C16.6993 13.9911 16.2754 14.1667 15.8333 14.1667H5.83333L2.5 17.5V4.16667C2.5 3.72464 2.67559 3.30072 2.98816 2.98816C3.30072 2.67559 3.72464 2.5 4.16667 2.5H15.8333C16.2754 2.5 16.6993 2.67559 17.0118 2.98816C17.3244 3.30072 17.5 3.72464 17.5 4.16667V12.5Z"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                    </svg>
                    <p>Chat</p>
                </div>
                <a href="/my-cart.html" class="item">
                    <svg
                        width="20"
                        height="20"
                        viewBox="0 0 20 20"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M7.50008 18.3333C7.96032 18.3333 8.33341 17.9602 8.33341 17.5C8.33341 17.0398 7.96032 16.6667 7.50008 16.6667C7.03984 16.6667 6.66675 17.0398 6.66675 17.5C6.66675 17.9602 7.03984 18.3333 7.50008 18.3333Z"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                        <path
                            d="M16.6666 18.3333C17.1268 18.3333 17.4999 17.9602 17.4999 17.5C17.4999 17.0398 17.1268 16.6667 16.6666 16.6667C16.2063 16.6667 15.8333 17.0398 15.8333 17.5C15.8333 17.9602 16.2063 18.3333 16.6666 18.3333Z"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                        <path
                            d="M0.833252 0.833344H4.16658L6.39992 11.9917C6.47612 12.3753 6.68484 12.72 6.98954 12.9653C7.29424 13.2105 7.6755 13.3408 8.06658 13.3333H16.1666C16.5577 13.3408 16.9389 13.2105 17.2436 12.9653C17.5483 12.72 17.757 12.3753 17.8333 11.9917L19.1666 5.00001H4.99992"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                    </svg>
                    <p>Cart</p>
                </a>
                <a href="/login.html" class="item">
                    <svg
                        width="20"
                        height="20"
                        viewBox="0 0 20 20"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M16.6666 17.5V15.8333C16.6666 14.9493 16.3154 14.1014 15.6903 13.4763C15.0652 12.8512 14.2173 12.5 13.3333 12.5H6.66658C5.78253 12.5 4.93468 12.8512 4.30956 13.4763C3.68444 14.1014 3.33325 14.9493 3.33325 15.8333V17.5"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                        <path
                            d="M10.0001 9.16667C11.841 9.16667 13.3334 7.67428 13.3334 5.83333C13.3334 3.99238 11.841 2.5 10.0001 2.5C8.15913 2.5 6.66675 3.99238 6.66675 5.83333C6.66675 7.67428 8.15913 9.16667 10.0001 9.16667Z"
                            stroke="#B8BABC"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        />
                    </svg>

                    <p>Profile</p>
                </a>
            </div>
            <div class="footer">
                <div class="container">
                    <div class="row first-row">
                        <div class="col-6 col-lg-auto">
                            <div class="logo">
                                <img
                                    src="../../images/logo-forms-living1.png"
                                    alt=""
                                />
                            </div>
                            <p>
                                Lorem ipsum dolor sit amet consectetur
                                adipisicing elit. Quibusdam praesentium quod
                                esse eos quae voluptate maxime fugiat dolorum
                                minima
                            </p>
                        </div>
                        <div class="col-6 col-lg-auto">
                            <div class="footer-title">Hunian Greenland</div>
                            <p>Green West</p>
                            <p>Green East</p>
                            <p>The Mainroad</p>
                            <p>The Icon</p>
                            <p>The Peak</p>
                        </div>
                        <div class="col-6 col-lg-auto">
                            <div class="footer-title">Hunian Greenland</div>
                            <p>President Suits</p>
                            <p>Green Suits</p>
                            <p>Excel Suits</p>
                            <p>Prime Suits</p>
                            <p>Basic Suits</p>
                        </div>
                        <div class="col-6 col-lg-auto">
                            <div class="footer-title">SpaceX Supermall</div>
                            <p>Medan</p>
                            <p>Jakarta</p>
                            <p>Surabaya</p>
                            <p>Malang</p>
                            <p>Solo</p>
                        </div>
                        <div class="col-6 col-lg-auto">
                            <div class="footer-title">Starship</div>
                            <p>Co-working Space</p>
                            <p>Studio X</p>
                            <p>Central Conf</p>
                        </div>
                    </div>
                    <hr />
                    <div class="row second-row">
                        <div class="col-6 col-lg-auto">
                            <div class="footer-title">SpaceX Supermall</div>
                            <p>Medan</p>
                            <p>Jakarta</p>
                            <p>Surabaya</p>
                            <p>Malang</p>
                            <p>Solo</p>
                        </div>
                        <div class="col-6 col-lg-auto">
                            <div class="footer-title">Starship</div>
                            <p>Co-working Space</p>
                            <p>Studio X</p>
                            <p>Central Conf</p>
                        </div>
                    </div>
                    <hr />
                    <div class="copyright">
                        <div class="copy-year">&#169; 2022 FORMS.Inc</div>
                        <div class="links">
                            <a href="#">Kebijakan privasi</a>
                            <a href="#">Syarat dan Ketentuan</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </GuestLayout>
</template>

<style lang="scss">
.with-nav {
    padding-bottom: 6rem !important;
}

.cta {
    .cta-text {
        .cta-subtitle {
            margin-bottom: 20px;
            color: $grey-light;
        }

        .cta-title {
            margin-bottom: 1.5rem;
            line-height: 1.3;
        }

        .cta-desc {
            margin-bottom: 2.5rem;
            color: $grey-light;
            font-family: "Questrial", sans-serif;
        }

        .actions {
            margin-bottom: 100px;

            .btn-primary {
                padding: 17px 24px;
            }
        }
    }

    .cta-img {
        position: relative;
    }

    .image-sliders {
        img {
            width: 100%;
            border-bottom-left-radius: 32px;
            object-fit: cover;
        }
    }

    .text-sliders {
        padding-bottom: 3rem;

        @include dotsWhite();
    }

    .sponsor {
        p {
            margin-bottom: 2.5rem;
        }

        .logos {
            display: flex;
            align-items: center;

            .item {
                margin-right: 3rem;

                img {
                    max-width: 140px;
                }
            }
        }
    }
}

@include breakpoint(mobileonly) {
    .cta,
    .projects,
    .sliders-index {
        display: none;
    }
}

.projects {
    .item {
        position: relative;
        margin-bottom: 3rem;

        img {
            width: 100%;
            border-radius: 30px;
        }

        .item-text {
            position: absolute;
            bottom: 2rem;
            left: 2rem;
            width: 70%;
            color: white;
            padding: 1.5rem;
            z-index: 2;
            @include blurBg;
        }
    }
}

.cta-mobile {
    .container {
        padding-bottom: 1.5rem;
    }

    .sliders-mobile {
        margin-bottom: 0;

        .item {
            position: relative;

            .logo {
                position: absolute;
                top: 1rem;
                left: 1rem;

                img {
                    width: 100%;
                    height: 20px;
                    object-fit: cover;
                }
            }

            img {
                border-radius: 10px;
                width: 100%;
                height: 180px;
                object-fit: cover;
            }

            .float-button {
                color: white;
                font-size: 10px;
                padding: 7px 14px;
                position: absolute;
                right: 1rem;
                bottom: 20px;
                z-index: 2;

                &:before {
                    z-index: -1;
                    content: "";
                    border-radius: 100px;
                    background-color: rgba($color: white, $alpha: 0.3);
                    backdrop-filter: blur(10px);
                    width: 100%;
                    height: 100%;
                    position: absolute;
                    top: 0;
                    left: 0;
                }
            }
        }

        @include dotsWhite();
    }
}

.search-unit {
    .container {
        padding-bottom: 2.5rem;

        .no-unit {
            text-align: center;
            margin: 2rem;

            img {
                width: 80%;
            }
        }

        .nav-tabs {
            @include overflowFlex;
            justify-content: start;

            .nav-link {
                color: $grey;
                font-size: 12px;
                padding: 6px 12px;
                border-radius: 10px;
                border: 1px solid #dedede;
                margin: 0;
                margin-right: 12px;

                &.active {
                    color: white;
                    background: $primary-normal;
                    border: none;
                }
            }
        }

        .units {
            @include overflowFlex;
            margin-top: 1rem;
            margin-right: -1.5rem;

            .item {
                margin-right: 12px;
                display: block;

                .item-img {
                    margin-bottom: 12px;

                    img {
                        width: 160px;
                        height: 100px;
                        object-fit: cover;
                        border-radius: 10px;
                    }
                }

                h6 {
                    margin-bottom: 4px;
                    font-size: 14px;
                }

                p {
                    font-family: "Questrial", sans-serif;
                    color: $grey-light;
                    margin-bottom: 0;
                    font-size: 12px;
                }
            }
        }
    }
}

.index .promotions {
    padding-bottom: 80px;
}

.sliders {
    .slider-item {
        position: relative;

        &::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1;
            height: 50%;
            background: linear-gradient(
                180deg,
                #ffffff 0%,
                rgba(255, 255, 255, 0) 100%
            );
        }

        .slider-img {
            position: relative;
        }

        .slider-content {
            position: absolute;
            z-index: 4;
            bottom: 0;
            width: 50vw;
            left: 50%;
            top: 50%;
            height: 80%;
            transform: translate(-50%, -50%);
            display: flex;
            flex-direction: column;
            justify-content: space-between;

            .desc {
                position: relative;
                padding: 2rem 5rem;
                text-align: center;
                color: white;

                .text {
                    margin-bottom: 2rem;
                    line-height: 2;
                }

                .more {
                    justify-content: center;
                }

                @include blurBg;
            }
        }
    }

    @include breakpoint(untilTablet) {
        .slider-item {
            .slider-img {
                img {
                    height: 450px;
                    object-fit: cover;
                    width: 100%;
                }
            }

            .slider-content {
                width: 70vw;
            }
        }
    }
}

.promotions {
    .items {
        .item {
            color: white;

            &.grey {
                .cashback,
                .qr {
                    background-color: $grey-light;
                }
            }

            &.green {
                .cashback,
                .qr {
                    background: $primary;
                }
            }

            .cashback {
                border-radius: 20px;
                background-color: $secondary-light;
                padding: 1.5rem;
                position: relative;

                .text-cashback {
                    position: relative;
                    z-index: 2;
                    width: 50%;
                }

                .bg-cashback {
                    position: absolute;
                    right: 0;
                    z-index: 0;
                    top: 50%;
                    transform: translateY(-50%);
                }

                .promo-date {
                    position: absolute;
                    right: 1rem;
                    top: 1rem;
                    z-index: 2;
                    @include blurBg;
                    padding: 4px 8px;

                    &:before {
                        border-radius: 100px;
                        z-index: 0;
                    }

                    .date-text {
                        position: relative;
                        z-index: 2;
                        display: flex;
                        align-items: center;

                        i {
                            margin-right: 0.5rem;
                            margin-bottom: -2px;
                        }
                    }
                }
            }

            .line {
                margin-top: -1rem;
                position: relative;
                margin-bottom: -1rem;

                img {
                    width: 100%;
                }
            }

            .qr {
                background-color: $secondary-light;
                padding: 1.5rem;
                border-radius: 20px;
                text-align: center;

                .qr-img {
                    margin-bottom: 1rem;
                }
            }

            @include breakpoint(mobileonly) {
                .qr {
                    display: none;
                }
            }
        }
    }

    @include breakpoint(mobileonly) {
        .items {
            flex-wrap: nowrap;
            @include overflowFlex;
            margin-right: -1.5rem;

            .col-12 {
                width: 90%;
            }

            .item {
                position: relative;

                &:before {
                    left: -12px;
                    content: "";
                    position: absolute;
                    top: 50%;
                    transform: translateY(-50%);
                    border-radius: 50%;
                    background-color: white;
                    width: 24px;
                    height: 24px;
                    z-index: 1;
                }

                &:after {
                    right: -12px;
                    content: "";
                    position: absolute;
                    top: 50%;
                    transform: translateY(-50%);
                    border-radius: 50%;
                    background-color: white;
                    width: 24px;
                    height: 24px;
                    z-index: 1;
                }

                .line {
                    display: none;
                }

                .cashback {
                    .promo-date {
                        display: none;
                    }

                    .text-cashback {
                        width: 60%;

                        h5 {
                            margin-bottom: 0;
                        }

                        > p {
                            display: none;
                        }

                        .mobile-only {
                            small {
                                font-size: 10px;
                            }

                            .btn {
                                padding: 6px 10px;
                                border-radius: 100px;
                                font-weight: 400;
                                margin-top: 0.5rem;

                                img {
                                    width: 14px;
                                    height: 14px;
                                }
                            }
                        }
                    }
                }
            }
        }
    }
}

.apps {
    color: white;
    padding-bottom: 100px;

    @include breakpoint(mobileonly) {
        display: none;
    }

    .container {
        position: relative;
        padding-bottom: 0;

        &::before {
            content: "";
            width: 100%;
            border-radius: 30px;
            background: linear-gradient(
                299.53deg,
                #58595b 54.82%,
                #8f8f8f 104.36%
            );
            height: 88%;
            position: absolute;
            bottom: 0;
            z-index: -1;
        }

        .ornament {
            &.one {
                right: -15%;
                top: -19%;
            }

            &.two {
                bottom: -40%;
                left: 22%;
            }
        }
    }

    .row {
        align-items: center;
        padding: 0 4rem;
    }

    .apps-preview {
        display: flex;
        align-items: flex-end;

        img {
            width: 100%;
        }

        .second {
            margin-left: -10rem;
        }
    }

    h2 {
        padding-right: 4rem;
        margin-bottom: 2rem;
        margin-top: 10%;
    }

    @include breakpoint(largeDesktop) {
        h2 {
            padding-right: 5rem;
        }
    }

    p {
        margin-bottom: 3rem;
    }

    .logos {
        display: flex;

        img {
            margin-right: 1.5rem;
        }
    }

    @include breakpoint(untilTablet) {
        .row {
            padding: 0 1rem;
        }

        .ornament {
            img {
                width: 250px;
            }
        }

        h2 {
            padding-right: 0;
            font-size: 24px;
        }

        p {
            font-size: 14px;
            margin-bottom: 1.5rem;
        }

        .logos {
            align-items: center;

            img {
                height: 45px;
            }
        }
    }
}
</style>
