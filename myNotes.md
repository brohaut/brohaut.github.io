# My Notes / My Help

## download online github repository
cd ~rohaut/Sites/
mkdir mysite
cd mysite
git clone https://github.com/brohaut/brohaut.github.io

git clone https://github.com/brohaut/myoclonus_back_averaging

## Local preview
cd ~rohaut/Sites/mysite; bundle exec jekyll serve --watch  
## Update local changes on github

### list of mismatches
git status
### update
cd ~rohaut/Sites/mysite; git add .; git commit -m 'minor update'; git push

cd ~rohaut/github/myoclonus_back_averaging; git add .; git commit -m 'upload'; git push


## help
http://stackoverflow.com/questions/11019839/how-to-use-terminal-commands-with-github#11019894

insert an image in a post:
![My helpful screenshot]({{ site.url }}/images/AST_3183.jpg)
or
![a picture of nature](http://placeimg.com/400/300/nature)

### ref for syntax Md (kramdown in config)
https://kramdown.gettalong.org/quickref.html#tables

{::comment}
blabla comment in post ...
{:/comment}
