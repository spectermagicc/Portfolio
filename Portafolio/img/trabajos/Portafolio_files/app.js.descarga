$(document).ready(function () {
    var inicio = $('#inicio').offset().top;
    var trabajos = $('#trabajos').offset().top;
    var contacto = $('#contacto').offset().top;
    var header = $('#header').offset().top;
    
    $('#flecha-volver').on('click', function () {
        $('html, body').animate({
            'scrollTop': header
        },1500)
    });
    
    $('#btn-acerca').on('click', function () {
        $('html, body').animate({
            'scrollTop': inicio
        }, 2000);
    });

    $('#btn-trabajos').on('click', function(){
        $('html, body').animate({
            'scrollTop': trabajos
        }, 2000);
    });

    $('#btn-contacto').on('click', function () {
        $('html, body').animate({
            'scrollTop': contacto
        }, 2000)
    });
});