# **Morphology Builder**

## **Purpose**
The `Morphology Builder` module defines and refines rules for word formation and morphological structures within the Aeltharic conlang. By establishing consistent guidelines for root and affix interactions, declension, conjugation, and dialectal variations, this tool ensures linguistic integrity and versatility.

---

## **1. Root and Affix Interactions**

### **1.1 Principles of Morphological Composition**
- **Root Definition**: The core semantic unit of a word.
- **Affix Types**:
  - **Prefixes**: Modify meaning by specifying nuances (e.g., negation, intensity).
  - **Suffixes**: Indicate grammatical categories (e.g., tense, case).
  - **Infixes**: Infused within roots for emphasis or ceremonial tones.

### **1.2 Harmony Rules**
- Maintain consonant-vowel harmony when combining roots and affixes.
- Ensure phonotactic constraints are adhered to, as defined in `phonology_toolkit.md`.

### **1.3 Semantic Integrity**
- Preserve root meaning while allowing affixes to modify scope, intensity, or grammatical role.

---

## **2. Declension and Conjugation**

### **2.1 Declension System**
Declension defines how nouns and adjectives change form based on grammatical case, number, and gender.

#### **2.1.1 Declension Cases**
1. **Nominative**: Subject of the sentence.
2. **Accusative**: Direct object of the verb.
3. **Genitive**: Possession or origin.
4. **Dative**: Indirect object.
5. **Ablative**: Motion away from or cause.

#### **2.1.2 Example Declension Table**
| Case         | Singular Root | Plural Root |
|--------------|---------------|-------------|
| Nominative   | velar         | velarion    |
| Accusative   | velarth       | velarionth  |
| Genitive     | velarin       | velarionen  |
| Dative       | velareth      | velarioneth |
| Ablative     | velaror       | velarionor  |

### **2.2 Conjugation System**
Conjugation applies to verbs to indicate tense, mood, aspect, and voice.

#### **2.2.1 Tenses**
- **Past**: Actions completed before now.
- **Present**: Actions occurring now.
- **Future**: Actions that will occur.

#### **2.2.2 Example Conjugation Table**
| Tense   | Root      | Conjugated Form |
|---------|-----------|-----------------|
| Past    | morath    | morathin        |
| Present | morath    | morathas        |
| Future  | morath    | morathor        |

#### **2.2.3 Additional Features**
- **Mood**: Indicative, imperative, subjunctive.
- **Voice**: Active, passive, and reflexive.

---

## **3. Dialectal Variations in Morphology**

### **3.1 Phonological Shifts**
- Regional dialects may alter affix pronunciations.
- Example: Morathic suffix "-in" becomes "-yn" in Thyrinic.

### **3.2 Morphological Constructs**
- Compound words vary by region:
  - Standard: _kaldrithar_ (flame-shadow).
  - Highland Dialect: _kaldrithir_ (flame-dark).

### **3.3 Case Reduction in Dialects**
- Some dialects simplify case systems:
  - Example: Northern Highland reduces the genitive and ablative cases to a single possessive case.

---

## **4. Examples of Morphological Constructs**

### **4.1 Nominal Constructs**
- Root: _thal_ (gate).
- Derived: _thalasor_ (gatekeeper).

### **4.2 Verbal Constructs**
- Root: _vel_ (to shine).
- Derived: _velaroth_ (it shines brightly).

### **4.3 Compound Words**
- _kalvelar_ (flame-light): Combining _kal_ (flame) and _velar_ (light).

---

## **5. Practical Applications**

### **5.1 Vocabulary Expansion**
Use this module to:
- Create new nouns, verbs, and adjectives based on user prompts.
- Generate culturally specific terms for rituals, myths, and daily use.

### **5.2 Testing Morphology**
- Validate forms using `automated_tests.md` to ensure phonological harmony and grammatical accuracy.

---

## **6. Integration with Other Modules**
- **`phonology_toolkit.md`**: Ensures morphological constructs adhere to sound system rules.
- **`evolution_and_dialects.md`**: Models how morphology evolves over time or across regions.
- **`lexicon_expander.md`**: Automatically incorporates generated constructs into the lexicon.

---

Developed as part of the Aeltharic GPT OS to enhance linguistic creativity and consistency.
