<template>
    <div class="About position-relative pb-5" id="about">
        <div class="container py-5">
            <h2 class="text-center my-5">О парковке</h2>
            <div class="row g-4 mb-5">
                <div class="col-lg-4 col-md-6">
                    <div class="About__item p-5 d-flex flex-column">
                        <div class="item__title">500</div>
                        <div class="item__description">машиномест</div>
                        <div class="item__img mt-auto text-end">
                            <img src="../assets/about_car.svg" alt="" class="img-fluid">
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="About__item p-5 d-flex flex-column">
                        <div class="item__title">Вежливый</div>
                        <div class="item__description">персонал</div>
                        <div class="item__img mt-auto text-end">
                            <img src="../assets/about_users.svg" alt="" class="img-fluid">
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="About__item p-5 d-flex flex-column">
                        <div class="item__title">Ответственность</div>
                        <div class="item__description">застрахована в страховой компании</div>
                        <div class="item__img mt-auto text-end">
                            <img src="../assets/about_lock.svg" alt="" class="img-fluid">
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="About__item p-5 d-flex flex-column">
                        <div class="item__title">Безопасность</div>
                        <div class="item__description">на объекте обеспечивается Федеральной службой
                            войск национальнойгвардии России
                        </div>
                        <div class="item__img mt-auto text-end">
                            <img src="../assets/about_star.svg" alt="" class="img-fluid">
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="About__item p-5 d-flex flex-column">
                        <div class="item__title">Более 20</div>
                        <div class="item__description">камер и периметральная охранная сигнализация</div>
                        <div class="item__img mt-auto text-end">
                            <img src="../assets/about_webcam.svg" alt="" class="img-fluid">
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="About__item About__item_action p-5 d-flex flex-column">
                        <div class="item__title">Забронируйте место на парковке</div>
                        <button class="mt-auto py-3">ЗАБРОНИРОВАТЬ</button>
                    </div>
                </div>
            </div>
            <div class="About__photos row g-4" id="camera">
                <div class="col-md-6">
                    <img src="../assets/about_online.svg" class="img-fluid" alt="">
                </div>
                <div class="col-md-6">
                    <div class="row g-4">
                        <div class="col-6">
                            <img src="../assets/about_img_1.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6">
                            <img src="../assets/about_img_2.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6">
                            <img src="../assets/about_img_3.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6">
                            <img src="../assets/about_img_4.jpg" alt="" class="img-fluid">
                        </div>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <img src="../assets/about_img_5.jpg" alt="" class="img-fluid">
                </div>
                <div class="col-6 col-md-3">
                    <img src="../assets/about_img_6.jpg" alt="" class="img-fluid">
                </div>
                <div class="col-6 col-md-3">
                    <img src="../assets/about_img_7.jpg" alt="" class="img-fluid">
                </div>
                <div class="col-6 col-md-3">
                    <img src="../assets/about_img_8.jpg" alt="" class="img-fluid">
                </div>
                <div class="col-12" v-show="show">
                    <div class="row g-4">
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_6.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_7.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_5.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_8.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_5.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_8.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_7.jpg" alt="" class="img-fluid">
                        </div>
                        <div class="col-6 col-md-3">
                            <img src="../assets/about_img_6.jpg" alt="" class="img-fluid">
                        </div>
                    </div>
                </div>
                <div class="col-12 mt-5">
                    <button @click="show=!show" :class="{'showed': show}" class="About__showMore mx-auto d-block">
                        {{show ? 'Скрыть фото':'Еще фото'}}
                        <img src="../assets/about_arrow.svg" class="img-fluid" alt="">
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<script src="../controllers/AboutController.js"></script>
<style lang="scss" src="../styles/_about.scss"></style>