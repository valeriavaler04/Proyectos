# STRIDESAFE

**Proyecto desarrollado por el Equipo 9 para el curso de Proyecto de Biodiseño 1**

## 👥 Integrantes

- José Vera Meza  
- Keyla Valeria Valer Blas  
- Bárbara Kassy Zevallos Chávez  
- Dayane Li Egoavil  
- Diego Carrascal  
- Yamil Yapuchura  

---

## 🧠 Sobre el Proyecto

**StrideSafe** es un dispositivo ergonómico diseñado para el **monitoreo preventivo de la temperatura en los pies de pacientes diabéticos**, con el fin de evitar la aparición de úlceras que podrían generar complicaciones graves.

Este sistema permite realizar un escaneo térmico de los pies (pie derecho e izquierdo) y reiniciar las lecturas con una interfaz de tres botones. Utiliza una **matriz térmica Panasonic de 8x8** y captura 192 puntos de temperatura mediante un sensor conectado a una ESP32.

> “Prevención, accesibilidad y monitoreo continuo”

---

## 🔧 Componentes Técnicos

- **Sensor térmico AMG8833**
- **Microcontrolador ESP32**
- **Actuador lineal L298N**
- **Sistema antirrebote con motor paso a paso**
- **Interfaz de tres botones (escaneo derecho, izquierdo y reinicio)**
- **Software embebido para captura de imágenes térmicas**

---

## ⚙ Funcionamiento del Dispositivo

1. El usuario posiciona el pie sobre el dispositivo.
2. Se capturan **tres fotos por área del pie**, generando una matriz térmica detallada.
3. Los datos se procesan en la ESP32 y se envían mediante una app para visualización y monitoreo.
4. El sensor funciona mediante **protocolo I2C** (IO22 e IO21 como pines SCL/SDA).

---

## 🌱 Impacto y Sostenibilidad

- Reducción en hospitalizaciones y tratamientos invasivos.
- Menor carga para el sistema de salud.
- Dispositivo reutilizable tras el tratamiento.
- Apto para zonas con difícil acceso médico.
- Bajo consumo energético (funciona sólo conectado).
- Uso de materiales reciclables y diseño modular.

---

## 📈 Optimización de Recursos

| Componente              | Costo estimado (S/.) |
|------------------------|----------------------|
| Switch                 | 1.00 – 3.00          |
| Sensor cámara térmica  | 70.00 – 90.00        |
| Regulador LDO          | 7.00 – 10.00         |
| ESP32                  | 25.00 – 35.00        |
| Actuador lineal        | 50.00 – 60.00        |
| Conector DC barrel     | 15.00 – 20.00        |

---

## 📲 Aplicación

El sistema está pensado para integrarse con una **app móvil**, que permite a los pacientes realizar el monitoreo desde casa, almacenando y consultando las lecturas térmicas a lo largo del tiempo.

---

## 🔗 Referencias

1. [Sensor de temperatura corporal – TE Medical](https://www.te.com/es/industries/medical-technologies/medical-products-components/medical-sensors/body-temperature-measurement.html)  
2. [Precios de componentes en Aliexpress](https://es.aliexpress.com/item/1005002514375645.html)

---

**STRIDESAFE** es una solución integral que **combina tecnología accesible, monitoreo continuo y diseño sostenible** para mejorar la calidad de vida de los pacientes diabéticos.  
