# SecurityKit

Framework modular de seguridad para aplicaciones iOS.  
Provee abstracciones para proteger datos, validar integridad del entorno y aplicar criptografía moderna.

---

## Propósito

Implementar buenas prácticas de seguridad en aplicaciones nativas sin comprometer la experiencia de usuario.

---

## Contenido

- Encriptación simétrica/asimétrica con CryptoKit
- Almacenamiento seguro con Keychain
- Autenticación biométrica (Face ID / Touch ID)
- Validación de entornos inseguros (debugger, jailbreak)
- Manejo seguro de credenciales y tokens

---

## Ejemplo

```swift
let password = "1234"
try KeychainHelper.shared.store("user_password", value: password)
```

---

## Integración

Importá `SecurityKit` en cualquier capa del sistema que requiera protección de datos o autenticación segura.
