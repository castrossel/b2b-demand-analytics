# 📊 Analítica Comercial B2B: Diagnóstico de Salud de Cartera (Churn vs. Contracción)

## 📌 Contexto del Caso de Estudio
Caso aplicado de analítica comercial sobre una distribuidora mayorista B2B de vestuario corporativo en Chile (datos anonimizados). El estudio audita **560 cuentas recurrentes**, **1.967 órdenes únicas** y **83.381 unidades normalizadas** para responder una pregunta crítica de gestión comercial: *¿Dónde está realmente el riesgo de pérdida de volumen en la cartera?*

---

## 🔍 Hallazgos Principales (Entrega 1)

| Estado de Cartera | Cuentas | % Cuentas | Unidades Históricas | % Volumen | Diagnóstico Comercial |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **Contracción de Presupuesto (Downsell Activo)** | 57 | 10,2% | 24.633 | 29,5% | **Foco prioritario:** clientes activos que recortaron drásticamente su último pedido. |
| **En Riesgo de Fuga (6–9m sin compra)** | 23 | 4,1% | 6.045 | 7,2% | Ventana crítica de contacto preventivo antes del abandono. |
| **Activo y Saludable** | 40 | 7,1% | 8.288 | 9,9% | Cartera estable con frecuencia y volumen sostenidos. |
| **Fuga Confirmada (Churn > 9m)** | 433 | 77,3% | 44.240 | 53,1% | El **80,7%** (35.711 u.) corresponde a clientes recurrentes perdidos (*True Churn*). |
| **Ocasional / En Observación** | 7 | 1,3% | 175 | 0,2% | Compras marginales sin historial consolidado. |

---

## 🛠️ Stack Tecnológico Utilizado
* **Procesamiento e Ingeniería de Datos:** Python 3, Jupyter Notebook (`Pandas`, `NumPy`).
* **Visualización Ejecutiva y Modelado BI:** Power BI Desktop (medidas explícitas en `DAX`, jerarquía visual semántica, formato condicional y *Tooltip* personalizado por cliente).

---

## 🗺️ Hoja de Ruta del Tablero Maestro
- [x] **Entrega 1:** Salud de Cartera B2B — Churn Confirmado vs. Contracción Activa (*Downsell*).
- [ ] **Entrega 2:** Preventa Predictiva — Ciclo de Reposición (*TBO*) y Alertas Tempranas de Recompra.
- [ ] **Entrega 3:** Nivel de Servicio (*Fill Rate*) y Brechas de Venta Cruzada (*Cross-Selling*).

---

## 📚 Referencias Metodológicas
* **Griffin, J., & Lowenstein, M. W. (2001).** *Customer WinBack: How to Recapture Lost Customers and Keep Them Loyal*. Jossey-Bass.
* **Reinartz, W. J., & Kumar, V. (2002).** *The Mismanagement of Customer Loyalty*. Harvard Business Review, 80(7), 86–95.
