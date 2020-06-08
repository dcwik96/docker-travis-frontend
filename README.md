## Aplikacja frontend+Travis (Docker)
### Funkcjonalność
Prezentacja hot reload pomocne przy rozwijaniu aplikacji oraz wykorzystanie TravisCI 
### Co nowego
1. Dockerfile.dev Dockerfile.prod
Stworzenie dwóch osobnych Dockerfile dostosowanych odpowiednio do rozwoju aplikacji oraz produkcyjnego wydania.
2. Volumes
Pozwalają przechowywać dane nie w kontenerze a poza nim. Zmniejsza to rozmiar kontenerów oraz pozwala na zachowanie danych po zatrzymaniu ich pracy
3. TravisCI
Narzędzie do CI. Plik .travis.yml
