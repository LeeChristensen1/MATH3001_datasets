# Purpose
I'd rather not keep getting the datasets from the government websites. Who knows, they might block us or something.

# Where they come from
* ExportToCsv.xlsx: https://www.aphis.usda.gov/livestock-poultry-disease/avian/avian-influenza/hpai-detections/commercial-backyard-flocks
* hpai-wild-birds.csv: https://www.aphis.usda.gov/livestock-poultry-disease/avian/avian-influenza/hpai-detections/wild-birds?page=1

# Usage
```python
pd.read_csv("https://github.com/LeeChristensen1/MATH3001_datasets/blob/main/hpai-wild-birds.csv?raw=true")
```

# One off statistics:
* There was one human infection from Feb 2022 to Feb 2023 in the USA which was at approximately the 20th of April 2022 (https://www.cdc.gov/bird-flu/php/technical-report/h5n1-031723.html).
* The number of poultry farms in the USA in 2022 was 168048 (https://www.nass.usda.gov/Publications/Highlights/2024/Census22_HL_Poultry.pdf)
