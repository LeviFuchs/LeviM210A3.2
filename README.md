# LeviM210A3.2
Um ein Dockerfile zu builden, wird dieser befehl gebraucht:
docker build -f Dockerfile.web -t meine-nginx-webseite:latest .

Im Befehl steht -f Dockerfile.web dieser ist nur nötig, wenn das Docker-File .web im Namen hat ansonsten wird das weggelassen.

Um das Docker zu runnen ist dieser Befehl zu verwenden:
docker run --name some-nginx -d -p 8080:80 meine-nginx-webseite:latest

wichtig ist das der gleiche Tag wie im erstem build befehl zu verwenden.