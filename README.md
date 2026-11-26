# Ondo

Web, documentación y descargas de **Ondo**, la app de Auralix Studio que graba clases y reuniones y las
convierte en texto, resumen, puntos clave y tareas, sin internet.

## Modelos

Los modelos de IA que descarga la app se publican en las
[releases](https://github.com/Auralix-Studio/ondo/releases).

| Modelo | Base | Licencia | Estado |
|---|---|---|---|
| Lume Lite v2 (`lume-lite-v2-q4_k_m.gguf`, 1,1 GB) | [Qwen/Qwen3-1.7B](https://huggingface.co/Qwen/Qwen3-1.7B) + LoRA | Apache 2.0 (ver `LICENSE-Qwen3.txt` en la release) | **Piloto**: entrenado solo con datos sintéticos; puede equivocarse o inventar detalles |

Lume Lite es un modelo derivado de Qwen3-1.7B (Apache 2.0), ajustado por Auralix Studio para resumir
clases en español y usar las herramientas del asistente de Ondo. Cuantizado a Q4_K_M con llama.cpp.
