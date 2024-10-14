# Iranian Social Norm Dataset

Welcome to the Iranian Social Norm Dataset repository! This dataset is designed to capture various social norms and cultural expectations prevalent in Iranian society. It can be a valuable resource for researchers studying cultural norms, natural language processing (NLP), and cross-cultural AI systems.

## Dataset Description

The dataset consists of four primary columns:

- **Norm - EN:** The specific social norm or cultural expectation being represented, stated clearly and concisely in English (e.g., 'Showing respect for elders').
- **Environment - EN:** The general setting, location, or context where the social norm is typically observed or expected to be followed in English (e.g., 'family gatherings', 'public spaces', 'workplace').
- **Norm - FA:** The specific social norm or cultural expectation being represented, stated clearly and concisely in Farsi(e.g., 'Showing respect for elders').
- **Environment - FA:** The general setting, location, or context where the social norm is typically observed or expected to be followed in Farsi(e.g., 'family gatherings', 'public spaces', 'workplace').
- **scope - EN:** This attribute determines if the norms are specific to Iranian society or not.
- **Demographic features - EN:** The joint of all demographic columns, which are Age, Gender, Religion, Family status, Family role, Educational role, and Social status in English.
- **Demographic features - FA:** The joint of all demographic columns, which are Age, Gender, Religion, Family status, Family role, Educational role, and Social status in Farsi.
- **Age - EN:** The Age of the person that the norm is associated with in English. Possible values: child, adult, elderly, and young.
- **Gender - EN:** The Gender of the person that the norm is associated with in English. Possible values: woman and man.
- **Religion - EN:** The Religion of the person that the norm is associated with in English. Possible values: Muslim, Christian, Jewish, Zoroastrian, and Not Muslim.
- **Ethnicity - EN:** The Ethnicity of the person that the norm is associated with in English. Possible values: Fars, Turk, Kurd, Arab, Baluch, Turkmen, and Qashqai.
- **Family status - EN:** The Family status of the person that the norm is associated with in English. Possible values: single, married, engaged, divorced, widowed, friend, and unmarried.
- **Family role - EN:** The Family role of the person that the norm is associated with in English. Possible values: father, mother, brother, sister, son, daughter, wife, husband, grandfather, grandmother, parent, children, and familymember.
- **Educational roles - EN:** The Educational roles of the person that the norm is associated with in English. Possible values: student, teacher, professor, University student.
- **Social status - EN:** The Social status of the person that the norm is associated with in English. Possible values: poor, middle class, and wealthy.
- **Age - FA:** The Age of the person that the norm is associated with in Farsi. Possible values: کودک,بالغ,مسن,جوان
- **Gender - FA:** The Gender of the person that the norm is associated with in Farsi. Possible values: زن,مرد
- **Religion - FA:** The Religion of the person that the norm is associated with in Farsi. Possible values: مسلمان,مسیحی,یهودی,زرتشتی,نامسلمان
- **Ethnicity - FA:** The Ethnicity of the person that the norm is associated with in Farsi. Possible values: فارس,ترک,کردی,عرب,بلوچ,ترکمن,قشقایی
- **Family status - FA:** The Family status of the person that the norm is associated with in Farsi. Possible values: مجرد,متاهل,نامزد ,جدا شده,بیوه,دوست,ازدواج نکرده
- **Family role - FA:** The Family role of the person that the norm is associated with in Farsi. Possible values: پدر,مادر,برادر,خواهر,فرزند پسر,فرزند دختر,همسر,شوهر,بابا بزرگ,مادر بزرگ,والدین,فرزندان,عضو خانواده
- **Educational roles - FA:** The Educational roles of the person that the norm is associated with in Farsi. Possible values: دانش آموز,معلم,استاد,دانشجو.
- **Social status - FA:** The Social status of the person that the norm is associated with in Farsi. Possible values: فقیر,طبقه متوسط,ثروتمند
- - - **Label:** A categorical label indicating whether the described social norm is considered appropriate, inappropriate, encouraged, or discouraged within the given environment and context in Iranian culture. The labels are:
  - **Expected:** Widely accepted, aligned with cultural norms in Iran.
  - **Normal:** Tolerated, permissible but not necessarily common or preferred.
  - **Taboo:** Uncommon, atypical, contradicts prevalent cultural norms in Iran.

## Data Statistics

The dataset contains 1,700 samples. The distribution of labels is as follows:
- **Expected:** 44.9%
- **Normal:** 31.1%
- **Taboo:** 24%

## Data Construction

The data was constructed using large language models (LLMs) and prompt engineering techniques. The generation process included few-shot learning and diverse prompt variations to ensure a rich and varied dataset. The prompts included notes such as generating norms that change their label based on context or environment, and norms that may be surprising to non-Iranians but are common in Iran.

Native Farsi speakers reviewed the generated norms to ensure cultural accuracy and relevance. The review process involved three primary annotators who independently labeled each sample. 

## Translation to English

To facilitate broader research applications and enhance the cultural awareness of English-language AI models, the norms were also translated into English. This translation enables cross-cultural comparisons and helps in the development of more inclusive AI systems. 

## Usage

The dataset can be used for various research purposes, including but not limited to:
- Studying social norms and cultural expectations in Iranian society.
- Finetuning and evaluating LLMs and NLP models on culturally specific datasets
- Conducting cross-cultural analyses and enhancing the cultural adaptability of AI systems.

## License

This dataset is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to thank the annotators and reviewers for their valuable contributions to this dataset.

---

Feel free to reach out if you have any questions or need further assistance.

Happy researching!

