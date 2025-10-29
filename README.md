# FoSpub

REPO IST PUBLIC; KEINE PERSÖHNLICHEN INFOS HIER COMITTEN

bitte git in RStudio einrichten;
https://youtu.be/1o25vy91Jx4?si=chcybAKpiqBVJVRy

*wichtig: File/New Project/ Existing Dir. auswählen(lieber nicht Desktop)
* Git installieren über die webseite
* checken ob RStudio git erkennt unter Rstudio Terminal >>which git<<
* Tools/Global Options/Git/SVN  git da aktivieren und Git exe dir muss das von which git sein 
* Github Konto online erstellen 
* unter Terminal nicht Console in RStudio(links unten) 
        git config --global user.name= "vorname" 
        git config --global user.email="@mail.de" (lieber das von GitHub)
        git config --global core.filemode false
        git config --global init.defaultBranch=main

* kurz die configs checken mit $ git config --global --list
* SSH key einrichten s. Video
* Console; 
>install.packages("usethis")
>library("usethis")
>setwd("Project Pfad oben")
>usethis::create_from_github("https://github.com/JonnyTtest/FoSpub")
* das müsste jetzt github project clonen als Project öffnen

# usage
* oben rechts wird "Git angezeigt"
* mit "Pull" aktualisieren
* sonst rechts unten files bearbeiten, speichern(wichtig), 
dann unter Git file auswählen und "Commit"en, hier noch nicht fertig;
"Close";Commit message(klar); "Commit"; "Close"; "Push"

ohne "Push" wird commit nicht gesendet
weiß ist bischen abfuck, aber lohnt sich, trust