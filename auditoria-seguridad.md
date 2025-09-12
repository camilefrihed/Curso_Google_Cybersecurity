# Auditoría de Seguridad – Botium Toys  

![Status](https://img.shields.io/badge/Status-Finalizado-brightgreen?style=flat-square)  
![Compliance](https://img.shields.io/badge/Compliance-PCI%20DSS%20%7C%20GDPR%20%7C%20SOC-important?style=flat-square)  
![Security](https://img.shields.io/badge/Security-Risk%20Assessment-orange?style=flat-square)  

---

## 1. Alcance y Objetivos  

**Alcance:**  
- Activos físicos y digitales de empleados  
- Productos en venta física y en línea  
- Sistemas de gestión y software  
- Red interna y acceso a Internet  
- Retención y almacenamiento de datos  
- Sistemas heredados con supervisión manual  

**Objetivos:**  
1. Evaluar activos y su impacto en el negocio.  
2. Completar lista de controles y cumplimiento.  
3. Fortalecer la postura de seguridad.  
4. Cumplir con regulaciones (PCI DSS, GDPR, SOC 1/2).  

---

## ⚠️ 2. Evaluación de Riesgos  

- **Riesgo principal:** Gestión de activos inadecuada y falta de controles.  
- **Puntuación de Riesgo:** `8/10 (Alto)`  

**Hallazgos clave:**  
- Acceso abierto a PII/SPII de clientes.  
- Datos de tarjetas sin cifrar.  
- Sin planes de recuperación ni copias de seguridad.  
- Políticas de contraseñas débiles.  
- Sistemas heredados sin mantenimiento.  
- Seguridad física robusta (CCTV, cerraduras, alarmas).  

---

##  3. Controles Administrativos  

| Control | Tipo | Estado | Observaciones |
|---------|------|--------|---------------|
| Menor privilegio | Preventivo | ❌ No | Acceso abierto a datos sensibles. |
| Planes de recuperación | Correctivo | ❌ No | No existen backups ni DRP. |
| Políticas de contraseñas | Preventivo | ❌ No | Requisitos básicos. |
| Gestión de cuentas | Preventivo | ❌ No | No se controla ciclo de vida. |
| Separación de funciones | Preventivo | ❌ No | Riesgo de abuso interno. |

---

## 4. Controles Técnicos  

| Control | Tipo | Estado | Observaciones |
|---------|------|--------|---------------|
| Firewall | Preventivo | ✅ Sí | Filtra tráfico malicioso. |
| IDS/IPS | Detectivo | ❌ No | No implementado. |
| Cifrado | Disuasivo | ❌ No | Sin cifrado en datos críticos. |
| Copias de seguridad | Correctivo | ❌ No | Riesgo alto de pérdida. |
| Antivirus | Preventivo | ✅ Sí | Activo y monitoreado. |
| Monitoreo sistemas heredados | Preventivo | ⚠️ Parcial | Sin cronograma formal. |

---

##  5. Controles Físicos  

| Control | Tipo | Estado | Observaciones |
|---------|------|--------|---------------|
| Caja fuerte | Disuasivo | ✅ Sí | Acceso restringido. |
| CCTV | Preventivo | ✅ Sí | Monitoreo constante. |
| Armarios cerrados | Preventivo | ✅ Sí | Protege red interna. |
| Señalización de alarmas | Disuasivo | ✅ Sí | Disuasión activa. |
| Detección incendios | Preventivo | ✅ Sí | Inventario protegido. |

---

##  6. Cumplimiento Normativo  

###  PCI DSS  
- ❌ Acceso restringido a datos  
- ❌ Procesamiento seguro  
- ❌ Cifrado de datos  
- ❌ Políticas de contraseñas  

###  GDPR  
- ⚠️ Control de acceso insuficiente  
- ✅ Notificación en 72h  
- ❌ Inventario de datos inexistente  
- ⚠️ Políticas de privacidad parciales  

### 🧾 SOC 1/2  
- ❌ Políticas de acceso no aplicadas  
- ❌ Confidencialidad no asegurada  
- ⚠️ Integridad parcial (sin cifrado/backups)  
- ⚠️ Disponibilidad comprometida  

---

##  7. Recomendaciones  

1. Implementar **menor privilegio** y separación de funciones.  
2. Instalar **IDS/IPS** para monitoreo de red.  
3. Cifrar **datos sensibles** y tarjetas de crédito.  
4. Crear **planes de recuperación** y realizar backups regulares.  
5. Usar **gestión centralizada de contraseñas**.  
6. Clasificar e inventariar **activos críticos**.  
7. Reforzar cumplimiento de **PCI DSS, GDPR y SOC**.  

---

## ✅ 8. Autoevaluación  

- Alcance, objetivos y riesgos revisados: ✔️  
- Riesgos de clientes, empleados y recursos: ✔️  
- Categorías de control documentadas: ✔️  
- Cumplimiento regulatorio evaluado: ✔️  

**Puntuación Final Recomendada:**  
# 🟢 `5/5`
