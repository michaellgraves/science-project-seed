# science-project-seed

### Seed data for science project
Includes:
* Science project content structure
* Sample
* index.html
* 404.html
* _config.yml with configuration required for site

### Instructions
1. Fork [science-project-seed] (https://github.com/michaellgraves/science-project-seed)
2. Create gh-pages branch within new repository
3. Replicate locally
4. Add jekyll-bootstrap-template as a submodule of your project

>git submodule add https://github.com/<user>/jekyll-bootstrap-template template


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
	* post should include this front matter (post is the default layout configured in _config.yml)
		*title: <title of your post>
		*tags: <any tags>
 

