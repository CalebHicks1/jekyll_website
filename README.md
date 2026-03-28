# Install dependencies (ubuntu):
Install Ruby:
```
sudo apt-get install ruby-full build-essential zlib1g-dev
```
Configure the installation path:
```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```
Install bundler:
```
gem install jekyll bundler
```
Install bundle:
```
bundle install
```
# Running the dev site
Build site:
```
jekyll build
```

Serve site:
```
bundle exec jekyll serve --livereload
```

Site is hosted at http://localhost:4000 by default
