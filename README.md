# meshiterro

## Rebuild
```
$ git clone https://github.com/rbenv/rbenv.git ~/.rbenv
$ echo 'export PATH="~/.rbenv/bin:$PATH"' >> ~/.bashrc
$ echo 'eval "$(rbenv init -)"' >> ~/.bashrc
$ exit

$ git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build
$ exit

$ rbenv install 2.6.3
$ rbenv global 2.6.3
$ rbenv rehash
$ ruby -v

$ cd ~/prog/rails/meshiterro
$ bundle install
$ bin/rails db:migrate
$ bin/rails s
```

