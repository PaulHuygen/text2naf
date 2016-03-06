# text2naf
Wrap a text in a NAF XML

The python (vs. 3) script text2naf reads a text from standard in and produces
a [NAF-formatted](http://wordpress.let.vupr.nl/naf/software/) document
on standard out. It is stuffed with undocumented and untested features.



## Usage

eg:

```
cat "I will be wrapped in NAF" | ./text2naf -l en >Iwrap.naf
```

To get an overview of the undocumented/untested features, do:

```
./text2naf -h
```

