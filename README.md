# Sviluppo di un applicazione Laravel con Docker
Ho [scritto un tutorial](https://didatticamillu.blogspot.com/2018/02/sviluppo-laravel-docker.html) sulla creazione di un ambiente di sviluppo per un'applicazione Laravel utilizzando Docker.
In questo repository ci sono i file che ho utilizzato per fare il setup dell'ambienete.

## Esecuzione
Per eseguire in locale l'applicazione d'esempio che ho creato devi svolgere prima i seguenti passi
- Connetti al container app con il comando `docker exec -it app bash`
- Spostati nella cartella blog e copia le impostazioni predefinite `cp .env.example .env`
- Genera delle chiavi di cifratura con il comando `php artisan key:generate`
- Esegui l'intallazione delle dipendenze del progetto con `composer install`

A questo punto dovresti poter visitare la pagina [http://localhost:8080](http://localhost:8080)
