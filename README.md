# The BRO Tales
[![pages-build-deployment](https://github.com/thebrotales/thebrotales.co.za/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/thebrotales/thebrotales.co.za/actions/workflows/pages/pages-build-deployment) [![.github/workflows/fix-ip.yaml](https://github.com/thebrotales/thebrotales.co.za/actions/workflows/fix-ip.yaml/badge.svg)](https://github.com/thebrotales/thebrotales.co.za/actions/workflows/fix-ip.yaml)

The Bonny, Ronnie and Onnie Tales. 

## Copyright and License

Software is licensed under MIT. 
All images are subject to copyright of The BRO Tales


# Running locally

```shell
sudo apt update
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler
bundle install
bundle exec jekyll serve --watch --force_polling --verbose --livereload --port 4001 --livereload-port 35728
```

