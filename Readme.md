# Australia Health Insurer Stats

This is an attempt to provide an aggregate and objective rating of private
health insurance companies in Australia based on their financials and other
metrics.  This is in contrast to most review sites which are based on user
reviews that are often subjective, biased and not representative of the
population.

## TL;DR

Based on % of revenue spent on benefits and average rate of complaints, the best
insurer in each state are:

| State | Best Insurer |
| ----- | ------------ |
| NSW | [HBF][HBF] |
| VIC | [HBF][HBF] |
| QLD | [Mildura][Mildura] |
| SA | [Mildura][Mildura] |
| WA | [Mildura][Mildura] |
| TAS | [QCH][QCH] |
| ACT | [Mildura][Mildura] |
| NT | [TFH][TFH] |

## Percentage of revenue spent on benefits (2022)

This is calculated by dividing benefits paid out by the premium revenue of each
insurer. The higher the percentage, the better.

Here is the summary of the results nation wide and per state:

| State | Top | 2nd | 3rd |
| ----- | --- | --- | --- |
| National | [HBF][HBF] (88.0) | [Police][Police] (86.7) | [HP][HP] (86.6) |
| NSW | [HBF][HBF] (96.7) | Latrobe (95.8) | [HP][HP] (93.3) |
| VIC | [HBF][HBF] (89.3) | [Police][Police] (87.0) | [HP][HP] (86.9) |
| QLD | [CBHSCH][CBHSCH] (116.1) | [Mildura][Mildura] (109.8) | CDH (102.7) |
| SA | [Mildura][Mildura] (266.2) | Transport (99.6) | [CBHSCH][CBHSCH] (99.0) |
| WA | [CBHSCH][CBHSCH] (126.3) | [Mildura][Mildura] (109.8) | HCF (99.3) |
| TAS | [CBHSCH][CBHSCH] (135.5) | [QCH][QCH] (135.0) | CDH (97.5) |
| ACT | [CBHSCH][CBHSCH] (219.4) | [Mildura][Mildura] (171.5) | RBHS (91.6) |
| NT | [TFH][TFH] (94.6) | Transport (86.6) | HCF (86.4) |

<details>

Notes:

- RT and NMW insurers were excluded as they had been merged with another insurer
  this year.
- State levies were excluded from the calculation as they were not paid out to
  members and also not paid in all states.
- It appears that some of the insurers have heavily subsidised members of one
  state (such as [CBHSCH][CBHSCH] in ACT paying out twice as much benefit as they received
  in premium from members in ACT) compared to others. This may be due to small
  number of members in some states which doesn't allow the even spread.
- Overall, [HBF][HBF] seems to return the most benefit to its members.

