# Operativa de la UI

# Rubén Dario entra en la WEB

- Mensaje que le ofrezca la seguridad que necesita
- Formulario:
    - Cantidad de dinero Origen
    - País de destino
- Botón de acción que invite a continuar: A VER CUANTO LES LLEGA

# Mostrar la información del dinero que va a llegar

    - ** Cantidad de dinero destino        AUTO **
        De alguna forma esta info incluye las otras: 
    - Tasa de cambio                    AUTO
    - Comisión                          AUTO

- Botón de acción que invite a continuar: INICIAR EL ENVIO

# Aquí empezamos a pedir datos al usuario

Hay datos que queremos que el usuario siempre tenga delante:
 (Dinero que manda y el que se recibe + 
 En cuanto tenga la oportunidad, el nombre del destinatario)

## Telefono (Tengo que incentivarle un poco)

Que introduzca el telefono y acto seguido, los datos del destinatario

       Nombre:                              |                  |
       Dame tú Telefono:                    |                  |
       ----
       Destinatario:
        Nombre:                             |                  |
        Apellido:                           |                  |
        Número de documento de identidad:   |                  |
        Dirección:                          |                  |
        Teléfono:                           |                  |
        ---
        Te debe haber llegado un código por SMS para validar tu teléfono, ponlo aquí: __________

## Resto de datos del usuario

(Le sigo mostrando los datos del envío)
- Le motivo: Para terminar, dame tus datos personales
- Pido sus datos:
    Apellido:
    Dirección:
    Teléfono:
    Email:
    Contraseña:

- El Documento de Identificación (DNI, NIE...)
  - Si estoy en una computadora, que lo busque en su ordenador
  - Si estoy en un móvil, que lo haga con la cámara (opcionalmente-pequeñito: busca entre mis fotos)

## Finalizar

- Resumen de los datos
- Le pido los que faltan:

    - Forma de pago
      - Tarjeta de crédito
        Datos de la tarjeta
    - Forma de entrega
  Le informo de los plazos de entrega

- Y le pido confirmación, con todos los datos delante

Ni de coña le ponemos al lado del botón ENVIAR un botón CANCELAR

## Por último:

Resguardo y felicitaciones

---

# UI. Aspectos a tener en cuenta

- Dado que estamos en un proceso con varias etapas, debemos ir informando al usuario de en qué etapa estamos dentro del proceso completo.
- Ojo al vocabulario
- Que pueda modificar los datos en cualquier momento
- Ir validando los datos sobre la marcha
- Ya le vamos llevando de la mano... No tiene alternativa. No necesita aprender
- Hay datos que siempre quiero que tenga en pantalla
---

Nos toca comenzar con el diseño de la UI para el proceso de envío de dinero.
(Una vez decidido que voy a enviar el dinero)
Planteo opciones:
- Y comparo:
  - EFECTIVIDAD
  - EFICIENCIA
  - Que cumplen con las cosas que he establecido en el documento de diseño
  - Satisfaction???


---

Una vez hecho esto, lo siguiente sería:
- Maquetar la UI
- Api (API Driven Development)

FRONTAL (Angular) -> http(REST) -> Microservicio C#
                     API (json)
                    v          v
                Frontal     Backend
                                v
                               BBDD

TDD: Test Driven Development



---


Enviar dinero
Actividad (BUSQUEDA / FILTRO: Rastrear transferencia) ---> HOME
Ubicaciones

---
Cuenta
  Destinatarios
Ayuda
Cerrar sesión

---

