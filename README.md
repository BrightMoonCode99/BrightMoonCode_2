# 🔐 Infraestructura de Ciberseguridad e IA - Cisco Systems Inc.

## 👥 Grupo de Investigación y Desarrollo

| Integrante | Rol en el Proyecto |
|------------|--------------------|
| **Sergio Guzmán Vergara** | Ciberseguridad / Coordinador |
| **Nicolás Rodríguez Salinas** | Especialista en Modelos Predictivos y Detección de Anomalías |
| **Mateo Andrés Lugo** | Ingeniero de Automatización y Respuesta a Incidentes |
| **Thomas Sifuentes Osorio** | Analista de Threat Intelligence (Cisco Talos) |

---

## 🎯 Objetivo General del Equipo

> *“Diseñar e implementar un modelo empresarial y metodologías de ciberseguridad basadas en inteligencia artificial para Cisco Systems Inc., mitigando vulnerabilidades y cerrando brechas en firewalls para garantizar transparencia y confianza.”*

---

## 🧠 Líneas de acción por integrante

### 🛡️ Sergio Guzmán Vergara – Arquitectura Zero Trust + IA Defensiva

- Implementación de **Zero Trust** (Duo, TrustSec, Secure Workload).
- Integración de **IA para verificación de transacciones humanas**.
- Supervisión de la **arquitectura multiagente** (Cisco AI Defense).

### 🤖 Nicolás Rodríguez Salinas – Modelos de ML y detección de anomalías

- Entrenamiento de modelos **LLM / SLM** (ej. Foundation-Sec-8B).
- Detección de patrones anómalos mediante **GraphRAG** y **grafos de conocimiento**.
- Implementación de **gemelo digital de red** para simulaciones de ataques.

### ⚙️ Mateo Andrés Lugo – Automatización y orquestación de respuestas

- Desarrollo de **agentes autónomos** (planificación, pruebas, ejecución).
- Integración con **MCP Servers** (Firewall, Identity, XDR).
- Automatización de **playbooks de respuesta** ante incidentes.

### 📡 Thomas Sifuentes Osorio – Threat Intelligence y monitoreo proactivo

- Alimentación de inteligencia desde **Cisco Talos**.
- Configuración de **XDR** para telemetría unificada.
- Simulaciones de ataques y **capacitación humana** contra ingeniería social.

---

## 🧱 Arquitectura de Solución (Basada en el documento)

```mermaid
graph TD
    A[Usuario / Slack] --> B[Interfaz Web/API]
    B --> C[Orquestador de Intentos]
    C --> D[LLM + RAG]
    D --> E[Filtro de Seguridad]
    E --> F[MCP Server - Firewall]
    E --> G[MCP Server - Identity]
    E --> H[MCP Server - XDR]
    F --> I[(Cisco FMC)]
    G --> J[(Cisco ISE)]
    H --> K[(Plataforma XDR)]
