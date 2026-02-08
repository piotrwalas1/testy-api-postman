
# Automated API Testing Pipeline (Postman + Newman + Jenkins)
# API Automation Testing Project (JSONPlaceholder)

## 📋 Opis projektu
Projekt przedstawia w pełni zautomatyzowany proces testowania API. Kolekcja testów stworzona w Postmanie jest automatycznie uruchamiana w środowisku CI/CD (Jenkins) przy użyciu Newmana. Po każdym uruchomieniu generowany jest czytelny raport HTML.

## 🛠 Technologie i narzędzia
* **Postman** – tworzenie kolekcji testów i asercji.
* **Newman** – uruchamianie testów z poziomu linii komend.
* **Jenkins** – automatyzacja procesu (CI/CD).
* **Newman-reporter-htmlextra** – generowanie zaawansowanych raportów wizualnych.
* **Git/GitHub** – kontrola wersji.

## 🚀 Funkcje
- Automatyczne pobieranie najnowszej wersji testów z repozytorium.
- Testowanie statusów odpowiedzi (200 OK, 404, itp.).
- Weryfikacja struktury JSON oraz poprawności danych.
- Generowanie raportów HTML dostępnych bezpośrednio w Jenkinsie.

 ## 🚀 Pliki: Przypadki testowe, raporty
* [**Przypadki Testowe**](https://github.com/piotrwalas1/PORTFOLIO/blob/main/API%20Automation%20Testing%20Project%20(JSONPlaceholder).pdf)
* [**Raport Newman**](https://github.com/piotrwalas1/PORTFOLIO/blob/main/newman2.jpg)
* [**Raport**](https://github.com/piotrwalas1/PORTFOLIO/blob/main/newman.jpg)

  <p align="center">
  <img src="https://github.com/piotrwalas1/PORTFOLIO/blob/main/newman2.jpg" width="600" title="raport1">
</p>

<p align="center">
  <img src="https://github.com/piotrwalas1/PORTFOLIO/blob/main/newman.jpg" width="600" title="raport2">
</p>
  

## ⚙️ Jak uruchomić projekt lokalnie
1. Sklonuj repozytorium: `git clone https://github.com/piotrwalas1/testy-api-postman.git`
2. Zainstaluj Newmana: `npm install -g newman`
3. Zainstaluj reporter: `npm install -g newman-reporter-htmlextra`
4. Uruchom testy: `newman run testy_api_collection1.json -r htmlextra`