| Insurer | National | NSW | VIC | QLD | SA | WA | TAS | ACT | NT |
| ------- | -------- | --- | --- | --- | -- | -- | --- | --- | -- |
| [ACA][ACA] | 77.7 | 76.5 | 74.3 | 86.4 | 80.6 | 66.3 | 94.7 | 22.0 | 36.7 |
| [AUHL][AUHL] | 76.4 | 76.1 | 74.4 | 84.4 | 84.7 | 83.1 | 74.2 | 53.2 | 48.8 |
| [BUPA][BUPA] | 80.7 | 76.6 | 78.8 | 86.0 | 81.9 | 89.7 | 79.4 | 65.7 | 77.8 |
| [CBHS][CBHS] | 86.6 | 83.9 | 85.7 | 98.5 | 89.9 | 82.7 | 91.1 | 67.3 | 52.2 |
| [CBHSCH][CBHSCH] | 85.6 | 72.1 | 79.4 | 116.1 | 99.0 | 126.3 | 135.5 | 219.4 |
| CDH | 75.0 | 72.6 | 78.4 | 102.7 | 63.3 | 43.5 | 97.5 | -22.7 | 57.7 |
| CUA | 77.9 | 68.6 | 63.0 | 87.4 | 75.8 | 63.2 | 46.2 | 46.1 | 54.2 |
| Defence | 86.0 | 83.6 | 84.4 | 91.1 | 86.3 | 89.4 | 83.7 | 76.3 | 78.4 |
| DHF | 78.6 | 75.8 | 77.6 | 85.1 | 77.2 | 92.8 | 63.6 | 72.6 | 63.9 |
| GMHBA | 83.8 | 82.4 | 83.1 | 90.4 | 80.3 | 84.2 | 86.0 | 85.6 | 65.8 |
| [HBF][HBF] | 88.0 | 96.7 | 89.3 | 101.9 | 95.1 | 87.2 | 89.7 | 67.9 | 76.4 |
| HCF | 85.1 | 82.2 | 86.3 | 87.9 | 89.5 | 99.3 | 93.9 | 82.2 | 86.4 |
| HCI | 75.2 | 82.4 | 71.4 | 76.4 | 81.9 | 66.1 | 76.1 | 43.1 | 62.7 |
| HIF | 80.5 | 80.2 | 80.1 | 88.1 | 76.6 | 79.9 | 80.8 | 61.7 | 64.8 |
| [HP][HP] | 86.6 | 93.3 | 86.9 | 96.5 | 86.1 | 85.9 | 88.0 | 47.5 | 59.3 |
| Latrobe | 79.4 | 95.8 | 77.9 | 83.4 | 82.9 | 80.2 | 76.3 | 45.3 | 33.6 |
| [Mildura][Mildura] | 83.3 | 22.8 | 86.7 | 109.8 | 266.2 | 109.8 | 61.7 | 171.5 | 55.8 |
| MOH | 81.4 | 78.7 | 79.2 | 91.4 | 92.1 | 84.8 | 76.0 | 69.1 | 67.7 |
| MPL | 82.9 | 77.7 | 80.9 | 88.0 | 86.1 | 93.1 | 81.0 | 69.8 | 82.8 |
| Navy | 85.0 | 84.5 | 84.4 | 94.3 | 87.7 | 91.8 | 80.7 | 61.9 | 68.5 |
| NHBA | 74.8 | 75.6 | 74.9 | 75.6 | 78.3 | 76.2 | 59.5 | 44.2 |
| NIB | 73.6 | 74.4 | 70.1 | 76.9 | 78.1 | 76.3 | 69.2 | 63.6 | 52.0 |
| Peoplecare | 83.6 | 81.5 | 86.3 | 89.0 | 76.1 | 78.8 | 82.0 | 75.2 | 50.1 |
| Phoenix | 81.6 | 80.1 | 82.6 | 92.2 | 79.3 | 75.7 | 71.2 | 41.3 | 48.6 |
| [Police][Police] | 86.7 | 87.4 | 87.0 | 89.3 | 85.7 | 87.0 | 81.5 | 69.0 | 78.7 |
| [QCH][QCH] | 83.6 | 80.2 | 71.0 | 84.2 | 73.6 | 65.9 | 135.0 | 57.6 | 53.6 |
| QTUH | 83.4 | 75.0 | 68.5 | 84.5 | 65.9 | 59.0 | 80.3 | 47.6 | 23.7 |
| RBHS | 75.2 | 77.5 | 72.3 | 69.9 | 71.0 | 53.9 | 73.6 | 91.6 | 41.1 |
| St Luke's | 83.9 | 76.6 | 76.6 | 90.5 | 75.2 | 69.9 | 84.5 | 81.0 | 43.9 |
| [TFH][TFH] | 84.5 | 83.2 | 84.4 | 98.9 | 86.7 | 96.3 | 85.6 | 75.2 | 94.6 |
| Transport | 84.4 | 74.1 | 84.4 | 94.7 | 99.6 | 83.4 | 84.9 | 47.4 | 86.6 |
| Westfund | 78.5 | 73.7 | 84.0 | 83.4 | 86.1 | 85.8 | 75.0 | 75.4 | 32.1 |

</details>

## Average number of complains (2022)

The lower the number, the better.

| Insurer | Avg. # of complaints per 100K member |
| ------- | -----------------------------------  |
| [ACA][ACA] | 0.0 |
| NHBA | 0.0 |
| RBHS | 0.0 |
| [Mildura][Mildura] | 2.8 |
| CUA | 7.4 |
| QTUH | 7.6 |
| [Police][Police] | 7.6 |
| HCI | 8.5 |
| Defence | 9.5 |
| Peoplecare | 11.3 |
| [QCH][QCH] | 11.7 |
| [HBF][HBF] | 11.8 |
| MPL | 11.9 |
| DHF | 12.4 |
| [TFH][TFH] | 13.1 |
| St Luke's | 13.3 |
| Westfund | 13.6 |
| [BUPA][BUPA] | 14.1 |
| NIB | 16.8 |
| GMHBA | 17.5 |
| HCF | 18.2 |
| Phoenix | 20.3 |
| Navy | 21.6 |
| CBHS | 21.6 |
| Latrobe | 22.8 |
| [HP][HP] | 23.9 |
| HIF | 24.4 |
| AUHL | 33.5 |
| CDH | 37.5 |
| CBHSCH | 38.8 |
| Transport | 50.3 |
| MOH | 61.5 |

## Sources

- [Operations of Private Health Insurers (Annual Report)](https://www.apra.gov.au/operations-of-private-health-insurers-annual-report)
- [Private Health Insurance industry updates](https://www.ombudsman.gov.au/industry-and-agency-oversight/industry-updates/private-health-insurance-updates)

[ACA]: https://acahealth.com.au/
[AUHL]: https://www.australianunity.com.au/
[BUPA]: https://www.bupa.com.au/
[CBHS]: https://www.cbhs.com.au/

[HBF]: https://www.hbf.com.au/
[CBHSCH]: https://www.cbhscorporatehealth.com.au/
[Police]: https://policehealth.com.au/
[Mildura]: https://www.mildurahealthfund.com.au/
[HP]: https://www.healthpartners.com.au/
[QCH]: https://www.queenslandcountry.health/
[TFH]: https://www.teachershealth.com.au/
