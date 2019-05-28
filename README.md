# SpeechAPI
SpeechRecognition for javascript environement.

----------------------------------
# Exemple:
```js
var speech = new SpeechAPI({});
speech.start(function(result){
  zone_de_texte.value = result;
});
```
----------------------------------
# How to use:
```js
var speech = new SpeechAPI({
  //json
  interimResult: true;
  continuous: true;
  //...
});

speech.started //Renvoie si la vocale est lancée ou non
speech.status //Renvoie si la vocale est valide ou non
speech.permanent //Retourne le résultat
speech.speech //Retourne la vocale elle même
```
