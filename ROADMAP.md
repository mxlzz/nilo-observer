# Observer — Hoja de ruta inicial

**Aprobación:** apertura de línea y revisión de antecedentes autorizadas; los diseños y experimentos de abajo son candidatos, no protocolos experimentales aprobados.

## E0 — Antecedentes y alcance (abierta)
Buscar literatura y desarrollos relevantes, verificar fuentes/código/versión y licencias. Candidatos de partida: Laboratorio histórico y escenarios Nilo 0.7, mecanismos de replay/persistencia de MineWorld y Bigville, herramientas de observabilidad, visualización temporal y simulación; revisar alternativas nativas antes de programar.
Entregable: inventario trazable, comparación crítica, vacíos y decisión de qué conviene reutilizar, adaptar, descartar o investigar. No establecer tecnología por anticipado.

## E1 — Hipótesis y protocolo (pendiente de E0)
Inventariar usuarios y preguntas concretas, elegir el primer caso de observación medible y verificar alternativas. No diseñar interfaz final antes de validar datos y necesidades.
Modelo sustituto posible: Trazas sintéticas versionadas y copias de evidencia pública de los otros laboratorios; no depender de sus runtimes ni imponer formato común.
Entregable: hipótesis falsable, baseline, controles, configuración, métricas y umbral de decisión, presupuesto y plan de reproducibilidad. No ejecutar hasta revisar y aprobar protocolo conforme a coordinación.

## E2 — Contraste mínimo (condicional)
Reconstrucción de secuencias y relaciones con procedencia, estados faltantes explícitos, comparación observación activada/desactivada sin alterar estado, latencia y coste; distinguir evento real, inferencia y presentación.
El ensayo concreto debe derivar de E0/E1; no es una obligación de implementar estos candidatos. Ejecutar solo lo necesario y registrar negativos.

## E3 — Replicación y revisión (condicional)
Repetir contrastes con variación justificada; auditar generalización y coste; comparar con mecanismos existentes; decidir avanzar, ajustar, pausar o cerrar. No integrar con otros laboratorios hasta contar con evidencia y un gate específico.
