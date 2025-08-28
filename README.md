# programacion-2-tp-2-tdd

Ejercicios de Test-Driven Development (TDD)

## 1. Leap Year

### Objetivo
Implementar una función que determine si un año es bisiesto siguiendo la metodología TDD.

### Especificaciones
Un año es bisiesto si cumple las siguientes reglas:
- ✅ **Es divisible por 4** → Es año bisiesto
- ❌ **Es divisible por 100** → NO es año bisiesto  
- ✅ **Es divisible por 400** → Es año bisiesto (excepción a la regla anterior)

### Ejemplos
- `2000` → **Bisiesto** (divisible por 400)
- `1900` → **No bisiesto** (divisible por 100 pero no por 400)
- `2004` → **Bisiesto** (divisible por 4)
- `2001` → **No bisiesto** (no divisible por 4)

### Progresión Sugerida de Tests

#### Paso 1: Caso base
#### Paso 2: Divisible por 4
#### Paso 3: Divisible por 100
#### Paso 4: Divisible por 400
### Implementación Final

### Archivos del Ejercicio
- **Test**: `src/test/java/com/tp2/leapyear/LeapYearTest.java`
- **Implementación**: `src/main/java/com/tp2/leapyear/LeapYear.java`
