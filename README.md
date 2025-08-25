# 💻 Basis van Programmeren – Upstream Repository

Welkom bij de upstream repository voor het vak **Basis van Programmeren**.  
Deze repo bevat de wekelijkse programmeeropdrachten en vormt de basis waaruit studenten hun werk starten.

> 📌 *Deze repository is **alleen-lezen** voor studenten.* Zij werken in hun eigen GitHub Classroom repository waarin deze repo als **upstream** wordt toegevoegd.

---

## 📚 Inhoud

Deze repository bevat één branch per week met daarin de oefeningen en/of voorbeelden:
main
├── week-01
├── week-02
├── week-03
├── ...
└── week-08

De `main` branch bevat alleen metadata zoals deze README.

---

## 🧭 Werkwijze voor studenten

> Let op: studenten werken in hun eigen **GitHub Classroom repo**. Deze repo dient als **upstream**.

### 1️⃣ Upstream instellen
Eenmalig in je lokale repo:

git remote add upstream https://github.com/dswembou/basisprogrammeren.git
git fetch upstream

### 2️⃣ Week branch ophalen
Aan het begin van de week:

git checkout -b week-03 upstream/week-03
git push -u origin week-03

### 3️⃣ Werken, committen en pushen
Tijdens de week werk je aan de opdrachten en commit je zoals gewoonlijk.

---

## 🔀 Einde van de periode
In week 8 merge je je laatste branch (week-08) naar de main branch:

git checkout main
git merge week-08
git push origin main

---

## 📬 Vragen?
Vragen over Git of Python?
Stel ze in de les of via Teams

---

© Opleiding Software Developer – Basis van Programmeren