# Your First Web Workflow

Welcome to your first web development module. Before you begin writing code, it is helpful to understand the basic workflow you will use throughout this course.

A website usually begins as files on your computer. You create and edit those files using a code editor, test them in a web browser, save your progress using GitHub, and eventually publish selected projects so other people can view them online. In this module, you will take your first step into that workflow by creating a simple **Hello Web** page and saving it in GitHub.

To learn more about how a simple website comes together, review:  
[MDN Web Docs: Your First Website](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website)

![Web development workflow diagram showing create files, test in browser, save to GitHub, and publish later.](images/01-web-workflow.png)

---

## 1. What Is Web Development?

Web development is the process of creating websites and web applications. In this course, you will focus mostly on the front-end side of web development. The front end is the part of a website people see and interact with in a browser.

Most beginner websites are built with three core technologies:

- **HTML** creates the structure of the page.
- **CSS** controls the appearance of the page.
- **JavaScript** can add interactivity.

In Module 1, you will begin with HTML because every webpage needs structure before it can be styled or made interactive.

To learn more about the basic tools and concepts used in web development, review:  
[MDN Web Docs: Getting Started Modules](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started)

![Three building blocks labeled HTML structure, CSS style, and JavaScript interaction.](images/02-html-css-js.png)

---

## 2. The Tools You Will Use

This course uses several important tools. You do not need to become an expert with them right away. In Module 1, the goal is to get your workspace ready and begin practicing.

**Visual Studio Code**, often called **VS Code**, is the code editor you will use to write HTML and CSS files. A code editor is similar to a writing tool, but it is designed for programming and website files.

**A web browser**, such as Chrome, Edge, Firefox, or Safari, is used to view and test your webpage. You will write your code in VS Code, then open your page in a browser to see the result.

**GitHub** is a platform for storing and organizing coding projects online. In this course, GitHub will help you save your work, submit projects, and build a record of your progress.

**GitHub Pages** is a GitHub feature that lets you publish a simple website from a repository. You will learn more about publishing later in the course.

