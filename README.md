## Mars.radio

1) [Install Ruby](https://jekyllrb.com/docs/installation/). For Mac, make sure you've installed [Homebrew](https://brew.sh/). Then:

    ```
    brew install rbenv
    echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
    source ~/.bash_profile
    eval "$(rbenv init -)"
    curl -fsSL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-doctor | bash
    rbenv install 2.7.1
    rbenv global 2.7.1
    ```

2) Install Jekyll and bundler gems

    ```
    gem install --user-install bundler jekyll
    echo 'export PATH="$HOME/.gem/ruby/2.7.1/bin:$PATH"' >> ~/.bash_profile
    source ~/.bash_profile
    ```

3) Clone this repository

    ```
    git clone https://github.com/brahman-ai/mars.radio
    ```

4) Initiailize it with bundler

    ```
    cd mars.radio
    bundle install
    ```

5) Launch locally

    ```
    bundle exec jekyll serve
    ```
    
6) Go to [http://localhost:4000](http://localhost:4000)
