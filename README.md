# www.karma.net/GUS

this is the website for Gus's campaign

## to run Jekyll locally

sudo gem install bundler
sudo gem install jekyll

cp Gemfile from other site that uses github pages already

bundle install

## to install obsidianhtml from source

goto the obsidian-html source dir (src/opensource/obsidian-html) - git pull and then install via pip3 (this installs the latest from github)

`pip3 install .`

### run the converter

you don't normally need to rm anything, as obsidianhtml does that for you, but I'm doing this because I'm using "non release" binaries at times ...

```rm -Rf output; rm -Rf _site; obsidianhtml convert -v```

### run jekyll

```bundle exec jekyll serve --trace --drafts```
