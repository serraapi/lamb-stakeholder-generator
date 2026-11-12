<p align="center">
  <img src="icona_generador.svg" width="110" alt="Logotip del Generador de Clients">
</p>

<h1 align="center">LAMB Client Generator</h1>

<p align="center">Clients simulats perquè l'alumnat practiqui entrevistes d'extracció de requisits</p>

---

Eina web estàtica (un sol fitxer HTML) per a assignatures universitàries de **Gestió de Projectes**. Permet configurar i generar clients simulats (*stakeholders*) amb qui l'alumnat practica entrevistes d'extracció de requisits i l'elaboració del Project Charter.

No cal instal·lar res: n'hi ha prou d'obrir el fitxer HTML en un navegador.

### Característiques principals

* **Integració amb LAMB:** exporta i importa els clients en format `.json`, llestos per desplegar com a assistents de LAMB.
* **Compatibilitat amb altres LLM:** permet copiar el prompt de sistema per fer-lo servir, per exemple, en Gemini Gems o ChatGPT.
* **Organització per pestanyes i fitxa del client:** l'editor es divideix en Projecte, Client, Comportament i Reunió, i una fitxa fixa mostra en viu tota la configuració i els botons d'exportar.
* **Cas configurable:** informació oberta que coneix l'alumne i informació oculta que el client només revela si l'alumne hi pregunta.
* **Perfil conductual en sis eixos:** experiència (E1), priorització econòmica, legal o ètica (E2), poder de decisió (E3), estil comunicatiu DISC (E4), gestió de la informació (E5) i perspectiva de gènere (E6, opcional). Els nivells d'E1, E4 i E5 inclouen marcadors observables perquè la personalitat es noti a la conversa.
* **Mode dinàmic:** cada conversa nova sorteja un perfil diferent amb els eixos que es deixin en «Aleatori». El sorteig es fa amb una llavor de dígits i es manté durant tota la conversa; en 100 converses de prova, cap eix no ha sortit esbiaixat. També es poden combinar eixos fixos i aleatoris.
* **Identitat aleatòria:** nom, càrrec i àrea funcional del client diferents a cada conversa.
* **Tancament de la reunió per torns:** el client compta els missatges, avisa quan li queda poc temps, fa un resum, demana confirmació i s'acomiada. Es pot desactivar o ajustar.
* **Mode avançat:** permet editar els textos de cada eix i nivell (conducta, marcadors i guia de maneig) i canviar el codi que activa l'avaluació.
* **Mode avaluació:** quan l'alumne escriu el codi d'avaluació («Code 42» per defecte), el client surt del rol i avalua l'entrevista amb una rúbrica de 9 criteris (nota sobre 100), els punts forts i febles, i una explicació del client que li ha tocat i com tractar-lo.
* **Interfície en català, castellà i anglès,** amb tema clar i fosc.

### Com es fa servir

1. Obre el fitxer HTML del generador en un navegador.
2. A **Projecte**, escriu l'empresa i el cas: la informació oberta i la informació oculta (una línia per requisit).
3. A **Client** i **Comportament**, defineix qui és el client i com es comporta, o activa el **mode dinàmic** perquè canviï a cada conversa.
4. A **Reunió**, tria l'idioma i la durada de la reunió.
5. Comprova la **fitxa del client** i descarrega el `.json`.
6. Importa el `.json` a LAMB com a assistent nou.
7. Explica a l'alumnat que, en acabar l'entrevista, ha d'escriure el codi d'avaluació per veure el resultat.
