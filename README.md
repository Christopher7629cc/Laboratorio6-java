# Laboratorio #6 — Estructuras de Control en Java

**Materia:** Desarrollo Web  
**Profesor:** @SarmientoEdu  
**Módulo:** 3 — Estructuras de Control  

---

## Para el estudiante

Lee el documento completo del laboratorio antes de empezar.

### Resumen rápido del flujo

```bash
# 1. Fork este repositorio en GitHub (botón Fork)
# 2. Habilita Actions en tu fork (pestaña Actions)
# 3. Clona tu fork
git clone https://github.com/TU-USUARIO/Laboratorio6-java.git
cd Laboratorio6-java

# 4. Crea tu rama (formato obligatorio)
git checkout -b lab6-apellido-nombre

# 5. Completa los ejercicios en src/
# 6. Por cada ejercicio: captura + commit
git add src/EjercicioX.java imagenes/ejX_resultado.png
git commit -m "ejX: descripción breve"

# 7. Push
git push origin lab6-apellido-nombre

# 8. Abre un Pull Request hacia SarmientoEdu/Laboratorio6-java
```

### Estructura

```
src/
├── Ejercicio1.java  — if/else if/else (20 pts)
├── Ejercicio2.java  — switch          (20 pts)
├── Ejercicio3.java  — while           (15 pts)
├── Ejercicio4.java  — do-while        (15 pts)
└── Ejercicio5.java  — for + try/catch (30 pts)
imagenes/            — capturas de pantalla (1 por ejercicio)
```

### Autograde

El autograde se ejecuta automáticamente al hacer push o abrir un PR.  
Ve a la pestaña **Actions** → job `autograde` → **Summary** para ver tu nota.

---

> **NO modificar** `autograde.java` ni `.github/workflows/autograde.yml`.
