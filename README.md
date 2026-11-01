# Optimalizace algoritmu výtahu

Tento projekt řeší optimalizaci řízení výtahu pro 400 lidí v 8patrové budově školy s cílem minimalizovat dobu čekání cestujících a snížit celkovou ujetou vzdálenost výtahu (úspora energie).

## Popis algoritmu
Implementovaný algoritmus využívá vylepšenou směrovou strategii (SCAN). Výtah efektivně seskupuje cestující jedoucí stejným směrem, eliminuje zbytečné změny směru jízdy a dynamicky reaguje na aktuální stav v kabině i na jednotlivých patrech.

## Spuštění simulace
1. Stáhněte si repozitář do počítače.
2. Otevřete soubor **`vytah.html`** v libovolném moderním webovém prohlížeči (Chrome, Firefox, Edge).
3. Přetáhněte konfigurační soubor zadání (např. `zadani-bezny-den-ve-skole-B746-8C6D.json`) do okna aplikace.
4. Klikněte na tlačítko **Spustit**.

## Matice odpovědnosti
| Člen týmu | Odpovědnost a úkoly |
|---|---|
| Matěj Jankech | Návrh a implementace optimalizovaného algoritmu v JS, testování simulace, vytvoření dokumentace a správa GitHub repozitáře |