@extends('layouts.app') <!-- Extiende el layout que creaste -->

@section('content') <!-- Sección de contenido -->
<div class="container text-center mt-5 custom-background">
    <h1 style="font-family: 'Cardinal', serif; color: #ff69b4; font-weight: bold;">
        Uñas Y Pestañas Ross
    </h1>
</div>

<div class="container mt-5 p-4" style="background-color: #f8d7da; border-radius: 15px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 800px; margin: 0 auto;">
    <h2 class="text-center" style="font-family: 'Cardinal', serif; color: #343a40; letter-spacing: 1px;">
        ¡Bienvenidos a Uñas y Pestañas Ross! 🌟
    </h2>

    <p class="lead mt-4" style="text-align: justify; font-size: 1.1em; line-height: 1.8; color: #343a40;">
        En <strong>Uñas y Pestañas Ross</strong>, nos especializamos en ofrecerte lo mejor en <strong>belleza femenina</strong> con productos y servicios de alta calidad. 💅✨ Nos enorgullece destacar por nuestras modernas técnicas de pintado de uñas y extensiones de pestañas, convirtiéndonos en un punto de referencia para los más jóvenes que buscan realzar su estilo con <strong>elegancia y creatividad</strong>.
    </p>

    <p class="lead mt-3" style="text-align: justify; font-size: 1.1em; line-height: 1.8; color: #343a40;">
        Estamos emocionados por lo que el futuro nos depara y, aunque todavía tenemos áreas en las que podemos mejorar, estamos comprometidos a <strong>expandir nuestro alcance</strong> y potenciar nuestra <strong>presencia en redes sociales</strong> para brindarte una experiencia aún más satisfactoria. 🎨💖
    </p>

    <p class="lead mt-3" style="text-align: justify; font-size: 1.1em; line-height: 1.8; color: #343a40;">
        ¡Gracias por ser parte de nuestra comunidad y acompañarnos en este viaje de belleza y transformación! 💫 <strong>¡No dudes en seguirnos</strong> para estar al tanto de nuestras <strong>novedades y promociones exclusivas</strong>!
    </p>

    <!-- Botón de llamada a la acción -->
    <div class="text-center">
        <a href="https://www.facebook.com/profile.php?id=61563486098673" target="_blank" class="btn btn-primary" style="background-color: #ff69b4; border: none;">
            Explora más
        </a>
    </div>
</div>

<div class = "container text-center mt-5">
<div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel" style="max-width: 600px; margin: auto;">
    <div class="carousel-inner">
        <div class="carousel-item active text-center">
            <img src="/icons/Uña4.jpg" class="d-block mx-auto" style="width: 100%; height: auto; max-height: 400px; object-fit: cover;">
        </div>
        <div class="carousel-item text-center">
            <img src="/icons/Uña5.jpg" class="d-block mx-auto" style="width: 100%; height: auto; max-height: 400px; object-fit: cover;">
        </div>
        <div class="carousel-item text-center">
            <img src="/icons/Uña6.jpg" class="d-block mx-auto" style="width: 100%; height: auto; max-height: 400px; object-fit: cover;">
        </div>
    </div>
</div>
</div>



@endsection
