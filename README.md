# RiceBenchmark: A Benchmark for Evaluating Genomic Foundation Models on Rice Tasks

<div align="center" style="line-height: 1;">
  <a href="https://huggingface.co/datasets/ZhejiangLab/RiceBenchmark" target="_blank">
      <img alt="Hugging Face" src="https://img.shields.io/badge/🤗%20Hugging Face-RiceBenchmark%20-ffc107"/>
  </a>
  <a href="https://modelscope.cn/datasets/zhejianglab/RiceBenchmark" target="_blank">
      <img alt="ModelScope" src="https://img.shields.io/badge/ModelScope-RiceBenchmark-blue?logo=modelscope&logoColor=blue"/>
  </a>
  <a href="https://github.com/zhejianglab/OneGenome-Rice" target="_blank">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-OGR Model-pink?logo=github&logoColor=white"/>
</a>
  </br>
  <a href="https://www.biorxiv.org/content/10.64898/2026.04.21.719822v1" target="_blank">
      <img alt="Technical Report" src="https://img.shields.io/badge/🧬%20bioRxiv- Technical Report-green"/> 
  </a>
  <a href="https://github.com/zhejianglab/RiceBenchmark/blob/main/LICENSE" target="_blank">
      <img alt="License" src="https://img.shields.io/badge/📑%20License- CC BY 4.0-lightgrey"/> 
  </a>
  <br>
</div>

## 1. Introduction
**RiceBenchmark** is a comprehensive evaluation benchmark designed to systematically assess the capabilities of genomic foundation models (gLMs) on rice-related tasks.

To enable standardized and reproducible evaluation, RiceBenchmark integrates:

- 26 curated benchmark datasets, organized into five task categories, covering a spectrum from:
  - local sequence identification
  - to complex population-level inference
- 5 additional evaluation tasks derived from the AgroNT study, with a focused selection of rice-specific datasets.

This design ensures coverage across multiple biological scales and task complexities, providing a robust framework for evaluating genomic language models. For further technical details, please refer to our [technical report](https://www.biorxiv.org/content/10.64898/2026.04.21.719822v1).

## 2. Download 
The benchmark is publicly available via the following platforms:

<div align="center">
  
| **Benchmark** | **Hugging Face** | **ModelScope** |
| :-------------: | :-----------------------: | :-------------------: |
| RiceBenchmark | [🤗 Hugging Face](https://huggingface.co/datasets/ZhejiangLab/RiceBenchmark ) | [🤖 ModelScope](https://modelscope.cn/datasets/zhejianglab/RiceBenchmark ) |

</div>

## 3. Data Sources and Composition
RiceBenchmark covers multiple key functional areas relevant to rice genomics, with 26 benchmark datasets designed to evaluate model performance on diverse tasks. The tasks can be broadly grouped into six categories:

- **Short-sequence Tasks (≤ 1 kb):** These tasks focus on local sequence identification, such as splice site detection and small regulatory elements, allowing evaluation of model performance on fine-grained, short-range genomic features.

- **Long-sequence Tasks (≤ 8 kb):** Designed to capture longer-range dependencies, these tasks include tissue-specific gene expression prediction, enabling assessment of models on more complex sequence contexts.

- **Single-nucleotide Tasks:** These tasks evaluate models at nucleotide-level resolution.

- **Sweep Region Identification Tasks:** Focused on evolutionary genomics, these tasks aim to identify genomic regions under selective sweeps using multi-scale sequences (8 kb, 32 kb, 100 kb), assessing the model’s ability to capture selection signals and evolutionary patterns.

- **Varieties Classification Tasks:** Designed to distinguish among japonica, indica, and wild rice varieties using multi-scale input sequences (8 kb, 32 kb, 128 kb), evaluating model performance in discriminating population-level genetic differences.

- **AgroNT Evaluation Tasks:** A subset of curated rice datasets from the AgroNT study, covering representative functional prediction problems such as chromatin accessibility, polyadenylation site prediction, and tissue-specific gene expression, sampled to improve computational efficiency while maintaining representativeness.

All datasets are derived exclusively from publicly available resources and published literature that impose no restrictions on AI training usage. They have further undergone task-oriented processing, normalization, and quality control to ensure consistency and usability for benchmarking purposes.

## 4. License and Responsible Use
The dataset is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. 

This dataset is constructed from publicly available data sources. We gratefully acknowledge the contributions of the original data providers, researchers, and organizations whose efforts made these resources publicly available and enabled the construction of this benchmark. All original content remains the property of its respective rights holders, and the release of this dataset does not imply ownership of the underlying data. Users are solely responsible for ensuring that their use of the dataset complies with applicable laws, regulations, and institutional policies, including but not limited to data protection, intellectual property, and biosecurity-related requirements.

The dataset must **not** be used for any purposes that may:

- violate applicable laws or regulations;
- infringe upon intellectual property or other legal rights;
- pose risks to biosafety, biosecurity, or public interest.

## 5. Contact 
For questions, feedback, or contributions, please open an issue in this repository or contact:
- 📧[opensource@zhejianglab.org](mailto:opensource@zhejianglab.org) 
- 📧[OneGenomeRice@zhejianglab.org](mailto:OneGenomeRice@zhejianglab.org)
