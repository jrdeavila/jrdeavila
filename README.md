<div id="imageContainer">
  <img id="lightImage" src="assets/Banner Prewiew Light.png" alt="Imagen para el tema claro">
  <img id="darkImage" src="assets/Banner Prewiew Dark.png" alt="Imagen para el tema oscuro">
</div>

<script>
  const isDarkMode = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;

  const imageContainer = document.getElementById('imageContainer');
  const lightImage = document.getElementById('lightImage');
  const darkImage = document.getElementById('darkImage');

  if (isDarkMode) {
    // Mostrar imagen oscura
    lightImage.style.display = 'none';
    darkImage.style.display = 'block';
  } else {
    // Mostrar imagen clara
    lightImage.style.display = 'block';
    darkImage.style.display = 'none';
  }
</script>


## Acerca de mí
¡Hola! 👋 Soy Jose De Avila, Desarrollador de software. Me encanta desarrollar soluciones tecnologías que involucren desarrollo de software, para que puedas crecer como negocio en el mundo de la innovación.
Hace tiempo he seguido la linea del desarrollo móvil con tecnologías como Flutter y React Native 💻📱. Ademas soy Desarrollador Laravel, Python (FastAPI), Certificado en Google GPC y Amazon Services.
Me encuentro culminando mis estudios en Ingeniería de sistemas en la [Universidad Popular del Cesar](https://www.unicesar.edu.co).

## Proyectos Destacados ⭐
1. **Mevo Taxis**
   - Es una app para solicitar transporte urbano de manera virtual. Implementa Flutter para desarrollo multiplataforma y Firebase para múltiples servicios internos.
   - https://github.com/jrdeavila/Move.git

2. **Sistematización de servicios internos (Club Valledupar)**
   - Proyecto de sistematización de servicios dentro del club. Implementando plataforma web y móvil. Ayudo a mejorar la eficiencia de los servicios de comida, reservación de áreas internas y tramites de documentos en un 80%. La plataforma web esta desarrollada en React.js con Laravel y la App móvil para socios del club está desarrollada en Flutter.
   - https://github.com/jrdeavila/club-valledupar-backend.git
   - https://github.com/jrdeavila/club_valledupar_app.git

3. **Observapp (Cámara de comercio de Valledupar)**
   - Es una app que permite a comerciantes y emprendedores visualizar indicadores socioeconómicos a través de minería de datos y análisis de inteligencia de negocios. Está desarrollada en Flutter e implementa una arquitectura de microservices para el manejo de lógica de negocio.
   - https://github.com/jrdeavila/observapp-ms.git
   - https://github.com/jrdeavila/mobile_opservapp.git
   - https://github.com/jrdeavila/admin_observapp.git



## Contacto 🔗
- Correo Electrónico: morenojr15@hotmail.com | jrdeavila@unicesar.edu.co
- LinkedIn: linkedin.com/in/jose-ricardo-de-ávila-moreno


¡Gracias por visitar mi perfil! Espero que encuentres interesantes mis proyectos y contribuciones. ¡Hagamos cosas increíbles juntos! 🚀
