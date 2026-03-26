[README.md](https://github.com/user-attachments/files/26288676/README.md)
# 🌍 Consulta del Viajero

Aplicación web para la gestión clínica de la **consulta del viajero internacional**. Desarrollada como herramienta de apoyo a la práctica clínica en medicina del viajero.

## ¿Qué hace?

Permite registrar de forma estructurada los datos de cada paciente que acude a consulta previo a un viaje internacional, y genera automáticamente los documentos y recomendaciones necesarios.

### Funcionalidades principales

- **Formulario multipaso** con los datos clínicos y del viaje relevantes para la consulta
- **Identificación anonimizada** del paciente (iniciales + fecha de nacimiento + sexo) para seguimiento de visitas repetidas
- **Guía de malaria SEMTSI 2025** integrada: consulta rápida por país con niveles de riesgo, especies de Plasmodium, temporada de lluvia y recomendaciones de quimioprofilaxis
- **Alertas automáticas** al introducir destinos: nivel de riesgo de malaria por zonas geográficas
- **Warnings clínicos** de vacunas vivas atenuadas (fiebre amarilla, tifoidea oral) en situaciones de riesgo: embarazo, posible embarazo, lactancia, inmunosupresión, antecedentes de inmunocompromiso y edad ≥65 años
- **Informe Word** descargable con todos los datos de la consulta
- **Prompt para Claude** generado automáticamente con todos los datos del caso, incluyendo la información de malaria de la guía SEMTSI, listo para obtener recomendaciones de vacunación y quimioprofilaxis
- **Base de datos local** acumulativa (localStorage): los casos se guardan entre sesiones en el mismo navegador
- **Exportación CSV** de todos los casos guardados para explotación posterior

## Cómo usar

Accede directamente desde el navegador:

👉 **https://evafbreton.github.io/consulta-viajero/**

No requiere instalación ni registro. Los datos se guardan localmente en el navegador.

## Fuentes

- Guía de recomendaciones para la prevención de malaria en viajeros internacionales — **SEMTSI 2025**
- CDC Yellow Book
- WHO International Travel and Health

## Aviso

Esta herramienta es un apoyo a la práctica clínica y **no sustituye el juicio clínico del profesional**. Las recomendaciones deben individualizarse siempre según el perfil de cada paciente.

---

*Desarrollado para uso clínico interno en medicina del viajero.*
