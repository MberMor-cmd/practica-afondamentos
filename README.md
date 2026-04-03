## 📊 **Proyecto de Afondamentos: Mermaid + Markdown**   
Este es mi primer repositorio profesional donde implemento documentación técnica estructurada. Según el temario del tercer trimestre, la combinación de estos dos lenguajes permite una claridad absoluta en el flujo de trabajo.   
## 🚀 **Configuración del Entorno**   
Siguiendo las pautas de la asignatura, he configurado:VS Code como editor principal.Git como motor de versiones.Extensiones para el renderizado de diagramas.   
## 🧠 **Lógica de Configuración**   
A continuación, represento el proceso que hemos seguido para poner a punto este PC:
```mermaid
graph TD
    A[Inicio: PC Nuevo] --> B(Instalar Git);
    B --> C[Configurar VS Code];
    C --> D{¿Clonado con éxito?};
    D -- Sí --> E[Documentar en README.md];
    D -- No --> F[Revisar URL de GitHub];
    F --> D
    E --> G[Subir cambios a la Nube];
    

