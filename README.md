blog
====

Blog for AiringPods.com

While you author, you can see the live changes by:
1. Run "jekyll serve --watch" from your root folder (in this case "blog" folder)
2. Then live changes are availavle @ http://localhost:4000/
3. Since we use compass/sass for styles, you need to also run the "compass watch" from /blog/styles folder


NOTE:
github doesnt run plugins, so we have to ensure what the plugin does, result as files in the repo 
(we do this for sitemap and compass/sass now)
cp ./_site/sitemap.xml ./

