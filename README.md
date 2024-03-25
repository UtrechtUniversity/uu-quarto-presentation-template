# UU Quarto presentation template

This is a template repository for creating a UU styled Quarto presentation. Quarto is an open source publishing system for creating (documentation) websites, presentations and books. Quarto allows you to write content using markdown, and you can create dynamic content using (among others) R and Python. Quarto will render your markdown(`.qmd`) or e.g. notebooks (`.ipynb`) to HTML, PDF, and more. The repository includes a GitHub actions workflow to automatically render your presentation to HTML and publish it to GitHub pages.

This repository contains [UU themed presentation example slides] written in `.qmd` files.

[Template presentation](https://utrechtuniversity.github.io/uu-quarto-presentation-template/uu_template)

## Getting Started:

- [Install Quarto](https://quarto.org/docs/get-started/)
- Click the green 'Use this template' button in the top right corner of this screen
- Choose your personal github account as 'Owner'.
- Clone the new repository to your PC
- Go to the presentations folder and rename `uu_template.qmd`
- Open the `.qmd` file in RStudio or VS Code and start working on your presentation. 
- Both [Rstudio](https://quarto.org/docs/get-started/hello/rstudio.html) and [VS Code](https://quarto.org/docs/get-started/hello/vscode.html) have Quarto extensions that can be installed and used to preview your presentation on your PC.
- Commit and push your changes to GitHub.

## Setting up GitHub Pages for your presentation:

Under *Settings* → *Pages* → *Build and deployment* the source must be switched to "GitHub Action". See this blog post for more information about [Quarto and GitHub pages](https://tarleb.com/posts/quarto-with-gh-pages/). 

Check [quarto.org](https://quarto.org/) for extended documentation on how to get started.

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Any comments can be submitted as [issues](https://github.com/UtrechtUniversity/uu-quarto-presentation-template/issues/new/choose), or submit a pull request as follows:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
