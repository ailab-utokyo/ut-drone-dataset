# UAV PHM Dataset (v3.x & v4.x) — Normal & Anomaly Zips
[![Data](https://img.shields.io/badge/data-zip-blue)](#file-list) [![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](#)
[![Made for PHM](https://img.shields.io/badge/domain-PHM%20%7C%20UAV-5A5)](#)

Curated flight logs for UAV health monitoring and anomaly detection.
Each entry below links to a **direct download** (no extra clicks) with a fallback **view** link.

## File List

> 💡 Click the filename to download the zip directly.

| Filename | Split | Condition / Fault | Size | Download | View (fallback) |
|---|---:|---|---:|---|---|
| **v3.1_normal.zip** | v3.1 | Normal | 639 MB | [Download](https://drive.google.com/uc?export=download&id=19q7rvhruWlHSvHF7FSb2-Y151dld317I) | [View](https://drive.google.com/file/d/19q7rvhruWlHSvHF7FSb2-Y151dld317I/view?usp=drive_link) |
| **v3.1_anomaly_imbalanced_propeller.zip** | v3.1 | Anomaly — imbalanced propeller | 615 MB | [Download](https://drive.google.com/uc?export=download&id=1GpBbNULSF2_w4DlW4eYHzF9-Bhi5T1o1) | [View](https://drive.google.com/file/d/1GpBbNULSF2_w4DlW4eYHzF9-Bhi5T1o1/view?usp=drive_link) |
| **v3.2_normal.zip** | v3.2 | Normal | 620 MB | [Download](https://drive.google.com/uc?export=download&id=1Ln0Ap6_O44HBbR361kICbQNPRbvi3asE) | [View](https://drive.google.com/file/d/1Ln0Ap6_O44HBbR361kICbQNPRbvi3asE/view?usp=drive_link) |
| **v3.2_anomaly_severely_imbalanced_propeller.zip** | v3.2 | Anomaly — severely imbalanced propeller | 643 MB | [Download](https://drive.google.com/uc?export=download&id=1nE0kEN3ZloaBsMejl2_wmXKabCtjFARs) | [View](https://drive.google.com/file/d/1nE0kEN3ZloaBsMejl2_wmXKabCtjFARs/view?usp=drive_link) |
| **v3.3_normal.zip** | v3.3 | Normal | 578 MB | [Download](https://drive.google.com/uc?export=download&id=1fv9SehJ0uBwx4tj7lyf0Ga1l6LT6dA5Q) | [View](https://drive.google.com/file/d/1fv9SehJ0uBwx4tj7lyf0Ga1l6LT6dA5Q/view?usp=drive_link) |
| **v3.3_anomaly_cracked_propeller.zip** | v3.3 | Anomaly — cracked propeller | 546 MB | [Download](https://drive.google.com/uc?export=download&id=1fo9D6cVndZRgwZL614QcbqJGMiauUEn0) | [View](https://drive.google.com/file/d/1fo9D6cVndZRgwZL614QcbqJGMiauUEn0/view?usp=drive_link) |
| **v4.1_normal.zip** | v4.1 | Normal | 1.03 GB | [Download](https://drive.google.com/uc?export=download&id=16w-vDxfU-Em6NLmeY8f_JOGVQIkwsxCp) | [View](https://drive.google.com/file/d/16w-vDxfU-Em6NLmeY8f_JOGVQIkwsxCp/view?usp=drive_link) |
| **v4.2_normal.zip** | v4.2 | Normal | 1.64 GB | [Download](https://drive.google.com/uc?export=download&id=1N6JuBu_y7gJPxV_d0pnQh_hwKB32_F_C) | [View](https://drive.google.com/file/d/1N6JuBu_y7gJPxV_d0pnQh_hwKB32_F_C/view?usp=drive_link) |
| **v4.3_normal.zip** | v4.3 | Normal | 1.38 GB | [Download](https://drive.google.com/uc?export=download&id=1MLlJE7kze-NB9NwF780CU7CyHZlaWbwv) | [View](https://drive.google.com/file/d/1MLlJE7kze-NB9NwF780CU7CyHZlaWbwv/view?usp=drive_link) |
| **v4.4_normal.zip** | v4.4 | Normal | 2.11 GB | [Download](https://drive.google.com/uc?export=download&id=1xFMJsvAm8ReLACURz594zOZmq1m-g6an) | [View](https://drive.google.com/file/d/1xFMJsvAm8ReLACURz594zOZmq1m-g6an/view?usp=drive_link) |

> **Total size:** ~9.8 GB (v3.x: ~3.6 GB, v4.x: ~6.2 GB)

---

## One-liner Downloads

### Using `wget`
```bash
# Download all zips to ./data
mkdir -p data && cd data

# v3.x
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=19q7rvhruWlHSvHF7FSb2-Y151dld317I" -O v3.1_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1GpBbNULSF2_w4DlW4eYHzF9-Bhi5T1o1" -O v3.1_anomaly_imbalanced_propeller.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1Ln0Ap6_O44HBbR361kICbQNPRbvi3asE" -O v3.2_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1nE0kEN3ZloaBsMejl2_wmXKabCtjFARs" -O v3.2_anomaly_severely_imbalanced_propeller.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1fv9SehJ0uBwx4tj7lyf0Ga1l6LT6dA5Q" -O v3.3_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1fo9D6cVndZRgwZL614QcbqJGMiauUEn0" -O v3.3_anomaly_cracked_propeller.zip

# v4.x
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=16w-vDxfU-Em6NLmeY8f_JOGVQIkwsxCp" -O v4.1_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1N6JuBu_y7gJPxV_d0pnQh_hwKB32_F_C" -O v4.2_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1MLlJE7kze-NB9NwF780CU7CyHZlaWbwv" -O v4.3_normal.zip
wget -q --show-progress \
  "https://drive.google.com/uc?export=download&id=1xFMJsvAm8ReLACURz594zOZmq1m-g6an" -O v4.4_normal.zip
```

### Using `curl`
```bash
# Download all zips to ./data
mkdir -p data && cd data

# v3.x
curl -L -o v3.1_normal.zip "https://drive.google.com/uc?export=download&id=19q7rvhruWlHSvHF7FSb2-Y151dld317I"
curl -L -o v3.1_anomaly_imbalanced_propeller.zip "https://drive.google.com/uc?export=download&id=1GpBbNULSF2_w4DlW4eYHzF9-Bhi5T1o1"
curl -L -o v3.2_normal.zip "https://drive.google.com/uc?export=download&id=1Ln0Ap6_O44HBbR361kICbQNPRbvi3asE"
curl -L -o v3.2_anomaly_severely_imbalanced_propeller.zip "https://drive.google.com/uc?export=download&id=1nE0kEN3ZloaBsMejl2_wmXKabCtjFARs"
curl -L -o v3.3_normal.zip "https://drive.google.com/uc?export=download&id=1fv9SehJ0uBwx4tj7lyf0Ga1l6LT6dA5Q"
curl -L -o v3.3_anomaly_cracked_propeller.zip "https://drive.google.com/uc?export=download&id=1fo9D6cVndZRgwZL614QcbqJGMiauUEn0"

# v4.x
curl -L -o v4.1_normal.zip "https://drive.google.com/uc?export=download&id=16w-vDxfU-Em6NLmeY8f_JOGVQIkwsxCp"
curl -L -o v4.2_normal.zip "https://drive.google.com/uc?export=download&id=1N6JuBu_y7gJPxV_d0pnQh_hwKB32_F_C"
curl -L -o v4.3_normal.zip "https://drive.google.com/uc?export=download&id=1MLlJE7kze-NB9NwF780CU7CyHZlaWbwv"
curl -L -o v4.4_normal.zip "https://drive.google.com/uc?export=download&id=1xFMJsvAm8ReLACURz594zOZmq1m-g6an"
```
