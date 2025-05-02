# UXBlueprints

**Catálogo de patrones de experiencia de usuario aplicados a SwiftUI.**

`UXBlueprints` recopila patrones de interfaz nativa usados en aplicaciones reales. Sirve como referencia práctica y técnica para construir experiencias consistentes, accesibles y modernas.

---

## Propósito

- Estandarizar decisiones de experiencia de usuario.
- Servir como biblioteca de referencia para nuevos módulos.
- Definir patrones reproducibles en SwiftUI.

---

## Contenido

- Composición de pantallas comunes (onboarding, formularios, listas).
- Patrones de feedback visual y accesibilidad.
- Casos de navegación y adaptabilidad responsiva.
- Integración de diseño sistemático con `InterfaceKit`.

---

## Pruebas

| Componente     | Tipo de prueba         |
|----------------|------------------------|
| Vistas         | Snapshot + lógica UI   |
| Accesibilidad  | XCTest UI              |
| Interacciones  | Unitarias              |

---

## Integración

`UXBlueprints` es accesible desde `ProductSuiteApp`. Puede ser utilizado como patrón base para otros módulos que requieran consistencia en la experiencia visual.

---

## Requisitos

- iOS 15+
- Swift 6
- Swift Package Manager

---

## Licencia

MIT © Matías Adrián Molina
