#
![Go ...](golang-logo.png "Go")

---

# Go is ...

- open source
- compiled
- static typed
- concurrent
- garbage collected
- fast

[https://golang.org](https://golang.org)

[Go play](https://play.golang.org)

---

# History

Design by Ken Thompson, Rob Pike &amp; Robert Griesemer

Open sourced in 2009

Current version as of Feb 2016 is 1.5.3

<img src="thompson01.jpg" style="display: inline-block;"/>&nbsp;&nbsp;<img src="Rob-pike-oscon.jpg" style="display: inline-block;"/>&nbsp;&nbsp;<img src="Robert_Griesemer.jpg" style="display: inline-block;">


# Presenter Notes
Google origin. Users of Go in production. dl.google.com and youtube vitess

---

# Features

- Statically typed
- Compiled Static Binary
- Garbage collected
- Easy to cross compile $GOOS &amp; $GOARCH
- Concurrency
- Interface without declaration
- Zero tolerance towards unused variables &amp; imports
- Extensive standard library

# Missing Features
- No function/operator overloading
- No implicit conversions
- No classes and type Inheritance. Composition/Embedding instead
- No Generics
- Errors (interface) preferred over Exceptions

# Presenter Notes
strong language -> no implicit conversions

add some stats around quick compilation

interface does not require explicity implements directive, like java

http://dave.cheney.net/2014/06/07/five-things-that-make-go-fast
https://speakerdeck.com/ftmamud/golang

---

# Syntax / Lex / Data Types
- identifier similar to C family, except for
      - `_` blank identifier
      - Should start with a utf-8 letter character, instead of letter
## Keywords

    !python
    break        default      func         interface    select
    case         defer        go           map          struct
    chan         else         goto         package      switch
    const        fallthrough  if           range        type
    continue     for          import       return       var

## Operators and Delimiters

    !python
    +    &     +=    &=     &&    ==    !=    (    )
    -    |     -=    |=     ||    <     <=    [    ]
    *    ^     *=    ^=     <-    >     >=    {    }
    /    <<    /=    <<=    ++    =     :=    ,    ;
    %    >>    %=    >>=    --    !     ...   .    :
    &^    &^=

# Presenter Notes
unicode letter character ie belonging to class Lu, Ll, Lt, Lm, Lo, or Nl
http://grokbase.com/t/gg/golang-nuts/133y5rq4a0/go-nuts-problem-with-using-devanagari-script-for-go-identifiers  
---

## Lexical elements

- Comments
- Integer literals
- Floating point literals
- Imaginary literals. floating-point or integer literal followed by lower case letter i
- Rune literals, a unicode code point. Inside single quote, \x or \u, \U
- String literals, raw vs interpreted
- Code structured into statements
- Statement terminator ;
- Automatic semi-colon insertion
- Explicit semi-colon required for multiple statement on single line

---

## Hello World

    !python
    package main
    import "fmt"

    func main() {
      fmt.Println("Hello world")
    }


- package
- import
- import aliasing
- visibility


---
## Data Types

--

# Control Structures

---

# Functions


---
