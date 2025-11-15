# proyecto-calculadora--de--presupuesto--mensual-1.0v
## Descripción del caso
La Calculadora de Presupuesto Mensual es un sistema que permite registrar ingresos y gastos, calcular el balance disponible y ofrecer una visión clara de la distribución del presupuesto. Su propósito es facilitar la organización financiera personal mediante funciones simples y accesibles.

---

## Objetivos
- Permitir el registro de ingresos e identificar su origen.
- Registrar gastos y clasificarlos.
- Calcular de manera automática el balance mensual.
- Mostrar al usuario la distribución del presupuesto de forma clara.
- Proponer el tipo de mantenimiento adecuado según las mejoras requeridas.

---

## Requerimientos

### Requerimientos Funcionales
1. El sistema debe permitir registrar ingresos.
2. El sistema debe permitir registrar gastos con categoría.
3. El sistema debe calcular el balance total restando ingresos menos gastos.
4. El sistema debe mostrar una lista de ingresos y gastos registrados.
5. El sistema debe validar que los valores ingresados sean positivos.

### Requerimientos No Funcionales
1. La interfaz debe ser sencilla e intuitiva.
2. El sistema debe responder en menos de dos segundos.
3. La aplicación debe ser compatible con navegadores modernos.

---

## Tabla de Pruebas

| ID Caso | Tipo | Requerimiento Asociado | Datos de Entrada | Resultado Esperado | Resultado Obtenido |
|--------|------|-------------------------|------------------|--------------------|---------------------|
| CP-U1  | Unitario | RF1 – Registrar ingresos | Ingreso: 1200 | El ingreso debe registrarse correctamente | Ingreso registrado correctamente |
| CP-U2  | Unitario | RF2 – Registrar gastos | Gasto: "Comida" – 150 | El gasto debe registrarse correctamente | Gasto registrado correctamente |
| CP-U3  | Unitario | RF3 – Calcular balance | Ingreso: 1200, Gastos: 400 | Balance esperado: 800 | Balance calculado: 800 |
| CP-V1  | Validación | RF2 – Validación de datos | Gasto: –50 | Debe mostrar error | Mensaje: "El valor debe ser positivo" |
| CP-V2  | Validación | RF1 – Campo obligatorio | Ingreso vacío | Solicitar dato válido | Mensaje: "Ingrese un valor válido" |

---

## Tipo de mantenimiento propuesto
El tipo de mantenimiento recomendado es el mantenimiento perfectivo, ya que se buscan agregar funciones nuevas que amplíen las capacidades del sistema, como:
- Gráficos de distribución del presupuesto.
- Categorización automática.
- Exportación de reportes.
- Alertas por porcentajes de gasto.

Este mantenimiento mejora la funcionalidad sin corregir fallos existentes.

---

## Reflexión sobre el control de versiones
El control de versiones es fundamental en el desarrollo de software, ya que permite llevar un registro detallado de cada cambio realizado. En proyectos como esta calculadora, ayuda a organizar las actualizaciones, corregir errores sin perder avances y coordinar el trabajo entre varios desarrolladores. Además, ofrece la posibilidad de volver a versiones anteriores en caso de fallos y garantiza una mayor trazabilidad y orden en la evolución del proyecto.
