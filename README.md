# Protein Function Prediction Dataset Curation

This project contains a series of pipelines for data preprocessing and curating
large-scale protein and gene ontology datasets with multiple features extracted from PFP from Kihara Lab (https://kiharalab.org/), UniProt,
QuickGO, and other Gene Ontology resources, alongside the implementation of a pipeline using networkx
to generate the Lin Score (semantic similarity metric) as a label.

## Environment

Please activate the environment before starting:

```bash
pip install requirements.txt
```

---

## Execution Order

### Step 1: run\_global1\_part1.sh

```bash
chmod +x Scripts_bash/run_global1_part1.sh
./Scripts_bash/run_global1_part1.sh
```

### Step 2: run\_global1\_part2.sh (approx. 17 minutes)

```bash
chmod +x Scripts_bash/run_global1_part2.sh
./Scripts_bash/run_global1_part2.sh
```

### Step 3: run\_global1\_part3.sh (approx. 1 hour)

```bash
chmod +x Scripts_bash/run_global1_part3.sh
./Scripts_bash/run_global1_part3.sh
```

### Step 4: run\_global1\_part4.sh (approx. 9 hours)

```bash
chmod +x Scripts_bash/run_global1_part4.sh
./Scripts_bash/run_global1_part4.sh
```

### Step 5: run\_global1\_part5.sh (approx. 12 hours)

```bash
chmod +x Scripts_bash/run_global1_part5.sh
./Scripts_bash/run_global1_part5.sh
```

### Step 6: run\_global1\_part6.sh

```bash
chmod +x Scripts_bash/run_global1_part6.sh
./Scripts_bash/run_global1_part6.sh
```

### Step 7: run\_global1\_part456val.sh (approx. 3 hours)

```bash
chmod +x Scripts_bash/run_global1_part456val.sh
./Scripts_bash/run_global1_part456val.sh
```

### Step 8: run\_global1\_part456test.sh (approx. 3 hours)

```bash
chmod +x Scripts_bash/run_global1_part456test.sh
./Scripts_bash/run_global1_part456test.sh
```

---

## Data Availability

Please note that the dataset referenced here is **not located in the same directory** as mentioned above.
The dataset is available upon request.
Please contact:

```
emiliatugol@gmail.com
```
## PygoSemSim

Please refer to the following link for PygoSemSim:

https://github.com/mojaie/pygosemsim
