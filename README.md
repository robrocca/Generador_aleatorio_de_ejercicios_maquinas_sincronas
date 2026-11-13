# Ejercicios de práctica · Máquinas síncronas

Generador de ejercicios de **máquinas síncronas** para la asignatura *Máquinas Eléctricas II* (Universidad de Zaragoza). Crea un enunciado nuevo cada vez, con datos distintos, y muestra la solución completa con su explicación para que el estudiante pueda comprobar su resultado.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24195538.svg)](https://doi.org/10.5281/zenodo.24195538)

## Qué cubre

Cada ejercicio tiene tres partes que se pueden elegir o dejar en aleatorio:

- **Tipo de máquina:** polos lisos o polos salientes.
- **Parte 1:** FEM desde la geometría · datos desde ensayos de vacío y cortocircuito · f.m.m. instantáneas de fase · triángulo de Potier (lisos) · Blondel desde V, I y φ (salientes).
- **Parte 2:** diagrama de f.m.m. · red de potencia infinita · Behn-Eschenburg con Xₗ + Xᵢ · Xₛ con f.d.p. capacitivo o inductivo · Xₛ desde E₀ y Eᵣ · Blondel desde I y ψ · Blondel y potencias · potencias de excitación y de reluctancia · diagrama completo (Fᵣ y Φᵣ).
- **Parte 3 (opcional):** compensador síncrono · líneas de flujo y fasores espaciales · potencias P y Q · diagrama fasorial de tensiones · ángulo de carga y P con Q = 0 · E₀ mínima para generar Q.

También se pueden fijar la **tensión nominal** (400 V – 13,8 kV) y la **potencia nominal** (10 kVA – 50 MVA).

## Cómo se usa

1. Elige el tipo de máquina, las partes y, si quieres, la tensión y la potencia.
2. Pulsa **Nuevo ejercicio** e intenta resolverlo.
3. Pulsa **Mostrar solución** para comprobar tus resultados paso a paso.

### Código del ejercicio

Cada ejercicio tiene un código (p. ej. `SDQK-400-200-2026`) que lo identifica de forma única. Escribiéndolo en «Código del ejercicio» y pulsando Intro se recupera exactamente el mismo enunciado, lo que permite que el profesorado asigne un ejercicio concreto o que los estudiantes compartan dudas sobre el mismo problema.

## Funcionamiento sin conexión

Es una única página HTML autocontenida: basta con abrir `index.html` en un navegador. El motor de fórmulas (MathJax) va incluido en el archivo. Las tipografías se cargan desde Google Fonts; sin conexión se usan las del sistema y todo sigue funcionando.

## Autoría y uso de IA

Diseño pedagógico, selección y planteamiento de los ejercicios, modelos de cálculo y validación técnica de las soluciones: Roberto Rocca (Universidad de Zaragoza).

La implementación del código se realizó con asistencia de IA generativa (Claude, Anthropic), bajo la dirección y revisión del autor.

## Licencia

- Código: [MIT](LICENSE).
- Enunciados y soluciones generados: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es).

## Cómo citar

Usa el botón **Cite this repository** de GitHub o el DOI de Zenodo.
