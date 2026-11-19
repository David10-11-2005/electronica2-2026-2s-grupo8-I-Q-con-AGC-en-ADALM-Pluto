# electronica2-2026-2s-grupo8-I-Q-con-AGC-en-ADALM-Pluto
**Proyecto:** Acondicionamiento digital de señales I/Q con AGC en la plataforma ADALM-Pluto
**Asignatura:** Electrónica II (TEP220342) – Telecomunicaciones, 4.º "A"
**Docente:** Mgs. Giovanny Cuzco
**Período:** 2026-2S

## Integrantes
- Alexis Cañar
- Marco Ordoñez

## Objetivo
Implementar detección de potencia (P = I² + Q²), filtrado IIR de primer orden y control automático de ganancia (AGC) sobre señales I/Q a 2,45 GHz y 2,5 MSPS en el ADALM-Pluto.
Medir su precisión, reducción de ruido, tiempo de convergencia y latencia, con un plan alterno en simulación con señales I/Q sintéticas.

## Parámetros de trabajo
| Parámetro | Valor |
|---|---|
| Portadora de prueba | 2,45 GHz |
| Frecuencia de muestreo | 2,5 MSPS |
| Plataforma | ADALM-Pluto (AD9363 y Zynq-7010) |
| Herramientas | Python, GNU Radio, IIO |

## Estructura del repositorio
- `docs/` – Avances semanales en PDF e informe final
- `src/` – Scripts en Python y flujogramas de GNU Radio
- `results/` – Gráficas, mediciones y tablas
