# Justificación del Proyecto SmartBudget

## Proceso de diseño

El proyecto comenzó a partir del diseño de un prototipo simple de la pantalla de login, tomando como referencia un mockup realizado en Figma. Este prototipo permitió definir la estructura visual, colores y jerarquía de los elementos antes de la implementación en código. A partir de este diseño, se construyó la estructura HTML inicial respetando una jerarquía semántica clara, identificando los componentes principales como navbar, formulario y footer.

## Metodología CSS

Para la organización de los estilos se utilice la metodología BEM, ya que permite mantener un código ordenado, legible y fácil de escalar. Esta metodología facilita identificar bloques, elementos y modificadores dentro del HTML y CSS, evitando conflictos entre clases.

## Uso de SASS

Se implementó el preprocesador SASS para mejorar la modularidad y reutilización del código. Los estilos fueron organizados siguiendo el patrón 7–1, separando responsabilidades en carpetas como abstracts, base, layout y components. Además, se utilizaron variables, mixins y anidamiento para optimizar el desarrollo.

## Modelo de cajas y layout

Se aplicó el modelo de cajas utilizando propiedades como margin, padding, border y box-sizing. El layout fue construido principalmente con Flexbox, permitiendo una correcta alineación y distribución de los elementos. Se implementaron media queries para asegurar un diseño responsive en dispositivos móviles y de escritorio.

## Uso de Bootstrap 4

Se integró Bootstrap 4 mediante CDN para agilizar el desarrollo y mantener consistencia visual. Se utilizaron componentes como navbar, cards, formularios y botones, junto con clases utilitarias para espaciado, alineación y tipografía. Bootstrap se utilizó como complemento sin perder la estructura y modularidad del código propio.

## Responsive y validación

El diseño fue probado utilizando las herramientas de inspección del navegador (DevTools), validando el modelo de cajas y el comportamiento responsive en distintos tamaños de pantalla.
