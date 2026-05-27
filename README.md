# Física Computacional - FIS 205

Este repositorio contiene los códigos, simulaciones y asignaciones desarrolladas durante el curso de Física Computacional. El trabajo se divide en dos ejes principales: el Proyecto Final y las Tareas regulares del semestre.

---

## 🚀 Proyecto Final: Termodinámica Cuántica Computacional

**Descripción:** Simulación y verificación numérica de la dinámica de un sistema de dos niveles (qubit) con *detuning* dependiente del tiempo. El proyecto contrasta la evolución exacta (con memoria del entorno, resuelta analíticamente vía funciones de Weber) frente a la aproximación puramente disipativa y sin memoria dictada por la Ecuación Maestra de Lindblad.

### 📊 Estado de Avance (Segunda Entrega - 70%)

Actualmente nos encontramos en la etapa de desarrollo correspondiente al 70% del proyecto. A continuación se detalla el progreso de los objetivos computacionales y analíticos:

**Fase 1: Implementación Numérica y Exacta (Completado)**
- [x] Derivación teórica del kernel de memoria y la ecuación de evolución exacta.
- [x] Implementación del integrador numérico propio de orden fijo (RK4).
- [x] Validación cruzada utilizando algoritmos de paso adaptativo (`scipy.integrate.solve_ivp` - RK45).
- [x] Evaluación de la solución analítica exacta mediante `mpmath.pcfd` (funciones cilíndricas parabólicas de Weber).

**Fase 2: Simulación de Sistemas Abiertos (Completado)**
- [x] Configuración del Hamiltoniano dependiente del tiempo en `QuTiP`.
- [x] Implementación del operador de colapso para la simulación de la Ecuación de Lindblad.
- [x] Extracción y ploteo de la dinámica poblacional $\rho_{ee}(t)$ para ambos regímenes.

**Fase 3: Termodinámica y Conclusiones (Pendiente - Próxima Entrega)**
- [ ] Cálculo numérico del Trabajo Extraído ($|W|$) y el Calor Disipado ($|Q|$).
- [ ] Análisis comparativo de la eficiencia termodinámica (Exacta vs. Lindblad).
- [ ] Formato final de gráficos vectoriales para calidad de publicación.
- [ ] Redacción final del informe en LaTeX y conclusiones.

---

## 📚 Tareas

En la carpeta [`/Tareas`](./Tareas) se encuentran almacenadas las asignaciones menores desarrolladas durante las clases prácticas del curso. Cada subcarpeta o *notebook* contiene su propio enunciado y la resolución computacional correspondiente.
