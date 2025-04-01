# ✅ MANDATORY PRE-IMPLEMENTATION CHECKLIST

**❗ STOP!** Before writing ANY code or suggesting ANY changes, you MUST complete the following steps. This process ensures robust, root-cause-driven solutions — not temporary patches.

---

## 1. 🔍 SEARCH FIRST

Run the following to investigate the existing codebase and gather context:

- `grep_search` – search for relevant functionality  
- `file_search` – look for similar files or patterns  
- `list_dir` – inspect relevant directories  
- `@web` – *(optional but encouraged)* find industry-standard patterns, best practices and or novel methodologies online  

---

## 2. 📝 DOCUMENT FINDINGS

Fill out the following based on your investigation:

### Existing Files Found:
- [List all relevant files found]

### Existing Functionality:
- [Describe what already exists]

### Gaps Identified:
- [List what's missing or needs enhancements]

### Proposed Approach:
- [ ] Enhance existing code  
- [ ] Create new files *(requires justification)*  
- [ ] Refactor existing code
- [ ] If multiple good options are available, ask the user which approach they would like you to proceed with before proceeding

---

## 3. 🛠️ BEGIN IMPLEMENTATION

### Pre-Implementation Hypothesis

- What is the **root cause** of the issue based on the user's inqury and from Step 1?
- Why is your proposed solution the most **robust** and **reliable**, not just a cheap workaround?

✅ Revisit your Step 1 findings:  
- Did `grep`, `file_search`, or `list_dir` reveal reusable logic?  
- Use `@web` to find similar or stronger patterns.

⚠️ **Avoid bandaid fixes.** Prioritize code health and long-term stability.

### Plan your Edits
- [ ] Clearly list each change (file/function/line/component)
- [ ] Map each change directly to a gap identified in Step 2
- [ ] Note any risks, assumptions, or open questions

### Apply your Edits
- [ ] Accurcy and precision is very important when applying edits
- [ ] Always include comments in the code explaining how the code works
- [ ] Ensure your edits align with all previous steps
- [ ] Always compete step 4 (ADD COMMIT COMMENT) after successfully applying edits

---

## 4. 📝 ADD COMMIT COMMENT (include `git commit -m "[your commit comment]"` in your response)

- Use **Markdown formatting** for easy copy-paste
- Comments must be:
  - ✅ **Comprehensive**, yet **super brief**
  - ✅ Reflective of the **entire conversation & implementation**
  - ✅ Submitted only once you believe the issue is fully resolved

---

❌ **IF YOU SKIP THIS CHECKLIST, YOU ARE VIOLATING THE MOST IMPORTANT RULE** ❌
