# ComposeZad1
Laboratorium 6 Docker Compose
Jakub Winsyk

# Jak zacząć

Należy zacząć od pobrania mojego repozytorium do wybranego przez siebie folderu za pomocą komendy:
```
git clone https://github.com/kysniw/ComposeZad1.git
```

Następnie przechodzimy do folderu kysniw_docker_compose:
```
cd ComposeZad1/kysniw_docker_compose
```

# Przygotowanie przeglądarki
Aby udało się uruchomić usługę należy na naszej przeglądarce odblokować port 6666:

  Dla Mozilli Firefox:
  W polu wpisywania adresu www wpisać:

  `about:config`

  W polu wyszukiwania preferencji wpisać:

  `network.security.ports.banned.override`

  A następnie dodać zmienną typu *String* i nazwać:

  `6666`


  Dla Google Chrome:
  Można odpalić przeglądarkę z poziomu terminala razem z parametrem:

  `--explicitly-allowed-ports=6666`

# Uruchomienie
Teraz z poziomu folderu docker_kysniw_compose należy wpisać w terminalu komendę:
```
docker-compose up
```

Następnie w przeglądarce w polu wpisywania adresów www wpisać:

`localhost:6666`
