# Data Dictionary

This dictionary describes the columns exported in `ai.csv` and `ai.json`.

| Field          | Type            | Description                                                     |
| -------------- | --------------- | --------------------------------------------------------------- |
| Domain         | string          | Fully qualified domain name.                                    |
| Status         | string          | Current acquisition state for the domain in the public extract. |
| PurchasePrice  | number | null   | Visible purchase price when available.                          |
| RenewalPrice   | number | null   | Visible renewal price when available.                           |
| Attractiveness | number | null   | Composite naming score used as a decision-support signal.       |
| Demand         | number | null   | Relative buyer-pressure score when available.                   |
| Length         | number | null   | Character count without the TLD.                                |
| Registrar      | string          | Registrar name when known.                                      |
| Created        | datetime | null | Creation timestamp when known.                                  |
| Expires        | datetime | null | Expiry timestamp when known.                                    |
