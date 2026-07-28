# Data

## dataset_10_stocks_b3.csv
One row per classified news event (N=10,108).

| column          | description                                        |
|-----------------|----------------------------------------------------|
| idx             | event id                                           |
| ticker          | B3 stock ticker                                    |
| date            | publication date of the headline                   |
| sentimento      | LLM label: POSITIVE / NEUTRAL / NEGATIVE           |
| sentimento_num  | numeric encoding: +1 / 0 / -1                      |
| t0              | event date T0                                      |
| ar_t0           | abnormal return at T0                              |
| ar_t1           | abnormal return at T+1                             |
| car             | cumulative abnormal return CAR[T0, T+1]            |

## dataset_10_gigantes_tcc.csv
Raw scraped headlines (N=10,798) from Google News, 2023–2024.
Columns: ticker, search_term, title, link, published, source, datetime.
