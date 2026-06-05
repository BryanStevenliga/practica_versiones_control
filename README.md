#  Gestión de Repositorios Colaborativos, Protección de Ramas y Automatización CI/CD en GitHub

---

##  Equipo y Dinámica de Roles (Flujo Cruzado)

Para cumplir con los objetivos de la práctica, implementamos un esquema de **roles cruzados e intercambiables**, permitiendo que ambos experimentáramos tanto la administración de la seguridad como el flujo de desarrollo:

* **Steven Ninasunta** * `Repository Admin` ➔ Gestión de políticas de seguridad, restricción de la rama `main` y auditoría de código.
  * `Core Developer` ➔ Creación de ramas secundarias, maquetación y resolución de conflictos de integración.
* **Brayan Viracocha** * `Core Developer` ➔ Desarrollo de módulos base, generación de commits y simulación de colisiones de código.
  * `Repository Admin` ➔ Revisión cruzada en *Submit review* y aprobación formal de *Pull Requests*.

---

##  Hitos Implementados en el Proyecto

* **Estructura Base:** Inicialización del entorno colaborativo a través de este archivo `README.md`.
* **Seguridad y Gobernanza:** Configuración de reglas estrictas para blindar la rama `main`, requiriendo aprobaciones mandatorias antes de cualquier *merge*.
* **Automatización (CI/CD):** Despliegue de un pipeline automatizado con GitHub Actions mediante el motor `ci.yml`.
* **Gestión de Crisis:** Detección en tiempo real de un fallo crítico de integración continua y aplicación exitosa del parche técnico definitivo mediante el commit `2009d0b`.

---

## Entrega Oficial
> 📄 **[Ver Informe Técnico en PDF](./Informe_Final_Laboratorio.pdf)** > 
