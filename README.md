# WCAG (wcag)

Web Content Accessibility Guidelines (WCAG) are a set of international standards published by the W3C Web Accessibility Initiative (WAI) for making web content accessible to people with disabilities. WCAG covers a wide range of recommendations across four principles (Perceivable, Operable, Understandable, Robust), with conformance levels A, AA, and AAA. WCAG 2.2 (ISO/IEC 40500:2025) is the current standard, while WCAG 3.0 is in active development targeting broader coverage of websites, mobile apps, VR environments, and digital documents.

**URL:** [Visit APIs.json URL](https://www.w3.org/WAI/standards-guidelines/wcag/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Accessibility, W3C, WCAG, Web Standards, Disability, Inclusive Design

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### WCAG 2.2

Web Content Accessibility Guidelines 2.2, the current stable version and ISO/IEC 40500:2025 standard. Introduces 9 new success criteria beyond WCAG 2.1, including focus appearance, dragging movements, and consistent help. Organized into four POUR principles.

**Human URL:** [https://www.w3.org/TR/WCAG22/](https://www.w3.org/TR/WCAG22/)

#### Tags:

 - WCAG 2.2, Accessibility, Web Standards, ISO

#### Properties

- [WCAG 2.2 Specification](https://www.w3.org/TR/WCAG22/)
- [WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)
- [WCAG GitHub Repository](https://github.com/w3c/wcag)
- [Success Criterion Schema](json-schema/wcag-success-criterion-schema.json)
- [Conformance Claim Schema](json-schema/wcag-conformance-claim-schema.json)
- [Success Criterion Structure](json-structure/wcag-success-criterion-structure.json)
- [Conformance Claim Structure](json-structure/wcag-conformance-claim-structure.json)

### WCAG 3.0

W3C Accessibility Guidelines 3.0 working draft, expanding scope to cover mobile apps, VR, authoring tools, and digital documents. Introduces outcome-based testing and a new scoring model. Working Draft published January 2026.

**Human URL:** [https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/](https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/)

#### Tags:

 - WCAG 3.0, Accessibility, Web Standards, Working Draft

#### Properties

- [WCAG 3.0 Introduction](https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/)
- [WCAG 3.0 Editor Draft](https://w3c.github.io/wcag3/guidelines/)
- [WCAG 3.0 GitHub Repository](https://github.com/w3c/wcag3)

### WAI-ARIA

Accessible Rich Internet Applications 1.2 specification providing semantic roles, states, and properties for accessible user interface components.

**Human URL:** [https://www.w3.org/TR/wai-aria/](https://www.w3.org/TR/wai-aria/)

#### Tags:

 - WAI-ARIA, Accessibility, Semantic Web, User Interface

#### Properties

- [WAI-ARIA Specification](https://www.w3.org/TR/wai-aria/)
- [ARIA in HTML](https://www.w3.org/TR/aria-in-html/)
- [ARIA Authoring Practices GitHub](https://github.com/w3c/aria-practices)

### Accessibility Conformance Testing (ACT) Rules

Machine-executable rules for testing WCAG 2.x conformance, enabling consistent automated accessibility evaluation.

**Human URL:** [https://www.w3.org/WAI/standards-guidelines/act/](https://www.w3.org/WAI/standards-guidelines/act/)

#### Tags:

 - ACT Rules, Accessibility Testing, Automated Testing, WCAG

#### Properties

- [ACT Rules Overview](https://www.w3.org/WAI/standards-guidelines/act/)
- [ACT Rules Community](https://act-rules.github.io/)

## Common Properties

- [W3C Web Accessibility Initiative](https://www.w3.org/WAI/)
- [W3C Accessibility Standards Overview](https://www.w3.org/WAI/standards-guidelines/)
- [W3C GitHub Organization](https://github.com/w3c)
- [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/test-evaluate/tools/list/)
- [WCAG-EM Report Tool](https://github.com/w3c/wcag-em-report-tool)
- [WCAG Vocabulary](vocabulary/wcag-vocabulary.yml)
- [WCAG JSON-LD Context](json-ld/wcag-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Four Accessibility Principles (POUR) | Perceivable, Operable, Understandable, and Robust — the organizing framework for all WCAG success criteria. |
| Three Conformance Levels | Level A (minimum), Level AA (standard), and Level AAA (enhanced) for graduated implementation. |
| Testable Success Criteria | Specific, testable criteria providing a clear pass/fail basis for accessibility evaluation. |
| ACT Rules Integration | Machine-executable rules enabling consistent automated testing across evaluation tools. |
| Techniques and Failures Documentation | Sufficient techniques, advisory techniques, and common failures for each success criterion. |
| WCAG 3.0 Outcome-Based Model | Scoring-based conformance model replacing binary pass/fail for more nuanced assessment. |

## Use Cases

| Name | Description |
|------|-------------|
| Legal Compliance | Meeting legal accessibility requirements including ADA, Section 508, EN 301 549, and AODA. |
| Automated Accessibility Testing | Integrating ACT Rules into CI/CD pipelines to catch WCAG violations automatically. |
| Screen Reader Compatibility | WAI-ARIA roles and properties enable accessible rich web applications. |
| Accessibility Auditing | WCAG criteria as the evaluation framework for manual and automated audits. |
| Inclusive Design | Building accessibility in from the design phase rather than retrofitting. |

## Integrations

| Name | Description |
|------|-------------|
| axe-core | Popular open-source accessibility testing engine mapping rules to WCAG success criteria. |
| WAVE | Web Accessibility Evaluation Tool visually highlighting WCAG issues on web pages. |
| Lighthouse | Google Lighthouse includes accessibility audits mapped to WCAG criteria. |
| NVDA and JAWS | Screen readers implementing WAI-ARIA API mappings for blind and low-vision users. |
| ISO/IEC 40500 | WCAG 2.2 is identical to ISO/IEC 40500:2025 for international procurement. |

## Artifacts

### JSON Schema

- [wcag-success-criterion-schema.json](json-schema/wcag-success-criterion-schema.json)
- [wcag-conformance-claim-schema.json](json-schema/wcag-conformance-claim-schema.json)

### JSON Structure

- [wcag-success-criterion-structure.json](json-structure/wcag-success-criterion-structure.json)
- [wcag-conformance-claim-structure.json](json-structure/wcag-conformance-claim-structure.json)

## Vocabulary

- [WCAG Vocabulary](vocabulary/wcag-vocabulary.yml) — Normative taxonomy mapping 6 resources, 7 actions, 5 personas, and 4 domains across the W3C accessibility standards ecosystem

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
