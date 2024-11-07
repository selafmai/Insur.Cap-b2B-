# Insur.Cap - Avtonomni InsurTech Sistem

## 🎯 O projektu
Insur.Cap je napreden sistem za avtomatizacijo zavarovalniških procesov, ki uporablja umetno inteligenco in strojno učenje za analizo tveganj, ocenjevanje polic in upravljanje zavarovalniških produktov.

https://www.linkedin.com/company/insur-cap/

DEMO [AIA]: https://app.wordware.ai/explore/apps/2eb15610-a218-4262-b1f1-22daa3e1e461

![image](https://github.com/user-attachments/assets/63ccce47-6024-42d7-bfee-2ff408e2bfb4)

Medium: https://medium.com/@ales.furlanic/agentic-workflow-solutions-the-emerging-trend-in-insurance-technology-3f8ec9f9e2c1

Medium: https://medium.com/@ales.furlanic/behavioral-underwriting-using-agentic-ai-and-no-code-c7910969764d


## 🚀 Ključne funkcionalnosti

### 1. MGA Analitik
- Avtomatska kategorizacija zavarovalniških povpraševanj
- Identifikacija ključnih tveganj
- Generiranje priporočil za zavarovanje
- Analiza vhodnih dokumentov (PDF, CSV, DOC)

### 2. Ocenjevalec tveganj (Underwriter)
- Izračun ocene tveganja
- Predlaganje ustreznih zavarovalnih polic
- Izračun premij
- Odkrivanje potencialnih prevar

### 3. Upravitelj polic
- Ustvarjanje osnutkov polic
- Določanje kritja in izključitev
- Generiranje pogojev zavarovanja
- Upravljanje posebnih pogojev

### 4. Analitik izpostavljenosti
- Izračun izpostavljenosti tveganjem
- Analiza faktorjev tveganja
- Predlogi za zmanjšanje tveganj
- Ocena zaupanja v analizo

### 5. ESG skladnost
- Analiza okoljskega vpliva
- Ocena ogljičnega odtisa
- Integracija z vremenskimi podatki
- Predlogi za trajnostno poslovanje

## 💻 Tehnične specifikacije
- Python 3.8+
- Gradio UI
- Asyncio za asinhrono delovanje
- Integracija z zunanjimi API-ji (Climatiq, Weather API, Google API)
- Beleženje dogodkov (logging)
- Podatkovna baza PostgreSQL

![image](https://github.com/user-attachments/assets/9b4bc41b-131f-4e42-8633-31c909708f9b)


## 🛠️ Namestitev in zagon

NAVODILA ZA ZAGON INSUR.CAP APLIKACIJE
=====================================

1. PRIPRAVA OKOLJA
-----------------
- Prepričajte se, da imate nameščen Python 3.8 ali novejšo verzijo
- Priporočamo uporabo virtualnega okolja (venv)

2. USTVARJANJE VIRTUALNEGA OKOLJA
-------------------------------
# Windows
python -m venv venv
.\venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate

3. NAMESTITEV POTREBNIH KNJIŽNIC
------------------------------
pip install -r requirements.txt

4. KONFIGURACIJA
--------------
- Preverite, da imate pravilno nastavljeno .env datoteko
- Vnesite svoje API ključe v .env datoteko
- Preverite, da so vsi potrebni API ključi veljavni

5. ZAGON APLIKACIJE
-----------------
# Windows
python main.py

# Linux/Mac
python3 main.py

6. DOSTOP DO APLIKACIJE
---------------------
Aplikacija bo dostopna na:
- Lokalni URL: http://localhost:7860
- Gradio bo generiral tudi javni URL za deljenje (če je share=True)

7. TESTIRANJE
-----------
Za testiranje lahko uporabite naslednje primere:

Primer 1 - Avtomobilsko zavarovanje:
"Potrebujem zavarovanje za nov avto, star 2 leti. Vozim predvsem po mestu, imam 5 let izkušenj z vožnjo."

Primer 2 - Nepremičninsko zavarovanje:
"Zavarovanje za hišo v Ljubljani, staro 15 let. Imam vgrajen protipožarni sistem in alarm."

Primer 3 - Zdravstveno zavarovanje:
"Iščem dodatno zdravstveno zavarovanje s kritjem za zobozdravstvene storitve. Star sem 35 let, redno športno aktiven."

8. ZAUSTAVITEV APLIKACIJE
-----------------------
- Pritisnite Ctrl+C v terminalu za zaustavitev aplikacije
- Deaktivirajte virtualno okolje z ukazom: deactivate

OPOMBE
------
- V primeru težav preverite insurance_system.log datoteko
- Prepričajte se, da so vsi potrebni porti prosti (privzeto 7860)
- Za produkcijsko okolje prilagodite nastavitve v .env datoteki 
