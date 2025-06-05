# Ruby Permission Issue for installing jekyll
Indicator: Local path is “usr/bin/ruby” rather than “usr/local/bin/ruby”
Fix: Install ruby version manager
- brew install rbenv
- rbenv init
- rbenv install 3.1.2
- rbenv global 3.1.2
- Restrat terminal
- rbenv init
- rbenv global 3.1.2
- Which ruby → check that its something like “/Users/jonathanngai/.rbenv/shims/ruby”

- Then do gem install jekyll 
