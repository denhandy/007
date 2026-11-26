# Data dictionary

| Field | Meaning | Unit or values | Example |
|---|---|---|---|
| id | Unique competitor ID | Text | c01 |
| name | Fictional competitor name | Text | Miette Orbit |
| concept | Short description | Text | All-day brunch |
| segment | Price segment | Premium, Mid-market, Value | Premium |
| experienceScore | Experience level | Integer from 1 to 5 | 4 |
| arrondissement | Paris district | Integer from 1 to 20 | 11 |
| neighborhood | Area in Paris | Text | Saint-Ambroise |
| lat | Latitude | Decimal degrees | 48.8618 |
| lng | Longitude | Decimal degrees | 2.3741 |
| avgMenuPrice | Average main dish price | Euros, or null | 19 |
| followers.instagram | Instagram followers | Count | 12700 |
| followers.tiktok | TikTok followers | Count, or null | 2300 |
| followers.facebook | Facebook followers | Count | 910 |
| rating | Average rating | Out of 5 | 4.3 |
| reviewCount | Number of reviews | Count | 216 |
| source | Data source | Text | Fictional sample |
| lastChecked | Date checked | YYYY-MM-DD | 2026-11-20 |
| fictional | Whether the record is fictional | Boolean | true |

## After the workshop
Figures are collected by hand from public pages, each with its source URL and date, never by scraping. A human checks every figure before use. Set fictional to false for real records.
