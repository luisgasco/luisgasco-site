---
title: Cómo utilizar Twitter contra el ruido

# Link this post with a project
projects: []

# Date published
date: '2019-04-03T00:00:00Z'

# Date updated

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: '[Dragana Gordic/Shutterstock](https://www.shutterstock.com/es/image-photo/hand-smart-phone-dark-female-using-780954466)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - NLP

categories:
  - dissemination

---

<span><a href="https://theconversation.com/profiles/luis-gasco-707423">Luis Gascó</a>, <em><a href="https://theconversation.com/institutions/universidad-politecnica-de-madrid-upm-1649">Universidad Politécnica de Madrid (UPM)</a></em></span>

<p>La Organización Mundial de la Salud identifica la contaminación acústica como la segunda causa medioambiental que más afecta a la salud de las personas tras la polución del aire. En Europa, se estima que <a href="http://www.euro.who.int/__data/assets/pdf_file/0008/136466/e94888.pdf">el 25% de los ciudadanos están expuestos a niveles de ruido excesivos</a>. Esto supone un incremento de riesgos para la salud y pérdidas de calidad de vida en la ciudadanía, principalmente como consecuencia del estrés y la falta de descanso.</p>

<p>Con intención de reducir la contaminación sonora, se realizan cada cinco años mapas estratégicos de ruido a nivel europeo que permiten conocer tanto los niveles de ruido producidos por el transporte en entornos urbanos, como los puntos negros acústicos presentes en ciudades. Además, algunos gestores urbanos deciden instalar monitores de ruido que complementan la información proporcionada por los mapas, por registrar otros orígenes de ruido como el asociado a las <a href="https://www.mdpi.com/2076-3298/5/12/134">actividades de ocio</a>.</p>

<p>Junto al fenómeno físico y objetivo del ruido, la contaminación acústica tiene un <a href="https://link.springer.com/article/10.1007/s40726-017-0060-x">claro componente subjetivo en su percepción</a>. Como consecuencia, el ciudadano busca soluciones y se queja para compartir su malestar con la situación. Para ello, las administraciones públicas han abierto canales que facilitan la comunicación entre los ciudadanos y los órganos gestores en esta temática. Sin embargo, gran parte de la población decide no utilizar estos canales de comunicación porque, o bien no los conoce, o no se siente cómoda con ellos, optando por compartir sus quejas en plataformas no diseñadas de forma expresa para este uso, como las redes sociales. </p>

<p>Desde la llegada de la era de la información, se ha generalizado la utilización de estas plataformas. Actualmente, cuentan con más de <a href="https://www.brandwatch.com/blog/amazing-social-media-statistics-and-facts">3.000 millones de usuarios diarios</a> que producen un gran volumen de datos potencialmente útiles para diversas materias. Algunos ejemplos de esos usos son los estudios de mercado sobre <a href="https://www.netbase.com/wp-content/uploads/Casestudy_Arby_03_2018.pdf">la valoración pública de productos</a> o la medida del sentimiento político. </p>

<p>Recientemente, investigadores de la Universidad Politécnica de Madrid hemos demostrado en un <a href="https://doi.org/10.1016/j.scitotenv.2018.12.071">estudio pionero</a> que se puede extraer de esos datos información sobre la percepción ciudadana hacia actividades ruidosas en ciudades. Un hecho que abre una nuevas posibilidades de actuación para la gestión de este contaminante en ciudades e infraestructuras del transporte.</p>

<h2>Cómo seguir la pista al ruido en Twitter</h2>

<p>El método está basado en la aplicación de un algoritmo de análisis de texto que, por una parte, permiten detectar automáticamente quejas sobre contaminación sonora y, por otra, clasificarlas según el origen de estas. </p>

<p>En primer lugar, el sistema extrae textos cortos compartidos en Twitter. A continuación, basándose en la presencia de términos relacionados con el ruido, el uso de emoticonos y las categorías gramaticales de las palabras del texto, un algoritmo de <em>machine learning</em> detecta las quejas relacionadas con el ruido compartidas por los usuarios. </p>

<p>Por último, utilizando un diccionario de términos asociados a fuentes de ruido específicas, se clasifican las quejas detectadas en distintas categorías según su origen (música, naturaleza, interior, transporte, humano y mecánico).</p>

<figure class="align-center ">
            <img alt="" src="https://images.theconversation.com/files/265562/original/file-20190325-36256-1n2clt1.jpg?ixlib=rb-1.1.0&amp;q=45&amp;auto=format&amp;w=754&amp;fit=clip" srcset="https://images.theconversation.com/files/265562/original/file-20190325-36256-1n2clt1.jpg?ixlib=rb-1.1.0&amp;q=45&amp;auto=format&amp;w=600&amp;h=294&amp;fit=crop&amp;dpr=1 600w, https://images.theconversation.com/files/265562/original/file-20190325-36256-1n2clt1.jpg?ixlib=rb-1.1.0&amp;q=30&amp;auto=format&amp;w=600&amp;h=294&amp;fit=crop&amp;dpr=2 1200w, https://images.theconversation.com/files/265562/original/file-20190325-36256-1n2clt1.jpg?ixlib=rb-1.1.0&amp;q=15&amp;auto=format&amp;w=600&amp;h=294&amp;fit=crop&amp;dpr=3 1800w, https://images.theconversation.com/files/265562/original/file-20190325-36256-1n2clt1.jpg?ixlib=rb-1.1.0&amp;q=45&amp;auto=format&amp;w=754&amp;h=369&amp;fit=crop&amp;dpr=1 754w, https://images.theconversation.com/files/265562/original/file-20190325-36256-1n2clt1.jpg?ixlib=rb-1.1.0&amp;q=30&amp;auto=format&amp;w=754&amp;h=369&amp;fit=crop&amp;dpr=2 1508w, https://images.theconversation.com/files/265562/original/file-20190325-36256-1n2clt1.jpg?ixlib=rb-1.1.0&amp;q=15&amp;auto=format&amp;w=754&amp;h=369&amp;fit=crop&amp;dpr=3 2262w" sizes="(min-width: 1466px) 754px, (max-width: 599px) 100vw, (min-width: 600px) 600px, 237px">
            <figcaption>
              <span class="caption">Esquema del proceso de identificación y clasificación de los tuits.</span>
              <span class="attribution"><span class="source">Luis Gascó</span>, <span class="license">Author provided</span></span>
            </figcaption>
          </figure>

