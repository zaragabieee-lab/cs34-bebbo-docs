# Bebbo Parenting App Technical Documentation Style Guide

> A standardized Markdown style guide for creating clear, consistent, and user-focused technical documentation for the Bebbo Parenting App.

---

# Purpose and tone

The Bebbo Parenting App documentation must provide accurate, accessible, and user-centered guidance for parents, caregivers, healthcare workers, and contributors using the application.

Documentation should always prioritize:

- Clarity.
- Simplicity.
- Consistency.
- Accessibility.
- Empathy.
- Actionable guidance.

The writing style must remain professional while maintaining a supportive and approachable tone appropriate for parenting and child development contexts.

## Writing voice standards

### Use active voice

Use active voice in all instructional and explanatory content.

#### Preferred

- “Open the **Vaccinations** module.”
- “Track your child’s milestones regularly.”

#### Avoid

- “The **Vaccinations** module should be opened.”
- “Milestones can be tracked regularly.”

---

## User-centered language

Write instructions from the user’s perspective.

### Preferred

- “Check your child’s upcoming vaccine schedule.”
- “Review the child’s growth measurements.”

### Avoid

- “Users should review growth information.”
- “The parent must verify the vaccination records.”

---

## Empathetic communication

Because Bebbo supports parenting and child development, documentation should maintain a respectful and empathetic tone.

### Preferred

- “If you miss a vaccination schedule, the app provides reminders to help you stay updated.”
- “Parents can monitor milestones at their own pace.”

### Avoid

- “Failure to complete vaccinations may result in missed tracking.”
- “Parents must comply immediately.”

---

# Terminology and word choice

Use consistent terminology across all documentation to avoid confusion and improve usability.

## Technical jargon

Avoid unnecessary technical jargon whenever possible. When technical terms are required:

1. Define the term on first use.
2. Provide a simplified explanation in plain language.
3. Use the same term consistently throughout the document.

### Example glossary

| Technical Term | Preferred Explanation |
| --- | --- |
| Milestone Tracking | Monitoring a child’s developmental progress over time. |
| Growth Measurement | Recording a child’s height, weight, and development indicators. |
| Vaccination Schedule | A timeline of recommended vaccine doses for children. |

---

## Acronym management

Always spell out acronyms on first mention.

### Correct

- “The World Health Organization (WHO) provides vaccination guidance.”

### Incorrect

- “WHO provides vaccination guidance.”

After the first mention, the acronym may be used consistently throughout the document.

---

## Preferred terminology

| Preferred | Discouraged |
| --- | --- |
| Parent or caregiver | User |
| Child growth tracking | Kid stats |
| Upcoming vaccines | Pending shots |
| Health checkup | Medical inspection |
| Development milestone | Child status |
| Sign in | Login |
| Select | Click |

---

## Glossary guidelines

Documentation may include a glossary section when technical terminology appears frequently.

A glossary should:

- Provide concise definitions.
- Use plain language.
- Include references when necessary.
- Remain alphabetically organized.

---

# Markdown formatting rules

All Bebbo documentation must follow standardized Markdown formatting conventions for readability and consistency.

## Heading hierarchy

Use heading levels consistently to maintain logical document structure.

| Heading Level | Usage |
| --- | --- |
| `#` | Document title |
| `##` | Major sections |
| `###` | Subsections |
| `####` | Minor subsections |

### Example structure

```markdown
# Child Development

## Vaccinations

### Measurement

#### Health Checkups
```

---

## Heading capitalization

### Use title case for module names

Use Title Case only for official module names or major application features.

#### Examples

- Child Development
- Vaccinations
- Health Checkups
- Child Growth

### Use sentence case for descriptive headings

Use sentence case for explanatory or informational headings.

#### Examples

- Tracking your child’s progress
- Managing vaccination reminders
- Understanding milestone reports

---

## Bold text usage

Use bold formatting only for:

- UI labels.
- Navigation items.
- Buttons.
- Important warnings.

### Correct

- Select **Child Development**.
- Tap **Save** to continue.
- Review **Upcoming Vaccines** regularly.

### Incorrect

- **This paragraph explains the growth tracker.**
- **Parents should check reminders often.**

---

## Backticks and code formatting

Use backticks only for:

- Filenames.
- Technical identifiers.
- Variables.
- Commands.
- Markdown syntax examples.

### Correct

- Open the `README.md` file.
- Update the `child_growth_data` variable.
- Run `npm install`.

### Incorrect

- `Vaccinations`
- `Child Development`
- `Reminder Notification`

---

## Lists

Use bulleted or numbered lists for steps, rules, and grouped information.

### List formatting rules

- Start each bullet point with a capital letter.
- End complete sentences with a period.
- Maintain parallel grammatical structure.
- Keep list items concise.

### Correct

- Open the **Health Checkups** section.
- Review upcoming appointments.
- Update your child’s records regularly.

### Incorrect

- open the health section
- Reviewing appointments
- update child records regularly

---

## Tables

Use Markdown tables for:

- Comparisons.
- Definitions.
- Feature summaries.
- Formatting standards.
- Do’s and don’ts.

### Example

| Vaccine Status | Description |
| --- | --- |
| Upcoming | Scheduled vaccines that are not yet completed. |
| Overdue | Vaccines requiring immediate attention. |
| Received | Vaccines already administered. |

---

## Code blocks

Use fenced code blocks for:

- Markdown examples.
- Configuration examples.
- Terminal commands.
- Structured technical content.

### Example

````markdown
```bash
npm install
```
