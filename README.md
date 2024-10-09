# Documento base para Diseño de Software I, II y III

## Proyectos Disponibles

Este repositorio contiene una lista de proyectos disponibles para que los estudiantes trabajen en ellos. Cada proyecto está organizado en su propia carpeta dentro de este repositorio.

### Lista de Proyectos

#### Proyecto 1: CREAVI

La arquitectura CREAVI está conformada por tres capas, el cliente o frontend, el servidor o backend y la capa de conexión a apis externas como H5P Lumi, Moodle o apis de inteligencia artificial.

Cliente: Esta capa es la gestionada por el usuario y contiene los elementos HTML5, también es creada dinámicamente dependiendo de las necesidades del proyecto o metodología desplegada. Se presentan usuarios como administrador, encargado de gestionar el sitio; docente investigador, encargado de crear las metodologías, usuario tutor, encargado de gestionar los proyectos y usuario estudiante, quien consume las lecciones y contenidos de los proyectos.

Servidor: El servidor se encarga de procesar todas las necesidades del cliente a través de las rutas dinámicas. Tiene un módulo de usuario que gestiona los permisos y los contenidos que se le entregan al cliente, un módulo administrador encargado de gestionar los demás módulos, módulo de bases de datos para mantener la persistencia de los datos del sistema, módulo json-csv encargado de mantener las plantillas de estructuras de los componentes pre establecidos y nuevos componentes, así como también guardar las versiones de los mismos y sus respectivos creadores, módulo de componentes diseñado para gestionar el modulo de control de versiones en función a los componentes creados o editados, módulo de archivos quien administra los archivos binarios subidos a la plataforma y que también se pueden almacenar en Google drive y por último, el módulo de conexión a APIs externas, el cual permite extraer información de otras aplicaciones a través de sus APIs.

- **Repositorio:** [https://github.com/orgs/GIB-dds-creavi/repositories](https://github.com/orgs/GIB-dds-creavi/repositories) 
- **Contacto:** Alexander Toscano Ricardo [atoscano@correo.unicordoba.edu.co]
- **Componentes:** [https://github.com/area-de-informatica/.github/tree/main/creavi-components](https://github.com/area-de-informatica/.github/tree/main/creavi-components)
