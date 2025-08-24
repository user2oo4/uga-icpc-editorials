# Contribution Guide

Thank you for your interest in contributing to the UGA ICPC Club Editorial Repository! By sharing your editorials and solutions, you help build a valuable resource for all club members. Please follow these guidelines to ensure consistency and clarity.

---

## Table of Contents

- [Getting Started](#getting-started)
- [How to Add Your Editorial](#how-to-add-your-editorial)
- [Naming Conventions](#naming-conventions)
- [Folder Structure](#folder-structure)
- [Editorial Formatting Tips](#editorial-formatting-tips)
- [Pull Request Process](#pull-request-process)
- [Code of Conduct](#code-of-conduct)
- [FAQ](#faq)

---

## Getting Started

1. **Fork** or **Clone** this repository to your own GitHub account.
2. **Create a new branch** for your contribution:
   ```bash
   git checkout -b add/your-editorial-name
   ```
3. **Add your editorial and/or code** in the correct folder based on the semester, week, and problem.

---

## How to Add Your Editorial

- Place your solution(s) and corresponding editorial in the appropriate folder (see [Folder Structure](#folder-structure)).
- Include both the code file (e.g., `.py`, `.cpp`) and a Markdown explanation (e.g., `problem_a.md` or `A_Soup_Explanation.md`).
- If you're unsure where to add your file, ask a maintainer or open an issue.

---

## Naming Conventions

- **Branch name:** `add/{short-description}` (e.g., `add/week-2-segment-tree-editorial`)
- **Editorial Markdown file:**  
  - For weekly problems: `problem_{letter}.md` (e.g., `problem_a.md`)
  - For contest problems: `{ProblemCode}_Explanation.md` (e.g., `A_Soup_Explanation.md`)
- **Code file:**  
  - Use the original problem code and language extension (e.g., `problem_a.cpp`, `A_Soup.py`)
- **Folders:**  
  - Use lowercase and hyphens for week/topic folders (e.g., `week-2-dp/`)
  - For practice contests: `practice-contest-{number}-{date}/` (e.g., `practice-contest-1-2025-09-01/`)

---

## Folder Structure

```
icpc-editorials/
│
├── README.md
├── CONTRIBUTING.md
├── resources/
│   └── useful-links.md
│
└── fall-2025/
    ├── week-0-welcome/
    │   ├── problem_a.md
    │   ├── problem_a.cpp
    │   └── problem_b.py
    ├── week-1-complexity/
    │   └── ...
    ├── week-2-dp/
    │   └── ...
    └── practice-contests/
        ├── practice-contest-1-2025-09-01/
        │   ├── A_Soup.py
        │   ├── A_Soup_Explanation.md
        │   └── ...
        └── practice-contest-2-2025-09-15/
            └── ...
```

---

## Editorial Formatting Tips

- Start with a **problem statement summary** (optional, but helpful).
- Clearly explain your **approach and reasoning**.
- If possible, include **time and space complexity analysis**.
- Use **Markdown formatting** for clarity (lists, code blocks, bold/italic, etc.).
- Add **sample input/output** and explanations if helpful.
- Reference any **useful resources** in the [resources](resources/) folder.

---

## Pull Request Process

1. **Commit** your changes with a descriptive message, e.g.,  
   ```
   git commit -m "Add editorial for week 2 DP problem A"
   ```
2. **Push** your branch:
   ```
   git push origin add/your-editorial-name
   ```
3. **Open a Pull Request (PR)** on GitHub.
4. Wait for **review**—maintainers may suggest changes.
5. Once approved, your contribution will be merged!

---

## Code of Conduct

- Be respectful and constructive.
- Credit all contributors.
- Do not plagiarize—write your own explanations and code.
- If you use external resources, cite them.

---

## FAQ

- **Q:** Can I submit solutions in any language?  
  **A:** Yes! Include the language in the file extension.

- **Q:** What if I spot a typo or mistake?  
  **A:** Please open a PR to fix it, or create an issue.

- **Q:** Who can contribute?  
  **A:** All club members and the broader ICPC community are welcome!

---

Thank you for making this a great resource for everyone! 🚀
