<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Manuales técnicos
    
    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.jpg')})`}" data-aos="fade-left"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-right")
        p.mb-0 Un manual de mantenimiento es un documento de comunicación técnica destinado a dar recomendaciones e información necesaria para mantener el sistema de manera efectiva. Este puede incluir una definición del entorno de soporte de #[em software], funciones y responsabilidades del personal de mantenimiento, actividades regulares esenciales para el soporte, etc.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Manual de operación y mantenimiento: definición, beneficios, creación
    
    p.mb-5(data-aos="fade-right") En las empresas se necesita una fuente unificada de información para realizar sus tareas con la misma eficiencia. 

    .row.justify-content-end.align-items-center.mb-5
      .col-lg-4.col-8.img-03.zindex-1.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img02.svg' alt="Imagen decorativa")
      .col-2.d-lg-none.d-flex
      .col-xl-6.col-lg-7.zindex-2(data-aos="fade-left")
        .arrow-left.BG13.p-4
          p.text-white.mb-0 Un manual de operación y mantenimiento, también conocido como manual de operación y mantenimiento, es un documento completo y detallado que brinda a los empleados de mantenimiento información sobre cómo verificar, reparar y mantener la maquinaria y el equipo. Su objetivo principal es estandarizar los procesos técnicos en una empresa para mejorar su calidad. Aparte de eso, contiene las mejores prácticas y pautas de seguridad. No solo los empleados y técnicos de mantenimiento confían en este documento, sino también los gerentes, ejecutivos y contratistas externos.
      .col-lg-1.d-lg-flex.d-none

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Beneficios de un manual de operación y mantenimiento
    
    p.mb-5(data-aos="fade-right") Si aún pasa por alto la importancia de crear manuales de operación y mantenimiento, a continuación, se indica exactamente cómo mejorar el rendimiento de su empresa:

    .tarjeta.BGIMG04.p-lg-5.p-4.mb-5(data-aos="zoom-in")
      .tarjeta.tarjeta--blanca.p-4
        SlyderA(tipo="b")
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img03.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Cree un repositorio para la información
              p.mb-0 Ese es un gran error cuando todas las instrucciones que usa un equipo se almacenan en diferentes lugares y lleva mucho tiempo encontrarlas. Los empleados deben tener acceso rápido a la base de datos para no perder tiempo.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img04.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Evite el tiempo de inactividad no planificado
              p.mb-0 Todo el mundo sabe que el tiempo de inactividad no planificado conduce a una disminución de los ingresos. Probablemente, uno no puede prever todas las roturas inesperadas, pero al menos sí reducir drásticamente el tiempo de inactividad al crear instrucciones claras sobre cómo reparar el equipo y quién es responsable de eso.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img05.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Contribuir a los estándares de seguridad
              p.mb-0 La seguridad de los empleados siempre ha sido una de las principales prioridades de todas las empresas, por grandes que sean. Un manual de operaciones y mantenimiento es una excelente solución para instruir a los empleados sobre cómo mantener el equipo de manera segura y mostrarles lo que no se debe hacer. Seguir las normas de seguridad ayuda a evitar accidentes y, en consecuencia, acciones legales.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img06.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Contribuir a los estándares de calidad
              p.mb-0 Un manual de O&amp;M brinda pautas inequívocas sobre todos los procesos de trabajo en una empresa. Cuando todos los empleados siguen las mismas instrucciones, completan sus tareas por igual. Los procesos unificados están libres de errores e inconsistencias. Eso proporciona su alta calidad.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img07.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Acelere el aprendizaje y la incorporación
              p.mb-0 Cuando se contratan nuevos empleados, definitivamente necesitan un tutor al principio. Pero eso no es correcto depender completamente de un tutor. Parte de la información se puede aprender de un manual o instrucción. Eso ahorra tiempo para ambas partes: tutores y recién llegados.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Tipos de manuales de operación y mantenimiento
    
    p.mb-5 Es una práctica común que las grandes empresas creen diferentes tipos de manuales de operación y mantenimiento. Estos son diferentes subsistemas. Digamos que no siempre se supone que los diferentes equipos estén involucrados en el flujo de trabajo de los demás, por eso se puede decir que pueden existir diferentes tipos de manuales de O&amp;M según el tipo de trabajo o actividad, funciones y público, encontrando:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.order-lg-1.order-2(data-aos="fade-right")
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Manuales de instalación, operación y mantenimiento.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Manuales de procedimientos de emergencia.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Manuales de recursos humanos y manuales de empleados.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Manuales de asistencia técnica.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Manuales de #[em software].
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Manuales para la administración de datos.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Guías de copia de seguridad y recuperación.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Manuales de asistencia técnica.
      .col-lg-5.col-10.px-5.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema2/img08.svg' alt="Imagen decorativa")

    .row.justify-content-center.mb-5
      .col-lg-8.cajon.color-acento-botones.p-4(data-aos="flip-up")
        p.mb-0 El objetivo principal de esta división es proporcionar a un empleado información en un ámbito particular y para una situación particular.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 ¿Qué se incluye en un manual de operación y mantenimiento?
    
    p.mb-5(data-aos="fade-right") Por supuesto, los manuales pueden ser bastante diversos (maquinaria, construcción, #[em software], etc.) y su contenido puede ser diferente, pero estas son las cosas que probablemente encontrará en uno de ellos:

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img09.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4
        .h4.t-p(data-aos="fade-left") Información sobre la empresa<br><br>
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Información general: audiencia, terminología, alcance de un manual, etc.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Características operativas de la maquinaria.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Especificaciones técnicas del equipo.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Planos y mapas para indicar las posiciones de las piezas del equipo.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Dibujos de ingeniería de maquinaria y equipo.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Horarios de mantenimiento.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Información de contacto de los proveedores de equipos.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Documentación de mantenimiento de emergencia.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Reglas de seguridad.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 ¿Cómo crear un manual de operación y mantenimiento?
    
    p.mb-5(data-aos="fade-right") Se necesita tiempo y esfuerzo para crear un manual de operación y mantenimiento. No se trata simplemente de reunir toda la información en un solo documento. Tenga en cuenta:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-7.order-lg-1.order-2
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 01
          .col
            .p-4
              .h5.mb-0 Es muy importante que el manual sea claro, fácil de entender y útil. Entonces, averigüe cómo lograr esto.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 02
          .col
            .p-4
              .h5.mb-0 Elija una herramienta de escritura técnica.
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 03
          .col
            .p-4
              .h5.mb-0 Hoy en día, seguramente se puede encontrar una enorme lista de diversas herramientas técnicas de escritura.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 04
          .col
            .p-4
              .h5.mb-0 Cada uno de ellos tiene sus propias ventajas y desventajas y está dirigido a resolver problemas particulares.
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 05
          .col
            .p-4
              .h5.mb-0 Tenga en cuenta que debe elegir una herramienta que se adapte a su proceso de escritura individual y satisfaga sus necesidades únicas.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 06
          .col
            .p-4
              .h5.mb-0 El equipo de más que nadie, conoce los problemas a los que se enfrentan los redactores técnicos a diario.
      .col-lg-5.col-8.px-5.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema2/img10.svg' alt="Imagen decorativa")

    p.mb-5(data-aos="fade-right") Por eso se recomienda que preste atención a lo siguiente:

    .row.justify-content-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img11.svg' alt="Imagen decorativa")
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta BG02")
          div.px-2(titulo="Fácil colaboración en equipo")
            p.mb-0 Es una práctica común cuando un equipo de escritores técnicos escribe un manual enorme y varios revisores lo revisan. Todos pueden hacerlo simultáneamente. ¿Su herramienta de creación de ayuda facilita la colaboración? Si no, esa es una buena razón para cambiarlo.
          div.px-2(titulo="Rápida actualización de los temas existentes")
            p.mb-0 Los manuales cambian con el tiempo. Deben actualizarse y no debe consumir tanto tiempo como crear documentación desde 0. ¿Tu herramienta te permite actualizar temas en un par de clics? Si no es así, busque una herramienta que se ocupe de eso.
          div.px-2(titulo="Versión simple de la documentación técnica")
            p.mb-0 Una de las cosas más desafiantes es crear diferentes versiones del mismo documento. ¿Cómo haces eso ahora? ¿Tienes que copiar y pegar fragmentos de texto que son comunes para varios temas? Sería mucho más fácil almacenarlos en un repositorio separado y usarlos cuando los necesite.
          div.px-2(titulo="Análisis profundo")
            p.mb-0 ¿Su herramienta le permite realizar un seguimiento de la preparación de su proyecto o si los usuarios encuentran útiles sus temas o no? ¿Cuáles de los temas son más populares y cuáles no? Las estadísticas detalladas pueden mostrarle todos los puntos débiles de su documentación.

    p.mb-5(data-aos="fade-right") Estos son solo algunos de los beneficios que puede obtener utilizando una herramienta adecuada. Es por eso que es un gran problema tomar la decisión correcta.

    .row.justify-content-center.mb-4
      .col-lg-6.col-sm-10.mb-xl-0.mb-4(data-aos="fade-right")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/tema2/img12.png' alt="Imagen decorativa")
          .tarjetas-up_card.BGT01.p-lg-4.p-sm-3.p-1
            .title.d-flex.align-items-center.justify-content-center.mb-lg-4.mb-2
              span
                i.fas.fa-caret-up.fa-2x.me-3
                i.fas.fa-caret-down.fa-2x.me-3
              h4.mb-0 Hacer un plan
            p.text-center.mb-0 Crear una pieza de documentación técnica eficiente y agradable es una tarea desafiante. No se puede hacer en el acto. Uno debe pensar qué debe incluirse en un documento, por qué esta información es vital, qué formato debe usar, qué diseño es el mejor, cómo debe ser la arquitectura del documento y muchas cosas más. Un plan consistente y bien pensado le mostrará las brechas de información existentes y cómo se pueden eliminar.
      .col-lg-6.col-sm-10.mb-xl-0.mb-4(data-aos="fade-left")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/tema2/img13.png' alt="Imagen decorativa")
          .tarjetas-up_card.BGT01.p-lg-4.p-sm-3.p-1
            .title.d-flex.align-items-center.justify-content-center.mb-lg-4.mb-2
              span
                i.fas.fa-caret-up.fa-2x.me-3
                i.fas.fa-caret-down.fa-2x.me-3
              h4.mb-0 Colaborar con las pymes
            p.text-center.mb-0 Seguramente un redactor técnico no puede estar al tanto de todos los procesos que tienen lugar en una empresa. Por eso es importante colaborar con varias partes interesadas para obtener la mayor cantidad de información posible y crear una documentación completa. Asegúrate de hacerlo todo bien y no olvides documentar el llamado conocimiento tribal, la práctica común que existe en todos los equipos pero que nunca ha sido documentada.

    separador
    #t_2_1.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 2.1 Especificaciones

    p.mb-5(data-aos="fade-right") Hay muchos tipos diferentes de manuales técnicos específicos que contienen información detallada con orientaciones o instrucciones con el fin de guiar o mejorar la eficacia de las tareas a realizar, veamos los siguientes:

    .tarjeta.BGIMG04.p-lg-5.p-4.mb-5(data-aos="zoom-in")
      .tarjeta.tarjeta--blanca.p-4
        SlyderB.px-1(:datos="datosSlyder")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo escribir un manual técnico
    
    p.mb-5(data-aos="fade-right") Ahora se verán los pasos exactos que debe seguir para escribir un manual técnico altamente efectivo:

    .tarjeta.BGIMG04.p-lg-5.p-4.mb-5(data-aos="zoom-in")
      PasosB.color-acento-botones
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img24.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Defina su público objetivo
            p El primer paso que debe dar en el proceso de redacción de su manual técnico es definir su público objetivo. Puede pensar que conoce a sus clientes, pero la realidad es que las empresas con frecuencia operan con suposiciones y conceptos erróneos.
            p.mb-0 Conozca los usuarios. Descubra cómo están utilizando sus productos, cuáles son sus desafíos y su nivel de experiencia técnica. Esto le permitirá presentar su manual al nivel correcto sin presionar a sus usuarios más allá de sus habilidades actuales. Su equipo de atención al cliente puede ser un recurso valioso cuando se trata de conocer a sus clientes. Podrán decirle qué preguntas hacen los clientes con frecuencia y cómo los clientes usan sus productos.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img25.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Diseñe una plantilla
            p Todos sus documentos dentro de su manual técnico deben seguir una estructura predefinida. Cuando sus usuarios saben qué esperar, esto mejora su experiencia con el manual y hace que su contenido sea más consistente. Esto es especialmente crítico cuando está utilizando un equipo de escritores para crear su manual, como probablemente lo será. 
            p La plantilla debe contener información vital relacionada con la estructura del documento. Esto incluye si usar una tabla de contenido, los títulos y subtítulos, así como las opciones de formato. 
            p.mb-0 Tener una plantilla estandarizada les brinda a sus escritores un tiempo más fácil cuando se trata de crear contenido nuevo. Pueden seguir un conjunto de reglas predefinidas que su organización ha implementado para garantizar la correcta presentación del contenido.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img26.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Resuma el propósito del producto/característica
            p.mb-0 Cuando se trata de escribir su manual técnico, debe asegurarse de que es el experto cuando se trata de explicar su producto y cómo usarlo. Reserve suficiente tiempo para explorar todo sobre los productos y su caso de uso previsto, así como sus características y cómo operarlos. En esta etapa, probablemente querrá obtener información de expertos en la materia, como ingenieros o gerentes de productos, quienes tendrán una contribución significativa para hacer su documentación. Podrán proporcionar información sobre el producto que no esperaría, como fallas comunes y métodos de solución de problemas. También es posible que desee encuestar a sus clientes para averiguar cómo utilizan su producto y sus funciones. Luego puede asegurarse de que su manual técnico sea completo y se adapte a las necesidades de sus clientes.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img27.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Agregue instrucciones paso a paso
            p.mb-0 Debe presentar sus instrucciones a los usuarios en un formato paso a paso. No hay nada peor en un manual técnico que un muro de texto temido, que no es muy accesible para los usuarios que buscan solucionar un problema. Cuando sus instrucciones se presentan paso a paso, puede explicar qué debe hacer el sistema en cada etapa de la operación. Las instrucciones paso a paso son más fáciles de seguir y permiten a los usuarios realizar un seguimiento de su progreso fácilmente. Los usuarios pueden comprender los pasos que deben seguir de antemano, lo que facilita el proceso de solución de problemas. También son más fáciles de escanear, lo que permite a los usuarios decidir rápidamente si el documento resolverá su problema antes de embarcarse en una solución.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img28.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Hágalo visualmente atractivo
            p Ningún manual técnico está completo sin representaciones visuales del producto y sus características. Pueden ser capturas de pantalla, diagramas, fotografías o incluso videos. Los activos visuales rompen el muro de texto al que los usuarios se enfrentarían y también les permite interpretar la documentación de manera más eficaz.
            p Si su manual es para un producto de #[em software], las capturas de pantalla muestran a los clientes cómo se supone que debe verse su producto y los guía a través de las instrucciones con más éxito que el texto solo. Con imágenes y diagramas de productos, los clientes se familiarizan con el funcionamiento correcto del producto y pueden diagnosticar exactamente dónde algo salió mal.
            p.mb-0 Los activos visuales facilitan la descripción del proceso de solución de problemas y también reducen los posibles costos de traducción.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img29.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Amplíe para revisión por pares
            p.mb-0 Su documentación debe revisarse internamente antes de que esté lista para su publicación. Un grupo de pares que incluya expertos en la materia es vital para garantizar que la documentación sea precisa y tenga sentido para los usuarios. Por eso también es importante contratar los servicios de usuarios no técnicos, que podrán resaltar áreas en las que la documentación es difícil de entender. La documentación con errores es peor e inútil para los clientes, pues presenta una imagen de marca negativa y significa que sus instrucciones no son adecuadas para su propósito. Tampoco desea representar su producto de una manera que vaya en contra de la estrategia de la empresa. Los revisores expertos pueden ayudarle aquí.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img30.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Publique el artículo
            p.mb-0 Finalmente, está listo para publicar la documentación. Es probable que haya pasado por un largo proceso para llegar a esta etapa, por lo que publicar sus artículos es un gran hito. Una vez que haya publicado su documentación, no olvide revisar y verificar si hay algún error que pueda haber pasado por alto. Esto incluye asegurarse de que su contenido se muestre correctamente y se vea bien en cualquier dispositivo. Asegúrese de que sus clientes conozcan la documentación enlazándola de manera destacada en su sitio web e incluyéndose en los correos electrónicos de bienvenida. Si su producto es físico, incluye versiones impresas con cada entrega o informe a los clientes dónde pueden encontrar su manual en línea.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img31.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Recopile los comentarios de los usuarios
            p.mb-0 Después de la publicación, su manual técnico nunca está completamente terminado. La ventaja de los manuales en línea es que puede recopilar comentarios de los usuarios bastante detallados sobre cada aspecto de su documentación. Puede ver cuántas visitas han recibido ciertas páginas, votos a favor y en contra, y qué páginas generaron un ticket de soporte. También es posible que desee encuestar a sus clientes para obtener sus comentarios cualitativos sobre la utilidad de su documentación. Pregúnteles si el contenido satisfizo sus necesidades y cualquier mejora que les gustaría ver. Utilice los comentarios de sus clientes para mejorar continuamente la documentación y asegurarse de que satisfaga las necesidades de los clientes.
        .row.justify-content-center
          .col-lg-4.col-8.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img32.jpg' alt="Imagen decorativa")
          .col-lg-8
            .h4.t-p Analice, actualice y mantenga
            p.mb-0 A medida que sus productos se desarrollen y actualicen, también debería hacerlo su manual técnico. Es probable que su equipo de producto agregue nuevas funciones o corrija errores que dificultan la experiencia del usuario. Su documentación debe cambiar para reflejar el producto y debe verificar continuamente su precisión. A veces, su producto puede sufrir cambios tan significativos como para requerir la actualización masiva de todas las capturas de pantalla en su manual. Deje tiempo en el proceso de desarrollo para tener en cuenta la actualización de la documentación.


    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Mejores prácticas para escribir un manual técnico
    
    p.mb-5(data-aos="fade-right") Aplique las siguientes prácticas: 

    .BGIMG05.px-md-5.px-4.mb-4(data-aos="zoom-in")
      LineaTiempoB.color-secundario(:datos="datosLineaTiempoB")
    
    separador
    #t_2_2.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 2.2 Procedimientos
    
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img37.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 La implementación y documentación de los procedimientos ayudan a la empresa a revisar objetivamente la efectividad de sus procesos y explorar la posibilidad de hacer las cosas de manera diferente; por consiguiente tener en cuenta que:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-7.order-lg-1.order-2
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Un manual de políticas y procedimientos es una herramienta empresarial clave para cualquier organización que es muy útil si se diseña e implementa correctamente.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Hay muchas razones para tener un manual de políticas y procedimientos, incluyendo; controles internos, cumplimiento normativo, capacitación de empleados y consistencia, por nombrar algunos.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Además de ahorrar tiempo en la determinación de los procesos, un manual de procedimientos documentado reduce los errores y mejora la eficiencia de los empleados.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Las políticas y los procedimientos son necesarios para el cumplimiento de las reglamentaciones, controles internos, requisitos operativos, gestión de riesgos y deficiencias continuas.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Muchas organizaciones se someten a una auditoría anual y deben proporcionar a los auditores controles internos documentados y políticas relacionadas.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Si las políticas no están bien documentadas, los auditores podrían potencialmente reportar debilidades de control interno y anotarlas en su informe de auditoría.
      .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema2/img38.svg' alt="Imagen decorativa")

    .row.justify-content-center.mb-5
      .col-lg-5.col-10.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img39.svg' alt="Imagen decorativa")
      .col-lg-7
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Además, varias agencias requieren que los empleadores desarrollen y sigan políticas relacionadas con los beneficios de los empleados, informes de tiempo, etc.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Los manuales de políticas y procedimientos pueden adoptar una variedad de formatos, desde una descripción general de las políticas organizacionales hasta procesos/procedimientos detallados.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Proceder a documentar los detalles específicos en cada área, como la nómina, los desembolsos, los recibos, el proceso de cierre mensual, etc.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Otra buena herramienta para incorporar en el manual de políticas y procedimientos es el calendario de fechas de vencimiento.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Documentar los ciclos de nómina, las fechas de pago, la inscripción anual abierta para beneficios, etc. Un calendario que describa tareas y proyectos semanales, mensuales y anuales puede ser muy útil. Además de ayudar en la estructura organizativa general de la entidad, un calendario también evita que los empleados pasen por alto o pierdan una fecha límite importante.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Formalizar políticas y procedimientos puede parecer una gran tarea, pero vale la pena el esfuerzo.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Tenga en cuenta que estas políticas son dinámicas y deben actualizarse de vez en cuando a medida que se necesitan cambios.

    .row.justify-content-center.mb-5
      .col-auto.BGR01.px-4.py-2(data-aos="fade-left")
        .h4.text-center.mb-0 Pero ¿qué es un manual de políticas y procedimientos y qué se debe tener en cuenta?
    
    ImagenInfografica.color-secundario.mb-5(data-aos="zoom-in")
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema2/img40.svg')

      .BGR13.p-3(x="26.3%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 01
        p.text-white.mb-0 Un manual de políticas y procedimientos es un documento codificado que describe todas las políticas, los procedimientos, los SOP, las mejores prácticas y las reglas necesarias que los empleados de la organización deben seguir.
      .BGR13.p-3(x="32.7%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 02
        p.text-white.mb-0 Es necesario modificar las reglas y crear un manual que los empleados puedan consultar para fines de cumplimiento y gestión de riesgos.
      .BGR13.p-3(x="38.3%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 03
        p.text-white.mb-0 Se instruye a los nuevos empleados para que lean el manual cuando se unan a la organización para que puedan alinearse con los requisitos comerciales, de cumplimiento y de gestión de riesgos de la organización.
      .BGR13.p-3(x="44%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 04
        p.text-white.mb-0 Estos manuales también se usan como referencia cada vez que ocurre un problema.
      .BGR13.p-3(x="50.3%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 05
        p.text-white.mb-0 Actúan como una guía que puede ayudar a los empleados confundidos a tomar la decisión correcta cuando sea necesario.
      .BGR13.p-3(x="56.1%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 06
        p.text-white.mb-0 Crear un manual de políticas y procedimientos es vital y concluyente para las organizaciones.
      .BGR13.p-3(x="61.7%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 07
        p.text-white.mb-0 El manual debe elaborarse para garantizar que la organización y sus empleados se comporten de manera legal, ética y consciente del cumplimiento.
      .BGR13.p-3(x="67.3%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 08
        p.text-white.mb-0 Las políticas y los procedimientos varían de una empresa a otra, por lo que no existe una plantilla que cada empresa pueda simplemente copiar y usar.
      .BGR13.p-3(x="73.7%" y="93.7%" numero="+")
        .h2.text-end.t-g.mb-0 09
        p.text-white.mb-0 Para crear un manual de políticas y procedimientos que realmente pueda ofrecer un modelo para la cultura organizacional, es importante dar algunos pasos antes de diseñarlo.

    .row.justify-content-center.mb-5
      .col-auto.BGR01.px-4.py-2(data-aos="fade-left")
        .h4.text-center.mb-0 Ya resuelta la pregunta, tenga en los siguientes pasos:
    
    TabsB.color-primario.mb-5(data-aos="zoom-in")
      .py-4.py-md-5(titulo="Paso 1. Comprensión de las necesidades y requisitos legales" :icono="require('@/assets/curso/tema2/img41.svg')")
        .row.justify-content-center
          .col-lg-5.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img41.png' alt="Imagen decorativa")
          .col-lg-7
            ul.lista-ul--color
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Requisitos legales.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Visión de la empresa.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Políticas que dependen del estilo de gestión.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Objetivos de la organización.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Procedimientos.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Cumplimiento de leyes y reglamentos. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Asesoramiento de un profesional especializado en creación de manuales que conozcan las leyes comerciales locales.
      .py-4.py-md-5(titulo="Paso 2. Cuantas más partes interesadas, mejor" :icono="require('@/assets/curso/tema2/img42.svg')")
        .row.justify-content-center
          .col-lg-5.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img42.png' alt="Imagen decorativa")
          .col-lg-7
            ul.lista-ul--color
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | El manual debe enumerar el enfoque de mejores prácticas para cada procedimiento. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Si los empleados intentan ignorar o eludir el manual, es una señal de que lo que está escrito en el manual no es práctico ni eficiente.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | La solución a este problema es incluir a más partes interesadas en la discusión sobre la creación del manual. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Las personas que trabajan en la base y en la primera línea tienen más conocimientos que las personas que trabajan en la gestión.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | El manual debe reflejar una imagen precisa del entorno de trabajo y puede haber situaciones en las que el manual no sea aplicable.
      .py-4.py-md-5(titulo="Paso 3. La colaboración es necesaria" :icono="require('@/assets/curso/tema2/img43.svg')")
        .row.justify-content-center
          .col-lg-5.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img43.png' alt="Imagen decorativa")
          .col-lg-7
            ul.lista-ul--color
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Es necesario un sistema de gestión de documentos. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Estos sistemas permiten que varias personas vean, revisen, editen y compartan el mismo documento mientras realizan un seguimiento de los cambios realizados por todos. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Esto permite que las personas dejen comentarios, realicen ediciones y luego los dejen para su aprobación y realmente colaboren en la creación de un manual de políticas y procedimientos que funcione para todas las partes interesadas de la organización.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Los sistemas de gestión de documentos eliminan por completo la necesidad de enviar archivos o actualizaciones y permiten que las personas se concentren en mejorar la última versión del documento.
      .py-4.py-md-5(titulo="Paso 4. Usar las herramientas de GRC correctas" :icono="require('@/assets/curso/tema2/img44.svg')")
        .row.justify-content-center
          .col-lg-5.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema2/img44.png' alt="Imagen decorativa")
          .col-lg-7
            ul.lista-ul--color
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Los manuales de políticas y procedimientos están intrínsecamente vinculados a la gestión de gobierno, riesgos y cumplimiento, por lo que existen muchas herramientas basadas en GRC para la gestión de políticas y procedimientos. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Estas herramientas van más allá de los sistemas normales de gestión de documentos porque han sido diseñadas especialmente para ser utilizadas en la gestión de políticas y procedimientos. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Estas herramientas no son difíciles de usar o adquirir: simplemente es necesario suscribirse a las herramientas basadas en la nube.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Sus computadoras son una de las herramientas más importantes que necesita para administrar la empresa.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Se usan para comunicarse con los empleados, anunciar sus productos y servicios a los clientes, crear y almacenar sus archivos e investigar sobre las tendencias de la industria, entre otras cosas. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Es por eso que siempre necesita mantenerlos en la mejor forma, limpiando regularmente sus computadoras. 

    .row.justify-content-center.mb-5
      .col-auto.BGR01.px-4.py-2(data-aos="fade-left")
        .h4.text-center.mb-0 Razones por las que siempre debe mantener sus computadoras ordenadas:
    
    .BGIMG03.px-md-5.px-4.mb-5(data-aos="zoom-in")
      SlyderF(columnas="col-xl-4 col-md-6")
        .tarjeta.color-acento-contenido.h-100.p-4
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema2/img45.png' alt='Imagen decorativa')
          p.mb-0 Con el tiempo, el polvo se acumula dentro de las computadoras y obstruye el ventilador, lo que provoca un sobrecalentamiento.
        .tarjeta.color-primario.h-100.p-4
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema2/img46.png' alt='Imagen decorativa')
          p.text-white.mb-0 Cuando las computadoras se sobrecalientan, funcionan más lentamente. Este retraso hace que tanto las máquinas como sus usuarios realicen menos trabajo, lo que reduce la productividad.
        .tarjeta.color-acento-contenido.h-100.p-4
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema2/img47.png' alt='Imagen decorativa')
          p.mb-0 Las computadoras pueden albergar gérmenes, virus y bacterias que pueden enfermar a los usuarios.
        .tarjeta.color-primario.h-100.p-4
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema2/img48.png' alt='Imagen decorativa')
          p.text-white.mb-0 La limpieza regular extiende la vida útil de sus computadoras.

    .row.justify-content-center.mb-5
      .col-auto.BGR01.px-4.py-2(data-aos="fade-left")
        .h4.text-center.mb-0 Ahora bien, ¿qué implica la limpieza de tus ordenadores?
    
    p.mb-5(data-aos="fade-left") Si lo está haciendo usted mismo, esto es lo que debe hacer:

    .row.justify-content-center.mb-4
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img49.svg' alt="Imagen decorativa")
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta BG02")
          .row.justify-content-center.align-items-end(titulo="Reúna sus materiales de limpieza")
            .col-lg-8.order-lg-1.order-2
              p Necesitará:
              ul.lista-ul--color
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Agua.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Alcohol isopropílico o limpiacristales.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Toallitas limpiadoras de pantallas de ordenador.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Ropa de microfibra.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Espolvoreadores de aire comprimido.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Cotonetes.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Palillos de dientes.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Destornillador.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  | Cepillo de pintura.
            .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img50.svg' alt="Imagen decorativa")
          .row.justify-content-center(titulo="Apague todo")
            .col-lg-11
              p.mb-0 Apague sus computadoras y desenchúfalos del tomacorriente. Esto reduce el riesgo de descargas eléctricas durante la limpieza.
          .row.justify-content-center(titulo="Limpie los componentes uno a uno")
            .col-12.mb-4
              p.mb-0 Varias partes de la configuración de su computadora deben limpiarse regularmente, lo que incluye:
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema2/img51.svg' alt="Imagen decorativa")
            .col-lg-8.mb-4
              ul.lista-ul--color
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  p.mb-0 #[b La torre o CPU de la computadora.] La torre de la computadora acumula polvo que puede disminuir gradualmente el rendimiento de la máquina.<br><br>Coloque la torre de la computadora encima de una lona. Proteja el área, use una máscara y retire la carcasa con un destornillador. Limpie los componentes internos con aire comprimido.
            .col-12.mb-4
              ul.lista-ul--color
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  p.mb-0 #[b El monitor.] Use toallitas limpiadoras para eliminar manchas o manchas en la superficie del monitor. Alternativamente, puede usar un paño de microfibra humedecido con alcohol o agua corriente. Nunca vierta directamente ningún líquido sobre el monitor para evitar dañar sus componentes internos.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  p.mb-0 #[b El teclado.] Según un estudio, los teclados sucios contienen bacterias debido al polvo, la suciedad y los restos de comida. Para limpiarlo, voltee el teclado, golpéelo suavemente, use un pincel e hisopos de algodón con aire comprimido. Limpie la superficie con alcohol semanalmente.
                li(style="margin-bottom: 2px")
                  i.fas.fa-check-circle.t-ac
                  p.mb-0 #[b El ratón.] Comience desconectando el mouse de la computadora y retirando la batería, si la hay. Luego, limpie el exterior del mouse con un paño suave y elimine la suciedad y la suciedad de las grietas con un palillo. Finalmente, limpie el sensor y otros componentes del mouse con un bastoncillo de algodón ligeramente humedecido con alcohol isopropílico. No utilice una fuerza excesiva en el hisopo, ya que esto puede dañar el sensor del mouse.
            .col-12
              .tarjeta.BG05.p-4
                .row.justify-content-center
                  .col-lg-2.col-4.mb-lg-0.mb-4
                    img(src='@/assets/curso/tema2/img52.svg' alt="Imagen decorativa")
                  .col-lg-10
                    p.text-white.mb-0 Después de limpiar todos los periféricos de sus computadoras, asegúrese de que estén completamente secos antes de volver a enchufarlos. Recuerde limpiar sus computadoras una vez cada seis meses para garantizar su rendimiento óptimo. Además de limpiar regularmente sus computadoras, también es importante asegurarse de que su sistema de TI esté libre de #[em malware] y otras ciber amenazas.

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    mostrarIndicador: true,
    datosSlyder: [
      {
        titulo: '<span style="color: #5573C6">Los Manuales de productos</span>',
        texto:
          'Brindan a los usuarios una descripción general básica de un producto. Les dice a los usuarios para qué es el producto, explica sus características y cómo configurar, mantener y usar el producto.',
        imagen: require('@/assets/curso/tema2/img14.jpg'),
      },
      {
        titulo:
          '<span style="color: #5573C6">Los manuales de reparación</span>',
        texto:
          'Son instrucciones detalladas sobre cómo solucionar el producto en caso de que surja un problema. <br><br>Ayudan a los usuarios a realizar el mantenimiento de rutina, así como a realizar reparaciones importantes.',
        imagen: require('@/assets/curso/tema2/img15.jpg'),
      },
      {
        titulo:
          '<span style="color: #5573C6">Las Guías de solución de problemas</span>',
        texto:
          'Son un documento estructurado que diagnóstica síntomas, elimina posibles causas y confirma al usuario cuando el sistema vuelve a estar operativo.',
        imagen: require('@/assets/curso/tema2/img16.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Los Manuales de usuario</span>',
        texto:
          'Son una guía detallada que ayuda a los clientes a familiarizarse con su producto o servicio y a superar problemas básicos con la configuración y el mantenimiento.',
        imagen: require('@/assets/curso/tema2/img17.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Documentación de la API</span>',
        texto:
          'Es un manual de referencia completo que explica a usuarios cómo trabajar e integrar la API del <em>software</em>. Contiene detalles relacionados con las funciones, clases, tipos de devolución y argumentos, junto con tutoriales y ejemplos prácticos de trabajo.',
        imagen: require('@/assets/curso/tema2/img18.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Un SDK</span>',
        texto:
          'Es un conjunto de herramientas, bibliotecas, documentación, ejemplos de código, procesos y guías que permiten a los desarrolladores de <em>software</em> crear aplicaciones.',
        imagen: require('@/assets/curso/tema2/img19.jpg'),
      },
      {
        titulo:
          '<span style="color: #5573C6">Las notas de lanzamiento de la versión</span>',
        texto:
          'Son documentación técnica que se proporciona junto con el lanzamiento de un nuevo producto o actualización de <em>software</em>.',
        imagen: require('@/assets/curso/tema2/img20.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Los manuales técnicos</span>',
        texto:
          'Son útiles para que los nuevos usuarios puedan instalar y ejecutar su producto, lo que reduce el tiempo que le lleva al usuario dominar su producto. Además, brindan advertencias sobre almacenamiento, temperatura y evitar el contacto con líquidos para seguridad.',
        imagen: require('@/assets/curso/tema2/img21.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Los manuales técnicos</span>',
        texto:
          'Son recursos valiosos para operadores y nuevos usuarios, evitando responsabilidades legales y mejorando la fidelidad de clientes.',
        imagen: require('@/assets/curso/tema2/img22.jpg'),
      },
      {
        titulo:
          '<span style="color: #5573C6">Por último, es importante recordar que la empresa</span>',
        texto:
          'Se compromete a garantizar el éxito del cliente y asegurarse de que el producto continúe funcionando de manera óptima.',
        imagen: require('@/assets/curso/tema2/img23.jpg'),
      },
    ],
    datosLineaTiempoB: [
      {
        titulo: 'Centrarse en el problema a abordar',
        texto:
          'Al escribir un manual técnico, generalmente tendrá problemas específicos que desea abordar en un artículo en particular. Indique el problema claramente en la introducción y concéntrese en resolver el único problema por artículo. No desea abrumar a los usuarios con información o distraerlos con muchos detalles técnicos.',
        icono: require('@/assets/curso/tema2/img33.svg'),
      },
      {
        titulo: 'Presentar instrucciones en orden secuencial',
        texto:
          'Al presentar su manual, asegúrese de estructurar sus pasos en orden secuencial para no confundir a su audiencia. Un paso debe seguir lógicamente al otro y ayudar a los clientes a cumplir con un proceso.',
        icono: require('@/assets/curso/tema2/img34.svg'),
      },
      {
        titulo: 'Usar un lenguaje sencillo',
        texto:
          'Usar una jerga demasiado técnica solo servirá para confundir a tus lectores cuando busquen una respuesta simple. Use un lenguaje que sus clientes encuentren fácil de entender y si debe usar un término técnico, explíquelo o enlace a un glosario.',
        icono: require('@/assets/curso/tema2/img35.svg'),
      },
      {
        titulo: 'Agregar tabla de contenido',
        texto:
          'Los artículos largos se beneficiarán de una tabla de contenido al principio, desglosando el contenido en títulos. Esto es útil para los usuarios que deseen desplazarse a una sección relevante y evitar tener que leer el artículo completo.',
        icono: require('@/assets/curso/tema2/img36.svg'),
      },
      {
        titulo: 'Agregar imágenes donde sea necesario',
        texto:
          'Como ya se mencionó, es vital proporcionar imágenes que puedan darle vida a su manual y mejorar la comprensión para sus usuarios. Las imágenes no deben ser puramente decorativas sino empleadas de alguna manera para explicar parte de la documentación.',
        icono: require('@/assets/curso/tema2/img33.svg'),
      },
      {
        titulo: 'Educar al usuario sobre las instrucciones de seguridad',
        texto:
          'Al escribir su documentación, no olvide incluir información que eduque a los usuarios sobre las instrucciones de seguridad. Aprender a utilizar el producto de forma correcta y segura es una parte importante del manual de formación y debe incluirse desde el principio.',
        icono: require('@/assets/curso/tema2/img34.svg'),
      },
      {
        titulo: 'Tenga en cuenta a los usuarios discapacitados',
        texto:
          'Al publicar su documentación, debe pensar en cómo se presenta. Por ejemplo, usando una fuente san serif y colores de alto contraste para el texto y el fondo. Estas consideraciones de accesibilidad son cruciales para los usuarios discapacitados que pueden sufrir de baja visión, por ejemplo.',
        icono: require('@/assets/curso/tema2/img35.svg'),
      },
    ],
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
