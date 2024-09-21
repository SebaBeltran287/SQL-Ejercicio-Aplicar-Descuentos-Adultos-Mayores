Aquí te dejo una versión más concisa del README.md, con solo lo más importante:

markdown
Copiar código
# Aplicar Descuentos a Pacientes Adultos Mayores

Este repositorio contiene un script SQL que aplica descuentos a pacientes adultos mayores en la Clínica Ketecura y registra los cambios en una tabla de auditoría.

## Funcionalidades Principales

- **Cálculo de Edad**: Función que calcula la edad del paciente a partir de su fecha de nacimiento.
- **Descuento por Edad**: Determina el porcentaje de descuento según la edad del paciente.
- **Aplicación del Descuento**: Actualiza el costo de atención de pacientes mayores de 60 años.
- **Auditoría de Cambios**: Registra el costo anterior, el nuevo costo, la edad y el descuento aplicado.

## Estructura de las Tablas

- **`ATENCION`**: Almacena las atenciones médicas y sus costos.
- **`PORC_DESCTO_3RA_EDAD`**: Define los porcentajes de descuento según rangos de edad.
- **`AUDITORIA_DESCUENTOS`**: Guarda un registro histórico de los descuentos aplicados.
