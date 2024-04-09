## Pagina analizada El portal web de la policía
### siendo un portal al que accederíamos en caso de emergencia, el performance así como las buenas prácticas de UX/UI deberían ser una prioridad.

##### Principales virtudes encontradas en la página

- Excelentes prácticas 
- Optimizada al 100% para accesibilidad 
    - atributos y roles encajan perfectamente
    - no hay ninguna propiedad [aria-hidden="true"] presente en el <body>
    - todos los [role] presentan la forma correcta del atributo [aria-*] 
    - imagenes con su respectivo [alt]
- Gran performance SEO (HTML Semántico, links, indexado, mobile friendly,)

##### Principales problemas encontrados en la página
- Una página con poco performance (imagenes con mala resolución)
- enlaces rotos [twitter]
- Imagen de fondo [background-img] muy pesadas que hace que el navegador demore mucho tiempo en renderizar 
- no usa el protocolo HTTP/2
- Mucho código JavaScript sin usar cargado en la página
- las imagenes no tienen un tamaño definido explicitamente por lo que genera problemas al cargar otros elementos

En conclusíon una página con mucho cuidado en áreas como acesibilidad uso de las Best Practices y buen posicionamiento SEO con contenido relevante y bien enlazado, pierde toda su funcionalidad 
por un cuidado pobre en el performance, codigo innecesario que se carga y ocupa espacio, imagenes nada optimizadas y muy mal uso de herramientas para una carga veloz. 

Es cierto que han mejorado la disposición de los elementos (UI) para ser mas amigable y appealing a nivel visual dejando de lado la optimización del uso de recursos y la experiencia (UX).
Entendiendo que todo el tema performance y UX fue asesinado hace unos años con la legislación de solicitud de uso de cookies, que rompe todo el flujo orgánico de una navegación satisfactoria. 

![captura de pantalla de los resultados de WaveReport](/Screenshot%202024-04-09%20at%2020.14.02.png)
![captura de pantalla de los resultados de LightHouse](/Screenshot%202024-04-09%20at%2020.14.36.png)

