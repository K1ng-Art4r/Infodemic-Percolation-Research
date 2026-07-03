# Data

This project uses two different sources of data.

## Synthetic Data

The first notebook generates a synthetic social network directly in code.

The generated network simulates:

- multiple echo chambers;
- bridge links between communities;
- influencer nodes;
- weighted social connections;
- competing misinformation and fact-check spreading.

No external dataset is required for this part of the project.

---

## Hoaxy Dataset

The second notebook validates the proposed model using the public **Hoaxy** dataset.

The dataset contains Twitter retweet interactions related to misinformation claims and fact-checking articles.

It is downloaded automatically inside the notebook from the official public archive:

https://zenodo.org/records/1154840/files/PLOS_hoaxy_network_dataset.zip?download=1

---

## Why raw data is not included

The original dataset is **not stored** in this repository because:

- it is relatively large;
- it is publicly available;
- the notebook downloads it automatically;
- this repository focuses on reproducibility of the research rather than data storage.

---

## Expected directory after running the notebook

```text
hoaxy_data/
└── release_datasets/
    └── retweet.preelection.all.csv
```

This directory is intentionally excluded from Git.

---

## Generated Data

During execution the notebooks may also generate intermediate files and processed datasets.

These files are created automatically and are not required for understanding the methodology presented in this repository.
