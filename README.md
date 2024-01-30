# Links to where you can download bioimage datasets



## Histology
eg. Haematoxylin and Eosin (H&E) stained slides

- Colorectal Cancer (H&E)
  - Link to download:
    - https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest-backup/download/
- CAMELYON (H&E)
  - Whole slide images, so individual files are big (~800 MB - ~8 GB)
  - Link to more information:
    - https://camelyon17.grand-challenge.org/Background/
  - Link to download:
    - https://registry.opendata.aws/camelyon/
  - Command to view dataset with `awscli`:
    - `aws s3 ls --human-readable --no-sign-request s3://camelyon-dataset/CAMELYON17/`
  - Colorectal cancer
    - Small images (150x150 px)
    - Single class for each image (aka a "patch")
    - Link to dataset:
      - https://zenodo.org/records/53169