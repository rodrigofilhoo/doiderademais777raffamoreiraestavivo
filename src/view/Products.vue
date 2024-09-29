<script setup lang="ts">
import Navbar from '../components/Navbar.vue'
</script>

<template>
    <Navbar />
    <section class="py-5">
        <div class="container px-4 px-lg-5 my-5">
            <div class="row gx-4 gx-lg-5 align-items-center">
                <div class="col-md-6"><img class="card-img-top mb-5 mb-md-0" src="https://www.cdnlogo.com/logos/v/92/vue-js.svg" alt="..." /></div>
                <div class="col-md-6">
                    <!-- nome do produto -->
                    <h1 class="display-5 fw-bolder">nome produto</h1>
                    <div class="fs-5 mb-5">
                        <!-- preco do produto -->
                        <span>R$40.00</span>
                    </div>
                    <!-- descricao do produto -->
                    <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium at dolorem quidem modi. Nam sequi consequatur obcaecati excepturi alias magni, accusamus eius blanditiis delectus ipsam minima ea iste laborum vero?</p>
                    
                    <div class="d-flex">
                        <div class="dropdown show me-3">
                        <a class="btn btn-success dropdown-toggle" href="#" role="button" id="dropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Valores
                        </a>

                        <div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                            <a class="dropdown-item" href="#">Diário</a>
                            <a class="dropdown-item" href="#">Semanal</a>
                            <a class="dropdown-item" href="#">Quinzenal</a>
                            <a class="dropdown-item" href="#">Mensal</a>
                        </div>
                    </div>
                        <input class="form-control text-center me-3" id="inputQuantity" type="num" value="1" style="max-width: 3rem" />
                        <button class="btn btn-outline-dark flex-shrink-0" type="button">
                            <i class="bi-cart-fill me-1"></i>
                            Adicionar ao carrinho
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="py-5 bg-light">
        <div class="container px-4 px-lg-5 mt-5">
            <h2 class="fw-bolder mb-4">Produtos Relacionados</h2>
            <div class="row gx-4 gx-lg-5 row-cols-2 row-cols-md-3 row-cols-xl-4 justify-content-center">
                <div class="col mb-5">
                    <div class="card h-100">
                        <!-- imagem-->
                        <img class="card-img-top" src="https://www.cdnlogo.com/logos/v/92/vue-js.svg" alt="..." />
                        <!-- detalhes-->
                        <div class="card-body p-4">
                            <div class="text-center">
                                <!-- Product name-->
                                <h5 class="fw-bolder">Nome</h5>
                                <!-- Product price-->
                                R$40.00
                            </div>
                        </div>
                        <!-- Product actions-->
                        <div class="card-footer p-4 pt-0 border-top-0 bg-transparent">
                            <div class="text-center"><a class="btn btn-outline-dark mt-auto" href="#">Ver Opções</a></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>