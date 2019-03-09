# Initializarea gitu-lui intr-un proiect nou.

## Pasi necesari:

### Pasul 1
```
Crearea unui nou repositori in Github, care se va lasa gol fara sa il atingi.
```

### Pasul 2 ( Initializare GIT )
```
Navigarea spre ruta proiectului actual in calculator si initializarea GIT.
Acest git local este defapt Source Controlul tau principal pe care il poti utiliza pentru a adauga si commite modificari care ulterior pot fi updatate pe Github, a nu se confunda Git cu Github.
```
```
git init
```

### Pasul 3 ( Adaugarea tuturor fisierelor in Staging )
```
Stating este o pre faza inaintea unui commit, pentru a verifica istoricul fisierelor modificate si nemodificate se tasteaza -git status- acesta va returna in consola o lista de fisiere neadaugate in Staging cu, culoarea rosie si o lista cu verde care le are deja in evidenta cum ca ar fi fost modificate de la ultimul commit facut anterior daca a fost vreodata.
```
```
git add .
``````
Git add este metoda de adaugare in staging a fisierelor locale, acest staging este efectuat doar local nimic nu este atins pe server momentan, punctul dupa add reprezinta toate fisierele, se poate de asemenea scrie si git add 'index.html' pentru a adauga doar un singur fisier.
```

### Pasul 4 ( Comiterea fisierelor adaugate in staging )
```
git commit -m "Modificarea Nav-barului"
```
```
Git commit reprezinta metoda, a se lua in considerare ca doar fisierele adaugate in staging cu git add vor fi comise, '-m' reprezinta un parametru ce specifica ca va urma un mesaj dupa iar acest mesaj este definitia comitului respectiv, spre exemplu avem e implementat un tabel care tine toate motocicletele lui tati, la mesaj vom scrie niste cuvinte cheie care definesc taskul respectiv sau chiar taskul si numarul acestuia.
```

### Pasul 5 ( Adaugarea originii pentru uploadarea fisierelor pe Github )
```
git remote add origin https://github.com/diansebastian23/Florentin.git
```
```
Originea este locatie unde doresti sa faci comitul si updatarea proiectului, acesta origine deseori o regasesti exact dupa ce ai creat repositoriul din Github este afisata mai jos daca dai scroll.
```

### Pasul 6 [ Uploadarea fisierelor de pe calculator (local) pe serverul Github ]
```
git push -u origin master
```
```
Momentan va fi folosita metoda exact asa cum este scrisa nu intram in mai multe detalii pentru a nu te bruia dar ca sa sti ca generalitate Master reprezinta Branch-ul principal, deobicei se face doar 1 singur commit pe Master si dupa se face separat pe alte branch-uri si dupa se face Merge in principal la Master, dar asta doar ca sa stii momentan dam doar upload pe master.
```

### Atat a fost tot :-D 