To learn more about GitHub and why developers use it, complete the assigned Microsoft Learn module as part of this week’s lab:  
[Microsoft Learn: Introduction to GitHub](https://learn.microsoft.com/en-us/training/modules/introduction-to-github/)

![Course tools diagram showing VS Code, browser, GitHub, and GitHub Pages.](images/03-course-tools.png)

---

## 3. Understanding Files and Folders

Websites are made from files and folders. One of the first habits you will build as a web developer is keeping your project files organized.

For your first webpage, you will create a simple project folder. Inside that folder, you will create an HTML file.

A basic Module 1 project might look like this:

```text
hello-web
│
├── index.html
└── README.md
```

The file named **index.html** is important. On many websites, `index.html` is the default homepage. When someone visits a site, the browser often looks for that file first.

The **README.md** file is a short description of your project. In GitHub, a README helps explain what the repository contains.

To learn more about creating a basic webpage file, review:  
[MDN Web Docs: Your First Website](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website)

![Example project folder structure showing hello-web with index.html and README.md files.](images/04-files-folders.png)

---

## 4. Your First HTML Page

HTML uses elements to organize content on a webpage. Most HTML elements have an opening tag, content, and a closing tag.

For example:

```html
<p>This is a paragraph.</p>
```

The opening tag is `<p>`.  
The content is `This is a paragraph.`  
The closing tag is `</p>`.

A simple HTML page includes a standard structure. Your first page may look similar to this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Hello Web</title>
</head>
<body>
    <h1>Hello Web!</h1>

    <p>My name is [your name], and this is my first webpage for WEB 110.</p>

    <p>In this module, I am learning how to create an HTML file, use GitHub, and organize my web development work.</p>
</body>
</html>
```

Here is what each part does:

- `<!DOCTYPE html>` tells the browser this is an HTML document.
- `<html>` contains the whole webpage.
- `<head>` contains information about the page, such as the title.
- `<title>` controls the title shown in the browser tab.
- `<body>` contains the content people see on the webpage.
- `<h1>` creates a main heading.
- `<p>` creates a paragraph.

At this stage, your page does not need to be fancy. The goal is to create a working HTML file and begin understanding the basic structure.

To learn more about HTML syntax and page structure, review:  
[MDN Web Docs: Basic HTML Syntax](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax)

![Side-by-side example showing HTML code on the left and browser output on the right.](images/05-first-html-page.png)

---

## 5. What Is GitHub?

GitHub is a website developers use to store, organize, and share coding projects. A project in GitHub is usually stored in a **repository**, often called a **repo**.

For this module, you will create your first repository. Think of a repository as a project folder that lives online. It keeps your files together and helps track changes as your project grows.

You will use GitHub in this course to store course projects, submit links to your work, practice a real-world developer workflow, and eventually publish selected webpages.

You do not need to learn every GitHub feature right now. In Module 1, focus on creating an account, creating a repository, adding your files, and submitting the correct link.

To learn how to create your first repository, review:  
[GitHub Docs: Quickstart for Repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

![Two-column comparison showing a project folder on a computer and a repository on GitHub.](images/06-what-is-github.png)

---

## 6. Saving Your Work in GitHub

When an HTML file is only on your computer, it is easy to lose track of your work. GitHub gives you a place to store your project online and submit your work for review.

In this module, you will upload your `index.html` file to a GitHub repository named `hello-web`.

Your repository should include:

```text
hello-web
│
├── index.html
└── README.md
```

Later in the course, you will learn how to use GitHub Pages to publish selected projects as live websites. For now, the goal is to practice creating a repository and saving your files correctly.

To learn more about GitHub repositories, review:  
[GitHub Docs: Quickstart for Repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

![Step-by-step diagram showing index.html moving from a local computer into a GitHub repository.](images/07-save-to-github.png)

---

## 7. A Note About AI and Copilot

AI tools can be helpful, but they should not do the learning for you. In this course, you may use tools like GitHub Copilot or generative AI to ask questions, explain confusing code, brainstorm text for a project, or help troubleshoot errors.

For example, an appropriate AI prompt might be:

```text
Explain what each line of this beginner HTML file does in simple terms.
```

Another appropriate prompt might be:

```text
I am new to HTML. Can you help me find the missing closing tag in this code?
```

An inappropriate use would be asking AI to complete the entire assignment without reading, testing, or understanding the code.

In this course, AI is a support tool. You are still responsible for your final work.

To learn more about GitHub Copilot as a coding support tool, you may review:  
[Microsoft Learn: Introduction to GitHub Copilot](https://learn.microsoft.com/en-us/training/modules/introduction-to-github-copilot/)

![Illustration showing AI as a support tool helping a student think through code while the student remains responsible for the work.](images/08-ai-support-tool.png)

---

## 8. What You Will Do in This Module

In this module, you will begin building your web development workflow. You will set up your tools, complete guided practice, create your first GitHub repository, write a simple HTML page, and save it in GitHub.

By the end of this module, you should have:

- A working VS Code setup
- A GitHub account
- Completed Microsoft Learn practice evidence
- A first GitHub repository
- A simple `index.html` page
- Your work uploaded to GitHub

This first page is small on purpose. Every web developer starts with the basics: creating a file, writing code, saving work, testing in the browser, and organizing files carefully.

The goal for this module is to get started, practice the workflow, and build confidence.

To review how these pieces fit together, return to:  
[MDN Web Docs: Your First Website](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website)

![Checklist graphic showing Module 1 tasks: install tools, practice coding, create files, create GitHub repository, and submit evidence.](images/09-module-01-checklist.png)

---

## References

GitHub Docs. (n.d.). *Quickstart for repositories*. https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories

MDN contributors. (2025a, April 18). *Getting started modules*. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started

MDN contributors. (2025b, June 23). *Your first website*. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website

MDN contributors. (2026, February 6). *Basic HTML syntax*. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax

Microsoft Learn. (n.d.). *Introduction to GitHub*. https://learn.microsoft.com/en-us/training/modules/introduction-to-github/

Microsoft Learn. (n.d.). *Introduction to GitHub Copilot*. https://learn.microsoft.com/en-us/training/modules/introduction-to-github-copilot/

---

## Attribution & License

This lecture was created by **Jennifer Lee** for **WEB 110: Web Development Fundamentals**. Original instructional content and visuals are licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**, unless otherwise noted.

Suggested attribution:  
Lee, J. (2026). *WEB 110 Module 1: Your First Web Workflow*. Licensed under CC BY 4.0.

https://creativecommons.org/licenses/by/4.0/
