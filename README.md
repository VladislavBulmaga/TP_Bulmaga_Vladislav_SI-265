# Tehnici de Programare

**Student:** Bulmaga Vladislav  
**Grupa:** SI-265  
**Universitatea:** Universitatea Tehnică a Moldovei  
**Facultatea:** Calculatoare, Informatică și Microelectronică (FCIM)  
**Specialitatea:** Securitate informațională

Acest repository conține lucrările mele de laborator la disciplina **Tehnici de programare**. Fișierele sunt organizate pe laboratoare și pot fi deschise folosind linkurile de mai jos.

## Lucrări de laborator

| Nr. | Laborator | Conținut |
|---|---|---|
| 1 | [Laboratorul 1](Laborator_1/) | Raport în format Word |
| 2 | [Laboratorul 2](Laborator_2/) | Raport în format Word |
| 3 | [Laboratorul 3](Laborator_3/) | Program Python |
| 4 | [Laboratorul 4](Laborator_4/) | Scripturi Python, module și fișiere de date |
| 5 | [Laboratorul 5](Laborator_5/) | Digital Forensics: fișiere, probe și raport |
| 6 | [Laboratorul 6 — GitHub](Laborator_6_GitHub/) | Git, GitHub și raportul laboratorului |
| 7 | [Laboratorul 7](Laborator_7/) | Enumerare Linux și compararea fișierelor SUID |
| 8 | [Laboratorul 8](Laborator_8/) | Analiza autentificărilor și detectarea atacurilor brute-force |
| 9 | [Laboratorul 9](Laborator_9/) | Analiza proceselor și evenimentelor Windows |
| 10 | [Laboratorul 10](Laborator_10/) | Digital Forensics: magic bytes, SHA-256, `with` și teste `pytest` |

> **Notă:** GitHub afișează folderele alfabetic, astfel că `Laborator_10` poate apărea între `Laborator_1` și `Laborator_2`. Tabelul de mai sus păstrează ordinea numerică.

## Cum pot fi verificate programele

Pentru a descărca repository-ul:

```powershell
git clone https://github.com/VladislavBulmaga/TP_Bulmaga_Vladislav_SI-265.git
cd TP_Bulmaga_Vladislav_SI-265
```

Programele Python se rulează din terminal, din folderul laboratorului corespunzător. Pentru testele automate din laboratoarele 7–9, se poate folosi `py -m pytest -q` din folderul fiecărui laborator (cu `pytest` instalat).

**Exemplu — Laboratorul 10:**

```powershell
cd Laborator_10
py -m arsenal.forensics.amprente arsenal/forensics/probe
py -m pytest -q arsenal/forensics/test_amprente.py
cd reparare
py -m pytest -q
```

În timpul verificării locale, pentru Laboratorul 10 au trecut **3 teste pentru partea A** și **3 teste pentru partea B**.

## Laboratorul 6 — Depozite de exercițiu

- [exercitiu-git](https://github.com/VladislavBulmaga/exercitiu-git)
- [exercitiu-2](https://github.com/VladislavBulmaga/exercitiu-2)
- [Raportul Laboratorului 6](Laborator_6_GitHub/L6_TP_Bulmaga_Vladislav_SI-265.md)

---

*Proiect realizat pentru activitățile de laborator la UTM.*
