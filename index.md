<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" href="estilos.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
    <link rel="shortcut icon" href="img/circulo.png">
    <!-- surang de flaticon -->
    <title>Sigue al Capitan</title>

</head>

<body class=" bg-dark m-0 p-0 ">

    <div class="container-fluid">
        <div class="row">

            <div class="col-12">
                <section class="main-container">

                    <div class="container-fluid pt-4 pb-4 ">
                        <div class="row align-items-start">
                            <div class="col-3">

                                <div id="imagenes_id" class="imagenes">
                                    <img id="exito_id" src="./img/felices.jpg" alt="">
                                </div>

                            </div>
                            <div class="col-6 ">

                                <div class="container">
                                    <div class="row ">

                                        <div class="col-12">

                                            <div class="container">
                                                <div class="row mt-4 ">
                                                    <div class="d-flex justify-content-center">
                                                        <div id="rebanada_superior_izquierdo_id"
                                                            class="col-6 me-1 rebanadas_radio rebanada_superior_izquierdo">

                                                        </div>
                                                        <div id="rebanada_superior_derecho_id"
                                                            class="col-6  rebanadas_radio rebanada_superior_derecho">
                                                        </div>

                                                    </div>

                                                </div>
                                                <div class="row">

                                                    <div class="d-flex justify-content-center">
                                                        <div id="rebanada_inferior_izquierda_id"
                                                            class="col-6 me-1 mt-1  rebanadas_radio rebanada_inferior_izquierdo">
                                                        </div>
                                                        <div id="rebanada_inferior_derecha_id"
                                                            class="col-6 mt-1 rebanadas_radio rebanada_inferior_derecho">
                                                        </div>

                                                    </div>
                                                </div>

                                                <div class="row">

                                                    <section class="d-flex justify-content-center mt-3 pt-4 ">
                                                        <button id="inicio_id" class="btn btn-success"
                                                            onclick="iniciarJuego()">▶ </button>

                                                    </section>

                                                </div>

                                            </div>


                                        </div>
                                    </div>

                                </div>

                            </div>
                            <div class="col-3">
                                <div id="imagen_2_id" class="imagenes">
                                    <img id="exito_2_id" src="./img/celebración_derecha.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>

            </div>
            </section>
        </div>


        <div class="row">
            <div class="col-12 text-center">
                <h1 id="titulo_id" class="text-light ">Repite las instrucciones</h1>

                <div class="container">
                    <div class="row">
                        <div class="col-12">

                        </div>
                    </div>
                </div>

            </div>

        </div>
    </div>










    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"
        integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js"
        integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="script.js"></script>
</body>

</html>