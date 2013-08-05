Setting Up a Dev Environment for Ruby on Rails on Mac OSx
=============================

Preparing for Ruby
------------------
- Get a Github account
----------------------
http://www.github.com

- Install XCode
---------------
https://developer.apple.com/xcode/

- Install Command Line Tools for Xcode
--------------------------------------

- Install Homebrew
------------------
http://brew.sh/

ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

brew update

- Install Rbenv and Ruby-build
------------------------------
brew install rbenv ruby-build
echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
source ~/.bash_profile

rbenv install 1.9.3-p448 && rbenv global 1.9.3-p448
rbenv rehash

- Install Bundler
-----------------
gem install bundler
rbenv rehash

- Install Postgres
------------------
