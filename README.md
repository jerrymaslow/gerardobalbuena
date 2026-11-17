# Reto 1: The Core Engine - Lógica y Arquitectura Frontend

## 1. Justificación de la Arquitectura en el Cliente (RA 1)
Desarrollar este motor de cálculo financiero directamente en el navegador (*Client-Side*) ofrece ventajas clave frente a una arquitectura de servidor:
- **Privacidad y Seguridad:** Los datos financieros del usuario no viajan por la red ni se almacenan en servidores externos de forma prematura.
- **Rendimiento Instantáneo:** Se elimina la latencia de red (*round-trip*) al procesar simulaciones iterativas de interés compuesto de manera local.
- **Escalabilidad:** Se reduce drásticamente la carga de procesamiento en los servidores backend al delegar el cálculo al dispositivo del cliente.

## 2. Tecnologías y Estándares Utilizados
- JavaScript Puro (**Vanilla JS**) estructurado mediante el Patrón de Módulo Revelador.
- Tipado seguro y conversión explícita para evitar errores de concatenación.
- Métodos avanzados de colecciones (`Array.prototype.map` y `Array.prototype.filter`).