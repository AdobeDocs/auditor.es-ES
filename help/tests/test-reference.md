---
description: Esta referencia proporciona más información sobre las pruebas que realiza Adobe Experience Platform Auditor.
seo-description: This reference provides more information about the tests Adobe Experience Platform Auditor performs.
seo-title: Test reference
title: Referencia de prueba
uuid: f1d0769e-a2bd-4cec-acd1-146793644895
exl-id: b368bf43-2007-4f98-a965-ed8fc07c0fdf
source-git-commit: 286a857b2ff08345499edca2e0eb6b35ecf02332
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 100%

---

# Referencia de prueba{#test-reference}

Esta referencia proporciona más información sobre las pruebas que realiza Adobe Experience Platform Auditor.

**Versión de criterios de prueba actuales:** 1.0.5

Cada prueba tiene una ponderación. La puntuación de la prueba es igual a la ponderación asignada. Si supera una prueba con una ponderación de cinco puntos, recibirá cinco puntos.

* 0: Advierte de problemas que debe tener en cuenta pero que no afectan a la puntuación.
* 1: Recomienda una optimización. No afecta a la precisión de los datos.
* 2: Si no realiza esta prueba, no tendrá acceso a las últimas funciones y correcciones de Experience Cloud.
* 3: Prueba de la eficacia y si la implementación cumple las prácticas recomendadas.
* 4: En caso de error, es posible que esté recopilando datos poco fiables.
* 5: Error en el que se podrían perder datos.

Las pruebas se superan o no. Comprueban el cumplimiento o el incumplimiento de las condiciones de prueba, por lo que no hay puntuaciones parciales para el cumplimiento parcial. Por ejemplo, si la prueba comprueba la última versión de una solución de Adobe y solo está una versión por detrás, obtendrá la misma puntuación que si estuviera cinco versiones por detrás. Las últimas versiones incluyen mejoras de rendimiento y corrección de errores, por lo que se recomienda utilizar la última versión.

Se **recomienda especialmente** corregir cualquier resultado de los niveles 4 o 5.

Se **recomienda** corregir cualquier resultado de los niveles 1 a 3.

## ¿Qué tecnologías de Adobe clasifica Platform Auditor?  {#section-52833b71c05448aaae508e6070a387f5}

* Advertising Cloud DSP
* Advertising Cloud Search
* Analytics
* DTM
* Servicio de Experience Cloud ID (anteriormente, servicio de Marketing Cloud ID)
* Target

Actualmente, las siguientes soluciones de Adobe no están incluidas en las pruebas de implementación. Se prevé ofrecer soporte para estas soluciones en futuras actualizaciones.

* Advertising Cloud Creative
* Audience Manager
* Campaign
* Adobe Experience Platform Launch
