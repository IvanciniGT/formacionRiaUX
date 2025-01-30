
# UX/Usabilidad/UI

## UX

Tiene ver con cómo un usuario percibe la interacción con nuestro producto / servicio = ALGO TOTALMENTE SUBJETIVO

Peter Morville analiza el tema de la UX en su libro "Ambient Findability" y lo representa con un diagrama que se llama "Honeycomb of User Experience" (panal de abejas de la experiencia del usuario). Determina que hay 7 factores que influyen en la UX:

- **Useful**: ¿Es útil para el usuario?
- **Usable**: ¿Es fácil de usar?            <- USABILIDAD
- **Desirable**: ¿Es atractivo?
- **Findable**: ¿Es fácil de encontrar?
- **Accessible**: ¿Es accesible?
- **Credible**: ¿Es creíble?
- **Valuable**: ¿Aporta valor a usuario/negocio?

## Usabilidad

Es un concepto definido por una norma ISO.
Es la capacidad de un producto / servicio de ser usado por un usuario para alcanzar un objetivo específico de manera eficaz, eficiente y satisfactoria:
- Eficaz: ¿Se logra el objetivo?                                        <- Podemos trabajar mucho (REQUISITOS / Casos de uso)
- Eficiente: ¿Se logra el objetivo en el menor tiempo posible?          <- Podemos trabajar mucho (Facilidad / Tiempo)
- Satisfactorio: ¿El usuario está contento con el proceso?              <- Este es más complejo de trabajar (subjetivo)

## UI

La UI al final es lo que usa el usuario para interactuar con el producto / servicio. Es la parte visible y tangible de la UX.
DEBE REFORZAR todos los conceptos de UX.

### Principios de Jakob Nielsen (Usabilidad)

Jakob Nielsen es un experto en usabilidad y tiene 10 principios que se deben seguir para tener una buena usabilidad:

#### 1. Visibilidad del estado del sistema

El sistema en todo momento debe informar al usuario de lo que está pasando. Si el sistema está procesando algo, debe informar al usuario de ello.
- Mensajes de confirmación
- Un botón se debe deshabilitar si no se puede usar
- Un botón se debe deshabilitar si acaba de ser pulsado y estoy esperando respuesta... y mostrarme una ruedita girando..

#### 2. Coincidencia entre el sistema y el mundo real

Los elementos de la UI (lenguaje, iconos, etc.) deben ser familiares para el usuario. Deben seguir las convenciones del mundo real.

Mucho cuidado con el vocabulario que usamos en la UI. Si usamos un vocabulario técnico, el usuario no lo va a entender.

#### 3. Control y libertad del usuario

El usuario debe poder rehacer una acción si se ha equivocado. Debe poder deshacer una acción.
Debe poder investigar y explorar el sistema sin miedo a romperlo.

#### 4. Consistencia y estándares

El aspecto visual, el lenguaje, la forma de interactuar, etc. deben ser consistentes a lo largo de todo el sistema.
Y además, consistente con otros sistemas a los que el usuario esté acostumbrado.

#### 5. Prevención de errores

El sistema debe ser capaz de prevenir errores. 
Por ejemplo, en un formulario, quiero ir ayudando al usuario a rellenarlo correctamente, ofreciendo información en tiempo real...
No esperar a que acabe de rellenar el formulario para decirle que se ha equivocado.

#### 6. Reconocimiento en lugar de memorización

Un sistema intuitivo es aquel en el que el usuario no tiene que memorizar cosas.

#### 7. Flexibilidad y eficiencia de uso

EFICACIA: Es que el usuario consiga hacer lo que quiere hacer.
EFICIENCIA:  Es que lo haga en el menor tiempo posible y cometiendo el menor número de errores.

Diseñar el sistema tanto para usuarios avanzados como para usuarios novatos.

#### 8. Diseño estético y minimalista

El diseño debe ser atractivo y no debe tener elementos innecesarios.

#### 9. Ayuda a los usuarios a reconocer, diagnosticar y recuperarse de errores

-> Tu usuario de github está ocupado... pero puedes usar en su lugar estos otros.
-> Las fechas de tu hotel están ocupadas... pero puedes usar estas otras.
-> No puedes mandar tanto dinero en una única transacción... La cantidad máxima es de 1000€

#### 10. Ayuda y documentación

La mínima ayuda y documentación posible. El sistema debe ser lo suficientemente intuitivo como para no necesitar ayuda.
Simplemente quizás necesito un campo (i) al lado de un campo para explicar qué es lo que se espera en ese campo.









                QUIEN ESTA EN CONTACTO CON NEGOCIO 
                    vvv
    Usuario  <  Business Analyst  <  UI
                    v    ^
                Personal de UX    <  Desarrollo
                                  <  QA

---

# UX - Usabilidad - UI

UX: 7 Factores:
- Useful
- Usable
- Desirable
- Findable
- Accessible
- Credible
- Valuable

Usabilidad: ISO
- Eficaz
- Eficiente
- Satisfactorio

Principios de Jakob Nielsen:
- Visibilidad del estado del sistema
- Coincidencia entre el sistema y el mundo real
- Control y libertad del usuario
- Consistencia y estándares
- Prevención de errores
- Reconocimiento en lugar de memorización
- Flexibilidad y eficiencia de uso
- Diseño estético y minimalista
- Ayuda a los usuarios a reconocer, diagnosticar y recuperarse de errores
- Ayuda y documentación


---


Tabla con REGISTROS:
- Datos identificativos del registro                                        <<<<< SIEMPRE DEBE IR
- Otros datos de interés para el usuario
  - Filtros para acceder al detalle (datos en los que se basa el usuario para decidir entrar o no al detalle)   <<<<< SIEMPRE DEBE IR
  - Datos adicionales de interés para el usuario       (Si son pocos y aportan valor y evitan al usuario acceder al detalle) <<< LOS PONGO

  - Hay unos cuantos datos que para el usuario pueden ser SUFICIENTES para evitar acceder al detalle:
    - Si hay más de la cuenta, le puedo poner una flechita a la derecha  (V ver más)

Todos esos datos, los debo traer con el resultado de la query (JSON)

ESCENARIOS DE USO:
- No es lo mismo una tabla (LISTADO) donde vaya a intentar buscar un dato para acceder a él
- Que una tabla (LISTADO) donde estoy monitorizando registros a la caza de un evento

HAY VECES que ya que la tabla responde a DISTINTOS CASOS DE USO lo que hago es montar distintas tablas, atendiendo a cada caso de uso.


Depende de a lo que esté orientando el sistema:
- Muchas veces hacemos un sistema orientado a ENTIDADES (Hago un reflejo de la BBDD en la pantalla)
      MENU:
        ENVIOS
        PERSONAS
        UBICACIONES
        ... 
- Otras veces diseño un sistema en base a CASOS DE USO (Hago un reflejo de los procesos de negocio en la pantalla)
      MENU:
        CONSULTAR ENVIOS CON INCIDENCIAS
        CONSULTAR ENVIOS PENDIENTES DE TRAMITAR

---

