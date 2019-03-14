# HelloIngegneria
Versioning di benvenuto al corso di ingegneria informatica.

Come procedere per dare il proprio saluto

-Registrare un'account su github usufruendo dei vantaggi volti agli studenti
-Scaricare ed installare github desktop ed accedere con le proprie credenziali
-All'apertura di github desktop per aggiungere la Repository "HelloIngegneria" è sufficente cliccare sul pulsante "clone a Repository " e inserire l'url della repository:  https://github.com/ClaudioSirocchi/HelloIngegneria;
fatto ciò verrà creata una copia locale sulla quale lavorare;

Dopo aver configurato git hub desktop è necessario configurare l'add-on di EGit  scaricabile dal marketplace di Eclipse :  http://marketplace.eclipse.org/content/egit-git-integration-eclipse

Una volta che abbiamo installato EGit basta creare un nuovo progetto Java e chiamarlo HelloIngegneria.

Per mettere in relazione il nostro progetto con la repository:
- Nella sezione Package Explorer fare clic col pulsante destro sulla directory del proggetto che si vuole legare alla nostra repository;
-Sul menu a tendina spostarsi sulla voce Team e selezionare la voce "Share Project"
-Sulla finestra che si apre cliccare sul pulsante  "Create..."; si aprirà un'altra finestra dove cliccando su "Browse..." dove dovremmo andare a selezionare la cartella della Repository che ci siamo copiati sul nostro PC poi confermare e di nuovo confermare.

A questo punto sul menu a tendina alla voce Team Saranno comparse numerose funzioni, basta modificare il programma scrivendo il proprio nome e poi fare commit sulla Repository locale e successivamente in quella online nel seguente modo:

-Recarsi sul menu a tendina alla voce team
-Selezionare l'operazione di commit
-Nel menu che compare nella parte inferiore di Eclipse spostare i file modificati dalla sezione "Unstaged Changes" alla sezione "Staged Changes" e infine un messaggio nella TextBox "Commit Message" dove esplicitare le modifiche apportate.
-Cliccare sul pulsante Commit in basso a destra.

Dopo aver fatto il commit basterà aprire GitHub Desktop e cliccare sulla voce "PushOrigin" nel menu in alto a destra.

Fatto ciò avrete Caricato la vostra versione di HelloIngegneria nella repository online.

