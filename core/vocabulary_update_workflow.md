# **Workflow for Updating Canonical Vocabulary and Developments**

## **1. Modular Input Tracking**

### Dynamic Input Logs
- All user inputs and GPT outputs related to new vocabulary and linguistic rules should be logged automatically in a dedicated file, e.g., `/logs/new_terms_log.md`.

### Classification Tags
Assign metadata to each entry, such as:
- **Category**: (e.g., noun, verb, ceremonial term, etc.)
- **Context**: (e.g., mythological, everyday, poetic, etc.)
- **Usage Examples**: Annotate examples for clarity.

---

## **2. Validation and Review Pipeline**

### Human Review
- Regularly review the log for consistency with existing rules in `/core/language_rules.md`.

### Automated Validation
- Develop a script in `/testing/automated_tests.md` to:
  - Cross-check new terms against phonological, morphological, and syntactic rules.
  - Flag entries that conflict with existing canonical definitions.

---

## **3. Integration into Core Definitions**

### Interactive Update System
- Use a command or dashboard option to integrate validated terms directly into `/core/language_rules.md` or `/modules/language_tools/lexicon_and_roots.md`.
- Allow tagging of terms as **provisional** or **canonical** during integration.

### Version Control
- Track changes using Git to maintain versioned backups of updates to the canonical language files.

---

## **4. Update Propagation**

### Automatic Sync Across Modules
- Once new vocabulary is added, automatically update all modules referencing the core definitions, including:
  - Syntax validation rules.
  - Dialect and evolution tools.
  - Ceremonial and poetic templates.

---

## **5. Feedback Loop for Refinement**

### User Suggestions
- Allow users to suggest refinements or additions to vocabulary via `/testing/user_feedback.md`.

### Iterative Refinement
- Revisit provisional entries after they’ve been used in multiple contexts for further validation or promotion to canonical status.

---

# **Proposed File and Workflow Enhancements**

## **Files for Vocabulary Updates**

1. **`/logs/new_terms_log.md`**:
   - Temporary storage for all new vocabulary.
   - Example format:
     ```
     - **Word**: Tharnvel (light-bearer)
     - **Category**: Noun
     - **Context**: Mythological
     - **Usage Example**: Tharnvel moravel thyra velor. ("The light-bearer carries truth.")
     - **Status**: Provisional
     ```

2. **`/testing/automated_tests.md`**:
   - Scripts to validate new terms against phonology, morphology, and syntax rules.

3. **`/core/language_rules.md`**:
   - Central repository of validated rules and vocabulary, updated regularly.

4. **`/modules/language_tools/lexicon_and_roots.md`**:
   - Derived from `/core/language_rules.md` for use in language tools.

---

## **Key Functionalities for Streamlining Updates**

### Automated Logging
- GPT captures all generated vocabulary terms during use and appends them to `/logs/new_terms_log.md` with contextual metadata.

### Validation Interface
- A web-based or command-line tool for reviewing, validating, and integrating new terms.

### Conflict Detection
- Automated scripts to highlight conflicts between new terms and existing rules (e.g., phonological violations or semantic overlaps).

### Provisional Vocabulary Integration
- A mechanism to test new terms in practice (e.g., myth generation or ceremonial language) before finalizing them in the core rules.

### Batch Updates
- Allow batch approval and integration of multiple new terms for large updates.

---

# **Example Workflow**

## **User Interaction**
1. User generates a new term while crafting a myth: *Velithnor* (light of the storm).
2. GPT appends it to `/logs/new_terms_log.md` with metadata:
   ```
   - **Word**: Velithnor
   - **Category**: Noun
   - **Context**: Poetic
   - **Usage Example**: Velithnor thyra moroth. ("The storm's light flows to rest.")
   - **Status**: Provisional
   ```

## **Validation Phase**
3. A reviewer or automated script checks the term for alignment with `/core/language_rules.md`:
   - Phonological match: **Pass**
   - Morphological construction: **Pass**
   - Semantic alignment: **Pass**

## **Integration Phase**
4. The term is approved and added to `/core/language_rules.md`:
   ```
   - Velithnor (Noun): Light of the storm. Context: Poetic, ceremonial.
   ```

5. Updates propagate automatically to dependent modules like `/modules/language_tools/lexicon_and_roots.md`.

---

# **Benefits**

1. **Scalability**: Easily handles large volumes of new vocabulary.
2. **Accuracy**: Ensures all updates adhere to canonical rules.
3. **Collaboration**: Allows users and contributors to participate in language evolution.
4. **Adaptability**: Supports testing and refinement before terms become canonical.
