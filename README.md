<img src="https://mmss.iimas.unam.mx/dmmss/wp-content/uploads/2026/02/cropped-LogoUNAM_IIMAS_Negro50-scaled-2.png" width="200"/>

### Datos Masivos II
# Exposición: Sistemas de recomendación basados en contenido
> Equipo Tres: Castrillo Cruz Karen Arlet, Ramos González Nadia, Zamora Antiga Ángel Javier.

---

El presente repositorio forma parte de una serie de exposiciones realizadas en el curso de Datos Masivos II, y reúne el material con el que el equipo explicó los sistemas de recomendación basados en contenido, con base en el capítulo 4 de *Recommender Systems: The Textbook* de Charu C. Aggarwal (Springer, 2016).

Incluye la presentación de la exposición y los enlaces a Vibe Rhythming, un sistema de recomendación de canciones que lleva a la práctica lo expuesto.

| Material | Descripción | Enlace |
|---|---|---|
| Presentación | Diapositivas de la exposición, en un solo archivo HTML | [Ver en línea](https://nad2710.github.io/SistemasRecomendacionContenido_DMII/Presentacion/sistemas_recomendacion_contenido.html) · [`Presentacion/`](Presentacion/) |
| Sistema de recomendación | Código de la aplicación Vibe Rhythming | [makore-0612/vibe-rhythming](https://github.com/makore-0612/vibe-rhythming) |
| Versión de la exposición | Código de la aplicación al momento de crear este repositorio | [commit `09479d9`](https://github.com/makore-0612/vibe-rhythming/tree/09479d9) |
| Deploy | Aplicación en vivo en Streamlit Community Cloud | [vibe-rhythming.streamlit.app](https://vibe-rhythming.streamlit.app/) |

[![Plataforma en vivo](https://raw.githubusercontent.com/makore-0612/vibe-rhythming/09479d9/assets/readmeport.png)](https://vibe-rhythming.streamlit.app/)

## Sistema de recomendación

Vibe Rhythming procesa recomendaciones en tiempo real a partir de los gustos del usuario, con cuatro clasificadores: vecinos más cercanos, Naive Bayes, reglas de asociación y regresión logística.

La estructura del código, cómo correr la aplicación y las licencias del dataset y la tipografía se detallan en el [README de su repositorio](https://github.com/makore-0612/vibe-rhythming#readme).

```text
SistemasRecomendacionContenido_DMII/
└── Presentacion/
    └── sistemas_recomendacion_contenido.html   # diapositivas de la exposición
```

> Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas, Universidad Nacional Autónoma de México. Noviembre, 2026
