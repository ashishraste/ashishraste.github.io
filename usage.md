Adding a new tab on the blog's main page.
---
1. Create "/new_page.md" file specifying the path where its content will be added.
2. Add "new_page" href in _layouts/default.html as that is acting the default 
index page, as per the /index.html settings, being served in the site.
3. Write content in "/new_page.md" file that will be populated in html in the content directory by jekyll.


Adding a new blog-post
---
1. Write the content of the blog post in Liquid YAML format and save it as a markdown file having the name-format as YYYY-MM-DD-Title.md under _posts/. 


For publishing the site pages on Github
---
1. Build the site at the parent directory level which is nothing but the source branch.
2. Go to the _site/ folder which has the built content and where the master branch points to, commit the changes and push them to Github.


Adding a new theme for Github pages
---
1. Refer to : [adding a new theme](https://help.github.com/articlesadding-a-jekyll-theme-to-your-github-pages-site/)