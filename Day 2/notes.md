# Red-Nosed Reports

## Contexto:

En la primer localización, la planta de energia nuclear, los trabajadores te piden que revises unos reportes inusuales para saber cuales son seguros y cuales no.
Cada reporte esta compuesto por niveles.

## Problema:

Encuentra los reportes seguros. Ten en cuenta que un reporte solo es seguro si:

- Sus niveles son todos ascendentes o decrecientes.
- Cada nivel adjacente difiere por lo menos en uno y como maximo tres.

## Pasitos:

1. Separar cada reporte y convertir los valores a tipo int.
2. Encontrar si un reporte es decreciente o creciente y si en algun punto esa tendencia se corta.
3. Encontrar por cuanto difiere cada nivel de cada reporte.
