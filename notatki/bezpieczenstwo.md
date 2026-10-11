- dlaczego w repozytorium nie wolno zapisywać haseł ani kluczy dostępu i dlaczego samo usunięcie pliku z hasłem nie wystarcza?
Zadaniem repozytorium jest kontrola wersji kodu i innego typu plikow. Wrzucenie hasla czesto podowuje ze zostaje ono rozpowszechnione po wielu systemacgh CI/CD oraz zapisane w historii wersji (commit) nawet po usunieciu.
