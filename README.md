# conversion-moneda

Descripción
---
Proyecto en Python para convertir monedas. Es la solución final de una práctica donde se analizó una problemática de una empresa ficticia y se implementó la lógica de conversión.

Características
---
- Conversión entre monedas (ej.: USD ⇄ ARS).
- Entrada por consola (o posibilidad de integrarlo en una función para usar en otros scripts).
- Código simple y comentado para fines didácticos.

Requisitos
---
- Python 3.8+ (recomendado)
- Dependencias listadas en `requirements.txt` (si no hay dependencias externas, no hace falta).

Cómo ejecutar
---
1. Clonar el repo:
   ```
   git clone https://github.com/bautimeling-svg/conversion-moneda.py.git
   cd conversion-moneda.py
   ```
2. Ejecutar el script (ajustá el nombre si el archivo principal tiene otro nombre):
   ```
   python conversion-moneda.py
   ```
3. Seguir las instrucciones en consola (ingresar monto y moneda origen/destino).

Ejemplo de uso
---
- Entrada:
  - Monto: 100
  - Origen: USD
  - Destino: ARS
- Salida:
  - 100 USD = 35000 ARS (ejemplo)

Notas
---
- Si usás APIs en tiempo real (p. ej. tasas), agregá instrucciones para obtener la API key.
- Para producción, considerá manejar errores, validaciones y tests.

Mejoras sugeridas
---
- Añadir un archivo `requirements.txt`.
- Incluir tests unitarios básicos (pytest).
- Crear una versión con interfaz simple (Streamlit) para demo.
- Renombrar el repo para quitar la extensión `.py` (p. ej. `conversion-moneda`).

Licencia
---
Si querés permitir reutilización, podés agregar un `LICENSE` (ej. MIT).
