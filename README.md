# dynamity

# README – Python Learning & Automation Repo

Toto repo slouží jako **učební a cvičný prostor** pro základy Pythonu, algoritmizaci, OOP, práci se soubory, Git a první kroky v ML. Obsahuje úkoly, příklady a zadání.

---

## Obsah

1. [Základy programování v Pythonu](#1-základy-programování-v-pythonu)
2. [Základy algoritmizace a Python](#2-základy-algoritmizace-a-python)
3. [Debugování](#3-debugování)
4. [Skriptování – práce se soubory](#4-skriptování--práce-se-soubory)
5. [Základy OOP](#5-základy-oop)
6. [Mini‑projekt s OOP](#6-mini-projekt-s-oop)
7. [Git – časté situace a řešení](#7-git--časté-situace-a-řešení)
8. [Základy ML](#8-základy-ml)

---

## 1. Základy programování v Pythonu

**Topics:**

* proměnné, datové typy (int, float, str, bool, list, dict, tuple, set)
* operátory, podmínky (`if/else`), cykly (`for`, `while`)
* funkce a návratové hodnoty
* práce s výjimkami (`try/except`)

**Úkoly:**

* Napiš funkci, která sečte čísla od 1 do N.
* Vytvoř program, který spočítá počet samohlásek ve stringu.
* Ověř, zda je číslo prvočíslo.
* Seznam čísel: použij `min()`, `max()`, `sum()`, `enumerate()`.

---

## 2. Základy algoritmizace a Python

**Topics:**

* co je algoritmus (postup kroků)
* pseudokód vs. Python
* složitost algoritmů (big‑O)

**Příklady:**

* vyhledávání čísla v seznamu (lineární vs. binární hledání)
* třídění (bubble sort vs. `sorted()` v Pythonu)

**Úkoly:**

* Implementuj vlastní funkci pro bubble sort.
* Porovnej čas běhu `for` cyklu a vestavěné funkce `sum()`.

---

## 3. Debugování

**Topics:**

* `print()` debugging
* použití `pdb` / debug módu v IDE
* čtení chybových hlášek

**Úkoly:**

* Úmyslně vlož chybu do kódu a najdi ji pomocí debug módu.
* Vysvětli, jak se liší `KeyError`, `IndexError` a `TypeError`.

---

## 4. Skriptování – práce se soubory

**Topics:**

* čtení a zápis (`open`, `with`)
* práce s CSV (`csv` modul, `pandas` – později)
* práce s adresáři (`os`, `pathlib`)
* mazání souborů, archivace (`shutil`, `zipfile`)

**Úkoly:**

* Program, který vymaže všechny `.tmp` soubory ze složky.
* Skript, který uloží seznam čísel do CSV a zase ho načte.
* Skript, který zazipuje složku do `backup.zip`.

---

## 5. Základy OOP

**Topics:**

* třídy a instance
* atributy a metody
* `__init__`, `__str__`, `__repr__`
* dědičnost a polymorfismus

**Úkoly:**

* Třída `Car` (atributy: značka, rok, rychlost; metoda `accelerate`).
* Třída `ElectricCar` dědí z `Car`, přidává kapacitu baterie.

---

## 6. Mini‑projekt s OOP

**Zadání:**
Vytvoř program **„Správa knihovny“**:

* Třída `Book` (název, autor, rok vydání).
* Třída `Library` (metoda pro přidání knihy, vyhledání, výpis všech).
* Přidej funkci pro uložení seznamu knih do CSV.

**Cíl:** spojit OOP + práci se soubory.

---

## 7. Git – časté situace a řešení

**Otázky a scénáře:**

* Jak vytvořit nový branch a proč?
* Jak zrušit poslední commit?
* Jak sloučit branch (merge vs. rebase)?
* Co dělat, když je konflikt?
* Jak udělat revert změny?
* Jak nastavit `.gitignore`?

---

## 8. Základy ML

**Topics:**

* Co je Machine Learning?
* Typy ML: supervised, unsupervised
* Základní knihovny: `scikit-learn`, `pandas`, `numpy`

**Úkoly (úplné začátky):**

* Načti dataset Iris z `sklearn.datasets`.
* Rozděl data na train/test.
* Natrénuj `DecisionTreeClassifier`.
* Vyhodnoť přesnost.

---

## Jak postupovat

* Každý blok má vlastní složku `topics/<nazev>`.
* Ke každému bloku připrav PR s řešeními.
* Kód formátovat `black`, kontrolovat `ruff`.
* Testy psát přes `pytest`.

---

> 📌 **Tip:** Repo lze použít jako „learning diary“ – každý úkol + vlastní poznámky v Markdownu.
