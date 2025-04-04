# Project Boli Dataset

**Project Boli** is a multimodal dataset developed to support research into the characteristics, dynamics, and impact of stuttering. It contains synchronized audio, text, and metadata collected from individuals who stutter. The dataset is intended for use by researchers, clinicians, and speech-language professionals.

---

## 📁 Dataset Components

### 1. Stutter Types
Stuttering events in the dataset are categorized into the following five types:

| Code | Type             | Description                                      |
|------|------------------|--------------------------------------------------|
| B    | Block            | Sudden interruption or cessation of speech      |
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

---

### 3. Audio Files
`.wav` audio clips representing stuttering events.

- **Naming Convention:**
  - `B_fortell.wav`  
    - `B`: Block stutter  
    - `fortell`: Word during which the stutter occurred

Clips are aligned with transcript data.

---

### 4. Excel Metadata File
An Excel spreadsheet containing:

- Demographic details (e.g., age, gender)
- Questionnaire responses related to life experiences with stuttering
- Language background and task information

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

Please cite the dataset as follows:

