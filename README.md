# Project Boli Dataset

**Project Boli** is a multilingual dataset developed to support research into the characteristics and impact of stuttering. It contains synchronized audio, text, and metadata collected from individuals who stutter. The dataset is intended for use by researchers, clinicians, and speech-language professionals.

---

## 📁 Dataset Components

### 1. Stutter Types
Stuttering events in the dataset are categorized into the following five types:

| Code | Type             | Description                                      |
|------|------------------|--------------------------------------------------|
| B    | Block            | Pausing or blockage in speech                    |
| IN   | Interjections    | Unintended insertions of sounds or words        |
| PR   | Prolongations    | Unusually extended sounds within a word         |
| SR   | Sound Repetition | Repetition of syllables or individual sounds    |
| WR   | Word Repetition  | Repetition of entire words                      |

---

### 2. Transcripts
Textual transcriptions of recorded speech with annotations marking the stuttering events.

- **Naming Convention:**
  - `10_727253_EI.txt`  
    - `10`: Number of stuttering instances  
    - `727253`: Speaker ID  
    - `EI`: "Explain Image" task in English  
  - `10_727253_E1.txt`  
    - Same speaker, first English paragraph task

Each transcript includes timestamps and stutter type labels.

- **File Format Explanation:**
  - Each stuttering instance is represented by **two lines**:
    1. The **first line** shows start time, end time, and stutter type.
    2. The **second line** repeats the timestamps followed by the stuttered word.
   
    For Example :

      | 5.526907   | 6.871290   | SR           |
      | 5.526907   | 6.871290   | s s sunset   |


---

### 3. Audio Files
`.wav` audio clips representing stuttering events corresponding to which the transcripts are provided..


Provided audio clips are aligned with transcript data.

---

### 4. Excel Metadata and Questionnaire File
Excel spreadsheet contains:

- Demographic details (e.g., age, gender)
- Questionnaire responses related to life experiences with stuttering

This data supports in-depth analysis and cross-referencing with audio/text features.

---

## ✅ Intended Use

Project Boli can be used for:

- Research in speech-language pathology
- Training machine learning models for stutter detection
- Clinical assessments and therapy tools
- Linguistic analysis of disfluencies

---

## 📄 Citation

A. Batra, M. Narang, N. K. Sharma and P. K. Das, "Boli: A dataset for understanding stuttering experience and analyzing stuttered speech," ICASSP 2025 - 2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Hyderabad, India, 2025, pp. 1-4, doi: 10.1109/ICASSP49660.2025.10888349. keywords: {Tongue;Annotations;Open Access;Event detection;Manuals;Signal processing;Data collection;Acoustics;Multilingual;Speech processing;Indian stuttered speech dataset;Intelligibility assessment;read speech;spontaneous speech;Stuttering event detection},



