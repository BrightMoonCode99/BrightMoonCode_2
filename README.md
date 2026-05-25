# 🌐 Infraestructura Cisco: Ciberseguridad e IA

## 👥 Grupo de Trabajo - Infraestructura Cisco Systems Inc.

| Nombre | Rol | Especialidad |
|--------|-----|---------------|
| **Sergio Guzmán Vergara** | Hacking Ético Básico | Detección de vulnerabilidades, pruebas de penetración iniciales y análisis de superficies de ataque. |
| **Nicolás Rodríguez Salinas** | Análisis Básico | Recolección y procesamiento de datos de seguridad, identificación de patrones anómalos. |
| **Mateo Andrés Lugo** | IA Básica | Implementación de modelos simples de machine learning para clasificación de tráfico y anomalías. |
| **Thomas Cifuentes Osorio** | IA Básica | Asistencia en entrenamiento de modelos y automatización de respuestas ante incidentes. |

---

## 🛡️ Ciberseguridad + IA: Enfoque desde Cisco

### 🔐 Problemática identificada (documento VR2)
- Vulnerabilidades críticas como **CVE-2026-20131** (zero-day explotado por ransomware Interlock).
- Explotación de fallos en **SD-WAN** durante 3 años (CVE-2026-20127).
- Uso creciente de **IA maliciosa** (Slopoly, FraudGPT, WormGPT, Deepfakes).

### 🧠 Solución propuesta
1. **Verificación de transacciones humanas** para mitigar ataques basados en IA.
2. **Arquitectura moderna de seguridad** con accesos temporales y microsegmentación.
3. **Monitoreo constante + capacitación humana** mediante simulaciones realistas.

### Enlce Presentacion
- https://canva.link/rru0tdt4oo938dt
---

## 🤖 Arquitectura IA para Seguridad (basada en Cisco)

```mermaid
graph TD
    A[Usuario / Slack] --> B[Interfaz Web/API]
    B --> C[Orquestador de Intentos]
    C --> D[LLM + RAG]
    D --> E[Filtro de Seguridad Anti-Inyección]
    E --> F[MCP Server - Firewall]
    E --> G[MCP Server - Identity]
    E --> H[MCP Server - XDR]
    F --> I[(Cisco FMC / CDO)]
    G --> J[(Cisco ISE)]
    H --> K[(Plataforma XDR)]
