# 🔥 Fortinet Hardening Templates & Baselines

Bienvenido a mi bóveda de configuraciones de seguridad perimetral. En este repositorio comparto plantillas de configuración (CLI), baselines y políticas restrictivas enfocadas en dispositivos **FortiGate (FortiOS)**.

La filosofía de estas plantillas es simple: **Zero Trust y Default Deny**. Todo lo que no está explícitamente permitido, muere en el firewall.

## 🗂️ Contenido del Repositorio

*   📄 `fortigate-baseline-hardening.cli`: Script base para aplicar un hardening extremo a un equipo recién sacado de la caja o reseteado de fábrica (Gestión de puertos, restricción de accesos administrativos, políticas de contraseñas y desactivación de servicios inseguros).
*   *(Próximamente)* Plantillas de segmentación de interfaces (VLANs).
*   *(Próximamente)* Políticas de IPS y perfiles de seguridad para ambientes OT/IT.

## ⚠️ Advertencia de uso
Estos scripts están diseñados en mi entorno de R&D (Homelab). **NO** los copies y pegues directamente en un entorno de producción sin antes leer y adaptar los segmentos de red (Trust/Untrust) e IPs administrativas. Aplicar un baseline de hardening a ciegas puede dejarte fuera de la gestión del equipo.

---
*Mantenido por Marcelo Bugallo (DarthChelo).*
