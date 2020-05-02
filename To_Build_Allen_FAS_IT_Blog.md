# Build Allen_FAS IT Blog SOP

Install Ruby
```
# Install Homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install ruby
```

# Build Allen_FAS IT Blog SOP
```
$ mkdir Allen_FAS
$ cd Allen_FAS
$ git init
$ git checkout --orphan gh-pages
$ baseurl: /Allen_FAS

```
This GitHub:
    https://github.com/hcchen/Allen_FAS.git

## To Fix 「Page build failure」
http://blog.tmaize.net/posts/2019/10/13/%E8%A7%A3%E5%86%B3-page-build-failure.html



##
```
allenchendeMacBook-Pro:ruby allen$ ruby -v
ruby 2.3.7p456 (2018-03-28 revision 63024) [universal.x86_64-darwin18]
```
## install Jekyll on MacOS Mojave
1. Install rbenv via brew
``
brew install rbenv ruby-build
``

2. Add rbenv to bash so that it loads every time you open a terminal
``
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile
``
3. Install Ruby through rbenv and set as default
``
rbenv install 2.6.3
rbenv global 2.6.3
``
4. Install Jekyll
``
gem install bundler jekyll
``