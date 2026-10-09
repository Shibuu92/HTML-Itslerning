# Educational HTML Templates for itslearning

A collection of reusable HTML templates designed to create structured, visually appealing, and student-friendly educational content in **itslearning**.

The templates are primarily developed for vocational education, particularly Information and Communication Technology (ICT), but can be adapted for other subjects and educational environments.

## 📚 About the Project

This repository contains HTML-based educational materials, including assignments, course introductions, instructions, and theoretical learning resources.

The main purpose is to improve how educational content is presented in itslearning by making it easier for students to read, understand, and follow instructions.

Instead of relying on basic text formatting, these templates use HTML and inline CSS to create consistent layouts with clear headings, instructional sections, step-by-step guides, and highlighted information.

The materials were originally designed for use in vocational ICT education at Prakticum in Finland.

## 🎯 Project Goals

- Create visually consistent educational materials.
- Make assignments easier for students to understand.
- Provide clear, step-by-step instructions.
- Improve accessibility and readability.
- Reduce unnecessary spacing and formatting issues in itslearning.
- Allow teachers to reuse and customize templates.
- Support practical and independent learning.

## 🧩 Types of Educational Content

### 1. Course Introductions

HTML templates for introducing a course, including its objectives, content, classroom routines, expectations, and submission requirements.

### 2. Practical Assignments

Structured assignments with learning objectives, instructions, practical exercises, checklists, and submission information.

Examples include:

- Creating and sending ZIP files through school email.
- Joining Microsoft Teams meetings and exploring meeting controls.
- Creating PowerPoint presentations.
- Working with Microsoft Office applications.
- File management and other digital tools.

### 3. Theoretical Learning Materials

Educational pages explaining concepts and providing examples, comparisons, and discussion questions.

For example, a lesson comparing Nordic and American customer service approaches, including practical examples from IT support.

### 4. ICT Exercises

Templates can also be used for topics such as operating systems, virtualization, networking, cybersecurity, computer hardware, and troubleshooting.

## 🎨 Design and Styling

The templates use a consistent visual design with:

- Colored header sections.
- Clearly separated content areas.
- Step-by-step instructional blocks.
- Highlighted warnings and important information.
- Checklists and submission instructions.
- Responsive content widths.
- Readable typography and spacing.

The current design primarily uses a turquoise color scheme.

| Element | Color |
|---|---|
| Main header | `#0f766e` / `#06b6d4` |
| Section headers | `#0d9488` |
| Secondary headers | `#0891b2` |
| Important information | `#f59e0b` |
| Checklists and submission | `#16a34a` |
| Main background | `#ffffff` |

### Why Inline CSS?

itslearning may modify or override certain HTML elements and CSS rules.

To improve compatibility, the templates use **inline CSS** rather than external stylesheets.

Example:

```html
<div style="background:#0d9488;
            padding:12px 16px;
            border-radius:8px;
            color:#ffffff;">
  Educational content
</div>
```

This approach makes the templates easy to copy and paste into the itslearning HTML source editor.

## 🚀 How to Use

1. Open the HTML template you want to use.
2. Copy the HTML code.
3. Open your course or assignment in itslearning.
4. Open the content editor and select **Source / Källa**.
5. Paste the HTML code.
6. Return to the visual editor and preview the result.
7. Save or publish the content.

**Note:** Some formatting may vary depending on the itslearning editor and institutional settings.

## 🛠️ Customization

Teachers can modify the templates without advanced programming knowledge.

You can change:

- Titles and descriptions.
- Learning objectives.
- Assignment instructions.
- Colors and backgrounds.
- Number of steps.
- Checklists.
- Submission requirements.
- Course-specific information.

For example, changing the background color of a section:

```html
<div style="background:#0d9488;
            color:#ffffff;
            padding:10px 15px;">
  Assignment Instructions
</div>
```

Change `#0d9488` to another color to customize the appearance.

## 💻 Technologies Used

- HTML5
- Inline CSS
- Basic responsive layouts
- Unicode symbols and emojis

The templates do not require JavaScript, external CSS frameworks, or additional libraries.

## 📁 Suggested Repository Structure

```text
itslearning-html-templates/
│
├── README.md
│
├── course-introductions/
│   └── digital-tools.html
│
├── assignments/
│   ├── school-email.html
│   ├── microsoft-teams.html
│   └── powerpoint-presentation.html
│
├── theory/
│   └── nordic-service-model.html
│
└── templates/
    └── assignment-template.html
```

This is a suggested organization. Additional subjects and templates can be added as the project grows.

## 👨‍🏫 Intended Audience

These templates are primarily intended for:

- Vocational education teachers.
- ICT instructors.
- Teachers using itslearning.
- Educators creating digital assignments.
- Anyone interested in improving the visual presentation of online learning materials.

## ⚠️ Compatibility Notes

The templates are designed with itslearning in mind, but compatibility may vary.

Some things to consider:

- The editor may override certain text styles.
- Inline CSS is generally more reliable than external stylesheets.
- Excessive margins and padding may create unwanted whitespace.
- Tables should be tested on smaller screens.
- Text contrast should remain readable.
- Some HTML or CSS properties may be removed by the editor.

Always preview your content before publishing it to students.

## 📌 Future Development

Possible improvements include:

- Additional HTML assignment templates.
- More ICT-related educational materials.
- Alternative color themes.
- Improved mobile layouts.
- More reusable content components.
- Swedish and English template variations.
- Accessibility improvements.

## 📄 License

No license has been selected yet. Add a `LICENSE` file if you want to define how others may reuse, modify, or distribute the templates.

---

**Educational HTML Templates for itslearning**

Making digital learning materials clearer, more consistent, and easier to use.
