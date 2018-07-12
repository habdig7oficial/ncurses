# ncurses

Ncurses Bindings for Crystal

## Installation


Add this to your application's `shard.yml`:

```yaml
dependencies:
  ncurses:
    bitbucket: SamualLB/ncurses
```


## Usage


```crystal
require "ncurses"
```

Basic Printing

```crystal
NCurses.init

NCurses.stdscr.print "Hello world!"

NCurses.end_win
```

## Contributing

1. Fork it ( https://bitbucket.org/SamualLB/ncurses.git )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- (https://github.com/jreinert) Joakim Reinert - creator, maintainer
- (https://bitbucket.org/SamualLB) Samual Black - maintainer
