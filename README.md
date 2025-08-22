# UAV PHM Dataset (v3.x) — Normal & Anomaly Zips

[![Data](https://img.shields.io/badge/data-zip-blue)](#file-list) [![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](#)
[![Made for PHM](https://img.shields.io/badge/domain-PHM%20%7C%20UAV-5A5)](#)

Curated flight logs for UAV health monitoring and anomaly detection.
Each entry below links to a **direct download** (no extra clicks) with a fallback **view** link.

## File List

> 💡 Click the filename to download the zip directly.

| Filename | Split | Condition / Fault | Download | View (fallback) |
|---|---:|---|---|---|
| **v3.1_normal.zip** | v3.1 | Normal | [Download](https://drive.google.com/uc?export=download&id=1SXgmbpI23PAA3_SwSa_GUJFCT4qih7VQ) | [View](https://drive.google.com/file/d/1SXgmbpI23PAA3_SwSa_GUJFCT4qih7VQ/view?usp=drive_link) |
| **v3.1_anomaly_imbalanced_propeller.zip** | v3.1 | Anomaly — imbalanced propeller | [Download](https://drive.google.com/uc?export=download&id=1KQKEJrCmV3vh9_p0i29nEcbV8Cqq9nXJ) | [View](https://drive.google.com/file/d/1KQKEJrCmV3vh9_p0i29nEcbV8Cqq9nXJ/view?usp=drive_link) |
| **v3.2_normal.zip** | v3.2 | Normal | [Download](https://drive.google.com/uc?export=download&id=1-IIXddvRFW9Jh0QfWS1CG7YpaxYl1vHg) | [View](https://drive.google.com/file/d/1-IIXddvRFW9Jh0QfWS1CG7YpaxYl1vHg/view?usp=drive_link) |
| **v3.2_anomaly_severely_imbalanced_propeller.zip** | v3.2 | Anomaly — severely imbalanced propeller | [Download](https://drive.google.com/uc?export=download&id=1qg-Z8O0DSnoleTiX4wVmSlKb_ZF_2URX) | [View](https://drive.google.com/file/d/1qg-Z8O0DSnoleTiX4wVmSlKb_ZF_2URX/view?usp=drive_link) |
| **v3.3_normal.zip** | v3.3 | Normal | [Download](https://drive.google.com/uc?export=download&id=1gEYMvcIxXwiU_RmFuYNAkWLk3CjnuWk5) | [View](https://drive.google.com/file/d/1gEYMvcIxXwiU_RmFuYNAkWLk3CjnuWk5/view?usp=drive_link) |
| **v3.3_anomaly_cracked_propeller.zip** | v3.3 | Anomaly — cracked propeller | [Download](https://drive.google.com/uc?export=download&id=1HnvvqsH3jQpeZf1PbR3uL-dIVQXFQqWO) | [View](https://drive.google.com/file/d/1HnvvqsH3jQpeZf1PbR3uL-dIVQXFQqWO/view?usp=drive_link) |

---

## One-liner Downloads

### Using `wget`
```bash
# Download all zips to ./data
mkdir -p data && cd data
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1SXgmbpI23PAA3_SwSa_GUJFCT4qih7VQ" -O v3.1_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1KQKEJrCmV3vh9_p0i29nEcbV8Cqq9nXJ" -O v3.1_anomaly_imbalanced_propeller.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1-IIXddvRFW9Jh0QfWS1CG7YpaxYl1vHg" -O v3.2_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1qg-Z8O0DSnoleTiX4wVmSlKb_ZF_2URX" -O v3.2_anomaly_severely_imbalanced_propeller.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1gEYMvcIxXwiU_RmFuYNAkWLk3CjnuWk5" -O v3.3_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1HnvvqsH3jQpeZf1PbR3uL-dIVQXFQqWO" -O v3.3_anomaly_cracked_propeller.zip
```

### Using `curl`
```bash
# Download all zips to ./data
mkdir -p data && cd data
curl -L -o v3.1_normal.zip "https://drive.google.com/uc?export=download&id=1SXgmbpI23PAA3_SwSa_GUJFCT4qih7VQ"
curl -L -o v3.1_anomaly_imbalanced_propeller.zip "https://drive.google.com/uc?export=download&id=1KQKEJrCmV3vh9_p0i29nEcbV8Cqq9nXJ"
curl -L -o v3.2_normal.zip "https://drive.google.com/uc?export=download&id=1-IIXddvRFW9Jh0QfWS1CG7YpaxYl1vHg"
curl -L -o v3.2_anomaly_severely_imbalanced_propeller.zip "https://drive.google.com/uc?export=download&id=1qg-Z8O0DSnoleTiX4wVmSlKb_ZF_2URX"
curl -L -o v3.3_normal.zip "https://drive.google.com/uc?export=download&id=1gEYMvcIxXwiU_RmFuYNAkWLk3CjnuWk5"
curl -L -o v3.3_anomaly_cracked_propeller.zip "https://drive.google.com/uc?export=download&id=1HnvvqsH3jQpeZf1PbR3uL-dIVQXFQqWO"

```

