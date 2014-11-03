# empty-haskell-project

This repository contains just an empty Haskell project.


## How you can use it


## How it was created

Steps...


### 1. Create the repository in GitHub


### 2. Clone the repository (from GitHub to your computer)

Using one of these methods:

- git clone 
- [Clone in Desktop](github-mac://openRepo/https://github.com/Learning-Haskell/empty-haskell-project)
- [Download ZIP](https://github.com/Learning-Haskell/empty-haskell-project/archive/master.zip)


### 3. Create the minimal cabal project files

#### cd

``` bash
$ cd empty-haskell-project/
```

Files at this point:

``` bash
$ ls
LICENSE		README.md
```

#### cabal init

``` bash
$ cabal init
Package name? [default: empty-haskell-project] 
Package version? [default: 0.1.0.0] 
Please choose a license:
 * 1) (none)
   2) GPL-2
   3) GPL-3
   4) LGPL-2.1
   5) LGPL-3
   6) AGPL-3
   7) BSD2
   8) BSD3
   9) MIT
  10) MPL-2.0
  11) Apache-2.0
  12) PublicDomain
  13) AllRightsReserved
  14) Other (specify)
Your choice? [default: (none)] 14
Please specify? CC0 1.0 Universal
Author name? [default: Ross Kendle] 
Maintainer email? [default: ross.kendle@gmail.com] 
Project homepage URL? https://github.com/Learning-Haskell/empty-haskell-project
Project synopsis? Just an empty Haskell project
Project category:
 * 1) (none)
   2) Codec
   3) Concurrency
   4) Control
   5) Data
   6) Database
   7) Development
   8) Distribution
   9) Game
  10) Graphics
  11) Language
  12) Math
  13) Network
  14) Sound
  15) System
  16) Testing
  17) Text
  18) Web
  19) Other (specify)
Your choice? [default: (none)] 1
What does the package build:
   1) Library
   2) Executable
Your choice? 2
What is the main module of the executable:
 * 1) Main.hs (does not yet exist)
   2) Main.lhs (does not yet exist)
   3) Other (specify)
Your choice? [default: Main.hs (does not yet exist)] 
What base language is the package written in:
 * 1) Haskell2010
   2) Haskell98
   3) Other (specify)
Your choice? [default: Haskell2010] 
Include documentation on what each field means (y/n)? [default: n] n

Guessing dependencies...

Generating LICENSE...
Warning: unknown license type, you must put a copy in LICENSE yourself.
Generating Setup.hs...
Generating empty-haskell-project.cabal...

You may want to edit the .cabal file and add a Description field.
```

Files at this point:

``` bash
$ ls
LICENSE				README.md			Setup.hs			empty-haskell-project.cabal
```

### 4. Create Main.hs

``` haskell
-- Main.hs
main = print "Hello World"
```

Files at this point:

``` bash
$ ls
LICENSE				README.md			empty-haskell-project.cabal
Main.hs				Setup.hs
```

### 5. Run

``` bash
$ runhaskell Main.hs
"Hello World"
```

### 6. Edit README.md

Edit this document!

### 7. Commit and Sync to GitHub

Using one of these methods:

- GitHub Mac (or GitHub Windows)
- ```git ...```

