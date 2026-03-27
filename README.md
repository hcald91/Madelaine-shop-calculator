# 🧵 Madelaine Shop — Calculadora de Negocio

Herramienta interactiva para analizar la rentabilidad de una tienda de lencería en Yereván, Armenia, combinando fabricación artesanal local e importación desde China.

🔗 **[Ver calculadora en vivo](https://hcald91.github.io/Madelaine-shop-calculator/madelaine-shop-calculator.html)**

---

## ¿Qué hace esta calculadora?

Tiene 4 módulos con sliders interactivos que actualizan los números en tiempo real:

| Módulo | Descripción |
|--------|-------------|
| **Fabricación propia** | Calcula el costo por prenda (tela, avíos, mano de obra) y la ganancia mensual según cuántas prendas confecciona Madelaine |
| **Importar de China** | Desglosa el costo real de cada prenda importada incluyendo flete, arancel aduanero (12%) e IVA de aduana (20%) no recuperable |
| **Modelo combinado** | Proyección mensual unificando ambos canales, con gráfico de barras de ingresos vs costos |
| **Inversión inicial** | Desglose de los ~$2,663 necesarios para arrancar: equipamiento, primer inventario y setup del local |

---

## Contexto del negocio

**Empresa:** Մադելայնե Շոփ (Madelaine Shop) — ՍՊԸ  
**ՀVՀՀ:** 00542756  
**Régimen fiscal:** Շրջանառության հարկ (Turnover Tax) desde enero 2026  
**Ubicación:** Nor Aresh, Erebuní, Yereván, Armenia  

### Actividades planeadas
- Confección artesanal de lencería (blúmers y ajustadores)
- Importación de lencería desde China vía 1688/Alibaba
- Venta en tienda física en Yereván
- Venta online en Ozon y Wildberries Armenia

### Régimen fiscal aplicado en los cálculos
- **5%** sobre ingresos por confección y servicios (Turnover Tax)
- **3.5%** sobre ingresos por venta de productos importados (Turnover Tax)
- IVA de importación (20%) tratado como costo no recuperable

---

## Tecnologías

- HTML5 + CSS3 vanilla (sin frameworks)
- [Chart.js 4.4.1](https://www.chartjs.org/) para los gráficos
- Sin backend, sin build step — abre directo en el navegador
- Compatible con modo oscuro del sistema operativo

---

## Uso local

```bash
git clone https://github.com/hcald91/Madelaine-shop-calculator.git
cd Madelaine-shop-calculator
# Abre el archivo directamente en tu navegador
open madelaine-shop-calculator.html
```

No necesita servidor ni dependencias. Funciona offline (excepto Chart.js que carga desde CDN).

---

## Estructura del proyecto

```
Madelaine-shop-calculator/
├── madelaine-shop-calculator.html   # Calculadora completa (todo en un archivo)
└── README.md
```

---

*Calculadora con fines estimativos. Los valores reales pueden variar según el mercado, tipo de cambio AMD/USD y condiciones aduaneras vigentes en Armenia.*
