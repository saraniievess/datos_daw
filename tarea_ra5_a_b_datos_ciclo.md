.# Práctica RA5 · a+b — Datos e información

## 1) Caso
- Sistema: Aplicación móvil de ventas online
- Contexto: Una tienda usa una app para registrar compras y analizar a sus clientes

## 2) Datos
- 23 compras realizadas hoy
- 20€ (precio de un producto)
- 12:14 (hora de la compra)
- ID cliente: 2882
- Producto: camiseta negra
- Código postal: 41900

## 3) Información
- El producto más vendido hoy es la camiseta negra, las ventas son más altas antes del mediodía y la mayoría de los clientes es del códido postal 41900

## 4) Diferencia
- El dato es un valor sin contexto (20€) y la información procesa los datos y saca una conclusión (mayores ventas a las 12)

## 5) Ciclo del dato
- Captura: La app registra cada compra realizada por los usuarios
- Almacenamiento: Los datos se guardan en una base de datos
- Procesamiento: Se organizan y agrupan (por producto, hora, cliente…)
- Análisis: Se estudian patrones de compra
- Uso: Se toman decisiones comerciales
- Eliminación: Se archivan o eliminan datos antiguos según normativa

## 6) Aplicación
- Decisiones:
	- Aumentar stock de camisetas negras
	- Lanzar promociones en horas de baja venta
	- Personalizar ofertas según ubicación
- Valor:
	- Permite mejorar ventas
	- Optimiza recursos
	- Ayuda a entender mejor a los clientes

## 7) Tabla
| Dato | Información |
| 20€ | Precio medio de productos |
| 25 compras | Promedio de ventas diario |
| 12:14 | Hora con mayores ventas |
| Camiseta negra | Producto más vendido |
| 41900 | Código postal con más clientes |

## 8) Diagrama

Usuario → App → Base de datos → Procesamiento → Análisis → Decisión

## 9) Problemas
- Problema 1: Datos erróneos (precios incorrectos, registros duplicados)
- Solución 1: Validación automática de datos y control de errores
- Problema 2: Datos desactualizados (información antigua que ya no refleja la realidad actual)
- Solución 2: Actualización periódica de la base de datos y eliminación de registros obsoletos

## 10) Fuente
- Enlace: https://www.ibm.com/topics/data-analytics
