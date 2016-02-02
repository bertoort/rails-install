# rails-install

## First, Intall RVM

```curl -sSL https://get.rvm.io | bash -s stable --rails```

#### Load RVM into your shell sessions as a function

```source ~/.rvm/scripts/rvm```

```rvm user gemsets```

#### Test - should return rvm is a function
```type rvm | head -n 1```

#### Install Ruby 2.1.5

```rvm install 2.1.5```

```rvm use 2.1.5```

#### Intalling Rails

```gem install rails```

If you run into issues not being able to locate gems, set ```GEM_HOME="$HOME/.gems"```

#### Test
```rails -v```

#### Installing Bundler

```gem install bundler```

## Resources

* http://guides.rubyonrails.org/getting_started.html
* https://rubygems.org/
* http://bundler.io/
