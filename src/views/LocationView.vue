<template>
    <div class="Location position-relative pb-5" id="location">
        <div class="container pt-5">
            <div class="row pt-5">
                <div class="col-md-5 mb-4 mb-md-0">
                    <h2 class="mb-4">Где мы находимся</h2>
                    <div class="mb-5">
                        <h3 class="mb-2 extra32">Адрес</h3>
                        <div class="Location__info semi24-32">Пулковское ш., д. 41, лит. ЗИ, Санкт-Петербург</div>
                    </div>
                    <div class="mb-5">
                        <h3 class="mb-2 extra32">Координаты</h3>
                        <div class="Location__info semi24-32">55.58804713; 37.21705019</div>
                    </div>
                    <div class="Location__contacts mb-5">
                        <div class="mb-3">
                            <a href="https://wa.me/79210000000" target="_blank"
                                class="d-flex align-items-center semi24-32">
                                <img src="../assets/WhatsApp.svg" class="img-fluid me-3" alt="">
                                +7(921)000-00-00
                            </a>
                        </div>
                        <div>
                            <a href="tel:88005553535" class="d-flex align-items-center semi24-32">
                                <img src="../assets/phone-call.svg" class="img-fluid me-3" alt="">
                                Тел. 8 (800) 555-35-35</a>
                        </div>
                    </div>
                    <a href="#" class="Location__action">Найти в Навигаторе</a>
                </div>
                <div class="col-md-7">
                    <div class="h-100 w-100 Location__map text-button">

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script src="../controllers/LocationController.js"></script>
<style lang="scss" src="../styles/_location.scss"></style>