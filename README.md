![logo](https://user-images.githubusercontent.com/70900361/122216683-524b4880-ceb5-11eb-90e4-8ab4f59fa2d7.png)




# Suvepraktika teemal "Pakikulude optimeerimine: Parimautomaat"

![Image of our page](https://github.com/stellamarii/suvepraktika/blob/main/GitHubImages/main.png?raw=true)

### Eesmärk ja lühikirjeldus

Tallinna Ülikooli Digitehnoloogia instituudi tarkvara projekti kursuse raames oli meie eesmärgiks luua veebileht, mis laseks inimesel saata pakke pakiautomaatidega nii odavalt kui võimalik. Suvepraktika perioodil tegime veebilehe nimega Parimautomaat, mis laseb kasutajal sisestada paki mõõdud, kaalu, alg- ja lõppasukoha, ning nende järgi arvutab meie süsteem odavaima transpordifirma, millega seda pakki saata. Süsteem töötab muutes sisestatud aadressid koordinaatideks. Seejärel võtab andmebaasist pakiautomaatide koordinaadid ja arvutab nende vahemaad kasutaja sisestatud aadressidest (mis on kordinaatideks muudetud). Tulemused annab süsteem välja tulemuste lehel, kus on näidatud iga transpordifirma odavaimat viisi saata nimetatud pakki.

### Kasutatud tarkvara ja versioonid

•Opencagedata Geocoding API

•PHP v.7.4.20

•MySql v.15.1

•Html v.5

•Javascript v.puudub

•Css v.3

•Ajax v.puudub

### Projekti panustajad
Marcus-Indrek Simmer, 
Stella-Marii Tamme, 
Margen Peterson, 
Margarita Zahharova

### Paigaldusjuhised
Et lehte paigaldada enda lehele, soovitame me esiteks alustada andmebaasi koostamisega. Dpd.sql, itella.sql, omniva_machines.sql, pakid.sql ja accounts.sql leiab rootis asuvast kaustast nimega "ToDatabase".

Andmebaasi saab koostada kahe viisiga.
1) Importi dpd.sql, itella.sql, omniva_machines.sql, pakid.sql ja accounts.sql phpMyAdminiga andmebaasi.
2) Ava iga fail ja kopeeri igas failis olevad "CREATE TABLE..., INSERT INTO...., ALTER TABLE...," MySql-i selles järjekorras kuidas need faili on kirjutatud, ning üksaaval.

Järgmiseks tuleb laadida kõik projekti failid serverisse või arvutisse, mis toetab kõiki kasutatud tarkvarasid. Et enda andmebaase kasutada, tuleb muuta $database = "if20_marcus_praktika" mõnedes .php failides enda andmebaasiks. Turvalisuse huvides, tuleb teil teha enda config fail mis kosneb @serverhost, @serverUsername ja @serverPassword -ist, ning see config fail peab paiknema 2 directoryt enne projekti faile. (Loogilises mõttes, enne public_html-i)

Et veebilehte avada, tuleb avada index.php ja et süsteemihaldurit avada, tuleb avada "SystemMaintancePage" folderis index.php.

### License
![Image of Copyright](https://camo.githubusercontent.com/9e918e1e7cd28a73246cf1c8d2c9903da3e487a65931c823a2391afe4b4a0d04/68747470733a2f2f6c6963656e7365627574746f6e732e6e65742f702f7a65726f2f312e302f38387833312e706e67)

To the extent possible under law, Marcus-Indrek Simmer, Stella-Marii Tamme, Margen Peterson ja Margarita Zahharova have waived all copyright and related or neighboring rights to this work.

