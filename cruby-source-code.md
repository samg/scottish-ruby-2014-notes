CRuby Source Code

### Motivation:

Wanted to understand Ruby

* Object Model
* Metaprogramming
* GC

Speed up Ruby

* Rewrite parts of your code in C
* 10x - 50x faster

### Installing (some steps ommitted, YMMV)

$ brew install oenssl
$ autoconf
$ ./configure --prefix=$HOME/myruby --with-opt-dir=/user/local/Cellar/openssl/1.0.1.f optflags="-O0" debugflags="-g" --disable-install-doc
$ make

$ lldb ruby script.rb
 or use xcode for visual debugging



In the ruby source tree most of the useful information is in the root directory, not in subdirectories.

### Defining a method

```
rb_define_method(rb_cArray, "length", rb_ary_length, 0)
static VALUE rb_ary_length {
...

```

Need to convert types between ruby types and c types.
