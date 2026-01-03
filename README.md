# 🐼 Panda Template Manifest – SEO Agency Template

> **This document defines how AI must understand and operate on the SEO Agency template inside Panda.**  
> It is the highest authority for all AI-driven code suggestions.

---

## 1. Template Metadata (DO NOT MODIFY STRUCTURE)

```md
# Panda Template Manifest

template_name: "SEO Agency"
template_id: "panda-seo-agency-001"
template_version: "1.0.0"
template_type: "marketing-landing"
layout_style: "conversion-focused"
technology_stack: ["HTML5", "CSS3"]
responsive: true
dark_mode: false
rtl_supported: false

author: "Panda Templates"
last_updated: "2026-01-04"
```

---

## 2. Template Intent & Design Philosophy

```md
## Template Intent

This template is designed for:
- SEO agencies
- Digital marketing firms
- Growth consultants
- Performance marketing teams

Primary goals:
- Communicate authority & trust
- Explain SEO services clearly
- Drive lead generation
```

### Design Rules

```md
## Design Rules

- Conversion-first layout
- Data & metrics oriented sections
- Clear CTA placement
- Minimal distractions
```

⚠️ **AI DESIGN RULE**  
Do NOT introduce decorative-only elements that reduce conversion clarity.

---

## 3. File & Folder Structure (SOURCE OF TRUTH)

```md
## File Structure

/
├── index.html                         # Primary landing page
├── seo-agency/
│   ├── standalone.html                # Alternate layout
│   ├── css/
│   │   ├── style.css                  # Core styles (READ-ONLY)
│   │   └── custom.css                 # Overrides (READ-ONLY)
├── vendor/                            # Third-party libraries (READ-ONLY)
├── assets/                            # Images and icons
```

---

## 4. Change Control Rules (CRITICAL – AI ENFORCED)

### styles.css & custom.css (STRICT)

```md
- style.css and custom.css are READ-ONLY by default
- Modify CSS ONLY if explicitly requested by the user
- Vendor CSS must NEVER be edited
```

---

### Images (STRICT)

```md
Images are READ-ONLY by default.

Allowed ONLY if user:
- Mentions the specific image (filename/path/section), OR
- Provides a direct image URL

Vague visual requests must be rejected.
```

---

### Sections (STRICT)

```md
ALL sections are IMMUTABLE by default.

The AI MUST NOT:
- Add sections
- Remove sections
- Reorder sections

Allowed ONLY if user explicitly names the section.
```

---

## 5. Default AI Assumptions

```md
Unless explicitly stated:

- HTML structure remains unchanged
- CSS remains unchanged
- Images remain unchanged
- All sections remain present
- Only TEXT CONTENT is editable
```

---

## 6. Sections Overview (AI NAVIGATION MAP)

```md
1. Header / Navigation
2. Hero
3. Trust Indicators
4. SEO Services
5. Process
6. Case Studies
7. Testimonials
8. Pricing / Plans
9. CTA / Lead Form
10. Footer
```

---

## 7. Section-Level Contracts

```md
## Section: Hero

section_id: "hero"
html_container_id: "hero-section"
css_scope_prefix: ".hero"

Purpose:
- Establish authority
- Communicate core value

Editable Content:
- Headline
- Subheadline
- CTA text

Non-Editable:
- Layout
- Class names
```

---

## 8. Section Integrity Contract

```md
Sections are IMMUTABLE by default.

AI MAY:
- Edit text content

AI MUST NOT:
- Modify structure
- Rename classes or IDs
- Remove containers
```

---

## 9. CSS Architecture Rules

```md
- Section-scoped styles
- No frameworks
- No !important usage
- Mobile-first approach
```

---

## 10. Typography System

```md
Typography defined in CSS
AI must NOT change fonts unless explicitly requested
```

---

## 11. Color System

```md
Colors defined in CSS
AI must NOT introduce new colors unless explicitly approved
```

---

## 12. AI Code Suggestion Modes

### Full Code Suggestion

```md
- Return full file content
- Use only for major updates
```

### Diff-Based Partial Suggestion

```md
- Return minimal diffs
- Preferred for small edits
```

---

## 13. Mode Conflict Resolution

```md
Priority:
1. Explicit user instruction
2. Diff-based suggestion
3. Full code suggestion
```

---

## 14. Change Permission Matrix

```md
| Change Type       | Default | Explicit |
|------------------|---------|----------|
| Text             | ✅      | ❌       |
| CSS              | ❌      | ✅       |
| Images           | ❌      | ✅       |
| Sections         | ❌      | ✅       |
| Vendor files     | ❌      | ❌       |
| New files        | ❌      | ✅       |
| JavaScript       | ❌      | ✅       |
```

---

## 15. AI Hard Stop Conditions

```md
The AI MUST STOP if:
- CSS change implied but not requested
- Image change implied without image reference or URL
- Section change implied without naming section
- Vendor files are targeted
```

---

## 16. Version Notes

```md
v1.0.0
- Initial SEO Agency template
- Conversion-optimized structure
```

---

## 17. AI FINAL DIRECTIVE

```md
This manifest is the highest authority.

If conflicts arise:
→ Follow this document
→ Ask for clarification
→ Do NOT assume
```
