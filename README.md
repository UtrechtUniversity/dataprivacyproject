## Data Privacy Project - project landing page
This is the repository underlying the landing page of the Data Privacy Project at Utrecht University. We use this space to update the content and looks of the website.

You can access the website with information about the project here: https://utrechtuniversity.github.io/dataprivacyproject/

A related repository is that of the [Data Privacy Handbook](https://utrechtuniversity.github.io/dataprivacyhandbook/), a key deliverable within this project. You can access that repository [here](https://github.com/UtrechtUniversity/dataprivacyhandbook/#readme).

### Technical information
In this repository, we are using:
- The jekyll theme "Alembic", forked from [this repository](https://github.com/daviddarnes/alembic)
- Dependabot, to check for security issues and run automatic updates

Here's a quick summary of the folder contents in this repository:
- `.github`: contains dependabot settings
- `.jekyll-cache`: cached files, no need to do anything with this
- `_data`: data files from which the menu and people page is built
- `_drafts`: draft news posts (not published)
- `_includes`: html-files that make up parts of the webpages
- `_layouts`: the skeleton layout of the webpages
- `_posts`: markdown files that will become listed as newsposts, filename format should be "yyyy-mm-dd-title-of-post.md"
- `_sass`: styling of the website (e,g., colors, size, alignment, etc.)
- `assets`: fixed files like pdf documents (docs), images, fonts and javascripts
- `news`: contains the main page displayed on the news webpage. This is a collector-page which shows the collection of news posts
- `pages`: all web pages in editable .md format (except the homepage)
- Separate files:
  - `.gitignore`: which files or folder should not be tracked by git?
  - `Gemfile`: which Ruby gems are used in this theme?
  - `README.md`: this readme file
  - `_config.yml`: the site settings
  - `alembic-jekyll-theme.gemspec`: specifications of the theme gem
  - `index.md`: the homepage, should always be in the root of the repository