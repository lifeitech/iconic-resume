# Iconic Resume: A LinkedIn-style resume template

![resume preview](/resume.png)

[Demo](https://iconic-resume.netlify.app/) | [PDF](/resume.pdf)

Iconic Resume is a cv/resume template written in the Jekyll framework. 

## Features

- Two-column A4 layout.
- Icons and LinkedIn-style format with company logos for better visualization.
- Can add links to social media, code repos, papers, projects etc.
- Separation of contents with formats. All contents are placed in `_config.yml`. All styles are defined in `style.scss`. 
- Lightweight.

## Use the template without Ruby and Jekyll Installation

1. Fork this repository.
2. Create a `gh-pages` branch.
3. Go to Settings and select `gh-pages` as GitHub Pages source.
4. Edit `_config.yml`. Replace the dummy data with your own career details. Put your own icons in the `imgs` folder.
5. Go to https://username.github.io/resume.
6. Right-click the page and click `print...` to save your resume in PDF.

## Use the template locally

1. Install [Ruby](https://www.ruby-lang.org/en/).
2. Install [Jekyll](https://jekyllrb.com/docs/).
3. Clone or download the repository to your own machine.
4. Edit `_config.yml`. Replace the dummy data with your own career details. Put your own icons in the `imgs` folder.
5. `cd` to repository. Run `bundle exec jekyll serve`. 
6. Go to `localhost:4000`.
7. Right-click the page and click `print...` to save your resume in PDF.


## Things to Note

1. By default, your browser add margins to the document when you save the webpage for PDF. This should work fine, but you can also customize the margins if you want to.
2. Be sure to use square images.

## Contributions

If you have any suggestion, feel free to open issues or submit pull requests.