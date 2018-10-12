Sources of the main [mlr website](https://mlr-web.netlify.com/) including the blog post sources.

`blogdown` and Hugo are used to render the site. Deployment is done via Netlify.

# How to add a new blog post

1. Add yourself as an author to https://github.com/mlr-org/mlr/wiki/Misc#mlr-developer-team-and-contributors-page.

2. Create a new post in `content/post/`

3. Put external images in `static/images/<name of your post>`

4. Preview your post by running `blogdown::serve_site()`

5. Commit the Rmd and HTML file and possible external ressources.

6. Open a Pull Request. You can preview the changes on Netlify (FIXME: Improve this section when we have the first PR)
