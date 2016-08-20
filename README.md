# science-project-seed

### Seed data for science project

Leverages Jekyll theme: 
[jekyll-bootstrap-template] (https://github.com/michaellgraves/jekyll-bootstrap-template)

An example implementation of the theme and seed data can be found here: [sample-science-project] (https://michaellgraves.github.io/sample-science-project)

Seed data includes:
* Sample pages in pages directory. Any pages added here will show up on left-hand-side nav 
* Sample post in _posts directory. Any post added will be displayed in lab notes grid
* index.html
* 404.html
* _config.yml with configuration required for site
* .gitignore for a jekyll site

### Instructions
1. Fork [science-project-seed] (https://github.com/michaellgraves/science-project-seed)
2. Create gh-pages branch within new repository
3. Replicate locally
4. Add jekyll-bootstrap-template as a submodule of your project. From git shell:

>git submodule add https://github.com/michaellgraves/jekyll-bootstrap-template new_template

>git commit -m "adding submodules"

>git push


6. Update _config.yml parameters:
	* title
	* description
	* url
	* baseurl
	* submodule
	* plugins_dir 
	* layouts_dir
	* data_dir
	* includes_dir
	* author.name
	* author.twitter

7. Synch with remote repository
8. Add your user pages to the _posts directory
	* format YYYY-MM-DD-<post_name>.md
	* post should include title and tag parameters in front matter (post is the default layout configured in _config.yml)
9. Add sticky pages to pages directory

