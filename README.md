# Proyecto para practicar

Este es un proyecto de Vanilla TypeScript en Vite, para trabajar los ejercicios del curso sobre Principios SOLID y CleanCode.

Clonar o descargar el proyecto y luego:

```
yarn install
ó
npm install
```

Para ejecutar el proyecto, simplemente ejecuten
```
yarn dev
ó
npm run dev
```

---

# Apuntes del curso

## Clean Code y Deuda técnica

### 1. **¿Qué es la deuda técnica?**
* Es la falta de calidad en nuestro codigo, o falta de calidad en algún proceso del desarrollo de software que genera mayores costos económicos del proyecto.
Con mayores costos nos referimos a:
    * Tiempo en realizar mantenimientos del codigo del proyecto
    * Tiempo en refactorizar
    * Tiempo en comprender el código
    * Tiempo adicional en tranferir el proyecto a otra persona (si así lo necesitamos, por ejemplo: que una nueva persona se incorpore al equipo, una renuncia, etc.)
* Todo proyecto de software tiene deuda técnica
* Ejemplos de deuda técnica:
    * No hacer testing
    * No actualizar dependencias del proyecto
    * Falta documentación 
¿Cómo se paga la deuda técnica?
Por lo general se paga haciendo un refactor del código

### Tipos de deuda técnica
* **Deuda Imprudente**
Concientes de que estamos cayendo en deuda tecnica pero sin la intención de pagarla en el futuro -> "No hay tiempo, solo copia y pega eso"
* **Deuda Inadvertida**
Cuando no sabemos que estamos cometiendo deuda tecnica. Es mas peligrosa de todas
Usualmente cometida por juniors o falsos seniors -> "Que es un patron de diseño?"
* **Deuda Prudente**
Cuando estamos concientes que estamos cometiendo deuda tecnica pero nos comprometemos a saldar dicha deuda lo mas antes posible
* **Deuda Involuntaria**
Cuando a mitad del proyecto ya en desarrollo nos damos cuenta que la arquitectura, el patron de diseño, el framework, etc que elegimos no es el mejor para el proyecto -> Ahora sabemos como hacerlo

### ¿Como se paga una deuda tecnica?
**REFACTORIZACIÓN**
Proceso que tiene como objetivo mejorar el codigo sin alterar su comportamiento para que sea mas entendible y tolerante a cambios.

* Al hacer refactor es imprescindible contar con test autoamtizados.
* **"Si funciona, no lo toques"**
* La mala calidad del software siempre lo termina pagando alguien: el cliente, la empresa, nosotros mismos.

### 2. **¿Qué es clean code?**
En pocas palabras escribir el nombre de variables, funciones, clases, etc., de manera clara y significativa.

- 

