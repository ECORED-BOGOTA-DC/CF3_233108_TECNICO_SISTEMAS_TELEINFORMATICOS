<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Mantenimiento de equipos informáticos
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img01.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 El mantenimiento de los equipos es muy importante para que estos funcionen sin problemas. Un equipo informático que no se trata, puede acumular polvo y escombros, lo que puede resultar en un rendimiento lento. Además, su equipo puede infectarse con virus o #[em malware] si su antivirus no está actualizado. Los equipos funcionan bien cuando se cuidan, usted podría tener el mejor equipo informático que el dinero pueda comprar, pero sin un mantenimiento regular, es posible que no obtenga el mejor rendimiento de su inversión.
    
    .row.justify-content-center.mb-5
      .col-auto.BGR01.px-4.py-2(data-aos="fade-left")
        .h4.text-center.mb-0 Aquí hay tres razones por las que el mantenimiento regular de un equipo es una buena idea:
    
    TabsB.color-primario.mb-4(data-aos="zoom-in")
      .py-4.py-md-5(titulo="Equipos más ágiles y rápidos en su funcionamiento")
        .row.justify-content-center
          .col-lg-3.col-6.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img02.svg' alt="Imagen decorativa")
          .col-lg-9
            ul.lista-ul--color
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Con el tiempo, los archivos almacenados en su equipo pueden desorganizarse y fragmentarse, lo que hace que su equipo tarde más en cargarse y el acceso a programas y archivos se retrase. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Todos odiamos los equipos lentos y obsoletos y con un mantenimiento oportuno, puede garantizar que su equipo funcione correctamente. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Nuestros técnicos son expertos en velocidad de ejecución y controles de optimización que pueden identificar problemas y mantener su equipo funcionando a una velocidad óptima.
      .py-4.py-md-5(titulo="Exponer problemas")
        .row.justify-content-center
          .col-lg-3.col-6.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img03.svg' alt="Imagen decorativa")
          .col-lg-9
            ul.lista-ul--color
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Ya sea que su equipo sea nuevo o viejo, los problemas pueden surgir en cualquier momento. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Los equipos pueden ser impredecibles y todos sabemos que los pequeños problemas pueden convertirse en grandes problemas antes de darse cuenta. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Una de las mejores cosas del mantenimiento de su equipo es que puede identificar cualquier problema antes de que se vuelva demasiado grave. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Cuando su equipo no recibe mantenimiento, puede encontrarse con problemas que deberán abordarse; cuando los problemas no se abordan, puede haber consecuencias.
      .py-4.py-md-5(titulo="Evita los virus")
        .row.justify-content-center
          .col-lg-3.col-6.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img04.svg' alt="Imagen decorativa")
          .col-lg-9
            ul.lista-ul--color
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Cuando su equipo está infectado, se pueden sentir varios síntomas, desde ralentizaciones molestas hasta mensajes emergentes o contactos que le envían un correo electrónico sobre un correo electrónico extraño que aparentemente les envió.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Cuando esto ocurre en el hogar o en un negocio, puede ser costoso arreglarlo e incluso puede costarle dinero a la empresa de otras maneras, como la pérdida de productividad. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                p.mb-0 Pero mantener los equipos en buen estado puede mantener alejados tanto a los virus como al #[em malware] y mantener su equipo funcionando en óptimas condiciones. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                p.mb-0 El mantenimiento regular también puede ayudar a garantizar que su #[em software] antivirus esté actualizado y funcione correctamente. 
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Al mantener su equipo en buen estado con mantenimiento, puede prolongar la vida útil de su equipo.
              li(style="margin-bottom: 2px")
                i.fas.fa-check-circle.t-ac
                | Sin embargo, se ralentizan cuando llegan a cierto punto, pero seguir con el mantenimiento puede ayudar a que funcione de manera más eficiente. 

    separador
    #t_1_1.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 1.1 Características
    
    .row.justify-content-center.mb-5
      .col-lg-3.col-6.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img05.png' alt="Imagen decorativa")
      .col-lg-9
        p(data-aos="fade-left") Cuando se trata de mantenimiento, hay varias cosas que puede hacer para asegurarse de que su equipo informático funcione a su nivel óptimo.
        .row.justify-content-center.mb-5(data-aos="fade-left")
          .col-lg-1.col-2.mb-lg-0.mb-4
            img.mx-auto(src='@/assets/curso/temas/img01.svg' style="max-width: 35px" alt="Imagen decorativa")
          .col
            p.mb-0 Debido a que las computadoras son una parte tan integral de nuestras vidas, es importante que las cuidemos y mantengamos adecuadamente. Aquí exponemos las razones por las que necesita un mantenimiento informático profesional:

    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo limpiar su equipo informático
    
    p.mb-5(data-aos="fade-right") La limpieza regular de su computadora puede ayudar a prolongar su vida útil, ya que son propensas al polvo y al sobrecalentamiento; por ello, aplique este procedimiento:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta BG02")
          .row.justify-content-center(titulo="Saque el polvo de su teclado con aire comprimido")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img07.jpg' alt="Imagen decorativa")
            .col-lg-8
              p.mb-0 Desempolvar el teclado al menos una vez a la semana puede ayudar a mantenerlo (y reducir los riesgos para la salud). Limpie el teclado con un paño húmedo que no suelte pelusa, pero asegúrese de no sumergirlo en agua. Para áreas más difíciles de alcanzar, como entre las teclas del teclado, use un bote de aire comprimido.
          .row.justify-content-center(titulo="Limpie su monitor")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img08.jpg' alt="Imagen decorativa")
            .col-lg-8
              p.mb-0 Las huellas dactilares y otras manchas pueden aparecer regularmente en su monitor. Para mantener la vista de su pantalla fresca y limpia, limpie su monitor una vez por semana con un paño seco sin pelusa. Hágalo suavemente y no fuerte puede dañar su dispositivo. 
          .row.justify-content-center(titulo="Deshágase del polvo y las partículas de tu <em>mouse</em>")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img09.jpg' alt="Imagen decorativa")
            .col-lg-8
              p.mb-0 El teclado y el #[em mouse] necesitan ser desempolvados regularmente para que funcione correctamente. Para hacer esto, desconecte el #[em mouse] y dele la vuelta. A partir de ahí, querrá quitar el panel inferior y limpiar la bola con un paño sin pelusa. Puedes agregar alcohol isopropílico al paño para una limpieza más profunda. Deje que la bola se seque antes de volver a montar el ratón.
          .row.justify-content-center(titulo="Limpie el sistema a fondo")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img10.jpg' alt="Imagen decorativa")
            .col-lg-8
              p.mb-0 Cada tres a seis meses debe realizar una limpieza a fondo de todo su sistema de #[em hardware], utilice el recipiente de aire comprimido del paso 1 en el interior para evitar daños. Si tiene una computadora portátil, el desmontaje será diferente que con una computadora tradicional. Asegúrese de seguir las instrucciones que vienen con su dispositivo antes de comenzar a desarmarlo.
          .row.justify-content-center(titulo="Apague o reinicie su dispositivo regularmente")
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img11.jpg' alt="Imagen decorativa")
            .col-lg-8
              p.mb-0 Si bien apagar su dispositivo todas las noches no es un requisito con las computadoras nuevas, reiniciar regularmente ayuda a actualizar los recursos de su sistema. Si está trabajando con una computadora más antigua, debe apagar su dispositivo correctamente todas las noches para evitar el sobrecalentamiento. Si su dispositivo es más nuevo, considere reiniciarlo una vez al día y ponerlo en modo de suspensión cuando no esté en uso.
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img06.svg' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo cuidar su disco de almacenamiento
    
    p.mb-5(data-aos="fade-right") Realice los siguientes procedimientos:

    .tarjeta.BGIMG01.p-4.mb-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            .h4.mt-4 Desfragmente el disco duro
            p.mb-0 ¿Sabía que el disco es el eslabón más débil, cuando se trata de rendimiento de la computadora? Por eso es tan importante desfragmentar el disco duro una vez al mes. La desfragmentación es el proceso de reorganización de los datos en su disco duro para acelerar el acceso a los archivos. Divide un archivo en partes más pequeñas en tu dispositivo. Si bien cada computadora es diferente, generalmente puede encontrar funciones de desfragmentación en la pestaña Sistema y seguridad en el Panel de control.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img12.png' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            .h4.mt-4 Datos de copia de seguridad
            p.mb-0 Al menos una vez a la semana debe hacer una copia de seguridad de su disco. Si está trabajando en un proyecto importante, puede hacerlo todos los días para asegurarse de que sus archivos están almacenados de forma segura. La copia de seguridad de sus datos guarda archivos importantes en caso de que falle el disco duro o se cuelgue el sistema.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img13.png' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            .h4.mt-4 Configure el startup
            p.mb-0 Debe verificar periódicamente las aplicaciones que se ejecutan automáticamente al inicio. Estas aplicaciones pueden ralentizar su computadora. Desde la pestaña Configuración, debería poder navegar hasta Inicio para controlar qué aplicaciones se ejecutan.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img14.png' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            .h4.mt-4 Ejecute la limpieza del disco
            p.mb-0 Puede liberar espacio en el disco en su disco duro ejecutando una limpieza de disco. Esto limpiará los archivos temporales y los archivos de idioma adicionales, así como también eliminará los archivos adjuntos grandes y más.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img15.png' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            .h4.mt-4 Instale las principales actualizaciones de la computadora
            p.mb-0 Para mantener sus aplicaciones funcionando de manera segura y eficiente, debes verificar las actualizaciones importantes de la computadora al menos una vez al mes. Estas actualizaciones pueden ser críticas para la salud a largo plazo porque reparan agujeros de seguridad críticos y eliminan funciones innecesarias. También puede ajustar su configuración para que las actualizaciones se realicen automáticamente.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img16.png' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo eliminar el #[em malware]
    
    p.mb-5(data-aos="fade-right") El software malicioso no solo puede afectar a la computadora o al dispositivo infectado, es una amenaza para todos los equipos. A continuación, una explicación al respecto:
    
    .BGM03.px-md-5.px-4.py-4.mb-5
      figure(data-aos="zoom-in")
        img(src='@/assets/curso/tema1/img17.svg' alt="Imagen decorativa")
    
    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo mantener sus archivos sanos
    
    p.mb-5(data-aos="fade-right") Al respecto tenga en cuenta lo siguiente:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta BG02")
          .row.justify-content-center(titulo="Mover archivos similares a carpetas")
            .col-lg-11
              p.mb-0 Mantener archivos en su escritorio puede ralentizar su máquina. En su lugar, organice archivos similares en carpetas donde pueda encontrarlos fácilmente. Esto también ayudará a agilizar el proceso de limpieza cuando llegue el momento de eliminar elementos innecesarios.
          .row.justify-content-center(titulo="Eliminar programas no utilizados")
            .col-lg-11
              p.mb-0 Obtenga más espacio de memoria eliminando programas innecesarios de su dispositivo. Si filtra sus programas por tamaño, puede ver cuáles ocupan más memoria y decidir a partir de ahí qué puede eliminar.
          .row.justify-content-center(titulo="Limpiar la papelera de reciclaje")
            .col-lg-11
              p.mb-0 Cuando usted u otro usuario elimina un archivo, va a la papelera de reciclaje. Esto le da una última oportunidad de recuperar un archivo que ha eliminado, pero también puede obstruir el espacio en su disco duro si no lo limpia con regularidad. Una vez al mes, debe revisar la Papelera de reciclaje en busca de archivos que puedan haberse eliminado accidentalmente y borrar el resto.
          .row.justify-content-center(titulo="Eliminar archivos temporales de internet")
            .col-lg-11
              p.mb-0 Acelere su sistema eliminando archivos temporales de Internet y borrando su caché. Cada navegador tiene un método diferente para borrar estas #[em cookies]. Encuentre direcciones para su navegador.
          .row.justify-content-center(titulo="Transferir archivos a la nube")
            .col-lg-11
              p.mb-0 Los proveedores de almacenamiento en la nube le permiten almacenar gigabytes de espacio sin agotar la memoria de su disco duro. Mejor aún, le permite compartir sus archivos a través de múltiples dispositivos. A medida que descarga archivos a lo largo del día, transfiéralos al almacenamiento en la nube para ahorrar espacio en su disco duro.         
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img18.svg' alt="Imagen decorativa")

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img19.svg' alt="Imagen decorativa")
      .col-lg-8(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta BG02")
          .row.justify-content-center(titulo="Evite sobrecalentar tu dispositivo")
            .col-lg-11
              p.mb-0 Instale su computadora en un área de su oficina u hogar que tenga un buen flujo de aire, con dos pulgadas de espacio vacío a cada lado. Darle espacio a su máquina para que respire ayuda a prevenir el sobrecalentamiento, lo que extiende la vida útil de su dispositivo. Las pilas de papel y otros artículos que se colocan en su computadora también pueden hacer que se sobrecaliente, así que mantenga el área de su escritorio organizada y libre de desorden.
          .row.justify-content-center(titulo="Mantenga los cables organizados")
            .col-lg-11
              p.mb-0 El desorden de cables puede acumular polvo y dañarse fácilmente. Las estaciones de cable y otros organizadores de cables pueden ayudar a organizar su área. También le ahorrará tiempo y estrés la próxima vez que desconecte su computadora.
          .row.justify-content-center(titulo="No sobrecargue el dispositivo")
            .col-lg-11
              p.mb-0 Si está trabajando con una computadora portátil, puede ser tentador cargar la batería toda la noche. Si bien hacerlo no dañará el dispositivo, una de las mejores maneras de mantener la batería durante un período prolongado de tiempo es desenchufarla una vez que alcance el 100 %. También debe quitar la batería por completo si no va a utilizar el dispositivo durante un mes o más para ayudar a prolongar su vida útil.
          .row.justify-content-center(titulo="Mantenga alejados los alimentos y las bebidas")
            .col-lg-11
              p.mb-0 Solo se necesita una lata de refresco para destruir un dispositivo. Por muy tentador que sea disfrutar de un vaso de café mientras revisa sus correos electrónicos matutinos, siempre evite comer o beber cerca de su computadora para reducir el riesgo de derrames.
          .row.justify-content-center(titulo="Evite el spam mientras navegas")
            .col-lg-11
              p.mb-0 Si aparece un correo electrónico extraño en su bandeja de entrada o una ventana emergente inesperada mientras navega, resistir el impulso de abrirlo. Las estafas de #[em malware] pueden dañar en gran medida su dispositivo y poner en riesgo sus archivos y su privacidad. Al igual que un automóvil, su computadora necesita mantenimiento regular para funcionar correctamente. Hacer un mantenimiento regular de la computadora puede prolongar en gran medida la vida útil del dispositivo y puede mantenerlo más seguro mientras navega en línea. Al completar solo unos pocos pasos simples, obtendrá un sistema operativo más rápido y más saludable para trabajar.

    separador
    #t_1_2.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 1.2 Tipos de mantenimiento
    
    p.mb-5(data-aos="fade-right") El mantenimiento del sistema es un término general que abarca varias formas de mantenimiento de la computadora necesarias para mantener un sistema en funcionamiento. Los dos componentes principales del mantenimiento del sistema son el mantenimiento preventivo y correctivo. El mantenimiento preventivo implica tomar medidas para ayudar a mantener el funcionamiento del sistema, mientras que el mantenimiento correctivo implica el reemplazo o la reparación de un sistema o sus componentes después de que ya hayan fallado. A a continuación se describen:
    
    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Mantenimiento preventivo
    
    p.mb-5(data-aos="fade-right") El manten imiento preventivo se define como el mantenimiento proactivo de los equipos antes de que ocurra una falla.
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-7.order-lg-1.order-2
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 01
          .col
            .p-4
              .h5.mb-0 Preventivo implica tareas de rutina para garantizar que su sistema funcione de manera óptima y evitar problemas antes de que surjan. 
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 02
          .col
            .p-4
              .h5.mb-0 Hay varias medidas preventivas que puede tomar, incluida la instalación de actualizaciones de Windows, la detección de virus y #[em malware] y la ejecución de programas de limpieza. 
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 03
          .col
            .p-4
              .h5.mb-0 Los análisis antivirus y anti#[em malware] deben ejecutarse al menos una vez a la semana. 
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 04
          .col
            .p-4
              .h5.mb-0 Asegúrese de ejecutar actualizaciones para estos programas cada vez que se publiquen, ya que constantemente surgen nuevos virus y #[em malware].          
      .col-lg-5.col-8.px-5.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img20.svg' alt="Imagen decorativa")
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.col-8.px-5.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img21.svg' alt="Imagen decorativa")
      .col-lg-7
        .BGA04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 05
          .col
            .p-4
              .h5.mb-0 Mantenga su red segura, instale un #[em firewall].
        .BGB04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 06
          .col
            .p-4
              .h5.mb-0 Las sobretensiones y el sobrecalentamiento pueden destruir los equipos electrónicos, así que proteja su #[em hardware] invirtiendo en un protector contra sobretensiones.
        .BGA04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 07
          .col
            .p-4
              .h5.mb-0 Limpie su equipo periódicamente para eliminar el polvo.
        .BGB04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 08
          .col
            .p-4
              .h5.mb-0 Si alguna medida preventiva falla, siempre es una buena idea tener una copia de seguridad de los archivos importantes.
        .BGA04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 09
          .col
            .p-4
              .h5.mb-0 Invierta en un disco duro externo para guardar cualquier archivo importante en caso de que su computadora necesite ser reemplazada.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Mantenimiento correctivo
    
    p.mb-5(data-aos="fade-right") Se relaciona con lo siguiente:

    .row.align-items-center.mb-5
      .col-xl-1.d-xl-flex.d-none
      .col-xl-8.col-lg-10.order-lg-1.order-2
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BGR06.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 Comúnmente conocido como "reparación", es la corrección de un problema después de que la computadora ya se haya averiado. 
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BG07.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 El objetivo de esta forma de mantenimiento es restaurar la operatividad del sistema ya sea corrigiendo el problema o reemplazando los componentes dañados. 
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BG06.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 Las medidas correctivas comunes incluyen la eliminación de virus y #[em malware], la desinstalación de programas dañinos, el reformateo y la ejecución de una restauración del sistema, entre otras. 
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BG07.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 Muchos problemas informáticos comunes se solucionan fácilmente y no requieren un profesional de TI.
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BG06.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 Para realizar el mantenimiento correctivo, es importante primero diagnosticar el problema y descubrir la causa raíz.
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BGR07.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 Si no está seguro de la causa o de cómo solucionar su problema, consultar a un profesional de TI sería el mejor curso de acción.
            .col-lg-1.d-lg-flex.d-none
      .col-sm-3.col-2.d-lg-none.d-flex
      .col-lg-4.col-sm-6.col-8.img-01.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img22.svg' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Hacer que su máquina sea más confiable
    
    p.mb-5(data-aos="fade-right") Hay muchos pequeños pasos que uno puede tomar para optimizar el rendimiento de la computadora para que sea más rápida y confiable. Al respecto tenga en cuenta:


    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.mb-lg-0.mb-4
        .tarjeta-avatar-b.mb-4(data-aos="fade-right")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img03.svg' alt='Imagen decorativa')
          .tarjeta.color-primario--borde
            .p-4
              p.mb-0 No tener suficiente espacio en el disco duro puede ralentizar significativamente su computadora.
        .tarjeta-avatar-b.mb-4(data-aos="fade-right")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img04.svg' alt='Imagen decorativa')
          .tarjeta.color-acento-contenido--borde
            .p-4
              p.mb-0 Despeje el espacio del disco duro eliminando programas innecesarios y desfragmentando tu disco duro.
        .tarjeta-avatar-b.mb-4(data-aos="fade-right")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img03.svg' alt='Imagen decorativa')
          .tarjeta.color-primario--borde
            .p-4
              p.mb-0 La desfragmentación ayuda a acelerar su computadora y debe realizarse al menos una vez al mes.
        .tarjeta-avatar-b.mb-4(data-aos="fade-right")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img04.svg' alt='Imagen decorativa')
          .tarjeta.color-acento-contenido--borde
            .p-4
              p.mb-0 Cuando instale nuevos programas, a menudo se le presentará la opción de que el programa se inicie automáticamente cuando encienda la computadora, a veces, esta es la opción predeterminada.
        .tarjeta-avatar-b.mb-4(data-aos="fade-right")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img03.svg' alt='Imagen decorativa')
          .tarjeta.color-primario--borde
            .p-4
              p.mb-0 Cuantos más programas tenga ejecutándose automáticamente, más lento será el rendimiento de su computadora, por lo que debe desactivar esto siempre que sea posible. 
        .tarjeta-avatar-b.mb-4(data-aos="fade-right")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img04.svg' alt='Imagen decorativa')
          .tarjeta.color-acento-contenido--borde
            .p-4
              p.mb-0 Para que su conexión a Internet funcione más rápido, una de las cosas más sencillas que puede hacer es borrar su historial web y eliminar los archivos temporales de Internet.
      .col-lg-6
        .tarjeta-avatar-b.mb-4(data-aos="fade-left")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img03.svg' alt='Imagen decorativa')
          .tarjeta.color-primario--borde
            .p-4
              p.mb-0 Cuanto más a menudo realice estas acciones, menos tiempo llevará, así que intente apuntar al menos una vez a la semana. 
        .tarjeta-avatar-b.mb-4(data-aos="fade-left")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img04.svg' alt='Imagen decorativa')
          .tarjeta.color-acento-contenido--borde
            .p-4
              p.mb-0 El #[em software] espía y el #[em malware] también pueden ser la causa de la velocidad lenta de Internet.
        .tarjeta-avatar-b.mb-4(data-aos="fade-left")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img03.svg' alt='Imagen decorativa')
          .tarjeta.color-primario--borde
            .p-4
              p.mb-0 Asegúrese de tener programas anti#[em malware] instalados, actualícese cuando sea necesario y ejecute un análisis al menos una vez a la semana. 
        .tarjeta-avatar-b.mb-4(data-aos="fade-left")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img04.svg' alt='Imagen decorativa')
          .tarjeta.color-acento-contenido--borde
            .p-4
              p.mb-0 Puede evitar el #[em spyware] y el #[em malware] mediante el ejercicio de prácticas de descarga seguras, como la descarga desde sitios de buena reputación. 
        .tarjeta-avatar-b.mb-4(data-aos="fade-left")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img03.svg' alt='Imagen decorativa')
          .tarjeta.color-primario--borde
            .p-4
              p.mb-0 Si no está seguro de la seguridad o legitimidad de un programa, realice una búsqueda en Google para ver qué información puede encontrar y, si aún tiene dudas, abstenerse de instalar el programa por completo. y ejecute un análisis al menos una vez a la semana.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo eliminar el #[em malware] de su PC con Windows
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img23.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 Tenga cuidado con los signos de una PC plagada de #[em malware]: un rendimiento más lento de lo habitual, una repentina avalancha de ventanas emergentes y otros problemas anómalos. Si el comportamiento fuera de lo común a veces es el resultado de conflictos de #[em hardware], pero su primera acción debe ser descartar la posibilidad de infección por un virus, #[em spyware] u otra entidad nefasta, incluso si tiene un programa antivirus instalado.<br><br>Siga esta guía  paso a paso para obtener instrucciones sobre cómo deshacerse del #[em malware]:

    .row.justify-content-center.mb-4
      .col-lg-6.tarjeta.BG08.p-4(data-aos="flip-up")
        .row.justify-content-center.align-items-center
          .col-3.col-sm-2.col-lg-1
            img(src="@/assets/curso/temas/img05.svg" alt="Imagen decorativa")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h4.text-white.mb-0 Cómo eliminar el #[em malware] de su PC con Windows
              .col-sm-auto
                a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexo_1_Como_eliminar_el_malware_de_su_PC_con_Windows.pdf')" target="_blank" type="application/pdf")
                  span Descargar
                  i.fas.fa-link

    separador
    #t_1_3.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 1.3 Materiales y herramientas técnicas
    
    p.mb-5(data-aos="fade-right") El soporte y los servicios informáticos brindan servicios de diagnóstico, solución de problemas, mantenimiento y reparación para sistemas de TI:

    .BGIMG03.px-md-5.px-4.mb-5(data-aos="zoom-in")
      SlyderF(columnas="col-xl-4 col-md-6")
        .tarjeta.BG09.p-4.h-100
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema1/img24.svg' alt='Imagen decorativa')
          p.text-center.mb-0 A menudo realizado por el proveedor de servicios administrados (MSP), permite a los usuarios buscar y recibir servicios de administración y mantenimiento de computadoras de forma local o remota. 
        .tarjeta.BG09.p-4.h-100
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema1/img25.svg' alt='Imagen decorativa')
          p.text-center.mb-0 El soporte y los servicios informáticos son proporcionados por un técnico de reparación o soporte informático. 
        .tarjeta.BG09.p-4.h-100
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema1/img26.svg' alt='Imagen decorativa')
          p.text-center.mb-0 Aseguran que las operaciones generales de las computadoras y su #[em software], #[em hardware] o red relacionados funcionen correctamente. 
        .tarjeta.BG09.p-4.h-100
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema1/img27.svg' alt='Imagen decorativa')
          p.text-center.mb-0 El soporte informático se puede realizar localmente operando físicamente el dispositivo o de forma remota, iniciando sesión en la computadora de un usuario final para analizar un problema. 
        .tarjeta.BG09.p-4.h-100
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema1/img28.svg' alt='Imagen decorativa')
          p.text-center.mb-0 El soporte informático interactivo también se puede realizar por teléfono, correo electrónico o chat. 
        .tarjeta.BG09.p-4.h-100
          .row.justify-content-center.mb-3
            .col-6
              img(src='@/assets/curso/tema1/img29.svg' alt='Imagen decorativa')
          p.text-center.mb-0 La contratación de MSP que ofrecen soporte y servicios informáticos puede ayudar a su empresa a gestionar algunos problemas informáticos que pueda tener.
    
    p.mb-5(data-aos="fade-right") Los siguientes son algunos de los beneficios de contar con soporte y servicios informáticos:

    .tarjeta.BGIMG04.p-lg-5.p-4.mb-5(data-aos="zoom-in")
      .tarjeta.tarjeta--blanca.p-4
        SlyderA(tipo="b")
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img30.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Ahorrar dinero
              p.mb-0 La externalización de los servicios de TI le permitirá ahorrar dinero, ya que utilizan varios especialistas en TI. En lugar de pagar a su personal de TI interno con un salario anual, ahora puede pagar una tarifa más baja a un MSP. Además, en ciertos acuerdos, la solución subcontratada administra todos los aspectos de su soporte y servicios informáticos. Esto significa que el mantenimiento de #[em hardware] y #[em software] es parte del paquete, lo que reduce aún más sus gastos y le ahorra dinero a largo plazo.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img31.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Soporte las 24 horas
              p.mb-0 Si bien su negocio puede funcionar todo el día, sus empleados trabajan en un horario fijo. Por ejemplo, su empresa tiene un sitio web que ofrece algún tipo de servicio o compra, o información general sobre sus productos. Los clientes esperan que su sitio web esté siempre en funcionamiento, con toda la información necesaria disponible. Pero, si ocurre un problema inesperado, una sola hora de inactividad podría costar miles de dólares o más. Tener soporte y servicios informáticos confiables de terceros puede garantizar que su sitio web permanezca operativo las 24 horas del día, los 7 días de la semana. Un servicio externalizado monitoriza tu infraestructura y soluciona cualquier problema que surja en cualquier momento del día.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img32.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Le permite concentrarse en su negocio
              p.mb-0 Administrar un negocio requiere tiempo y esfuerzo. La externalización del soporte informático puede liberar tiempo al delegar la gestión de servicios de TI. Esto permite concentrarse en objetivos principales mientras los servicios de soporte mantienen las computadoras y la infraestructura técnica en funcionamiento sin problemas.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img33.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Mejorar el servicio al cliente
              p.mb-0 Los clientes tienden a tener poca paciencia cuando se trata de tiempos de espera.
          .row.justify-content-center
            .col-lg-4.col-8.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img34.jpg' alt="Imagen decorativa")
            .col-lg-8
              .h4.t-p.mb-3 Ampliar su negocio
              p.mb-0 Todo emprendedor sueña con hacer crecer su negocio. La expansión se traduce en éxito y más ingresos. Sin embargo, para hacer crecer su empresa, también necesita aumentar su infraestructura de TI y contratar un gran departamento de TI. En pocas palabras, necesita tener un gran presupuesto para que esto suceda. El uso de servicios de terceros le permite a su empresa escalar sin contratar a más personas ni agregar infraestructura. Puede subcontratar 'suscripciones' que escalan automáticamente mientras su empresa crece.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Herramientas para tener cuando se trabaja en una computadora
    
    .BGM10.px-md-5.px-4.mb-5
      figure(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img35.png' alt="Imagen decorativa")
      .row.justify-content-center
        .col-lg-10.img-02
          .tarjeta.BG11.p-4
            p.mb-0 La siguiente lista de herramientas está en orden de importancia, en nuestra opinión. Idealmente, cualquier técnico que vaya al sitio a reparar o solucionar problemas de computadoras debería tener la mayoría, si no todos, de ellos. Sin embargo, la mayoría de las situaciones no requieren todas estas herramientas al mismo tiempo. Por lo tanto, hemos dividido la lista en secciones para ayudarlo a identificar qué herramientas necesita para cada trabajo:
      .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/tema1/img36.jpg')})`}" data-aos="fade-right"
        )
        .bloque-texto-g__texto.p-4
          ul.lista-ul--color.lista-ul--separador
            li(style="margin-bottom: 2px" data-aos="fade-left")
              i.fas.fa-check-circle.t-ac
              | Muñequera antiestática o ESD.
            li(style="margin-bottom: 2px" data-aos="fade-left")
              i.fas.fa-check-circle.t-ac
              | Herramientas informáticas imprescindibles.
            li(style="margin-bottom: 2px" data-aos="fade-left")
              i.fas.fa-check-circle.t-ac
              | Correa ESD u otro dispositivo de protección ESD.
            li(style="margin-bottom: 2px" data-aos="fade-left")
              i.fas.fa-check-circle.t-ac
              | Destornillador, destornillador Phillips y destornillador Torx o broca.
            li(style="margin-bottom: 2px" data-aos="fade-left")
              i.fas.fa-check-circle.t-ac
              | Linterna.
          
    p.mb-5(data-aos="fade-right") Cuando compre un destornillador, trate de evitar cualquier destornillador que use imanes para sujetar las puntas. En su lugar, compre destornilladores que usan cojinetes de bolas para sujetar las puntas, teniendo en cuenta:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6.col-10.px-5.mx-auto.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img37.png' alt="Imagen decorativa")
      .col-lg-6(data-aos="fade-left")
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Lata de aire comprimido.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Herramientas de reparación y reemplazo de #[em hardware] de computadora.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Tapete antiestático.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Juego de destornilladores de precisión.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Aire comprimido.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Multímetro.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Piezas adicionales (p. ej., cable de alimentación, cable de red, teclado y ratón).
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Bolsas antiestáticas vacías.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Paño sin pelusa.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Soldador de bajo voltaje, mecha y carrete.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Cortacables y pelacables.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Pinzas o recogedor de piezas.
          
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Tarjeta postal.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Pistola de temperatura.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Pistola de calor.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            p.mb-0 #[em Spudger].
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Solución de problemas de #[em software] de computadora.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Unidad de salto USB con utilidades de solución de problemas y UBCD.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | CD vírgenes (en caso de que necesites hacer discos de restauración o copiar otra información).
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Pilas AA y AAA (para ratón y teclado inalámbricos).
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Herramienta de prensa.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Aspirador portátil.
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | herramientas de limpieza de computadoras.
      .col-lg-6.col-10.order-lg-2.order-1.px-5.mx-auto.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img38.png' alt="Imagen decorativa")
    
    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Mantenimiento de #[em hardware] y #[em software] informático

    p.mb-5(data-aos="fade-right") El mantenimiento en informática se trata de planificar tareas de revisión y reparación de #[em hardware] y #[em software], así:

    .row.justify-content-center.mb-4
      .col-lg-5.col-8.px-lg-5.px-4.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img39.svg' alt="Imagen decorativa")
      .col-lg-7.order-lg-1.order-2
        .BGA04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 01
          .col
            .p-4
              .h5.mb-0 El mantenimiento es necesario en la computadora para evitar fallas en el #[em hardware] o perder información valiosa y, la mayoría de las veces, el #[em hardware] se rompe sin previo aviso.
        .BGB04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 02
          .col
            .p-4
              .h5.mb-0 El exceso de calor acelera el deterioro de los delicados circuitos del sistema.
        .BGA04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 03
          .col
            .p-4
              .h5.mb-0 El polvo y la suciedad son la causa más común de sobrecalentamiento.
        .BGB04.row.mb-2(data-aos="fade-left")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 04
          .col
            .p-4
              .h5.mb-0 Por lo tanto, la limpieza de una carcasa se realiza para evitar que los componentes se sobrecalienten.
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7.order-lg-1.order-2
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 05
          .col
            .p-4
              .h5.mb-0 Los componentes de #[em hardware] de la computadora atraen el polvo, la suciedad, las pelusas, las fibras de las alfombras, el pelo de las mascotas y las partículas de humo.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 06
          .col
            .p-4
              .h5.mb-0 El aire del ventilador de enfriamiento de la computadora contiene suciedad que se deposita en los componentes y provoca un sobrecalentamiento que eventualmente resulta en una falla permanente del #[em hardware].
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 07
          .col
            .p-4
              .h5.mb-0 Como resultado de esto, se debe realizar una limpieza completa al menos una vez al año y si la computadora se usa en un ambiente cálido, polvoriento y húmedo, la limpieza se debe realizar con mayor frecuencia.
      .col-lg-5.col-8.order-lg-2.order-1.px-lg-5.px-4.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img40.svg' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Proceso de mantenimiento del #[em hardware] informático
    
    p.mb-5(data-aos="fade-right") El mantenimiento es necesario en la computadora para evitar fallas en el #[em hardware] o perder información valiosa, las acciones básicas en el mantenimiento, incluyen:

    .tarjeta.BGIMG04.p-lg-5.p-4.mb-5(data-aos="zoom-in")
      .tarjeta.tarjeta--blanca.p-4
        SlyderB.px-1(:datos="datosSlyder")
    
    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Herramientas para la limpieza del #[em hardware] de la computadora

    .BGM10.px-md-5.px-4.mb-5
      p.mb-5(data-aos="fade-right") Se debe usar un paño limpio no abrasivo como microfibra, algodón, camiseta, pañuelo de algodón y evitar el uso de toallas de papel, paños de cocina, pañuelos faciales, trapos viejos. También los siguientes elementos:
      .row.justify-content-center
        .col-xl-10
          .row.justify-content-center
            .col-lg.col-sm-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
              .BGS05.p-4.h-100
                .h1.t-l.text-end 01
                figure.mb-4
                  img(src='@/assets/curso/tema1/img50.svg' alt="Imagen decorativa")
                p.text-center.text-white.mb-0 Aspiradora portátil.
            .col-lg.col-sm-4.col-8.mb-lg-0.mb-4(data-aos="flip-right")
              .BGR01.p-4.h-100
                .h1.t-l.text-end 02
                figure.mb-4
                  img(src='@/assets/curso/tema1/img51.svg' alt="Imagen decorativa")
                p.text-center.text-white.mb-0 Solución de limpieza adecuada.
            .col-lg.col-sm-4.col-8.mb-lg-0.mb-4(data-aos="flip-up")
              .BGS05.p-4.h-100
                .h1.t-l.text-end 03
                figure.mb-4
                  img(src='@/assets/curso/tema1/img52.svg' alt="Imagen decorativa")
                p.text-center.text-white.mb-0 Cotonetes.
            .col-lg.col-sm-4.col-8.mb-lg-0.mb-4(data-aos="flip-left")
              .BGR01.p-4.h-100
                .h1.t-l.text-end 04
                figure.mb-4
                  img(src='@/assets/curso/tema1/img53.svg' alt="Imagen decorativa")
                p.text-center.text-white.mb-0 Hisopos de espuma.
            .col-lg.col-sm-4.col-8.mb-lg-0.mb-4(data-aos="fade-left")
              .BGS05.p-4.h-100
                .h1.t-l.text-end 05
                figure.mb-4
                  img(src='@/assets/curso/tema1/img54.svg' alt="Imagen decorativa")
                p.text-center.text-white.mb-0 Limpiador de DVD o CD-ROM.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo limpiar el ratón (#[em mouse]) 
    

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-md-6.order-lg-1.order-2.mb-lg-0.mb-4(data-aos="fade-right")
        LineaTiempoD.color-primario
          p.text-small(numero="1" titulo="Paso 1") Desconecte el cable del #[em mouse] de la parte posterior de la carcasa de la computadora.
          p.text-small(numero="2" titulo="Paso 2") Humedezca ligeramente un paño de limpieza con alcohol isopropílico y limpie la parte exterior del #[em mouse] y la alfombrilla de #[em mouse] de la computadora.
          p.text-small(numero="3" titulo="Paso 3") Retire la cubierta inferior del #[em mouse]. Para esto, dele la vuelta y observe las flechas direccionales que indican la dirección de rotación o cómo deslizarlo. Presione con los dedos en la dirección de las flechas y luego gire el #[em mouse] hacia arriba, dejando que la cubierta y la bola del #[em mouse] caigan en su mano.
          p.text-small(numero="4" titulo="Paso 4") Limpie la bola del #[em mouse] de la computadora con un paño sin pelusa humedecido con alcohol isopropílico. Ponlo a un lado.
      .col-lg-4.col-md-7.col-10.px-5.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="flip-up")
        img(src='@/assets/curso/tema1/img55.svg' alt="Imagen decorativa")
      .col-lg-4.col-md-6.order-3(data-aos="fade-left")
        LineaTiempoD.color-primario
          p.text-small(numero="5" titulo="Paso 5") Humedezca un hisopo con alcohol isopropílico y limpie entre, alrededor y encima de las teclas. Cambie los hisopos a medida que se ensucien. Es posible que necesite varios hisopos.
          p.text-small(numero="6" titulo="Paso 6") Vuelva a colocar la bola del #[em mouse] y la cubierta.
          p.text-small(numero="7" titulo="Paso 7") Limpie el cable del #[em mouse]. Humedezca ligeramente un paño de limpieza con una solución jabonosa suave y tire suavemente del cable a través del paño.
          p.text-small(numero="8" titulo="Paso 8") Vuelva a conectar el #[em mouse] a la computadora.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo limpiar su monitor
    
    .row.justify-content-center.mb-5
      .col-lg-5.col-10.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img56.svg' alt="Imagen decorativa")
      .col-lg-7(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta BG02")
          .row.justify-content-center(titulo="Paso 1")
            .col-lg-11
              p.mb-0 Desenchufe el cable de alimentación y el cable de la parte posterior del monitor y deje que se enfríe durante al menos 20 minutos.
          .row.justify-content-center(titulo="Paso 2")
            .col-lg-11
              p.mb-0 Aspire el exterior del monitor, en particular las ranuras de enfriamiento, los orificios o las ranuras en la superficie superior donde se puede haber acumulado polvo pesado u otros desechos. Sople aire comprimido en bocanadas cortas en ángulo con respecto a la superficie del monitor. El objetivo es eliminar el polvo y la suciedad sin dejar que nada caiga en los orificios de ventilación.
          .row.justify-content-center(titulo="Paso 3")
            .col-lg-11
              p.mb-0 Humedezca ligeramente un paño con una solución jabonosa suave y limpie las partes exteriores de plástico del monitor.
          .row.justify-content-center(titulo="Paso 4")
            .col-lg-11
              p.mb-0 Limpie los cables del monitor y el cable de alimentación mientras están desconectados. Humedezca ligeramente un paño con una solución jabonosa suave y pase suavemente los cables a través del paño.
          .row.justify-content-center(titulo="Paso 5")
            .col-lg-11
              p.mb-0 Consulte la documentación o llame al fabricante para averiguar si la pantalla de su monitor tiene revestimientos antideslumbrantes u otros revestimientos delicados. Si es así, pregunte al fabricante o las instrucciones de limpieza. Si no tiene estos revestimientos especiales, puede rociar un limpiador de ventanas en un paño sin pelusa y limpiarlo. No rocíe directamente sobre la pantalla. Los productos químicos pueden gotear dentro del monitor y dañarlo.
          .row.justify-content-center(titulo="Paso 6")
            .col-lg-11
              p.mb-0 Para entornos de fabricación polvorientos o sucios, use una cubierta antipolvo para computadora para proteger el monitor.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo limpiar el teclado de la computadora

    p.mb-5(data-aos="fade-right") La limpieza es importante para impedir que la acumulación de suciedad afecte a sus funciones. Limpie mensualmente o cuando sea necesario, teniendo en cuenta los siguientes pasos: 

    .tarjeta.BGIMG04.p-lg-5.p-4.mb-5(data-aos="zoom-in")
      PasosB.color-acento-botones
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 1
            p.mb-0 Retire el cable de la parte posterior de la carcasa de la computadora.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img57.jpg' alt="Imagen decorativa")
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 2
            p.mb-0 Use aire comprimido o aspiradora manual para sacar de un soplido el polvo y los residuos de las teclas, o puede utilizar un pincel.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img58.jpg' alt="Imagen decorativa")
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 3
            p.mb-0 Apunte entre las teclas y el aire comprimido para eliminar el polvo y los residuos restantes. 
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img59.jpg' alt="Imagen decorativa")
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 4
            p.mb-0 Use bocanadas cortas de aire aplicadas en un ángulo de aproximadamente 30 a 45 grados con respecto a la superficie del teclado. 
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img60.jpg' alt="Imagen decorativa")
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 5
            p.mb-0 Humedezca ligeramente un paño con una solución de jabón suave y limpie el exterior del teclado. No rocíe la solución de jabón directamente sobre el teclado.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img61.jpg' alt="Imagen decorativa")
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 6
            p.mb-0 Humedezca un hisopo con alcohol isopropílico y limpie entre, alrededor y encima de las teclas. Cambie los hisopos a medida que se ensucien. Es posible que necesite varios hisopos.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img62.jpg' alt="Imagen decorativa")
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 7
            p.mb-0 Limpie el cable del teclado. Humedezca ligeramente un paño de limpieza con una solución jabonosa suave y tire suavemente del cable a través del paño. Seque el cable con un paño seco.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img63.jpg' alt="Imagen decorativa")
        .row.justify-content-center.px-2
          .col-lg-6.order-lg-1.order-2
            .h4.t-p Paso 8
            p.mb-0 Para entornos de fabricación polvorientos o sucios, se recomienda una buena cubierta de teclado.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img64.jpg' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Carga y reemplazo de la batería
    
    p.mb-5(data-aos="fade-right") Esto se puede dividir en dos tipos que son:
    
    .row.justify-content-center.mb-5
      .col-lg-6.h-100.mb-lg-0.mb-4
        .tarjeta-avatar-b.mb-4(data-aos="fade-right")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img03.svg' alt='Imagen decorativa')
          .tarjeta.color-primario--borde
            .p-4
              p.mb-0 Carga y reemplazo de batería para computadora portátil.
      .col-lg-6.h-100.mb-lg-0.mb-4
        .tarjeta-avatar-b.mb-4(data-aos="fade-left")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/img04.svg' alt='Imagen decorativa')
          .tarjeta.color-acento-contenido--borde
            .p-4
              p.mb-0 Carga y reemplazo de batería para PC que usaba UPS.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS12.px-5.py-2
          .h3.mb-0 <i class="fas fa-check" style="padding-right: 5px"></i> Carga y reemplazo de la batería
    
    .BGIMG03.px-md-5.px-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
          img(src='@/assets/curso/tema1/img65.png' alt="Imagen decorativa")
        .col-lg-8(data-aos="fade-left")
          SlyderF.mb-5(columnas="col-lg-6")
            .tarjeta.color-secundario.p-4.h-100
              p.text-white.mb-0 Enchufe su computadora portátil en el enchufe y puede dejarla allí siempre que sea posible. 
            .tarjeta.color-secundario.p-4.h-100
              p.text-white.mb-0 Puede recargar la batería de su computadora portátil, ya sea que la batería esté completamente agotada o no.
            .tarjeta.color-secundario.p-4.h-100
              p.text-white.mb-0 No es necesario agotar por completo la batería de iones de litio de su computadora portátil cada vez que la usa. 
            .tarjeta.color-secundario.p-4.h-100
              p.text-white.mb-0 La batería de iones de litio tiene una opción de carga rápida. 
            .tarjeta.color-secundario.p-4.h-100
              p.text-white.mb-0 Esta opción está disponible en una pestaña personalizada dentro del cuadro de diálogo Opciones de energía o desde el #[em software] de batería especial que viene con su computadora portátil.
            .tarjeta.color-secundario.p-4.h-100
              p.text-white.mb-0 Por tanto, lo mejor será no sobrecargar la batería, cárguela cuando se esté agotando entre 20 % y 10 % y no la seque.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS12.px-5.py-2
          .h3.mb-0 <i class="fas fa-check" style="padding-right: 5px"></i> Para PC que están utilizando UPS
    
    .row.justify-content-center.mb-5
      .col-lg-7.order-lg-1.order-2
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") <i class="fas fa-check"></i>
          .col
            .p-4
              .h5.mb-0 La batería necesitaba estar completamente cargada antes de su uso al menos durante 4 a 6 horas.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") <i class="fas fa-check"></i>
          .col
            .p-4
              .h5.mb-0 Asegúrese de que el UPS se mantenga en contacto con su tierra eléctrica en todo momento. 
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") <i class="fas fa-check"></i>
          .col
            .p-4
              .h5.mb-0 No sobrecargue No permita que el UPS se apague solo porque puede dañar la batería.
      .col-lg-5.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img66.png' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Cómo limpiar una unidad de CD o DVD
    
    .bloque-texto-g.color-primario.w-40.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img67.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Compre un kit de limpieza láser para DVD.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | El kit se compone de un solo disco que está diseñado para girar en su unidad y eliminar todo el polvo de la lente.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Coloque el disco de limpieza de lentes láser de CD/DVD dentro de la bandeja de la unidad de DVD.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Cierre la bandeja y deje que el CD gire en la unidad.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | A medida que gira, limpiará la lente de la mayoría, si no toda, del polvo.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            |  Compre una lata de aire en aerosol.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Como precaución adicional, abra la bandeja del disco de su unidad y rocíe suavemente una lata de aire comprimido en ella.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            |  Esto eliminará cualquiera de los grandes pedazos de polvo que puedan estar al acecho dentro de la bandeja.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Mantenimiento del #[em software]
    
    p.mb-5(data-aos="fade-right") El mantenimiento de programas dentro del sistema informático como virus, eliminación de #[em spyware], #[em software] de copia de seguridad y eliminación del registro, limpieza. Cada PC debe instalarse con un antivirus, una copia de seguridad de la aplicación de eliminación de #[em spyware] y un limpiador de registro. Tenga en cuenta:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.col-10.px-5.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img68.png' alt="Imagen decorativa")
      .col-lg-7
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Siempre escanee su sistema una vez por semana.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            p.mb-0 El #[em hardware] también debe desfragmentarse al menos una vez al mes.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Elimine todos los archivos temporales y las #[em cookies] a intervalos regulares.
    
    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Tipos de mantenimiento de #[em software]

    p.mb-5(data-aos="fade-right") Los tipos de mantenimiento son cuatro (4), los cuales se explican a continuación:

    TabsB.color-primario.mb-5(data-aos="zoom-in")
      .py-4.py-md-5(titulo="Mantenimiento correctivo de <em>software</em>")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            ul.lista-ul--color.lista-ul--separador
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Implica el desarrollo y la implementación de una solución a los problemas que ocurren durante el uso de un programa de #[em software].
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Es la forma típica y clásica de mantenimiento (para #[em software] y cualquier otra cosa).
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Es necesario cuando algo sale mal en una pieza de #[em software], incluidas fallas y errores.
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                | Pueden tener un impacto generalizado en su funcionalidad en general y, por lo tanto, deben abordarse lo más rápido posible.
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Muchas veces, los proveedores de #[em software] pueden abordar problemas que requieren mantenimiento correctivo debido a los informes de errores que envían los usuarios.
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                | Si una empresa puede reconocer y solucionar los errores antes de que los usuarios los descubran, esta es una ventaja adicional que hará que su empresa parezca más respetable y confiable (a nadie le gusta un mensaje de error después de todo).
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img69.jpg' alt="Imagen decorativa")
      .py-4.py-md-5(titulo="Mantenimiento perfectivo de <em>software</em>")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            ul.lista-ul--color.lista-ul--separador
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Esta es una medida tomada por el programador de computadoras para actualizar la forma en que funcionan los programas de #[em software] o qué tan rápido procesa, solicita, desarrolla diseños de menú e interfaz de comando para garantizar que el programa tenga cero tolerancias a las fallas.
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Al igual que con cualquier producto en el mercado, una vez que el #[em software] se lanza al público, surgen nuevos problemas e ideas. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Los usuarios pueden ver la necesidad de nuevas funciones o requisitos que les gustaría ver en el #[em software] para que sea la mejor herramienta disponible para sus necesidades. Aquí es cuando entra en juego el mantenimiento perfecto del #[em software].
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 El mantenimiento perfecto de #[em software] tiene como objetivo ajustarlo agregando nuevas características según sea necesario y eliminando características que son irrelevantes o no efectivas en el #[em software] dado. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Este proceso mantiene la relevancia del #[em software] a medida que cambian el mercado y las necesidades de los usuarios.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img70.jpg' alt="Imagen decorativa")
      .py-4.py-md-5(titulo="Mantenimiento adaptativo de <em>software</em>")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2
            ul.lista-ul--color.lista-ul--separador
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Se encarga de los cambios que se producen en el desarrollo de #[em software]. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Si hay un cambio en la velocidad de los procesadores, el cambio afectará invariablemente el rendimiento del #[em software] en una sola interfaz de computadora con otros programas. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                | Los cambios en un programa requieren cambios en otros programas.
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 El mantenimiento de #[em software] adaptativo tiene que ver con las tecnologías cambiantes, así como con las políticas y reglas relacionadas. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Estos incluyen cambios en el sistema operativo, almacenamiento en la nube, #[em hardware], etc. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Cuando se realizan estos cambios, su #[em software] debe adaptarse para cumplir adecuadamente con los nuevos requisitos y continuar funcionando bien.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img71.jpg' alt="Imagen decorativa")
      .py-4.py-md-5(titulo="Mantenimiento preventivo de <em>software</em>")
        .row.justify-content-center
          .col-lg-8.order-lg-1.order-2 
            ul.lista-ul--color.lista-ul--separador
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Esta es una situación en la que los programadores de computadoras intentan prevenir problemas con los programas de #[em software] antes de que ocurran. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                | Buscan prevenir el mantenimiento correctivo y anticipar las necesidades de mantenimiento adaptativo antes de que los usuarios encuentren problemas. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Esto se hace mediante la ejecución de pruebas de sus programas para garantizar que el #[em software] pueda manejar grandes cargas de datos y otras operaciones estresantes sin dificultades. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 Los programadores informáticos también garantizan la compatibilidad probando el #[em software] con otros usuarios de programas que probablemente lo utilicen.
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 El mantenimiento preventivo de #[em software] mira hacia el futuro para que su #[em software] pueda seguir funcionando como se desea durante el mayor tiempo posible. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                | Esto incluye hacer los cambios necesarios, actualizaciones, adaptaciones y más. 
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                p.mb-0 El mantenimiento preventivo del #[em software] puede abordar pequeños problemas que en un momento dado pueden carecer de importancia pero que pueden convertirse en problemas mayores en el futuro.
              li(style="margin-bottom: 2px" data-aos="fade-left")
                i.fas.fa-check-circle.t-p
                | Estos se denominan fallas latentes que deben detectarse y corregirse para asegurarse de que no se conviertan en fallas efectivas.
          .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img72.jpg' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Las actividades de mantenimiento preventivo incluyen las siguientes
    
    .row.justify-content-between.mb-4
      .col-lg-6.order-lg-1.order-2
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 01
          .col
            .p-4
              .h5.mb-0 Instalación de #[em software] de protección antivirus y actualización.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 02
          .col
            .p-4
              .h5.mb-0 Instale los cortafuegos en su computadora.
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 03
          .col
            .p-4
              .h5.mb-0 Mantener actualizado el registro de la computadora.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 04
          .col
            .p-4
              .h5.mb-0 Asegúrate de que tu sistema operativo esté actualizado
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 05
          .col
            .p-4
              .h5.mb-0 Eliminar las #[em cookies].
      .col-lg-5.col-10.px-5.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img73.svg' alt="Imagen decorativa")

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Beneficios del mantenimiento del #[em software]
    
    .bloque-texto-g.color-primario.w-40.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img74.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Promueve una computadora completamente funcional y altamente confiable.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Si las operaciones de mantenimiento preventivo se realizan regularmente, una PC nunca funcionará lentamente o tendrá programas que cambien o bloqueen la computadora.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Cuando se usan programas como limpiadores CC o limpiadores de disco para limpiar su disco duro, y también ejecute el disco CD #[em Defraggler]. El proceso de desfragmentación empaqueta los archivos que se encuentran dispersos en el disco duro en un clúster configurado (desfragmentador de disco), lo que permite que el sistema de archivos los localice fácilmente.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Cuando una PC está protegida y mantenida por programas de limpieza S/W, la unidad de disco duro no será lenta y apenas se producirá fragmentación.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Limpieza de registros.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Se reducen los problemas por falta de mantenimiento.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Mantenimiento de ordenador de rutina
    
    p.mb-5(data-aos="fade-right") El mantenimiento de rutina de la computadora consiste en tareas realizadas en la computadora diaria, semanal o mensualmente para mantener la computadora funcionando de manera eficiente durante mucho tiempo; estas son:

    .BGIMG08.px-md-5.px-4.py-4.mb-5(data-aos="zoom-in")
      .row.justify-content-center
        .col-lg-8
          img(src='@/assets/curso/tema1/img75.svg' alt="Imagen decorativa")

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .row.mb-5
          .col-auto(data-aos="fade-right")
            .BGS01.px-5.py-2
              .h3.mb-0 Seguridad de internet
        ul.lista-ul--color.lista-ul--separador.mb-5
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Siempre ejecute un programa antivirus completamente actualizado cuando use Internet y también realice un análisis completo del sistema con su programa antivirus. 
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Es ideal ejecutar un #[em firewall] para bloquear amenazas potenciales.
        .row.mb-5
          .col-auto(data-aos="fade-right")
            .BGS01.px-5.py-2
              .h3.mb-0 Parches y actualizaciones
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Las empresas de #[em software] los lanzan regularmente para abordar los problemas de seguridad que se encuentran en los programas. 
          li(style="margin-bottom: 2px" data-aos="fade-right")
            i.fas.fa-check-circle.t-ac
            | Los administradores de sistemas y los técnicos de redes deben descargar y aplicar periódicamente estas actualizaciones para asegurarse de que sus computadoras y sus redes estén protegidas contra piratas informáticos, virus e intrusiones en la red.
      .col-lg-4.col-8.d-lg-flex.d-none(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img76.svg' alt="Imagen decorativa")

    p.mb-5(data-aos="fade-right") A continuación, se detallan las recomendaciones de mantenimiento del equipo informático:

    .bloque-texto-g.color-acento-contenido.w-40.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img77.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        ul.lista-ul--color.lista-ul--separador
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Nunca apague su computadora con el interruptor de encendido hasta que la ventana se haya cerrado.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Consiga una UPS (fuente de alimentación ininterrumpida) para su computadora.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Realice una copia de seguridad de sus datos en discos duros externos, DVD/CD Rom, USB/unidades, tarjeta de memoria, etc.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Ejecute escanear disco y desfragmentar al menos una vez al mes.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Nunca desconecte el periférico de la computadora cuando esté encendida.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Asegúrese de tener 300 Mbps o 500-600 Mbps de espacio libre en su unidad C para Windows XP, Vista o Windows 7.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | No permita que se carguen muchos programas cuando inicie su computadora.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Utilice el comprobador de antivirus con regularidad.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Use un programa de #[em firewall] para una conexión a Internet de alta velocidad.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            p.mb-0 Lleve un registro del disco de #[em software] que recibe con su computadora y el nuevo periférico.
          li(style="margin-bottom: 2px" data-aos="fade-left")
            i.fas.fa-check-circle.t-ac
            | Asegúrese de que la actualización de la ventana esté configurada.

    p.mb-5(data-aos="fade-right") El proceso de mantenimiento de #[em software] involucra varias técnicas de mantenimiento de #[em software] que pueden cambiar según el tipo de mantenimiento y el plan de mantenimiento de #[em software] implementado. La mayoría de los modelos de procesos de mantenimiento de #[em software] incluyen los siguientes pasos:

    .BGM09.px-md-5.px-4.py-4.mb-5
      .row.justify-content-center
        .col-lg-10
          ImagenInfografica.color-secundario(data-aos="zoom-in")
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/tema1/img78.svg')
            .tarjeta.BG13.p-3(x="16.7%" y="22.7%" numero="+")
              .h5.text-white.mb-2 Identificación y seguimiento
              p.text-white.mb-0 El proceso de determinar qué parte del #[em software] debe modificarse (o mantenerse). Esto puede ser generado por el usuario o identificado por el propio desarrollador de #[em software] según la situación y la falla específica.
            .tarjeta.BG13.p-3(x="7.8%" y="59%" numero="+")
              .h5.text-white.mb-2 Análisis
              p.text-white.mb-0 El proceso de analizar la modificación sugerida, incluida la comprensión de los efectos potenciales de dicho cambio; generalmente incluye un análisis de costos para comprender si el cambio vale la pena desde el punto de vista financiero y pruebas del #[em software] y el sistema.
            .tarjeta.BG13.p-3(x="15.5%" y="96%" numero="+")
              .h5.text-white.mb-2 Diseño
              p.text-white.mb-0 Diseñar los nuevos cambios utilizando especificaciones de requisitos.
            .tarjeta.BG13.p-3(x="84.2%" y="22.7%" numero="+")
              .h5.text-white.mb-2 Implementación
              p.text-white.mb-0 El proceso de implementación de los nuevos módulos por parte de los programadores.
            .tarjeta.BG13.p-3(x="92.7%" y="59%" numero="+")
              .h5.text-white.mb-2 Pruebas de aceptación
              p.text-white.mb-0 Los usuarios prueban la modificación para su aceptación. Este es un paso importante ya que los usuarios pueden identificar problemas en curso y generar recomendaciones para una implementación y cambios más efectivo.
            .tarjeta.BG13.p-3(x="85.2%" y="96%" numero="+")
              .h5.text-white.mb-2 Entrega
              p.text-white.mb-0 Actualizaciones de #[em software] o, en algunos casos, nueva instalación del #[em software]. Aquí es cuando los cambios llegan a los clientes.
          
    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Costo de mantenimiento de #[em software]
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7.order-lg-1.order-2
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 01
          .col
            .p-4
              .h5.mb-0 El costo del mantenimiento del #[em software] puede ser alto.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 02
          .col
            .p-4
              .h5.mb-0 Sin embargo, esto no niega la importancia del mantenimiento del #[em software].
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 03
          .col
            .p-4
              .h5.mb-0 En ciertos casos, el mantenimiento del #[em software] puede costar hasta dos tercios del ciclo completo del proceso de #[em software] o más del 50 % de los procesos SDLC.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 04
          .col
            .p-4
              .h5.mb-0 Los costos involucrados en el mantenimiento del #[em software] se deben a múltiples factores y varían según la situación específica. Cuanto más antiguo sea el #[em software], más costará el mantenimiento, ya que las tecnologías (y los lenguajes de codificación) cambian con el tiempo.
        .BGA04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG05.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 05
          .col
            .p-4
              .h5.mb-0 Renovar una pieza de #[em software] antigua para adaptarse a la tecnología actual puede ser un proceso excepcionalmente costoso en ciertas situaciones.
        .BGB04.row.mb-2(data-aos="fade-right")
          .col-lg-2.col-3.BG01.p-4
            p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 06
          .col
            .p-4
              .h5.mb-0 Además, es posible que los ingenieros no siempre puedan abordar los problemas exactos cuando buscan actualizar o mantener una pieza específica de #[em software].
      .col-lg-5.col-10.px-5.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img79.svg' alt="Imagen decorativa")
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.col-10.px-5.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img80.svg' alt="Imagen decorativa")
      .col-lg-7(data-aos="fade-left")
            .BGA04.row.mb-2(data-aos="fade-right")
              .col-lg-2.col-3.BG05.p-4
                p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 07
              .col
                .p-4
                  .h5.mb-0 Esto hace que utilicen un método de prueba y error, que puede resultar en muchas horas de trabajo.
            .BGB04.row.mb-2(data-aos="fade-right")
              .col-lg-2.col-3.BG01.p-4
                p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 08
              .col
                .p-4
                  .h5.mb-0 Existen ciertas formas de intentar reducir los costos de mantenimiento del #[em software].
            .BGA04.row.mb-2(data-aos="fade-right")
              .col-lg-2.col-3.BG05.p-4
                p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 09
              .col
                .p-4
                  .h5.mb-0 Estos incluyen la optimización de la parte superior de la programación utilizada en el #[em software], la tipificación fuerte y la programación funcional.
            .BGB04.row.mb-2(data-aos="fade-right")
              .col-lg-2.col-3.BG01.p-4
                p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 10
              .col
                .p-4
                  .h5.mb-0 Al crear un nuevo #[em software], así como al asumir proyectos de mantenimiento para modelos más antiguos, las empresas de #[em software] deben tener en cuenta los costos de mantenimiento de este.
            .BGA04.row.mb-2(data-aos="fade-right")
              .col-lg-2.col-3.BG05.p-4
                p.text-center.mb-0(style="font-weight: 900; font-size: 30px !important") 11
              .col
                .p-4
                  .h5.mb-0 Sin mantenimiento, cualquier #[em software] quedará obsoleto y esencialmente inútil con el tiempo.

    .row.mb-5
      .col-auto(data-aos="fade-right")
        .BGS01.px-5.py-2
          .h3.mb-0 Estrategias de mantenimiento de #[em software]

    p.mb-5(data-aos="fade-right") Recuerde que:

    .row.align-items-center.mb-5
      .col-xl-1.d-xl-flex.d-none
      .col-xl-8.col-lg-10.order-lg-1.order-2
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BGR06.w-100.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 Todas las empresas de #[em software] deben tener una estrategia específica para abordar el mantenimiento del #[em software] de manera efectiva y completa.
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img06.svg' alt='Imagen decorativa')
          .BG07.w-100.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 La documentación es una estrategia importante en el desarrollo de #[em software].
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BG06.w-100.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 La documentación debe incluir información sobre cómo funciona el código, soluciones a problemas potenciales, etc.
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img06.svg' alt='Imagen decorativa')
          .BG07.w-100.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 El control de calidad también es una parte importante de un plan de mantenimiento de #[em software].
            .col-lg-1.d-lg-flex.d-none
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="left: 5%")
            img(src='@/assets/curso/temas/img02.svg' alt='Imagen decorativa')
          .BG06.w-100.p-4.row.justify-content-center
            .col-lg-10.col-11
              .h4.mb-0 Si bien el control de calidad es importante antes del lanzamiento inicial de un #[em software], también se puede integrar mucho antes en el proceso (ya en la etapa de planificación) para garantizar que este se desarrolle correctamente y brindar información sobre cómo realizar cambios cuando sea necesario.
            .col-lg-1.d-lg-flex.d-none
      .col-sm-3.col-2.d-lg-none.d-flex
      .col-lg-4.col-sm-6.col-8.img-01.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img81.svg' alt="Imagen decorativa")


</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    datosSlyder: [
      {
        titulo: '<span style="color: #5573C6">Paso 1</span>',
        texto:
          'Siempre apague el sistema antes de realizar cualquier mantenimiento de la computadora.',
        imagen: require('@/assets/curso/tema1/img41.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 2</span>',
        texto:
          'Nunca rocíe líquidos sobre ningún componente de la computadora. Rocíe o vierta el líquido en un paño sin pelusa y limpie la PC con el paño. Evite los productos con cierta celulosa que dejarán rayas en su equipo de cómputo. ',
        imagen: require('@/assets/curso/tema1/img42.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 3</span>',
        texto:
          'Use una aspiradora portátil a batería o pruebe con aire comprimido para eliminar la suciedad, el polvo, los alimentos y el cabello de los teclados. Se recomienda usar una muñequera antiestática para reducir la transferencia de electricidad estática del cuerpo a la computadora.',
        imagen: require('@/assets/curso/tema1/img43.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 4</span>',
        texto:
          'No aplique una solución de limpieza que incluya agua directamente a los componentes de la computadora.',
        imagen: require('@/assets/curso/tema1/img44.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 5</span>',
        texto:
          'No use su aliento para soplar el polvo de los componentes porque su aliento contiene humedad y los componentes no están fabricados para ser resistentes a la oxidación.',
        imagen: require('@/assets/curso/tema1/img45.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 6</span>',
        texto:
          'A veces, es necesario reemplazar los ventiladores o limpiar físicamente algunos componentes de la computadora.',
        imagen: require('@/assets/curso/tema1/img46.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 7</span>',
        texto:
          'No use nada mojado o húmedo dentro de la carcasa de la computadora.',
        imagen: require('@/assets/curso/tema1/img47.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 8</span>',
        texto:
          'No permita que ningún componente o placa de circuito dentro de la carcasa de la computadora se moje o humedezca.',
        imagen: require('@/assets/curso/tema1/img48.jpg'),
      },
      {
        titulo: '<span style="color: #5573C6">Paso 9</span>',
        texto:
          'No intente limpiar la placa base con un paño, ya que puede dañar los componentes eléctricos. Utilice un paño ligeramente húmedo para limpiar el polvo y la suciedad del interior de la carcasa de la computadora.<br><br>No permita ninguna bebida alrededor de la maquinaria.<br><br>Evite vibraciones y golpes.',
        imagen: require('@/assets/curso/tema1/img49.jpg'),
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
