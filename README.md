#Project Zaza
> Homework project Zaza for **MACS, OS101, [FUT](http://freeuni.edu.ge)** - 2015 Fall

#Introduction
პროგრამა fsh (free shell) 'unix shell'-ის ერთ-ერთი იმპლემენტაციაა მსგავსად bash-ის, ksh-ის და csh-სა.

###Developers
Project is Written by the group of developers:
- [Developer 1](https://github.com/glaba13)
- [Developer 2](https://github.com/nikoloze)
- [Developer 3](https://github.com/tripoliati)
- [Developer 4](https://github.com/NutsaNutsa)

###External Libs
MakeFile უზრუნველყოფს პროექტის გაშვებისათვის მზადყოფნას, აყენებს ყველა საჭირო ბიბლიოთეკას, რომლებიც თავისმხრივ მოჰყვება კოდს

#Usage
user-ი თავს ისე გრძნობს, როგორც ტერმინალთან მუშაობისას: შეუძლია ისარგებლოს built-in ფუნქციებით, საკონტროლო ოპერატორებით, გარდა ჩაშენებული ბრძანებებისა fsh-ს ასევე შეუძლია სხვა ნებისმიერი გარე პროგრამის გაშვება

##Feature 1
- dsc 1
- dsc 2
- dsc 3

##Feature 2
- dsc 1
- dsc 2
- dsc 3
```
e.g.
some example
```

#Project Structure

###Tree
```
.
├── somesrc.c
├── makefile
├── README.md
├── somedir
│     ├── othersrc.c
│	    ├── otherheader.h
└── otherdir
      ├── somemoresrc.c
      └── somemoreheader.h
```

###Modules

- **modeule_one.[c/h]**:
> this module contains implementation of ...

- **modeul_two.[c/h]**:
> this module contains implementation of ...

``` C
...
typedef struct {
      int argc;
      char ** argv;
} some_struct;

void some_fn(some_struct* c);
...
```

- **main.c**:
> Entry point of the programm, ...

###makefile
project is built using [make](http://www.gnu.org/software/make/manual/make.html),
file contains instructions for [make](http://www.gnu.org/software/make/manual/make.html)
to build project.

###README.md
readme of the project.
