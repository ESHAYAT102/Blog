---
title: "My Environment"
description: "My VSCode Theme And Extensions."
pubDate: "Feb 1 2025"
heroImage: "/environment.png"
---

I've been meaning to share my development setup for a while now, and I figured it's finally time.  I primarily use VS Code for my projects, and I've customized it quite a bit to fit my workflow. This post will cover the VS Code extensions I rely on and other important settings.

<h3>VS Code Extensions</h3>

These are the extensions I find essential for my daily development:

*   [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer):  Launch a development local Server with live reload feature for static & dynamic pages.
*   [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner):  Run scripts directly in your VSCode.
*   [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag):  Keeps your HTML and JSX tags in sync when renaming. A real time-saver!
*   [Change Case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case): Quickly switch between different naming conventions (camelCase, snake_case, etc.).
*   [Choose A License](https://marketplace.visualstudio.com/items?itemName=ultram4rine.vscode-choosealicense):  Easily add a license file to your projects.  Important for open-source work!
*   [ES6 String HTML](https://marketplace.visualstudio.com/items?itemName=Tobermory.es6-string-html):  Provides syntax highlighting and other goodies for HTML within JavaScript strings.
*   [Multiple Cursor Case Preserve](https://marketplace.visualstudio.com/items?itemName=Cardinal90.multi-cursor-case-preserve):  Makes working with multiple cursors even better by preserving case.
*   [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode):  My go-to code formatter. Keeps everything consistent and readable.
*   [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols): Better icon theme for VS Code.

<h3>VS Code Settings</h3>

Currently, the only setting I've significantly customized is the font. I use the excellent [Cascadia Code](https://github.com/microsoft/cascadia-code) font for my VS Code editor.  It's highly recommend it and it's my favorite code font too!


<h3>Custom Theme: Demon</h3>

I've created my own VS Code theme called "Demon" by customizing the popular [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme).  You can find the theme files on GitHub: [demon-vscode-theme](https://github.com/ESHAYAT102/demon-vscode-theme).

<h4>Installation</h4>

1.  **Install the GitHub Theme:** First, install the [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme) from the VS Code Marketplace and set it to the "Dark default" theme.

2.  **Copy the Theme Code:** Go to the [demon-vscode-theme](https://github.com/ESHAYAT102/demon-vscode-theme) repository. Copy the entire code from the `theme.json` file.

3.  **Locate the GitHub Theme Files:** Open your file explorer and navigate to the `.vscode` directory. Inside, find the folder for the GitHub Theme extension.  The exact path might vary slightly depending on your operating system.  Look for a folder with a name similar to `github.github-vscode-theme-[version]`.

4.  **Replace the `dark-default.json` file:** Inside the GitHub Theme extension folder, you should find a `dark-default.json` file. **Make a backup of this file first!** Then, replace the contents of `dark-default.json` with the code you copied from the `theme.json` file in the "Demon" repository.

5.  **Restart VS Code:** Restart VS Code for the changes to take effect.

If everything is set up correctly, your VS Code should now be sporting the "Demon" theme!

![My VS Code Setup](/vscode.png)

There's another theme that I like a lot, which is the [Aura Spirit Dracula Theme](https://marketplace.visualstudio.com/items?itemName=JoseMurilloc.aura-spirit-dracula). It's a really good one!

<style>
    @media (max-width: 720px) {
        h3 {
            font-size: 1.5rem;
        }
        h4 {
            font-size: 1.3rem;
        }
    }
</style>
