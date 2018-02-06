# Automatismos/PLC

Proyectos de automatización desarrollados en FUP y KOP.

## Introducción

Este repositorio contiene mi experiencia personal obtenida en automatización industrial y programación de PLC. Me temo que no podré aprovechar este conocimiento con un propósito profesional, y es una lástima haber aprendido para nada. De manera que lo comparto por si a alguien pudiera resultarle de utilidad.

Se trata de un conjunto de 20 proyectos llevados a cabo con 3 tecnologías diferentes:

- Componentes de automatismos (CAD).
- Un PLC LOGO (KOP).
- Un autómata SIMATIC S7-200 (FUP).

Por lo que suman 60 proyectos en total.

## Funcionamiento

A continuación se expone brevemente el funcionamiento de cada proyecto:

- **arranque_motor:** arranque de un motor trifásico mediante pulsador de marcha, circuito biestable y pulsador de paro.

- **arranque_motor_temporizado:** igual que el anterior, pero el motor se apaga tras un tiempo especificado.

- **arranque_motores_cascada:** arranque de varios motores forzando un orden. Si el primero no está funcionando, no se puede encender el segundo; si el segundo no está funcionando, no se puede encender el tercero; etc.

- **arranque_motores_con_paro:** para que funcione uno de los motores, el otro debe estar apagado.

- **arranque_motores_sin_paro:** al encender cualquiera de los dos motores, el otro se apagará de forma automática.

- **cortadora:** se trata de una máquina cortadora (de madera, de metal... o lo que se nos ocurra) que antes de accionar el motor que hace girar la sierra, activa una sirena o alarma durante unos segundos para avisar a los trabajadores de que deben alejarse.

- **elevador:** se trata de un elevador de vehículos para un taller de mecánica. Se eleva o desciende bajo demanda, y se detiene al tocar con el suelo o llegar a su altura máxima.

- **estrella_delta_inversor:** se trata de un arranque Estrella-Delta con inversión de giro.

- **estrella_triangulo:** arranque Estrella-Triángulo de un motor.

- **giro_motor_interruptor_doble_camara:** controla la dirección de giro de un motor con un interruptor de doble cámara.

- **giro_motor_pulsador_doble_camara:** controla la dirección de giro de un motor con pulsadores de doble cámara.

- **grua:** se trata de una grúa de 8 movimientos (2 de elevación, 2 de orientación, 2 de distribución y 2 de traslación).

- **pozo:** se trata de un depósito de agua, un pozo y un motor-bomba. El motor se encarga de extraer agua del pozo y llevarla hasta el depósito, hasta que el primero se seque o el último quede lleno.

- **puerta_automatizada:** puerta eléctrica con sensor. Ej.: puerta automática de un supermercado.

- **puerta_garaje:** puerta eléctrica que detecta a los coches con un sensor. Ej.: parking de un supermercado.

- **puerta_temporizada:** puerta que se abre con un mando a distancia y que tiene un cierre temporizado. Ej.: garaje de una comunidad de vecinos.

> Más proyectos en proceso...

## Edición/Simulación

Para poder editar los proyectos y simularlos serían necesarias las siguientes herramientas de software:

- **CADe Simu:** para los proyectos CAD.
- **LOGO! Soft Comfort:** para los proyectos LOGO.
- **STEP-7 + Simulador S7-200:** para los proyectos del S7-200.

> Se trata de software propietario, de pago y con licencia. Debido a esto, no puedo facilitar enlaces de descarga.