<p>El algoritmo detecta automáticamente la presencia de eventos acústicos molestos para la ciudadanía de forma automática, e identifica la fuente sonora que genera la molestia. Además, es capaz de anticipar la aparición de sucesos molestos, algo esencial para diseñar acciones de intervención tempranas que permitan prevenir situaciones irritantes para la población.</p>

<h2>Nuevos paradigmas en la gestión urbana</h2>

<p>Dado que la ciudadanía comunica su malestar sobre muchos problemas en las redes sociales, las aplicaciones de la metodología desarrollada no se limitan al campo de la contaminación acústica. </p>

<p>El sistema puede utilizarse para la detección de otro tipo de problemas en una ciudad: desde desperfectos en el mobiliario urbano hasta la opinión de la ciudadanía sobre cambios en el planeamiento urbanístico de una localidad. Por ejemplo, se podría conocer de forma rápida la opinión de la ciudadanía sobre la semipeatonalización de la Gran Vía en Madrid, algo que permitiría a los gestores crear ordenanzas municipales más participativas.</p>

<figure class="align-center zoomable">
            <a href="https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=45&amp;auto=format&amp;w=1000&amp;fit=clip"><img alt="" src="https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=45&amp;auto=format&amp;w=754&amp;fit=clip" srcset="https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=45&amp;auto=format&amp;w=600&amp;h=363&amp;fit=crop&amp;dpr=1 600w, https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=30&amp;auto=format&amp;w=600&amp;h=363&amp;fit=crop&amp;dpr=2 1200w, https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=15&amp;auto=format&amp;w=600&amp;h=363&amp;fit=crop&amp;dpr=3 1800w, https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=45&amp;auto=format&amp;w=754&amp;h=456&amp;fit=crop&amp;dpr=1 754w, https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=30&amp;auto=format&amp;w=754&amp;h=456&amp;fit=crop&amp;dpr=2 1508w, https://images.theconversation.com/files/265559/original/file-20190325-36283-1idfc8b.png?ixlib=rb-1.1.0&amp;q=15&amp;auto=format&amp;w=754&amp;h=456&amp;fit=crop&amp;dpr=3 2262w" sizes="(min-width: 1466px) 754px, (max-width: 599px) 100vw, (min-width: 600px) 600px, 237px"></a>
            <figcaption>
              <span class="caption">El sistema sirve para detectar los motivos de las quejas, aplicar medidas y medir el efecto de estas.</span>
              <span class="attribution"><span class="source">Luis Gascó</span>, <span class="license">Author provided</span></span>
            </figcaption>
          </figure>

<p>Además, dadas las funcionalidades predictivas del sistema desarrollado, se podría utilizar para identificar problemas en situaciones en las que una rápida gestión es esencial, como en eventos multitudinarios. Por ejemplo, se podría detectar la saturación de los puestos sanitarios, el incumplimiento de los horarios marcados por los gestores urbanos o problemas de accesibilidad y limpieza a través de las quejas de los asistentes en las redes sociales. De este modo, se podrían implementar sistemas de gestión inteligentes en los que se redimensionaran estos servicios en función de las necesidades requeridas en cada momento.</p>

<p>Actualmente, los responsables del proyecto estamos buscando socios para realizar una prueba piloto en España —junto a sus colaboradores franceses de <a href="https://www.telecom-paristech.fr/">Télécom ParisTech</a>—. Principalmente, empresas de gestión de ciudades e infraestructuras de transporte, para realizar un proyecto de transferencia tecnológica a nivel europeo en el que se pueda testar su tecnología en un entorno real.<!-- Below is The Conversation's page counter tag. Please DO NOT REMOVE. --><img src="https://counter.theconversation.com/content/113886/count.gif?distributor=republish-lightbox-basic" alt="The Conversation" width="1" height="1" style="border: none !important; box-shadow: none !important; margin: 0 !important; max-height: 1px !important; max-width: 1px !important; min-height: 1px !important; min-width: 1px !important; opacity: 0 !important; outline: none !important; padding: 0 !important" referrerpolicy="no-referrer-when-downgrade" /><!-- Fin del código. Si no ve ningún código arriba, por favor, obtenga el nuevo código de la pestaña Avanzado después de hacer clic en el botón de republicar. El contador de páginas no recoge ningún dato personal. Más información: http://theconversation.com/es/republishing-guidelines --></p>


<p>Este artículo fue publicado originalmente en  <a href="https://theconversation.com">The Conversation</a>. Lea el <a href="https://theconversation.com/como-utilizar-twitter-contra-el-ruido-113886">original</a>.</p>




<img src="https://counter.theconversation.com/content/113886/count.gif?distributor=republish-lightbox-advanced" alt="The Conversation" width="1" height="1" style="border: none !important; box-shadow: none !important; margin: 0 !important; max-height: 1px !important; max-width: 1px !important; min-height: 1px !important; min-width: 1px !important; opacity: 0 !important; outline: none !important; padding: 0 !important" referrerpolicy="no-referrer-when-downgrade" />
