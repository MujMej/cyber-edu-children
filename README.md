# 📚 Cyber Heroji — Edukativni Materijali

> **Prezentacijski materijali i hub za edukaciju o sajber bezbjednosti djece i mladih uzrasta 9–15 godina**

[![Live Demo](https://img.shields.io/badge/🚀_Otvori_Materijale-mujmej.github.io-10b981?style=for-the-badge)](https://mujmej.github.io/cyber-edu-children/materials.html)
[![Kvizovi](https://img.shields.io/badge/🎮_Kvizovi-quizzes_repo-f59e0b?style=for-the-badge)](https://mujmej.github.io/quizzes/)
[![Jezik](https://img.shields.io/badge/Jezik-Bosanski-blue?style=for-the-badge)](#)
[![Uzrast](https://img.shields.io/badge/Uzrast-9–15_godina-purple?style=for-the-badge)](#)

---

## 📖 O projektu

**Cyber Heroji** je edukativni program o digitalnoj bezbjednosti za učenike uzrasta **9 do 15 godina**. Program se sastoji od **10 tematskih cjelina**, od kojih svaka uključuje:

- 📄 **PDF prezentaciju** za upotrebu u učionici
- 🎯 **Interaktivni kviz** (dostupan u [quizzes repozitoriju](https://github.com/MujMej/quizzes))
- 🔑 **Ključ** koji učenik dobija po uspješnom polaganju testa

Cilj programa je na pristupačan i zanimljiv način podučiti djecu temeljnim principima digitalne sigurnosti — od zaštite privatnosti do prepoznavanja lažnih vijesti i reagovanja na online incidente.

---

## 🗂️ Struktura programa — 10 tema

| # | Ikona | Tema | Ključ | Prezentacija |
|---|---|---|---|---|
| 1 | 🌳 | **Internet kao javni prostor** | `PARK` | [Tema1.pdf](Tema1.pdf) |
| 2 | 👣 | **Digitalni trag** | `OTISAK` | [Tema2.pdf](Tema2.pdf) |
| 3 | 🔐 | **Lični podaci i privatnost** | `SEF` | [Tema3.pdf](Tema3.pdf) |
| 4 | 🛡️ | **Lozinke i zaštita naloga** | `ŠTIT` | [Tema4.pdf](Tema4.pdf) |
| 5 | 🎭 | **Ko se krije iza ekrana?** | `MASKA` | [Tema5.pdf](Tema5.pdf) |
| 6 | 🧠 | **Društvene mreže i mozak** | `BALANS` | [Tema6.pdf](Tema6.pdf) |
| 7 | 💬 | **Cyberbullying i pozitivna zajednica** | `HRABROST` | [Tema7.pdf](Tema7.pdf) |
| 8 | 🔍 | **Lažne vijesti i kritičko razmišljanje** | `DETEKTIV` | [Tema8.pdf](Tema8.pdf) |
| 9 | 🤖 | **AI i deepfake** | `PAZI` | [Tema9.pdf](Tema9.pdf) |
| 10 | 🚨 | **Reakcija na incident** | `HEROJ` | [Tema10.pdf](Tema10.pdf) |

---

## 🏗️ Struktura fajlova

```
cyber-edu-children/
├── materials.html   # Glavni hub — PDF preuzimanje, pokretanje kviza
├── viewer.html      # Zaštićeni preglednik prezentacija
├── admin.html       # Admin panel
├── index.html       # Početna stranica
├── Tema1.pdf  →  Tema10.pdf    # Prezentacije (10 fajlova)
```

---

## 🔄 Kako se koristi u učionici

```
Prije časa
──────────
1. Edukator otvara materials.html
2. Preuzima ili pregledava PDF za željenu temu

Tokom časa
──────────
3. Prikazuje PDF prezentaciju (Part 1)
4. Klika "Kviz A" → pojavljuje se QR kod
5. Učenici skeniraju QR → unose kod → rješavaju Kviz A
6. Nastavlja sa Part 2 prezentacije
7. Klika "Kviz B" → učenici rješavaju Kviz B

Nakon časa
───────────
8. Učenici koji polože dobijaju ključ za tu temu
9. 10 položenih tema = sertifikat 🏆
```

---

## ✨ Funkcionalnosti materials.html

| Funkcija | Opis |
|---|---|
| 📄 **Preuzimanje PDF** | Direktan download prezentacije za svaku temu |
| 🎯 **Pokretanje Kviz A** | Otvara QR modal za prvu grupu pitanja |
| 🎯 **Pokretanje Kviz B** | Otvara QR modal za drugu grupu pitanja |
| 📱 **QR modal** | Generiše perzistentni 4-znakasti kod + QR sliku |
| 🌙 **Dark mode** | Podrška za tamnu temu |
| 🧭 **Navigacija** | Početna · Materijali · Quiz · Admin |

---

## 🎯 Pedagoški pristup

- **Kviz A** → prati **prvi dio** prezentacije (osnove, uzrast 9–11)
- **Kviz B** → prati **drugi dio** prezentacije (napredni scenariji, uzrast 11–15)
- Pitanja su u **scenarij formatu** — realne situacije, ne apstraktna teorija
- **Objašnjenja** uz svaki odgovor pojačavaju učenje

---

## 💻 Tehnologije

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)

- Čisti JS — **bez frameworka, bez servera**
- QR generacija via [api.qrserver.com](https://api.qrserver.com)
- Prezentacije u **PDF formatu** — rade na svim uređajima

---

## 🔗 Povezani repozitoriji

| Repozitorij | Opis | Link |
|---|---|---|
| 🎮 `quizzes` | Quiz engine sa pitanjima, bodovanjem i sertifikacijom | [GitHub](https://github.com/MujMej/quizzes) · [Live](https://mujmej.github.io/quizzes/) |

---

## 📁 Privatnost i podaci

Aplikacija **ne koristi server ni bazu podataka.**
Rezultati kvizova čuvaju se lokalno u browseru (`localStorage`).

---

## 👩‍💻 Autor

Razvijeno u svrhu edukacije o digitalnoj bezbjednosti za djecu i mlade.

**· with love, MujMej ·**

---

*© 2026 Cyber Heroji | Digitalna bezbjednost za djecu*
