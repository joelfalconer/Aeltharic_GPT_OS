# **Automated Tests for Aeltharic GPT OS**

## **Purpose**
This document outlines a comprehensive suite of automated tests designed to validate the syntax, semantics, and creative outputs of the Aeltharic GPT OS. These tests ensure adherence to Aeltharic language rules, worldbuilding principles, and user-defined guidelines for mythological, linguistic, and cultural consistency.

---

## **1. Categories of Tests**

### **1.1 Syntax Validation**
Tests for proper grammatical structure and adherence to the rules defined in `language_rules.md`.

#### **1.1.1 Sentence Structure**
- **Objective**: Verify compliance with defined syntax rules (e.g., SOV, OSV, or VSO based on context).
- **Test Cases**:
  1. Input: "Velar thyra moravel drith."
     - Expected: Valid.
     - Rationale: Proper SOV syntax for a neutral narrative.
  2. Input: "Thyra drith velar moravel."
     - Expected: Invalid.
     - Rationale: Syntax mismatch with the neutral narrative context.

#### **1.1.2 Morphological Rules**
- **Objective**: Ensure correct use of roots, affixes, and compounds.
- **Test Cases**:
  1. Input: "Thalvethis kal moravel."
     - Expected: Valid.
     - Rationale: Proper compounding of roots for "Ocean-Child guards fragile truth."
  2. Input: "Thal-vethis kal."
     - Expected: Invalid.
     - Rationale: Incorrect hyphenation in root compounding.

---

### **1.2 Semantic Integrity**
Tests to validate coherence, duality, and symbolic depth in generated outputs.

#### **1.2.1 Duality Representation**
- **Objective**: Confirm the interplay of light/shadow, creation/destruction in outputs.
- **Test Cases**:
  1. Input: "Generate a phrase about balance."
     - Expected Output: "Velar drith moravel thyra." (Light shadows fragile truth at the gate.)
     - Validation: Duality expressed in symbolic terms.

#### **1.2.2 Archetype Alignment**
- **Objective**: Ensure generated narratives align with defined archetypes in `mythos_and_philosophy.md`.
- **Test Cases**:
  1. Input: "Create a myth involving The Wanderer and The Keeper."
     - Expected Archetypes: The Wanderer seeks a gate guarded by The Keeper.
     - Validation: Narrative aligns with archetypal roles and mythological principles.

---

### **1.3 Creative Outputs**
Tests for modularity and richness in generated myths, poetry, and dialogues.

#### **1.3.1 Myth Generation**
- **Objective**: Validate modular prompt system for crafting myths.
- **Test Cases**:
  1. Input: "Generate a creation myth."
     - Expected Output: Myth aligning with `myth_generator.md`, showcasing cosmic origins and archetypes.
     - Validation: Inclusion of key elements (e.g., tension of opposites, Archetypes).

#### **1.3.2 Poetic Construction**
- **Objective**: Ensure rhythmic and thematic customization.
- **Test Cases**:
  1. Input: "Write an invocation for a ritual."
     - Expected Output: Poem adhering to Aeltharic rhythm and ceremonial tone.

---

### **1.4 Glyph Validation**
Tests for visual consistency and symbolic alignment in glyphs generated using `glyph_generator.md`.

#### **1.4.1 Glyph Syntax**
- **Objective**: Validate the structural design of glyphs based on linguistic roots.
- **Test Cases**:
  1. Input: Root "Vel" (Light).
     - Expected Glyph: Circular patterns emphasizing illumination.
  2. Input: Compound "Velisdrithar" (Light-Shadow Keeper).
     - Expected Glyph: Interwoven circles and sharp edges symbolizing balance.

#### **1.4.2 Visual Aesthetics**
- **Objective**: Confirm glyphs align with cultural principles from `visual_examples.md`.
- **Test Cases**:
  1. Input: "Design a glyph for Kalithron Velarinos."
     - Expected: Glyph reflects "The Forge of Beginnings" with radiant and structured patterns.

---

## **2. Automation Framework**

### **2.1 Input Validation**
- Check for proper format and expected context before processing.
- Example: Reject inputs with syntax violations.

### **2.2 Output Comparison**
- Compare generated outputs against canonical examples in:
  - `mythos_and_philosophy.md`
  - `language_rules.md`

### **2.3 Iterative Testing**
- Adjust prompts dynamically based on intermediate results to refine output accuracy.

---

## **3. Reporting and Feedback**

### **3.1 Error Logs**
- Maintain detailed logs of failed test cases.
- Include:
  - Input string.
  - Expected vs. actual output.
  - Suggested corrections.

### **3.2 User Feedback Integration**
- Prompt users to rate the coherence and relevance of generated outputs.
- Utilize feedback to iteratively refine test cases.

---

## **4. Sample Workflow**

1. **Input**: "Generate a heroic tale about The Ruiner."
2. **Validation**:
   - Syntax: Check sentence structure.
   - Semantics: Ensure The Ruiner embodies chaos and renewal.
   - Creative Depth: Verify narrative richness and alignment with archetypal roles.
3. **Output**: "The Ruiner casts shadow upon the Forge, birthing the first flame."
4. **Logs**:
   - Passed: Syntax, semantic integrity.
   - Failed: None.

---

## **5. Next Steps**

1. Expand test cases for evolving linguistic rules in `evolution_and_dialects.md`.
2. Integrate automated testing for user-submitted inputs.
3. Develop visual diff tools for glyph validation.

---

## **Conclusion**
The automated tests ensure that Aeltharic GPT OS consistently produces outputs that are linguistically accurate, culturally resonant, and creatively compelling. By adhering to these guidelines, the system evolves to meet the intricate demands of Aeltharic’s mythos and worldbuilding frameworks.
