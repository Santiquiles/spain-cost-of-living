# Cost of living in Spain by city (2026)

Monthly budgets for a single person in a 60 m² flat and a couple in 80 m², in 10 Spanish cities, built only from
primary sources: asking rents from idealista's monthly report and household spending from Spain's national
statistics institute (INE). No crowdsourced figures.

Interactive version with the method and per-city pages: **[Spain by Numbers, cost of living calculator](https://spainbynumbers.com/cost-of-living-calculator/)**.

| City | Rent, €/m² a month | Single, 60 m² | Couple, 80 m² |
|---|---|---|---|
| Madrid | €2026-09 | €2,314 | €3,693 |
| Barcelona | €2026-09 | €2,075 | €3,345 |
| Valencia | €2026-09 | €1,805 | €2,959 |
| Málaga | €2026-09 | €1,730 | €2,800 |
| Alicante | €2026-09 | €1,661 | €2,767 |
| Sevilla | €2026-09 | €1,544 | €2,552 |
| Granada | €2026-09 | €1,388 | €2,344 |
| Palma | €2026-09 | €1,961 | €3,138 |
| Bilbao | €2026-09 | €1,901 | €3,173 |
| Murcia | €2026-09 | €1,381 | €2,367 |
| Spain (national average) | €2026-09 | €1,741 | €2,877 |

Full table: [`data/spain-cost-of-living-2026.csv`](data/spain-cost-of-living-2026.csv) (10 cities, checked 2026-10-07).

## Columns

| Column | Meaning |
|---|---|
| `city`, `region` | City and autonomous community (spending data is regional) |
| `rent_eur_per_m2_month` | Asking rent per square metre, idealista report for the month in `rent_month` |
| `rent_source` | Exact idealista report used |
| `spending_per_person_year_eur` | INE household survey 2025: spending per person and year in that region, housing excluded |
| `food`, `transport`, `utilities`, `leisure`, `other_non_housing` | Breakdown of that spending, € per person and year |
| `single_60m2_month_eur` | Rent for 60 m² + one person's monthly spending |
| `couple_80m2_month_eur` | Rent for 80 m² + two people's monthly spending |

## Sources

- Rents: [idealista, rental price reports](https://www.idealista.com/news/) (asking prices, September 2026).
- Spending: [INE, Encuesta de Presupuestos Familiares 2025](https://www.ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736176806&menu=ultiDatos&idp=1254735976608), per person, by region, housing excluded.

## Limits

Asking rents run above signed rents, and regional spending averages hide differences between a city centre and its
suburbs. Use the numbers to compare cities and to plan, not as a quote. The website is refreshed when idealista and
INE publish; this repository is a snapshot as of 2026-10-07.

## License and citation

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Reuse freely with a link to the source:

```html
Source: <a href="https://spainbynumbers.com/cost-of-living-calculator/">Spain by Numbers, cost of living in Spain 2026</a>
```
