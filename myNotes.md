# My Notes / My Help


## download online github repository
cd ~rohaut/Sites/
mkdir mysite
cd mysite
git clone https://github.com/brohaut/brohaut.github.io

cd ~rohaut/Sites/mysite

## Local preview
bundle exec jekyll serve --watch   

## Update local changes on github
### list of mismach
git status
### update
git add .; git commit -m 'Type your commit message here'; git push


## help
http://stackoverflow.com/questions/11019839/how-to-use-terminal-commands-with-github#11019894

insert image in post:
![My helpful screenshot]({{ site.url }}/images/AST_3183.jpg)
or
![a picture of nature](http://placeimg.com/400/300/nature)
