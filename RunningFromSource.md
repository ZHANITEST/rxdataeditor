You need to download and install [Ruby](http://ruby-lang.org/) and [RubyGems](http://www.rubygems.org/). Once you got them installed, you have to install wxRuby with the following command:

```
[sudo] gem install wxruby-1.9.8
```

And then you have everything you need to run RXData Editor from the source code. You can execute it typing the following command from the source directory:

```
ruby rxdataed.rb
```

In Linux, you can enable yourself to run the script as an executable from any
directory changing its permissions and creating a symbolic link:

```
chmod +x rxdataed.rb
ln -s rxdataed.rb /usr/bin/rxdataed
```