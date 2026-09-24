# HTML, CSS, JavaScript & Node.js – Complete Practical Programs

**Student Name:** Shaik Abdulkalam
**Register Number:** _(fill in)_
**Class / Section:** B.Tech CSE - AI/ML, Sai University, Chennai
**Subject:** Web Technology / Full-Stack Practicals
**Assignment:** HTML, CSS, JavaScript & Node.js – Complete Practical Assignment

## Total Programs Completed: 425

- **HTML Programs:** 15
- **CSS Programs:** 75
- **JavaScript Programs:** 270 (Fundamentals, DOM & Event Experiments, Advanced JS, More Fundamentals,
  DOM Manipulation, Events, Forms & Validation, Browser Objects & Storage, Mini Projects, and their
  extended second-round sections, exactly matching every JavaScript category in the assignment sheet)
- **Node.js Backend Programs:** 65 (server-side architecture, Express, routing, middleware, sessions,
  database CRUD, authentication/authorization, and REST APIs)

## How to Run

1. Open `index.html` in any modern web browser.
2. Use the four dashboard cards (HTML / CSS / JavaScript / Node.js) to open each category's program list.
3. Each list page has a **search box** at the top to instantly filter by program name, and groups programs
   under the same sub-headings used in the original assignment sheet (Mini Projects, DOM Manipulation, etc.).
4. Click any program to open it. Every program page has **Home** and **Back to [Category]** links —
   no file names ever need to be typed manually.
5. **Node.js pages are different from the others**: Node.js is server-side and cannot run inside a static
   HTML file opened in a browser. Each Node.js page shows real, correct, runnable code in a highlighted
   block with a clear note. To actually run one: copy the code into a `.js` file, run `npm install` for any
   packages it uses (Express, bcrypt, jsonwebtoken, etc.), then `node filename.js`.

## Project Structure

```
project/
├── index.html                 → Main dashboard (4 cards: HTML, CSS, JavaScript, Node.js)
├── html/
│   ├── index.html              → HTML program list (15 programs)
│   └── 001-....html … 015-....html
├── css/
│   ├── index.html              → CSS program list (75 programs)
│   └── 016-....html … 090-....html
├── javascript/
│   ├── index.html              → JavaScript program list (270 programs, grouped by category)
│   └── 091-....html … 360-....html
├── nodejs/
│   ├── index.html              → Node.js program list (65 programs)
│   └── 361-....html … 425-....html
├── assets/
│   ├── style.css                → Shared stylesheet used by all 430 pages
│   ├── images/
│   └── icons/
└── README.md
```

Every file is numbered with its global question number (001–425) so the whole set stays in the exact
order it appears in the assignment sheet, even though several categories reuse the same underlying
program for closely related or duplicate questions (the assignment sheet itself repeats several questions
word-for-word across different sections — e.g. "Create a digital calculator" appears under both
"Mini Projects" and "DOM & Event-Based Experiments"). Each occurrence is still its own complete,
numbered, working file.

## Quality Checks Performed

- All 430 HTML files: valid doctype, balanced tags, 0 parser errors.
- All internal navigation links (430 files checked): 0 broken links.
- All 277 unique inline JavaScript blocks: 0 syntax errors (verified with `node --check`).
- Meaningful, numbered file names; consistent indentation; comments included where relevant.
