# **Phonology Toolkit for Aeltharic GPT OS**

## **Purpose**
The `phonology_toolkit.md` provides tools and guidance for designing, refining, and evolving phonological systems within the Aeltharic constructed language (conlang). This toolkit is essential for ensuring that all linguistic constructs adhere to the phonotactic constraints, consonant-vowel harmony, and thematic principles intrinsic to the Aeltharic framework. Additionally, it supports the simulation of phonological drift across dialects.

---

## **1. Sound Inventory Creation**

### **1.1 Core Phonemes**
The Aeltharic sound inventory is built on a balance of consonants and vowels that evoke ceremonial and mythological resonance. Use the following guidelines:

#### **1.1.1 Consonants**
| Place of Articulation | Stops  | Fricatives | Nasals | Approximants |
|------------------------|--------|------------|--------|--------------|
| Bilabial              | /p/, /b/ | /f/, /v/   | /m/    |              |
| Alveolar              | /t/, /d/ | /s/, /z/   | /n/    | /l/          |
| Velar                 | /k/, /g/ | /x/        |        | /w/          |
| Glottal               |          | /h/        |        |              |

#### **1.1.2 Vowels**
| Height       | Front     | Central  | Back     |
|--------------|-----------|----------|----------|
| High         | /i/, /ɪ/  |          | /u/, /ʊ/ |
| Mid          | /e/, /ɛ/  | /ə/      | /o/, /ɔ/ |
| Low          | /æ/       | /a/, /ɑ/ |          |

#### **1.1.3 Diphthongs**
| Diphthongs   | Example Words      |
|--------------|--------------------|
| /ai/         | Aeltharic          |
| /ei/         | Velarion           |
| /au/         | Drithauros         |

### **1.2 Steps for Custom Sound Inventory Creation**
1. Identify thematic focus (e.g., harsh consonants for martial contexts).
2. Select a subset of core phonemes.
3. Ensure consonant-vowel harmony.
4. Test with sample words.

---

## **2. Rules for Consonant-Vowel Harmony**

### **2.1 Harmony Principles**
Aeltharic maintains melodic harmony by pairing consonants and vowels based on their phonetic properties. This ensures ceremonial and poetic resonance.

#### **2.1.1 Core Rules**
- **Front vowels** (/i/, /e/) pair with alveolar and bilabial consonants.
- **Back vowels** (/u/, /o/) pair with velar consonants.
- Neutral vowels (/ə/) can appear in any context but are rare in ceremonial language.

#### **2.1.2 Example**
- Valid Pairing: `/tɛ/` (front consonant with front vowel).
- Invalid Pairing: `/kɛ/` (back consonant with front vowel).

### **2.2 Stress and Intonation**
- Stress typically falls on the penultimate syllable for most words.
- Intonation rises at the end of interrogative sentences.

---

## **3. Phonotactic Constraints**

### **3.1 Syllable Structure**
Aeltharic syllables follow the CV(C) structure:
- **C**: Consonant (mandatory).
- **V**: Vowel (mandatory).
- **(C)**: Optional closing consonant.

#### **Examples**
- **Valid**: /vel/, /drith/, /ael/.
- **Invalid**: /dvr/, /thlk/.

### **3.2 Phoneme Distribution**
1. Avoid clusters of more than two consonants.
2. Prohibit glottal stops in stressed syllables.

---

## **4. Guidelines for Phonological Evolution**

### **4.1 Dialectal Variations**
Phonological changes across dialects may involve:
1. **Lenition**: /t/ → /d/.
2. **Vowel Shift**: /a/ → /ɛ/.
3. **Cluster Reduction**: /str/ → /s/.

#### **Examples**
- Standard: /velar/ → Dialectal: /vɛlɛr/.
- Standard: /drithauros/ → Dialectal: /dritʰauros/.

### **4.2 Simulating Drift**
1. Apply gradual changes to specific phonemes.
2. Test resulting forms against phonotactic rules.
3. Integrate cultural or geographical influences to justify changes.

---

## **5. Practical Applications**

### **5.1 Generating Words**
- Use `lexicon_expander.md` to validate and store new words.
- Example Workflow:
  1. Generate a base word: `/velar` (guardian).
  2. Apply suffix: `/velaros` (of the guardian).

### **5.2 Creating Names**
Names in Aeltharic often follow the CV(C)V pattern:
- Example: /Tharion/, /Aelthyra/.

---

## **6. Tools and Resources**

- **Automated Phonology Tests**: Validate phonological integrity using `/testing/automated_tests.md`.
- **Glyph Alignment**: Pair phonemes with visual glyphs in `glyph_generator.md`.

---

This toolkit is integral to maintaining linguistic consistency and aesthetic resonance within the Aeltharic GPT OS. For further guidance, refer to the `language_rules.md` or consult the `user_feedback.md` for community insights.
