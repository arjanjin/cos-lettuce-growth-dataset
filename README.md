# Cos Lettuce Growth Stage Image Dataset

Images of Cos lettuce (*Lactuca sativa* var. *longifolia*) collected across three
growth stages — **small** (seedling), **medium** (mid-growth), and **large**
(near-harvest) — from a controlled indoor farming system and from Hydro Green
Garden Farm (collected with the farm's consent). The dataset was used to train and
evaluate a **YOLOv11** object-detection model for plant growth-stage classification
and computer-vision browning detection, as described in the associated publication.

## Associated publication

Chaoraingern, J., Pattaraanuvong, A., Paraksa, K., Khunthong, K., Nontiwantok, T.,
and Numsomran, A. *"Agentic AI-Driven Cultivation Advisory and Plant Disease
Diagnosis in a Controlled Indoor Farming System."* **AgriEngineering** (MDPI), 2026.
*(DOI to be assigned)*

## Dataset contents

| Folder    | Images | Growth stage        |
|-----------|:------:|---------------------|
| `small/`  |  102   | Seedling            |
| `medium/` |   99   | Mid-growth          |
| `large/`  |  100   | Near-harvest        |
| **Total** | **301**| —                   |

- **Format:** JPEG (`.jpg`)
- **Bounding-box annotations:** *not included.* Researchers wishing to use this
  dataset for object detection are encouraged to annotate using tools such as
  Roboflow or CVAT.

## Data collection

- Controlled indoor farming system
- Field images: Hydro Green Garden Farm (collected with consent)

## Directory structure

```
LettuceDataset/
├── small/     # 102 images — seedling stage
├── medium/    #  99 images — mid-growth stage
├── large/     # 100 images — near-harvest stage
└── README.md
```

## License

**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**
<https://creativecommons.org/licenses/by-nc/4.0/>

You are free to **Share** and **Adapt** the material under these terms:
- **Attribution** — give appropriate credit to the authors.
- **NonCommercial** — you may not use the material for commercial purposes.

## Citation

If you use this dataset, please cite the associated publication and this dataset
record (see `CITATION.cff`).

## Contact

**Corresponding author:** Assoc. Prof. Dr. Arjin Numsomran
Email: arjin.nu@kmitl.ac.th
Department of Instrumentation and Control Engineering, School of Engineering,
King Mongkut's Institute of Technology Ladkrabang (KMITL), Bangkok 10520, Thailand
