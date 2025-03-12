# Persian-user-profile-data
## 🗂️ Dataset Description

This is a **Persian dataset** containing **6,652 utterances** collected from different input sources, as shown in the table below.
### Table 1: Five main input sources of data collected in the research of Safari and Shamsfard (2024)

| Type                    | Resource                                                                                   | Dialogue No. | Utterance No. |
|-------------------------|--------------------------------------------------------------------------------------------|--------------|----------------|
| general data collection | English training sites with Persian transcriptions  <br> a dataset of free discussion dialogues | 74 <br> 99   | 571 <br> 2918  |
| translation             | manual translation of ConvAI2 corpus (Dinan et al., 2020)                                  | 72           | 1000           |
| gamification            | gamification through an online chatting site  <br> with random profiles for participants   | 94           | 1557           |
| augmentation            | augmenting semantic frames in the previously  <br> collected data by semi & fully automatic methods | -            | 336            |
| generation              | Instructing GPT-3.5 to generate dialogues  <br> without/with desired personal info.         | 335          | 5094           |

Each utterance is annotated with up to **three topic labels** and corresponding **slot values**.

### 🏷️ Topic Categories (13 total)
- greeting
- gender
- name
- education
- age
- marriage
- residence
- hobby
- family
- job
- goodbye
- weather
- other

### 🔢 Slot Types (9 total)
- name
- gender
- age
- residence
- marital status
- job
- hobby
- number of children
- number of siblings

### 📩 Access

To request access to the dataset, please contact: **pegh.safari@gmail.com**

## 📚 Citation

If you use this dataset or any part of this project, please cite the following paper:

> Safari, P., & Shamsfard, M. (2024). *Data augmentation and preparation process of PerInfEx: A Persian chatbot with the ability of information extraction*. IEEE Access, 12, 19158–19180.

### BibTeX
```bibtex
@article{safari2024data,
  title={Data augmentation and preparation process of perinfex: A persian chatbot with the ability of information extraction},
  author={Safari, Pegah and Shamsfard, Mehrnoush},
  journal={IEEE Access},
  volume={12},
  pages={19158--19180},
  year={2024},
  publisher={IEEE}
}

