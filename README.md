# Brainfuck in Formality
A simple [Brainfuck](https://esolangs.org/wiki/Brainfuck) interpreter written in [Formality](https://github.com/moonad/Formality).

Install Formality and run `fm -r BF_HelloWorld` or `fm -r PBF_HelloWorld`

Alternatively the file can be loaded automatically:

for the IO version

```
fm -l BF_HelloWorld#U2iN
fm -r BF_HelloWorld#U2iN
```

for the pure version of Brainfuck
```
fm -l PBF_HelloWorld#rMeV
fm -r PBF_HelloWorld#rMeV
```

for the version which can run with optimal beta reductions. (It doesn't mean that it is optimal. See ... )
```
fm -l PBF_HelloWorldOptimal#J4Mv
fm -o PBF_HelloWorld#rMeV
```
(This one gives `Maximum call stack size exceeded` when running under `fm -d` option.)

### TO DO:
1. Store the input if it contains more than one character.
2. Optimize?
