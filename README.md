# projectTest
test project for git and github

# configure git and github
git --version

se non installato recuperare l'installer dal sito

nella cartella del progetto git init

ls -a per visualizzare i files nascosti (.git verrà visualizzata)

git config --global user.name "otortini"
git config --global user.email "omar.tortini@libero.it"

creare repo su git con licenza e gitignore

creare il connettore tra il git del progetto e github
git remote add origin https://github.com/otortini/projectTest.git

operazione di pull
git pull origin main (main è il nome del branch)

git status (controllo lo stato dei file)
git add . aggiunge tutti i file a git
git add "nome file" specifico il file da aggiungere a git

git commit -m "messaggio"

git ha ora in canna i file da sparare sulla repo di github

operazione di push
git push origin "branch"

prima di push si può resettare quanto caricato in git con
git reset --mixed "branch"

git clone "https://github.com/otortini/projectTest.git"
