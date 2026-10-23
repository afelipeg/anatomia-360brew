# Anatomía de 360Brew

Página: https://afelipeg.github.io/anatomia-360brew/

Arquitectura de **Mixtral-8x22B**, el modelo abierto sobre el que LinkedIn construyó su ranker de investigación 360Brew. La página la verificó REA (ingeniería inversa) leyendo solo las cabeceras de los 59 archivos safetensors.

- `index.html`: página interactiva con proporciones a escala, recorrido por capas y expertos, cómo puntúa un post, manifiesto de 1.739 tensores y otros casos de uso.
- `anatomia-360brew-carrusel.pdf`: carrusel de 9 láminas (1080×1350) para LinkedIn.

## Procedencia y límites

- Fuente: `mistralai/Mixtral-8x22B-v0.1` (Apache 2.0). REA `inspect_model_artifact` en modo cabecera; contenido de los pesos no interpretado.
- Contexto: paper de 360Brew (LinkedIn, arXiv 2501.16450, retirado) y blog de ingeniería de LinkedIn de 2026.
- Los pesos de 360Brew no son públicos. LinkedIn no confirma que 360Brew ordene el feed en producción.
- Los puntajes y la elección de expertos de la página son ilustrativos y están marcados así.
