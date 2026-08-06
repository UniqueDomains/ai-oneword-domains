# Data Dictionary

This dictionary describes the columns exported in `ai.csv` and `ai.json`.

| Field          | Type                       | Description                                                     |
| -------------- | -------------------------- | --------------------------------------------------------------- |
| domain         | string                     | Fully qualified domain name.                                    |
| status         | string                     | Current acquisition state for the domain in the public extract. |
| purchase_price | number or null             | Visible purchase price when available.                          |
| renewal_price  | number or null             | Visible renewal price when available.                           |
| attractiveness | low, medium, high, or null | Public composite naming band used as a decision-support signal. |
| demand         | low, medium, high, or null | Public buyer-pressure band when available.                      |
| length         | number or null             | Character count without the TLD.                                |
| registrar      | string                     | Registrar name when known.                                      |
| created_at     | datetime or null           | Creation timestamp when known.                                  |
| expires_at     | datetime or null           | Expiry timestamp when known.                                    |
