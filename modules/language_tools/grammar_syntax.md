# **Grammar and Syntax for Aeltharic GPT OS**

## **Purpose**
This document outlines the grammar and syntax rules of the Aeltharic language. It provides guidance for sentence construction, word order, and grammatical inflection.

---

## **1. Sentence Structure**

### **Default Word Order**
- **Subject-Verb-Object (SVO)**
  - Example: *Velkalor thyra drith.*
    - Translation: "The light guards the shadow."

### **Complex Sentences**
- **Subordinate Clauses**:
  - Introduced with:
    - *Es-* (if): Conditional.
    - *Thar-* (because): Causal.
  - Example:
    *Tharilnar thyra velkalor, drithnor thyra tharvel.*
    - Translation: "Why does the flame shine? Because shadow guards balance."

---

## **2. Grammatical Features**

### **Noun Cases**
| **Case**       | **Suffix** | **Usage**                           | **Example**                     |
|----------------|------------|-------------------------------------|---------------------------------|
| Nominative     | *(none)*   | Subject of the sentence             | *Velkalor* (The shining flame) |
| Accusative     | *-en*      | Direct object                       | *Velkaloren* (the flame)       |
| Instrumental   | *-on*      | Means by which an action is done    | *Velkaloron* (by the flame)    |

### **Verb Inflection**
- **Tense**:
  - Present: *(none)*
  - Past: *-in*
  - Future: *-is*
  - Example:
    - *Moravel*: Carries.
    - *Moravelin*: Carried.
    - *Moravelis*: Will carry.
- **Aspect**:
  - Continuous: *-eth*
  - Perfective: *-ar*
  - Example:
    - *Drithkaleth*: Continuously shadowing.
    - *Drithkalar*: Perfectly shadowed.

### **Modifiers**
1. **Adjectives**:
   - Follow the noun they modify.
   - Example: *Thyra moroth* (The fragile gate).
2. **Adverbs**:
   - Precede the verb they modify.
   - Example: *Esmor thyra velkalor.* (Quickly, the flame shines.)

---

## **3. Syntax Rules**

### **Prepositional Phrases**
- Prepositions always precede the noun.
  - Example: *Thar velkalor thyra moroth.*
    - Translation: "For the flame guards the fragile gate."

### **Questions**
- **Yes/No Questions**:
  - Use *Es-* as a prefix.
  - Example: *Esvelkalor thyra drith?*
    - Translation: "Does the light guard the shadow?"
- **Open-Ended Questions**:
  - Use *Thar-* (why/how).
  - Example: *Tharilnar thyra drithkalor?*
    - Translation: "Why does the shadow flame shine?"

### **Negation**
- Prefix: *Noth-* (not).
  - Example: *Nothvelkalor thyra drith.*
    - Translation: "The light does not guard the shadow."

---

## **4. Sentence Types**

### **Declarative**
- Simple statement of fact.
  - Example: *Velkalor thyra drith.*
    - Translation: "The flame guards the shadow."

### **Imperative**
- Commands.
  - Example: *Velkalor thyra alor!* ("Light the gate now!")

### **Interrogative**
- Questions.
  - Example: *Esvelkalor thyra drith?*
    - Translation: "Does the flame guard the shadow?"

### **Exclamatory**
- Express strong emotion.
  - Example: *Velkalor al thyra moroth!*
    - Translation: "The flame shines on the fragile gate!"

---

## **5. Integration with Other Modules**

### **Lexicon Integration**
- Validate that new terms in `/modules/language_tools/lexicon_and_roots.md` conform to these grammatical rules.

### **Syntax Validator**
- Automate error checking for sentence structure.
  - Example: Ensure adjectives follow nouns and verbs align with tense and aspect.

---

## **6. Feedback and Expansion**
1. Log examples of incorrect syntax in `/testing/user_feedback.md` for analysis.
2. Refine rules and add exceptions based on real-world testing outputs.

Let me know if additional examples or rules are needed!
