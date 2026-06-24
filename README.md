# NextSet - Proyecto Final DAW (Curso 2025-2026)

Este repositorio contiene el proyecto intermodular que he presentado para cerrar el ciclo de Desarrollo de Aplicaciones Web en MEDAC (Davante), con el que saqué un **8/10**.

La idea detrás de **NextSet** se me ocurrió tras ver cómo muchos entrenadores personales y gimnasios locales siguen atascados gestionando la documentación y planes de entrenamiento caóticamente a sus clientes con Excels eternos, libretas o mandando PDFs pesados por WhatsApp. Diseñé esta plataforma (planteada como un modelo SaaS en la nube) para centralizar las rutinas, automatizar el control de marcas y simplificar las cuentas en un solo sitio que sea cómodo de usar en el día a día.

---

## ¿Cómo está hecho?, Stack técnico:

El desarrollo combina lo aprendido en los diferentes módulos del ciclo, buscando siempre que la interfaz sea ligera y cargue rápido con conexiones de datos móviles:

* **Frontend y maquetación:** HTML5, CSS3 nativo y JavaScript. El diseño está pensado con un enfoque **mobile-first** bastante estricto, ya que el cliente final va a registrar sus series y pesos directamente desde el móvil mientras entrena en la sala.
* **Estructura visual limpia:** Separé los estilos en archivos independientes (`styles.css`, `footer.css`, `cta.css`) para que el código sea mantenible. Usé variables globales (`:root`) para la paleta de colores corporativa (el naranja como identidad principal) y añadí algunas animaciones con `@keyframes` para dar fluidez y efectos de brillo al logotipo y botones.
* **Lógica y datos (Backend):** Toda la lógica de negocio, control de perfiles y sesiones corre sobre PHP y Java.
* **Persistencia:** Modelado relacional de la base de datos para almacenar el histórico de entrenamientos de los usuarios y el módulo de contabilidad de los entrenadores.

---

## ¿Qué hace la aplicación actualmente?

### Panel del Entrenador / Administrador
* **Gestor de clientes:** Permite crear fichas individuales y planificar o asignar rutinas semanales en pocos minutos de forma automatizada.
* **Control financiero básico:** Un pequeño panel en tiempo real para llevar al día los ingresos, beneficios y las suscripciones del mes.
* **Perfil de empresa:** Una sección diseñada para que los entrenadores o centros deportivos puedan anunciarse dentro de la plataforma mediante un pago mensual.

### Interfaz del Cliente (Vista Móvil)
* **Seguimiento en directo:** Una pantalla limpia donde el usuario ve su entrenamiento del día, puede marcar las series terminadas, apuntar los kilos levantados y ver el cálculo de kilocalorías diarias.

---

## La parte de negocio, Memoria del proyecto:

Como era un proyecto intermodular, la defensa ante el tribunal exigía justificar que la empresa era viable fuera de la pantalla. Por eso, el proyecto incluye:

* **Modelo legal y fiscal:** Elección de la forma jurídica, trámites necesarios para la puesta en marcha de la startup y el calendario de tributación para un software de suscripción.
* **Recursos Humanos y PRL:** Organigrama del equipo, diseño de las fichas de descripción de puestos de trabajo y el plan de prevención de riesgos laborales.
* **Viabilidad financiera:** Estudio del coste de producción por usuario, estimación de la inversión inicial necesaria y análisis de subvenciones para asegurar que el negocio sea rentable.

---

## Cosas por mejorar:
* Ser más estricta con el control de versiones en Git (usando ramas para meter nuevas características, aplicando lo aprendido en OpenWebinars).
* Refactorizar algunas partes del backend para arañar milisegundos de velocidad cuando se despliegue en un servidor cloud real.

## Ideas de futuro:
* Integrar un control de versiones más estricto con Git (aplicando formaciones complementarias de OpenWebinars) para la gestión sistemática de futuras ramas de desarrollo.
* Refactorizar módulos del backend para optimizar la velocidad de respuesta y la escalabilidad al desplegarlo en servidores cloud comerciales.
