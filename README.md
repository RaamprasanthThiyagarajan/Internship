# 🎓 College Admission Web Page

This project is a **responsive college admission web page** for **SSM Institute of Engineering and Technology**, built using HTML and CSS. The page showcases college details, department links, admissions info, and important notifications.

---

## 🌐 Live Preview

> (Add your hosted URL here if available)

---

## 📁 Features

- 🎓 College Name and Banner Display
- 🖼️ Full-screen Background Image using `h5` tag
- 📢 Two Scrolling Marquee Notifications:
  - Semester End Exam Timetable
  - Admissions Open Notice
- 🏫 College Overview Paragraph
- 🧑‍🏫 Department Links:
  - ECE, EEE, CSE, AIDS, CSBS
- 📥 Admission Page Link
- 📞 Contact Info Section

---

## 📄 HTML Structure

- `<!DOCTYPE html>` used for HTML5 compliance
- CSS styling applied using both:
  - Internal `<style>` tag for background
  - External stylesheet: `project_page1.css`
- Proper usage of:
  - `<center>`, `<h1>` to `<h5>`, `<marquee>`, `<ol>`, `<a>`, and `<p>` tags

---

## 📌 File Structure
/Project Root
│
├── index.html
├── project_page1.css
├── download.png
├── Banner.png
├── SSM.png
├── project_page2.html
├── project_page3.html
├── project_page4.html
├── project_page5.html
├── project_page6.html
└── project_page7.html

yaml
Copy
Edit

---

## 🔗 Important Links (from page)

- [📅 Semester End Exam Timetable - May 2025](https://ssmiet.ac.in/COE/SETE-May%202025%20-%20Timetable.pdf)
- [📌 Admission Page](https://ssmiet.ac.in/admission.html)

---

## 📞 Contact Information

- **Phone**: 0451-244-8800-899  
- **Email 1**: ssmietdgl@ssmiet.ac.in  
- **Email 2**: ssmietdgl@gmail.com  

---

## ✅ To Do / Improvements

- Convert `<marquee>` to modern scrolling methods using CSS/JS
- Make it mobile responsive
- Use semantic tags instead of `<h5>` for background styling

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- Basic Web Layout and Design  
- Inline and External Styling  

---

## 📸 Screenshots

> *(Add screenshots here once the project is live or running in browser)*

---

## 🧑‍💻 Author

- **Created by:** Raam Prasanth (Based on HTML you provided)

---

You can save the above content as README.md in your project folder. Let me know if you want help creating screenshots or deploying the project!









Ask ChatGPT
You said:
git branch check and switch


ChatGPT said:
Here's how you can check and switch Git branches using both command line and VS Code GUI:

✅ 1. Check Current Branch
bash
Copy
Edit
git branch
Shows all branches

Highlights your current branch with *

🔁 2. Switch to Another Branch
👉 To switch:
bash
Copy
Edit
git checkout branch-name
Or, in Git 2.23+:

bash
Copy
Edit
git switch branch-name
➕ 3. Create and Switch to New Branch
bash
Copy
Edit
git checkout -b new-branch
Or:

bash
Copy
Edit
git switch -c new-branch
🚮 4. Delete a Branch
bash
Copy
Edit
git branch -d branch-name
💡 Example
bash
Copy
Edit
git branch             # Check all branches
git switch dev         # Switch to 'dev' branch
git switch -c feature  # Create and switch to 'feature' branch
git branch -d test     # Delete 'test' branch
🖥️ In VS Code (GUI method)
Look at the bottom-left corner of VS Code → You'll see the current branch name.

Click the branch name → A list of branches will appear.

Select a branch to switch or click + Create new branch.

Let me know if you want to create, merge, or delete branches too!








You said:
how to use markdown code in vs code


ChatGPT said:
Great question! Here's how to use Markdown code in VS Code effectively:

✅ 1. Create a Markdown File
In VS Code:

Click File > New File or press Ctrl + N

Save the file with a .md extension (e.g., README.md)

✍️ 2. Write Markdown Code
Use standard Markdown syntax:

markdown
Copy
Edit
# Heading 1
## Heading 2
### Heading 3

**Bold Text**  
*Italic Text*  
[Link Text](https://example.com)

- Bullet List Item 1
- Bullet List Item 2

1. Numbered Item 1
2. Numbered Item 2

`Inline code`

Code block (use triple backticks)

css
Copy
Edit

> Blockquote
👀 3. Preview Markdown
Press Ctrl + Shift + V → Preview Markdown in side-by-side pane

Or right-click in the file → choose **Open Preview**

✨ Tip: You can also press Ctrl + K V for a split view (edit + preview)

🧩 4. Recommended Extensions (Optional)
Install these from the Extensions panel:

Markdown All in One – enhances editing, auto-preview, TOC

Markdown Preview Enhanced – for advanced previews (LaTeX, charts, etc.)

MarkdownLint – helps check formatting rules

📦 Example Markdown in VS Code
markdown
Copy
Edit
# My Project

This is a simple **Markdown** document.

## Features
- Easy to write
- Easy to preview
- GitHub-compatible

## Usage

```bash
npm install
npm start
License
MIT

yaml
Copy
Edit

---

Let me know if you want a **Markdown cheat sheet** or want to turn a `.md` into a web page!










