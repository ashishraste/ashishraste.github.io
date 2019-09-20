# Usage

## Adding a new tab on the blog's main page

1. Create "/new_page.md" file specifying the path where its content will be added.
2. Add "new_page" href in _layouts/default.html as that is acting the default
index page, as per the /index.html settings, being served in the site.
3. Write content in "/new_page.md" file that will be populated in html in the content directory by jekyll.

## Adding a new blog-post

1. Write the content of the blog post in Liquid YAML format and save it as a markdown file having the name-format as YYYY-MM-DD-Title.md under _posts/.

## Publishing the site pages on Github

1. Build the site at the parent directory level using the following command.
  
    ```bash
    bundle exec jekyll build
    ```

2. Run locally and test the changes.

    ```bash
    bundle exec jekyll run
    ```

3. Go to the _site/ folder which has the built content and commit/push its repo changes to Github.

## Adding a new theme for Github pages

1. Refer to [adding a new theme](https://help.github.com/articlesadding-a-jekyll-theme-to-your-github-pages-site/)
