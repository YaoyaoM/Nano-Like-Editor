# Nano-Like-Text-Editor-OCaml
## Sandy Jiang, Terryn Jung, Yaoyao Ma
We have implemented a text editor that has similar functionalities to Nano. There are search and replacing a text, cutting out an entire line, deleting text, inserting text, etc. We also implemented functions that save and duplicate files, deleting the file and renaming the file as well. 


- Assuming that OCaml is already installed (if not, you can download it here → https://ocaml.org/docs/install.html), the following packages would come with it:
  - oUnit (https://github.com/gildor478/ounit/releases/download/v2.2.2/ounit-v2.2.2.tbz)
  - ANSITerminal (https://github.com/Chris00/ANSITerminal/releases/download/0.8.2/ANSITerminal-0.8.2.tbz)
  - ocamlbuild (https://github.com/ocaml/ocamlbuild/archive/0.14.0.tar.gz)

- Then download this repository on your local disk. 

- Suppose you save it in ~/Downloads/cs3110-ms.zip. From the directory, issue the following commands to unzip the files and clean away the downloaded file:
```
$ unzip cs3110-ms.zip
$ rm cs3110-ms.zip
```

- In your terminal, navigate into the repo folder on your local filesystem.

- Issue the following command in your terminal to run our text editor:
```
$ make run
```

(We also have the following supplementary make commands available, although they are not necessary for to running this editor:
```
$ make build
$ make test
$ make zip
$ make docs
$ make docs-public
$ make docs-private
$ make clean
```
)
- Once you see the colorful welcome message on start, type `help` and hit enter to see instructions on how to use our editor.
