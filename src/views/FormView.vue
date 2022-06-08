<template>
    <div class="Form py-5">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h2>Парковка в&nbsp;Пулково с&nbsp;трансфером в&nbsp;аэропорт</h2>
                    <div class="Form__mini d-flex">
                        <div class="py-3 pe-3">
                            <div class="Form__duration">1-2 дня</div>
                            <div class="Form__price">350 руюлей</div>
                        </div>
                        <div class="py-3 px-3">
                            <div class="Form__duration">3-7 дней</div>
                            <div class="Form__price">250 руюлей</div>
                        </div>
                        <div class="py-3 ps-3">
                            <div class="Form__duration">7-14 дней</div>
                            <div class="Form__price">200 руюлей</div>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <img src="../assets/form_img.svg" alt="" class="img-fluid">
                </div>
            </div>
            <form action="#" class="d-md-flex">
                <div>
                    <label for="inDate">Дата и время въезда (вылет - 3 часа)</label>
                    <div class="input">
                        <input type="date">
                        <input type="date">
                    </div>
                </div>
                <div>
                    <label for="outDate">Дата и время выезда (прилет + 1 час)</label>
                    <div class="input">
                        <input type="date">
                        <input type="date">
                    </div>
                </div>
                <div>
                    <label for="s">&nbsp;</label>
                    <div class="input">
                        <button class="btn btn-success w-100">Найти место</button>
                    </div>
                </div>
            </form>
        </div>
    </div>
</template>

<script src="../controllers/FormController.js"></script>
<style lang="scss" src="../styles/_form.scss"></style>