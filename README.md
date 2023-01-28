# Iconic Resume: A LinkedIn-style resume template

![resume preview](/resume.png)

[Demo](https://iconic-resume.netlify.app/) | [PDF](/resume.pdf)

Iconic Resume is a cv/resume template written in the [Jekyll](https://jekyllrb.com/) framework. 

## Features

- Two-column A4 layout.
-  Company logos and icons for better visualization.
- Can add links to your social media, code repos, papers, projects etc.
- Separation of contents with formats. All contents are placed in [`_config.yml`](/_config.yml). All styles are defined in [`style.scss`](/style.scss). 
- Lightweight.

## Use this template WITHOUT Ruby and Jekyll Installation

1. Fork this repository.

2. Create a `gh-pages` branch.

3. Edit `_config.yml` (in the `gh-pages` branch). Replace the dummy data with your own career details. Put your own logos in the `imgs` folder. 

   ***Since you are going to deploy a project page instead of a personal page, be sure to uncomment the `baseurl`  on the first line in `_config.yml`.***

4. Go to `Settings -> Pages` page, and select `gh-pages` as GitHub Pages source.

5. Wait a few moments until the `Settings -> Pages` page says that "Your site is live at https://username.github.io/iconic-resume/". Go to that address, where `username` is your GitHub username.

6. Right-click the page and click `print...` to save your resume in PDF.

7. When you re-edit `_config.yml` or any other files, and commit the change, it will automatically trigger a GitHub Action to re-build the page. Wait until it finishes, before you refresh the https://username.github.io/iconic-resume/ link. You can view the build progress under the "Actions" tab in your forked repository.

## Use this template locally

1. Install [Ruby](https://www.ruby-lang.org/en/).
2. Install [Jekyll](https://jekyllrb.com/docs/).
3. Clone or download the repository to your own machine.
4. Edit `_config.yml`. Replace the dummy data with your own career details. Put your own icons in the `imgs` folder.
5. `cd` to repository. Run `bundle exec jekyll serve`. 
6. Go to `localhost:4000`.
7. Right-click the page and click `print...` to save your resume in PDF.


## Things to Note

1. By default, your browser add **margins** to the document when you save the webpage for PDF. This should work fine, but you can also customize the margins in your browser print setting popup if you want to.
2. Be sure to use **square** (e.g. 512x512) images for icons and logos.

## Contributions

If you have any suggestion, feel free to open issues or submit pull requests.