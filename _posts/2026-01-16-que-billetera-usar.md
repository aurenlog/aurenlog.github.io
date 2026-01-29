---
layout: post
title: "Qué billetera usar al empezar en Bitcoin (y por qué)"
date: 2026-01-16
categories: [bitcoin, principiantes]
excerpt: "Una guía práctica para entender qué es una wallet Bitcoin, la diferencia entre custodia y autocustodia, y cómo elegir una billetera adecuada al empezar."
comments_url: "https://github.com/aurenlog/aurenlog.github.io/issues/2"
---

Al poco tiempo de empezar a acumular sats (fracciones de bitcoin), es normal preguntarse si no necesitas una wallet, es decir, una billetera donde “guardar” tus bitcoin.  
Y aquí aparece la primera confusión importante. Una billetera Bitcoin **no es donde se guardan tus monedas**, porque tus bitcoin no están dentro de ninguna aplicación ni dispositivo:  
están registrados en la cadena de bloques (blockchain).
La wallet es, en realidad, **donde se guardan las claves que te permiten acceder a ellos**.


> **Una wallet no es donde están tus bitcoin, es cómo accedes a ellos.**


Entender esto cambia por completo cómo pensar sobre seguridad y custodia.

## Custodial vs no-custodial (el concepto que lo cambia todo)
En Bitcoin, la diferencia fundamental no es qué app usas, sino **quién controla las claves privadas**. Aquí hay dos modelos muy claros.
1. Custodial.
	Las claves no las tienes tu, las tiene un Exchange (Binance, Kraken), que guarda los bitcoins por tí. Es muy cómodo, solo tienes que recordar el usuario y la contraseña que usas para ingresar al exchange (y preferiblemente una clave de segundo factor de seguridad (2FA)). Funciona como las aplicaciones de los bancos a los que todos estamos acostumbrados. Pero tiene una consecuencia importante: si no tienes las claves, **no tienes control total sobre tus bitcoin**. El exchange puede congelar fondos, limitar retiradas o, en casos extremos, desaparecer.

2. Non-Custodial:
	Tu controlas las claves y además tu eres responsable de las mismas y por lo tanto de todos los bitcoins y nadie puede congelar, censurar o recuperar tus fondos por ti, pero tampoco nadie puede ayudarte a recuperar el acceso si pierdes tus claves. 
	
> La autocustodia no es gratis: **se paga con responsabilidad.**
> Este es el modelo al que apunta Bitcoin, pero no tiene por qué hacerse de golpe.

## Wallets móviles: empezar simple (Nunchuk)
Como primer paso hacia la autocustodia, una wallet móvil puede ser una muy buena opción.  
En mi caso he probado **Nunchuk**, y me parece una herramienta excelente para empezar ([Guía de Lunaticoin de cómo empezar](https://lunaticoin.blog/guias-y-tutoriales/nunchuk-tu-primera-wallet-bitcoin-de-testnet)).
Una wallet móvil:
- es non-custodial
- tiene poca fricción
- permite aprender los conceptos básicos
- es adecuada para cantidades pequeñas o de aprendizaje

Nunchuk, además, pone mucho énfasis en las buenas prácticas y no intenta “ocultar” lo que está pasando por debajo, algo que agradecí desde el principio.
Al crear una wallet, la aplicación te mostrará una serie de palabras (normalmente 24), conocidas como frase semilla o **frase mnemónica** (término más correcto). Estas palabras **no son aleatorias en el sentido cotidiano**, sino el resultado de un proceso matemático que garantiza un nivel de seguridad extremadamente alto.
Opcionalmente, puedes añadir una **passphrase** (a veces llamada “palabra 25”), que añade una capa extra de seguridad y también de complejidad.
**Esas palabras son las claves de acceso a tus bitcoin**, Por eso, no deben compartirse nunca, no deben almacenarse en formato digital (foto, documento de texto tipo word, excel), no deben estar accesibles a simple vista.   
Al principio, anotarlas en una libreta puede ser suficiente. Más adelante, podrás explorar estrategias más avanzadas para mejorar privacidad y resistencia.

> Una wallet móvil no es el destino final, pero sí **un muy buen primer paso**.

## Hardware wallets: cuando el importe ya importa (Krux)
Cuando la cantidad de bitcoin que custodies empiece a ser significativa —por ejemplo, el equivalente a una o dos nóminas/sueldos— probablemente te plantees elevar el nivel de seguridad. Aquí entran en juego las **hardware wallets**.
Aunque el nombre lleve a confusión, no son realmente “billeteras”, sino **dispositivos dedicados a generar y custodiar claves**.
Un dispositivo físico dedicado resuelve varios problemas:
- reduce la superficie de ataque frente a ordenadores o móviles
- aísla las claves de dispositivos conectados a internet
- permite firmar transacciones de forma **offline (air-gapped)**

Hay muchas alternativas comerciales y DIY. [Lunaticoin](https://lunaticoin.blog/podcasts/l277-que-hardware-wallet-bitcoin-comprar-en-2026) ha hecho recientemente un excelente repaso comparando distintas opciones, teniendo en cuenta precio, facilidad de uso y nivel de seguridad.

En mi caso, me atraen los dispositivos **DIY (hazlo tú mismo)**, porque permiten entender mejor qué estás usando y cómo funciona.  Entre opciones como SeedSigner o Krux, me decanté por **Krux**.
[Krux](https://selfcustody.github.io/krux/) puede instalarse en distintos dispositivos. Yo elegí un TZT, instalé el software y, con ayuda de un [tutorial](https://youtu.be/WiwmpO1k2zA?si=-HZt8dO9VMZNJW_A), empecé a usarlo en muy poco tiempo.
No es una solución “plug and play” como otras, pero ofrece:
- mucho control
- un enfoque muy alineado con la filosofía Bitcoin
- una excelente relación entre seguridad y transparencia

Eso sí: **no es mejor por defecto**, es mejor cuando ya sabes qué estás haciendo.

## El camino razonable
Un recorrido posible —no el único— podría ser:
- Exchange → para comprar
- Wallet móvil → para empezar a autocustodiar 
- Hardware wallet → cuando el importe y tu conocimiento lo justifican

A partir de ahí, pueden aparecer nuevos pasos:
- usar Sparrow
- montar un nodo Bitcoin

Pero eso ya es otro capítulo.
> En Bitcoin no se trata de hacerlo perfecto desde el día uno, sino de **mejorar tu posición con el tiempo**.