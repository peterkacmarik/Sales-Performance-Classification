# Sales Performance Binary Classification

## Popis projektu
Tento projekt sa zaoberá binárnou klasifikáciou predajných výkonov na základe rôznych vstupných charakteristík zákazníkov a produktov. Používa sa model neurónových sietí v PyTorch na predikciu, či má produkt alebo zákazník vysoký alebo nízky výkon na základe historických údajov.

## Súbory v projekte
- `sales_data.csv`: Dataset obsahujúci údaje o predajoch.
- `sales_performance.ipynb`: Obsahuje definície tried a funkcií pre model neurónovej siete a predikcie.

## Inštalácia
Pred spustením projektu sa uistite, že máte nainštalované všetky potrebné knižnice. Môžete to urobiť pomocou `pip`:

```bash
pip install numpy pandas scikit-learn torch matplotlib
```
### Použitie
Ak chcete spustiť model na vlastných dátach, postupujte podľa nasledujúcich krokov:
1. Načítajte dátový súbor `sales_data.csv` do koreňového adresára.
2. Spustite skript jupyter notebook `sales_performance.ipynb`:

## Ďalšie informácie
- Model: Používa sa model neurónovej siete s tromi skrytými vrstvami, Batch Normalization a Dropout.
- Štruktúra dát: Dátový súbor obsahuje rôzne charakteristiky zákazníkov a produktov, ktoré sa používajú na trénovanie a testovanie modelu.
- 
### Licencia
Tento projekt je licencovaný pod MIT licenciou.
### Zdroje
- [PyTorch dokumentácia](https://pytorch.org/docs/)
