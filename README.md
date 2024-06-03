# Persian Social Norm Dataset

Welcome to the Persian Social Norm Dataset repository! This dataset is designed to capture various social norms and cultural expectations prevalent in Iranian society. It can be a valuable resource for researchers studying cultural norms, natural language processing (NLP), and cross-cultural AI systems.

## Dataset Description

The dataset consists of four primary columns:

- **Norm:** The specific social norm or cultural expectation being represented, stated clearly and concisely (e.g., 'Showing respect for elders').
- **Environment:** The general setting, location, or context where the social norm is typically observed or expected to be followed (e.g., 'family gatherings', 'public spaces', 'workplace').
- **Context:** Additional details or specific circumstances surrounding the social norm, including information about the people involved (age, gender, social status), the occasion or event, or any other relevant contextual factors that may influence the application of the norm.
- **Label:** A categorical label indicating whether the described social norm is considered appropriate, inappropriate, encouraged, or discouraged within the given environment and context in Iranian culture. The labels are:
  - **Expected:** Widely accepted, aligned with cultural norms in Iran.
  - **Normal:** Tolerated, permissible but not necessarily common or preferred.
  - **Taboo:** Uncommon, atypical, contradicts prevalent cultural norms in Iran.

## Data Statistics

The dataset contains 1,760 samples and 334 unique environments. The distribution of labels is as follows:
- **Expected:** 51.5%
- **Normal:** 27.3%
- **Taboo:** 21.2%

## Data Construction

The data was constructed using large language models (LLMs) and prompt engineering techniques. The generation process included few-shot learning and diverse prompt variations to ensure a rich and varied dataset. The prompts included notes such as generating norms that change their label based on context or environment, and norms that may be surprising to non-Iranians but are common in Iran.

Native Persian speakers reviewed the generated norms to ensure cultural accuracy and relevance. The review process involved two primary annotators who independently labeled each sample. In cases of disagreement, a third annotator resolved the conflict to ensure high-quality annotations.

## Translation to English

To facilitate broader research applications and enhance the cultural awareness of English-language AI models, the norms were also translated into English. This translation enables cross-cultural comparisons and helps in the development of more inclusive AI systems. The Persian version of the dataset is available as `PSN-fa.csv`, and the English version is available as `PSN-en.csv`.

## Usage

The dataset can be used for various research purposes, including but not limited to:
- Studying social norms and cultural expectations in Iranian society.
- Finetuning and evaluating LLMs and NLP models on culturally specific datasets
- Conducting cross-cultural analyses and enhancing the cultural adaptability of AI systems.

## Citation

If you use this dataset in your research, please cite our paper:

## License

This dataset is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to thank the annotators and reviewers for their valuable contributions to this dataset.

---

Feel free to reach out if you have any questions or need further assistance.

Happy researching!

