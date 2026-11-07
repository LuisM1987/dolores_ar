# Dolores AR (Flutter + TDD)

App turística con **realidad aumentada por ubicación** para visitar Dolores Hidalgo: GPS + brújula + cámara,
trigonometría (Haversine, rumbo, campo de visión), modo demo sin GPS, pasaporte turístico con sellos y
un modelo 3D en realidad aumentada de superficie.

Práctica de **Desarrollo Móvil Integral · UTNG** (Manual paso a paso con TDD · Prof. Anastacio Rodríguez García).

- **Alumno:** Luis Manuel Arteaga Cruz
- **Número de control:** 1225100281
- **Grupo / Fecha:** GTID241


## Cómo ejecutar

```bash
flutter pub get
flutter test --reporter expanded     # pruebas automatizadas
flutter run                          # teléfono real (cámara, GPS y brújula)
flutter run -d chrome                # PC: usar el "Modo demo"
```


