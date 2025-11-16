# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Harjoitus 5:
Jouduin käyttämään apuna Copilottia siihen, miten saan myös opettajan repositorion pysymään. Tavallaan tämä kurssi on ollut ihan hyvä harjoitus myös tekoälyn promptaukseen. 
Mitä GitHub-repositoriosivulla näkyy? GitHubissa ei alkuun näkynyt muuta kuin vain repositorio Oppimisp-iv-kirja. Kirjoitusmuoto oli siis väärä, koska minulla oli ääkköset.
Mitä GitHub-repositoriosivulla nyt näkyy? Mitä haaroja näet GitHubissa, entä paikallisessa repositoriossasi? -Nyt haarat näkyvät myös omassa repositoriossani. Näen haaran main GitHubissa. 
Kysymys 6. Haettiin etärepositorion muutokset ilman, että ne yhdistettiin paikalliseen haaraan.
Palaa master-haaraan. Mitä komento status sanoo? Your branch is behind 'origin/main' by 1 commit.
Yhdistä origin/master-haaran muutokset. Mitä komento status nyt sanoo? Updating aac55cf..db3abeb
Fast-forward
 uusi.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 uusi.md

Huomio! git checkout origin/main siirtää detached HEAD-tilaan, jolloin nähdään etärepositoriossa olevat versiot,

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote remove origin | poistaa yhteyden etärepositorion kanssa|
| git remote add origin | yhdistää github repositorioon |
| git remote -v| tähän lyhyt kuvaus, mitä komento tekee |
| git push -u origin main | puskee sisällön GitHubiin |
| git remote add upstream | Lisää opettajan repositorion upstreamiksi |
|git fetch upstream |Hakee opettajan muutokset |
| git merge upstream/main | yhdistää opettajan tehtävät omaan main-haaraan |
| git branch |Näyttää haarat |
| git fetch origin | Hakee muutokset |
| git checkout origin/main | Näyttää etähaaran |
| git checkout main | Palaa omaan haaraan |
| git merge origin/main | yhdistää haarat |
