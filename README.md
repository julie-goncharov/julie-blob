# How-To build Julie-blob with Jekyll and BibTex-js		
from the scratch

## Setting up a GitHub Pages with Jekyll

[instructions on GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

### Create a repository (julie-blob)

* In the upper-right corner of any page, select , then click New repository.
* Repository Name: julie-blob

### On local computer

* git init julie-blob
* cd julie-blob
* echo "# julie-blob" >> README.md
* git init
  >Initialized empty Git repository in ~/julie-blob/.git/
* vi Gemfile
  >gem "github-pages", "~> 228", group: :jekyll_plugins
  >
  >jekyll new --skip-bundle
* bundle install
* git add .
* git commit -m 'Initial GitHub pages site with Jekyll'
* git push -u origin main

## Install Jekyll

[Install ASDF]( https://asdf-vm.com/guide/getting-started.html )	

* git clone https://github.com/excid3/asdf.git ~/.asdf		
* echo '. "$HOME/.asdf/asdf.sh"' >> ~/.zshrc		
* echo '. "$HOME/.asdf/completions/asdf.bash"' >> ~/.zshrc		
* echo 'legacy_version_file = yes' >> ~/.asdfrc
* exec $SHELL
* . .zshrc
### recreate folder  
* rm -rf julie-blob
* Download ZIP form GitHub and uncompress		
* cd julie-blob		
* git init		
* git remote add origin git@gh_julie:julie-goncharov/julie-blob.git		
* git remote -v		
	>origin git@gh_julie:julie-goncharov/julie-blob.git (fetch)
 	>	
	>origin git@gh_julie:julie-goncharov/julie-blob.git (push)	
* rm *		
* rm .DS_Store .gitignore		
* git pull origin main		
* git branch		
	>* main	
### install Ruby		
* asdf plugin add ruby		
* asdf install ruby 3.1.4		
* asdf global ruby 3.1.4		
* ruby -v		
	>ruby 3.1.4p223 (2023-03-30 revision 957bb7cb81) [x86_64-darwin21]	
* gem install jekyll bundler		
* gem install bundler:2.4.22		
* bundler install		
* bundler exec jekyll serve
   
http://127.0.0.1:4000/julie-blob/
  >press ctrl-c to stop.  
