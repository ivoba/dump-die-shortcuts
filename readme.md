# d($var); dd($var); shortcut functions for symfony's VarDumper component

[![Build Status][ico-travis]][link-travis]

Though this functions were rejected by symfony core team, it will probably still save tons of keystrokes around the world.  
Also see: https://github.com/ivoba/dump-die

## Installation

    composer require ivoba/dump-die-shortcuts --dev

## Usage

    d($var); // shortcut for dump($var);
    dd($var); // shortcut for dump_die($var);

### Credits

https://github.com/symfony/symfony/pull/13657  
https://github.com/symfony/symfony/pull/17267  
https://github.com/symfony/symfony/pull/19096  

one function package ;) npm style...

[ico-travis]: https://img.shields.io/travis/ivoba/dump-die-shortcuts/master.svg?style=flat-square
[link-travis]: https://travis-ci.org/ivoba/dump-die-shortcuts
