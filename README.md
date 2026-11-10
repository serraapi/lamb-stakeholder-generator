# LAMB Client Generator

Eina web estàtica (un sol fitxer HTML) per a assignatures universitàries de **Gestió de Projectes**. Permet configurar i generar clients simulats (*stakeholders*) amb qui l'alumnat practica entrevistes d'extracció de requisits i l'elaboració del Project Charter.

### Característiques principals

* **Integració amb LAMB:** exporta i importa els clients en format `.json`, llestos per desplegar com a assistents de LAMB.
* **Compatibilitat amb altres LLM:** permet copiar el prompt de sistema per fer-lo servir, per exemple, en Gemini Gems o ChatGPT.
* **Cas configurable:** informació oberta que coneix l'alumne i informació oculta que només revela el client si l'alumne hi pregunta.
* **Perfil conductual en sis eixos:** experiència (E1), priorització econòmica, legal o ètica (E2), poder de decisió (E3), estil comunicatiu DISC (E4), gestió de la informació (E5) i perspectiva de gènere (E6, opcional). Els nivells d'E1, E4 i E5 inclouen marcadors observables perquè la personalitat es noti a la conversa.
* **Mode dinàmic:** cada conversa nova sorteja un perfil diferent, amb els eixos que es deixin en «Aleatori». El sorteig es fa amb una llavor de dígits i es manté durant tota la conversa; en 100 converses de prova, cap eix no ha sortit esbiaixat. També es poden combinar eixos fixos i aleatoris.
* **Identitat aleatòria:** nom, càrrec i àrea funcional del client diferents a cada conversa.
* **Mode avançat:** permet editar els textos de cada eix i nivell (conducta, marcadors i guia de maneig).
* **Mode avaluació:** quan l'alumne escriu «Code 42», el client surt del rol i avalua l'entrevista amb una rúbrica de 9 criteris (nota sobre 100), els punts forts i febles, i una explicació del client que li ha tocat i com tractar-lo.
* **Interfície en català, castellà i anglès.**
