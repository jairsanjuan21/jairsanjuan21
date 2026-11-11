<a href="https://github.com/jairsanjuan21">
  <img src="./assets/hero.svg" width="100%" alt="Jair Sanjuan, estudiante de Ingeniería de Sistemas en la UDES. Tres sistemas: Notificaciones ANM en producción, Catálogo Fersautos en desarrollo y SG-SST en diseño." />
</a>

<p align="center">
  <img src="https://img.shields.io/badge/UDES-Ingeniería_de_Sistemas-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/Cúcuta-Colombia-141B34?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=jairsanjuan21&style=flat-square&color=141B34&label=visitas" />
</p>

Me gusta el software que alguien abre todos los días para hacer su trabajo.
Cada proyecto de este perfil empezó con una persona y un problema concreto,
no con una tecnología. Abajo está cada uno descompuesto como lo pienso:
**qué entra, qué se procesa y qué sale**.

## Sistemas

<a href="https://github.com/jairsanjuan21/NotificacionesANM">
  <img src="./assets/anm.svg" width="100%" alt="Notificaciones ANM, en producción. Vigila el portal de la Agencia Nacional de Minería y avisa antes de que venza un plazo." />
</a>

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `APScheduler` `PyMuPDF` `React` `Vite` `Telegram Bot API` `Railway`

<details>
<summary>Lo que resolví en este sistema</summary>

- Los plazos se calculan en **días hábiles con festivos de Colombia**, y "1 mes" como mes de corrido.
- Guarda copia de cada PDF por si la ANM lo retira del portal.
- Se vigila a sí mismo: alerta si un barrido falla o si el portal cambia su estructura.
- Dos bots de Telegram: uno para el usuario final y otro de administración.

</details>

<a href="https://github.com/jairsanjuan21/CatalogoFersautosSuzuki">
  <img src="./assets/fersautos.svg" width="100%" alt="Catálogo Fersautos Suzuki, en desarrollo. Lleva al cliente desde una publicación en redes hasta una solicitud de crédito lista." />
</a>

`Next.js` `TypeScript` `Tailwind CSS` `PostgreSQL` `Drizzle ORM` `Better Auth` `pdf-lib` `Docker`

<details>
<summary>Lo que estoy resolviendo en este sistema</summary>

- Un enlace por red social registra de dónde llegó cada cliente y preselecciona el modelo.
- La firma y las fotos de la cédula se capturan desde el celular, dentro del formulario.
- El PDF sale diligenciado con el formato oficial del concesionario.
- Cuatro módulos: catálogo, formulario de crédito, panel de la asesora y panel de administración.

</details>

<img src="./assets/sgsst.svg" width="100%" alt="Sistema web SG-SST, en diseño. Reúne en una sola vista la documentación de seguridad y salud de varias empresas." />

`Levantamiento de requerimientos` `Ciclo PHVA` `Multiempresa` `Stack por definir`

<details>
<summary>Decisiones de diseño hasta ahora</summary>

- Un consultor ve el archivo de todas las empresas que asesora desde una sola página.
- Los formatos se diligencian, se editan y se reutilizan al crear una empresa nueva.
- Dos perfiles: quien modifica y quien solo consulta.
- La app móvil de inspecciones y la firma digital quedan para la última fase.

</details>

## Cómo pienso un problema

```mermaid
flowchart LR
    A([Una persona<br/>con un problema]) --> B[Descomponer]
    B --> C[Reconocer patrones]
    C --> D[Abstraer]
    D --> E[Diseñar el algoritmo]
    E --> F[Construir y desplegar]
    F --> G([La persona<br/>lo usa])
    G -. retroalimentación .-> B
```

La flecha punteada es la parte que más me importa: un sistema en producción
me enseña más que cualquier diagrama inicial.

## Herramientas

**Construyo con**

<img src="https://skillicons.dev/icons?i=py,fastapi,postgres,java,spring,react,ts,nextjs,tailwind,vite,docker,linux,git&perline=13" />

**Explorando para machine learning y deep learning**

<img src="https://skillicons.dev/icons?i=sklearn,pytorch,tensorflow&perline=3" />

## Lo que viene

- [ ] Un servidor propio (VPS) donde los tres sistemas corran de forma independiente
- [ ] Terminar el catálogo Fersautos en local y entregarlo
- [ ] Pasar el SG-SST de diseño a desarrollo
- [ ] Llevar machine learning a un problema real, como estos tres

## Actividad

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jairsanjuan21/jairsanjuan21/output/github-snake-dark.svg" />
  <img alt="Animación de mis contribuciones en GitHub" src="https://raw.githubusercontent.com/jairsanjuan21/jairsanjuan21/output/github-snake.svg" width="100%" />
</picture>

## Hablemos

<p>
  <a href="mailto:jairsanjuan21@hotmail.com"><img src="https://img.shields.io/badge/Correo-jairsanjuan21@hotmail.com-141B34?style=for-the-badge&logo=microsoftoutlook&logoColor=white" /></a>
  <!-- Cuando tengas tu usuario de LinkedIn, descomenta esta línea y reemplaza TU-USUARIO:
  <a href="https://www.linkedin.com/in/TU-USUARIO"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  -->
</p>

<sub>Primero entiendo el problema. Luego escribo el código.</sub>
