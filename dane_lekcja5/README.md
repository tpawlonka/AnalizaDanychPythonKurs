# Dane do lekcji 5

Lekcja 5 jest poświęcona wizualizacji danych w Pythonie.

W tej lekcji korzystamy głównie z pakietu `nycflights13`, a dokładniej z tabel:
- `flights`
- `airlines`
- `weather`

## Instalacja

Jeśli pakiet nie jest dostępny lokalnie:

```bash
pip install nycflights13
```

## Co przygotowujemy w notebooku?

W notebooku powstaje tabela `viz_df`, która:
- zawiera wybrane kolumny z `flights`,
- ma dołączone pełne nazwy przewoźników z `airlines`,
- ma dołączone wybrane zmienne pogodowe z `weather`,
- zawiera dodatkowe kolumny pomocnicze do wizualizacji:
  - `month_name`
  - `weekday`
  - `dep_hour`
  - `is_delayed_dep`
  - `on_time_flag`
  - `route`

## Zakres lekcji

Lekcja obejmuje:
- `countplot()`
- `barplot()`
- `histplot()`
- `boxplot()`
- `violinplot()`
- `scatterplot()`
- `lineplot()`
- `heatmap()`
- `pairplot()`
- `plt.subplots()` i układy wielopanelowe
