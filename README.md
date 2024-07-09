# MeteoTrento
Abbiamo scelto la traccia numero 2 che chiedeva

Di sviluppare un’applicazione web in grado di visuallizzare il bollettino meteo della provincia di Trento:
- Leggere il servizio REST JSON messo a disposizione dalla regione Trentino Alto Adige;

- Visualizzare i dati in una interfaccia web (sfruttando anche immagini fornite dal servizio nell’interfaccia grafica)

- Creare un WS SOAP che faccia da «convertitore», convertendo servizio REST JSON in uno SOAP, e permetta di ricercare il meteo per uno specifico giorno

- Far funzionare l’applicativo in un container # Docker

Composizione del gruppo : Francesco Caldarelli (118393) e Giovanni Luongo (118863)

Per far partire il programma :
1) Avvia docker desktop
2) Crea una build dal docker file
3) Ora fai docker run -p 8080:80 nome-immagine
4) Nel browser ora digita localhost/home
