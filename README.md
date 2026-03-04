# Bank Marketing Data Analysis using Google AI Studio API

## 1. Tema

Šio darbo tema – banko marketingo duomenų analizė naudojant **Google AI Studio (Gemini) API** ir Python programavimo kalbą. Darbo metu analizuojamas klientų duomenų rinkinys ir siekiama nustatyti veiksnius, kurie daro įtaką klientų sprendimui pasirašyti terminuotą indėlį.

## 2. Darbo tikslas

Darbo tikslas – sukurti programą, kuri:

* įkelia duomenis iš CSV failo,
* atlieka paprastą duomenų analizę (EDA),
* perduoda duomenų santrauką dirbtinio intelekto modeliui per **Google AI Studio API**,
* gauna ir pateikia marketingo įžvalgas bei rekomendacijas.

## 3. Užduotis

Darbo metu buvo atliktos šios užduotys:

1. Įkelti banko marketingo duomenų rinkinį naudojant **Python ir pandas** biblioteką.
2. Atlikti pagrindinę duomenų analizę:

   * klasės (`y`) pasiskirstymas,
   * skaitinių stulpelių statistika,
   * trūkstamų duomenų analizė.
3. Paruošti duomenų santrauką ir suformuoti **promptą** dirbtinio intelekto modeliui.
4. Naudojant **Google AI Studio API (Gemini modelį)** gauti:

   * svarbiausius prenumeratos (`y`) prognozės veiksnius,
   * klientų segmentus,
   * marketingo rekomendacijas.
5. Atvaizduoti gautą analizę programos rezultatuose.

## 4. Naudotos technologijos

* Python
* Pandas
* Google AI Studio API
* Gemini modelis
* Google Colab

## 5. Darbo eiga

Darbo metu programa vykdo šiuos pagrindinius veiksmus:

1. **Duomenų įkėlimas (Load)**
   Duomenys įkeliami iš CSV failo naudojant pandas biblioteką.

2. **Duomenų analizė (Preprocess / EDA)**
   Apskaičiuojama:

   * target klasės pasiskirstymas,
   * statistinė skaitinių duomenų santrauka,
   * trūkstami duomenys.

3. **Duomenų perdavimas AI modeliui**
   Sukuriamas tekstinis promptas su duomenų statistika ir perduodamas Gemini modeliui per API.

4. **AI analizė**
   Modelis sugeneruoja įžvalgas apie:

   * svarbiausius marketingo veiksnius,
   * klientų segmentavimą,
   * marketingo strategijas.

5. **Rezultatų pateikimas**
   Programoje išspausdinamas AI sugeneruotas analizės tekstas.

## 6. Testavimas

Programa buvo testuojama naudojant Google Colab aplinką.

Testavimo metu buvo patikrinta:

* ar duomenys teisingai įkeliami iš CSV failo,
* ar generuojama duomenų statistika,
* ar veikia ryšys su Google AI Studio API,
* ar modelis grąžina analizės rezultatą.

Testavimo rezultatai parodė, kad programa veikia stabiliai ir pateikia logiškas marketingo įžvalgas.

## 7. Rezultatai

AI modelis, remdamasis duomenų statistika, nustatė pagrindinius veiksnius, kurie turi įtakos klientų sprendimui pasirašyti terminuotą indėlį, pavyzdžiui:

* pokalbio trukmė su klientu,
* ankstesnių marketingo kampanijų rezultatai,
* kontaktavimo būdas,
* klientų finansinė situacija.

Taip pat buvo pasiūlyti trys klientų segmentai ir marketingo strategijos kiekvienam segmentui.

## 8. Išvados

Atliktas darbas parodė, kad dirbtinio intelekto modeliai gali būti efektyviai naudojami marketingo duomenų analizei. Naudojant Google AI Studio API galima greitai generuoti įžvalgas ir rekomendacijas remiantis realiais duomenimis.

Šis metodas gali padėti įmonėms geriau suprasti klientų elgesį ir optimizuoti marketingo kampanijas.
