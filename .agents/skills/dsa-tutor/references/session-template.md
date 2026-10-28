# Plantilla de README de problema

Estructura canónica para `problems/<platform>/<slug>/README.md`, tomada de los
problemas ya resueltos (por ejemplo `problems/leetcode/0001-two-sum/README.md`).

```markdown
# <Nombre del problema>

## Fuente
<LeetCode (Problema N) | HackerRank | Practice>

## Dificultad
<Easy | Medium | Hard>

## Problema
<Enunciado en palabras propias. Qué entra y qué sale.>

## Ejemplo
Input:
```text
<entrada>
```

Output:
```text
<salida>
```
*(Explicación breve del resultado)*

## Qué entendí
<Qué pide realmente el problema; reformulación propia.>

## Mi razonamiento inicial
<Ruta de pensamiento: hipótesis, intentos fallidos, correcciones del mentor.>

## Qué necesito recordar
<Estado/memoria mental requerida durante el recorrido.>

## Estructura o patrón elegido
<Estructura o patrón y su técnica concreta.>

## ¿Por qué?
<Justificación basada en las operaciones requeridas.>

## Pseudocódigo
```text
<pseudocódigo en español>
```

## Errores que cometí
- <Error y la corrección>

## Solución
- [solution.ts](solution.ts) (TypeScript)
- [solution.py](solution.py) (Python)

## Complejidad
### Tiempo
$O(...)$ — <justificación>

### Espacio
$O(...)$ — <justificación>

## Qué aprendí
<Concepto transferible.>

## Reconocimiento futuro
<Señal para reconocer este patrón en el futuro.>
```

## Extras opcionales

- `<slug>-explicacion-sencilla.md`: explicación con dibujos y analogías para
  reforzar el modelo mental (ver `docs/patterns/two-pointers.md` como estilo).
- Actualizar en `README.md`: fila de "Problemas Resueltos" y "Learning Progress".
- Actualizar en `docs/learning-roadmap.md`: tabla "Estado Actual en el Repositorio".
