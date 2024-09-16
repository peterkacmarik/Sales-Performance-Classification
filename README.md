# Sales Performance Binary Classification

## Popis projektu
Tento projekt sa zaoberá binárnou klasifikáciou predajných výkonov na základe rôznych vstupných charakteristík zákazníkov a produktov. Používa sa model neurónových sietí v PyTorch na predikciu, či má produkt alebo zákazník vysoký alebo nízky výkon na základe historických údajov.

## Súbory v projekte
- `sales_data.csv`: Dataset obsahujúci údaje o predajoch.
- `model.py`: Obsahuje definície tried a funkcií pre model neurónovej siete a predikcie.
- `generate_data.py`: Skript na generovanie náhodných dát na testovanie modelu.
- `train.py`: Skript na trénovanie a validáciu modelu.
- `predict.py`: Skript na vykonávanie predikcií na nových dátach.
- `plot_results.py`: Skript na vizualizáciu výsledkov tréningu.

## Inštalácia
Pred spustením projektu sa uistite, že máte nainštalované všetky potrebné knižnice. Môžete to urobiť pomocou `pip`:

```bash
pip install numpy pandas scikit-learn torch matplotlib
```
## Ďalšie informácie
Model: Používa sa model neurónovej siete s tromi skrytými vrstvami, Batch Normalization a Dropout.
Štruktúra dát: Dátový súbor obsahuje rôzne charakteristiky zákazníkov a produktov, ktoré sa používajú na trénovanie a testovanie modelu.
