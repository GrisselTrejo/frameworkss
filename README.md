<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Tienda de Perritos</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
</head>

<body>
    <div class="container">
        <header
            class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-4 border-bottom">
            <div class="col-md-3 mb-2 mb-md-0">
                <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
                    <svg class="bi" width="40" height="32" role="img" aria-label="Bootstrap">
                        <use xlink:href="#bootstrap" />
                    </svg>
                </a>
            </div>

            <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
                <li><a href="#" class="nav-link px-2 link-secondary">Inicio</a></li>
                <li><a href="#" class="nav-link px-2">Perritos</a></li>
                <li><a href="#" class="nav-link px-2">Servicios</a></li>
                <li><a href="#" class="nav-link px-2">Preguntas Frecuentes</a></li>
                <li><a href="#" class="nav-link px-2">Contacto</a></li>
            </ul>

            <div class="col-md-3 text-end">
                <button type="button" class="btn btn-outline-primary me-2">Iniciar Sesión</button>
                <button type="button" class="btn btn-primary">Registrarse</button>
            </div>
        </header>
    </div>

    <main>
        <div class="container my-5">
            <div class="p-5 text-center bg-body-tertiary rounded-3">
                <svg class="bi mt-4 mb-3" style="color: var(--bs-indigo);" width="100" height="100">
                    <use xlink:href="#paw" />
                </svg>
                <h1 class="text-body-emphasis">Bienvenido a nuestra tienda de perritos</h1>
                <p class="col-lg-8 mx-auto fs-5 text-muted">
                    Aquí encontrarás los mejores amigos peludos para llevar a casa, junto con todos los servicios y productos que necesitan para estar felices y saludables.
                </p>
                <div class="d-inline-flex gap-2 mb-5">
                    <button class="d-inline-flex align-items-center btn btn-primary btn-lg px-4 rounded-pill"
                        type="button">
                        Ver Perritos
                        <svg class="bi ms-2" width="24" height="24">
                            <use xlink:href="#arrow-right-short" />
                        </svg>
                    </button>
                    <button class="btn btn-outline-secondary btn-lg px-4 rounded-pill" type="button">
                        Contáctanos
                    </button>
                </div>
            </div>
        </div>

        <section class="container">
            <div class="row row-cols-1 row-cols-md-4 mb-3 text-center">
                <div class="col">
                    <div class="card mb-4 rounded-3 shadow-sm">
                        <div class="card-header py-3">
                            <h4 class="my-0 fw-normal">Cachorro</h4>
                        </div>
                        <div class="card-body">
                            <h1 class="card-title pricing-card-title">$300<small
                                    class="text-body-secondary fw-light">/u</small></h1>
                            <ul class="list-unstyled mt-3 mb-4">
                                <li>Hasta 6 meses de edad</li>
                                <li>Vacunas al día</li>
                                <li>Consultas veterinarias</li>
                                <li>Acceso a juguetes y accesorios</li>
                            </ul>
                            <button type="button" class="w-100 btn btn-lg btn-outline-primary">Adoptar</button>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card mb-4 rounded-3 shadow-sm">
                        <div class="card-header py-3">
                            <h4 class="my-0 fw-normal">Joven</h4>
                        </div>
                        <div class="card-body">
                            <h1 class="card-title pricing-card-title">$500<small
                                    class="text-body-secondary fw-light">/u</small></h1>
                            <ul class="list-unstyled mt-3 mb-4">
                                <li>De 6 meses a 2 años</li>
                                <li>Vacunas al día</li>
                                <li>Consultas veterinarias</li>
                                <li>Entrenamiento básico</li>
                            </ul>
                            <button type="button" class="w-100 btn btn-lg btn-primary">Adoptar</button>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card mb-4 rounded-3 shadow-sm border-primary">
                        <div class="card-header py-3 text-bg-primary border-primary">
                            <h4 class="my-0 fw-normal">Adulto</h4>
                        </div>
                        <div class="card-body">
                            <h1 class="card-title pricing-card-title">$700<small
                                    class="text-body-secondary fw-light">/u</small></h1>
                            <ul class="list-unstyled mt-3 mb-4">
                                <li>Más de 2 años</li>
                                <li>Vacunas al día</li>
                                <li>Consultas veterinarias</li>
                                <li>Entrenamiento avanzado</li>
                            </ul>
                            <button type="button" class="w-100 btn btn-lg btn-primary">Adoptar</button>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card mb-4 rounded-3 shadow-sm">
                        <div class="card-header py-3">
                            <h4 class="my-0 fw-normal">Mayor</h4>
                        </div>
                        <div class="card-body">
                            <h1 class="card-title pricing-card-title">$200<small
                                    class="text-body-secondary fw-light">/u</small></h1>
                            <ul class="list-unstyled mt-3 mb-4">
                                <li>Más de 7 años</li>
                                <li>Vacunas al día</li>
                                <li>Consultas veterinarias</li>
                                <li>Cuidado especial</li>
                            </ul>
                            <button type="button" class="w-100 btn btn-lg btn-outline-primary">Adoptar</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-dark text-white text-center py-3 mt-5">
        <p>&copy; 2024 Tienda de Perritos. Todos los derechos reservados.</p>
    </footer>
</body>

</html>
