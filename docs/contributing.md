# **Contributing to the Aeltharic GPT OS**

## **Purpose**
The purpose of this document is to provide clear guidelines for contributing to the Aeltharic GPT OS. Contributions include developing modules, enhancing functionality, expanding language rules, and refining the creative and testing tools. All contributions should align with the linguistic and cultural framework of Aeltharic.

---

## **Code of Conduct**

### **Core Principles**
1. **Respect and Collaboration**: Contributors should foster a positive, collaborative environment.
2. **Adherence to Aeltharic Canon**: Ensure all contributions reflect the duality, cosmic cycles, and linguistic rules of Aeltharic.
3. **Open and Constructive Feedback**: Engage in respectful discussions for improvement.
4. **Inclusivity**: Contributions should welcome diverse ideas and perspectives.

For detailed guidelines, refer to the [Code of Conduct](#).

---

## **How to Contribute**

### **1. Reporting Issues**
- **Bug Reports**:
  - Clearly describe the issue.
  - Provide examples of incorrect or unexpected outputs.
  - Include steps to reproduce the issue, if possible.

- **Feature Requests**:
  - Explain the feature's purpose and its alignment with Aeltharic principles.
  - Provide examples or mockups if applicable.

Submit issues via the [GitHub Issue Tracker](#).

### **2. Suggesting Enhancements**
1. Ensure enhancements align with existing Aeltharic themes and rules.
2. Provide a clear description and rationale.
3. Where possible, include examples, such as:
   - Proposed glyphs for the `glyph_generator.md`.
   - Sample myths for the `myth_generator.md`.
   - Dialogue templates for `character_and_dialogue.md`.

### **3. Developing Modules and Tools**
Follow the steps below for proposing new modules or tools:

1. **Scope Definition**:
   - Define the purpose and target users.
   - Identify its relationship with existing modules (e.g., integrates with `poetic_and_ceremonial.md`).

2. **Implementation Plan**:
   - Describe the functionality.
   - Include examples and mock data where applicable.

3. **Validation**:
   - Develop test cases aligning with `automated_tests.md`.
   - Ensure outputs comply with `language_rules.md`.

4. **Submission**:
   - Fork the repository and create a new branch.
   - Implement changes.
   - Submit a pull request with detailed notes.

---

## **Workflow**

### **1. Forking the Repository**
1. Fork the main repository to your GitHub account.
2. Clone the fork to your local environment.
3. Set the original repository as the upstream remote:
   ```bash
   git remote add upstream <repository_url>
   ```

### **2. Working on Contributions**
1. **Create a Branch**:
   Use a descriptive branch name:
   ```bash
   git checkout -b feature/myth-enhancements
   ```

2. **Make Changes**:
   - Follow the structure and standards outlined in `system_instructions.md`.
   - Test functionality using the scripts in `automated_tests.md`.

3. **Commit Changes**:
   Write clear and concise commit messages:
   ```bash
   git commit -m "Added new myth template to `myth_generator.md`."
   ```

4. **Sync with Upstream**:
   Regularly sync your fork with the main repository:
   ```bash
   git fetch upstream
   git merge upstream/main
   ```

### **3. Submitting Changes**
1. Push changes to your fork:
   ```bash
   git push origin feature/myth-enhancements
   ```
2. Open a pull request:
   - Provide a detailed description of the changes.
   - Link to relevant issues, if applicable.
   - Specify how the changes adhere to Aeltharic rules.

---

## **Standards and Requirements**

### **1. Adherence to Language Rules**
- Ensure all contributions align with `language_rules.md`.
- Validate outputs against phonological, morphological, and syntactic principles.

### **2. Testing and Validation**
- Develop test cases using `automated_tests.md`.
- Perform manual testing for creative modules.
- Use examples to demonstrate functionality and adherence.

### **3. Documentation**
- Update relevant Markdown files.
- Include clear instructions, examples, and edge cases.
- Ensure changes are reflected in `readme.md` and `roadmap.md` if applicable.

---

## **Contribution Areas**

### **1. Language Development**
- Expand the lexicon in `lexicon_and_roots.md`.
- Refine grammar in `grammar_syntax.md`.

### **2. Creative Tools**
- Add myth templates to `myth_generator.md`.
- Propose poetic forms in `poetic_and_ceremonial.md`.

### **3. Visual Tools**
- Develop glyphs in `glyph_generator.md`.
- Add examples to `visual_examples.md`.

### **4. Testing and Feedback**
- Enhance `automated_tests.md`.
- Suggest improvements in `user_feedback.md`.

---

## **Review Process**
1. A maintainer will review your pull request within 7 business days.
2. Feedback will be provided for revisions, if needed.
3. Once approved, your changes will be merged into the main branch.

---

## **Acknowledgments**
We appreciate your contributions to the Aeltharic GPT OS. Your efforts help refine the system and bring Aeltharic to life for users worldwide.
