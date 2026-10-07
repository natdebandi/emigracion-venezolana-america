# Emigración venezolana en América

Tablero exploratorio sobre la emigración venezolana en el continente americano,
con Bolivia como contraste.

**Centro de Investigación en Inteligencia Artificial (CIAI) · UNSAM**
Grupo de Demografías y Trazas Digitales — Natalia Debandi

## Qué contiene

Un solo archivo, `index.html`, autocontenido: los datos y la librería de
gráficos viajan adentro. Se abre con doble clic y no necesita servidor.

Secciones: flujos anuales (Abel 2025), stock registrado (R4V), el crecimiento
año a año en mapa animado, serie larga 1990–2023, composición por sexo y edad,
censos nacionales de Argentina 2010/2022 y Chile 2024, perfil sociodemográfico,
y notas metodológicas.

## Fuentes

| Fuente | Qué mide | Cobertura |
|---|---|---|
| Abel 2025 | flujos bilaterales anuales | 1990–2023, 22 destinos |
| R4V | stock administrativo por país de acogida | feb-2018 a ago-2026, 17 países |
| Censos | stock por lugar de nacimiento | Argentina 2010 y 2022, Chile 2024 |

No se suman entre sí: son medidas distintas.

## Advertencia

El salto de 2018 en la serie de flujos (286.271 a 2.542.218) no es un error de
magnitud sino una convención de rezago del modelo: el flujo etiquetado como año
`t` corresponde al cambio de stock entre `t` y `t+1`. La lectura correcta es el
bienio 2018–2019. Está desarrollado en las notas metodológicas del tablero.

El stock de R4V es un piso, no un techo: no incluye a las personas en situación
irregular que no figuran en los registros oficiales.

## Reproducir

El código está en el repositorio de trabajo (`venezuela_regional`, privado).
Este repositorio solo publica la salida.

## Licencia

Los datos son de las fuentes citadas. Elaboración propia.
