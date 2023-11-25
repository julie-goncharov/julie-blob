# How-To build Julie-blob with Jekyll and BibTex-js		
from the scratch	
## Setting up a GitHub Pages with Jekyll
[instructions on GitHub] (https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

1. Install ASDF ( https://asdf-vm.com/guide/getting-started.html )		
git clone https://github.com/excid3/asdf.git ~/.asdf		
git clone https://github.com/excid3/asdf.git ~/.asdf		
git clone https://github.com/excid3/asdf.git ~/.asdf		
git clone https://github.com/excid3/asdf.git ~/.asdf		
git clone https://github.com/excid3/asdf.git ~/.asdf		
git clone https://github.com/excid3/asdf.git ~/.asdf		
git clone https://github.com/excid3/asdf.git ~/.asdf		
2. Download ZIP and uncompress		
3. cd julie-blob		
4. git init		
git remote add origin git@gh_julie:julie-goncharov/julie-blob.git		
git remote -v		
	origin git@gh_julie:julie-goncharov/julie-blob.git (fetch)	
	origin git@gh_julie:julie-goncharov/julie-blob.git (push)	
5. rm *		
rm .DS_Store .gitignore		
git pull origin main		
git branch		
	* main	
6. install ruby		
asdf plugin add ruby		
asdf install ruby 3.1.4		
asdf global ruby 3.1.4		
ruby -v		
	ruby 3.1.4p223 (2023-03-30 revision 957bb7cb81) [x86_64-darwin21]	
7. gem install jekyll bundler		
gem install bundler:2.4.22		
bundler install		
bundler exec jekyll serve		
http://127.0.0.1:4000/julie-blob/		
