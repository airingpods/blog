blog
====

Blog for AiringPods.com

While you author, you can see the live changes by:

1. Run "jekyll serve --watch" from your root folder (in this case "blog" folder)
2. Then live changes are availavle @ http://localhost:4000/
3. Since we use compass/sass for styles, you need to also run the "compass watch" from /blog/styles folder


NOTE:

Github Pages doesnt run plugins, So we have to ensure that whatever a plugin does, results as files in the repo.
Earlier we had to copy the generated sitemap.xml from _site folder to the repository. But, this is no more needed now, github supports jekyll-sitemap now.

