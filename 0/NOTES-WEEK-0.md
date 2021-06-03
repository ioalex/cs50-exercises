# Week 0

- [Week 0](#week-0)
  - [What is computer science?](#what-is-computer-science)
  - [Representing numbers](#representing-numbers)
  - [Text](#text)
  - [Images, video, sounds](#images-video-sounds)
  - [Algorithms](#algorithms)
  - [Pseudocode](#pseudocode)
  - [Scratch](#scratch)

## What is computer science?

- Computer science is problem solving.
- We can think of problem solving as the process of taking some input (details about our problem) and generate some output (the solution to our problem).

```text
input --> ☐ --> output
```

- The "box" in the middle is computer science, aka. the code we will be writing.
- To begin doing that, we’ll need a way to represent inputs and outputs, so we can store and work with information in a standardized way.

## Representing numbers

- Counting with fingers (where each digit represents a single value of one) uses a **unary** numbering system.
- Our everyday numbering system (where we have ten digits, 0 to 9) is decimal, or **base 10**, since there are ten different values that a digit can represent.

- Computers use a simpler system called **binary**, or **base 2**, with only two possible digits, 0 and 1.
- Since computers run on electricity, which can be turned on or off, we can conveniently represent a bit by turning some switch on or off to represent a 0 or 1.
- Inside modern computers, there are millions of tiny switches called **transistors** that can be turned on and off to represent different values.

In binary, with just two digits, we have powers of two for each place value:

```text
2^2 2^1 2^0
 #   #   #
```

This is equivalent to:

```text
4  2  1
#  #  #
```

## Text

- To represent letters, all we need to do is decide how numbers map to letters. Some humans, many years ago, collectively decided on a standard mapping of numbers to letters. The letter “A”, for example, is the number 65, and “B” is 66, and so on. By using context, like whether we’re looking at a spreadsheet or an email, different programs can interpret and display the same bits as numbers or text.
- The standard mapping, **ASCII**, also includes lowercase letters and punctuation.
- If we received a text message with a pattern of bits that had the decimal values 72, 73, and 33, those bits would map to the letters HI!. Each letter is typically represented with a pattern of eight bits, or a byte, so the sequences of bits we would receive are 01001000, 01001001, and 00100001.
- Other characters, such as letters with accent marks and symbols in other languages, are part of a standard called Unicode, which uses more bits than ASCII to accommodate all these characters.
- When we receive an emoji, our computer is actually just receiving a number in binary that it then maps to the image of the emoji based on the Unicode standard.

## Images, video, sounds

- An image, like the picture of the emoji, are made up of colors.
- With only bits, we can map numbers to colors as well. There are many different systems to represent colors, but a common one is **RGB**, which represents different colors by indicating the amount of red, green, and blue within each color.
- The resolution of an image is the number of pixels there are, horizontally and vertically, so a high-resolution image will have more pixels and require more bytes to be stored.
- Videos are made up of many images, changing multiple times a second to give us the appearance of motion, as an old-fashioned flipbook might do.
- Music can be represented with bits, too, with mappings of numbers to notes and durations, or more complex mappings of bits to sound frequencies at each moment of time.
- File formats, like JPEG and PNG, or Word or Excel documents, are also based on some standard that some humans have agreed on, for representing information with bits.

## Algorithms

- Now that we can represent inputs and outputs, we can work on problem solving. The box earlier will contain **algorithms**, step-by-step instructions for solving problems:

```text
input --> algorithms --> output
```

- When programming a computer, we need to be more precise with our algorithms so our instructions aren’t ambiguous or misinterpreted.
- When we write programs using algorithms, we generally care not just how correct they are, but how well-designed they are, considering factors such as efficiency.

## Pseudocode

- We can write pseudocode, which is a representation of our algorithm in precise English (or some other human language). For example:

```text
1  Pick up phone book
2  Open to middle of phone book
3  Look at page
4  If person is on page
5      Call person
6  Else if person is earlier in book
7      Open to middle of left half of book
8      Go back to line 3
9  Else if person is later in book
10     Open to middle of right half of book
11     Go back to line 3
12 Else
13     Quit
```

## Scratch

- We can write programs with the building blocks we just discovered:
  - functions
  - conditions
  - Boolean expressions
  - loops
- And we’ll discover additional features including:
  - variables
  - threads
  - events
  - …
- Before we learn to use a text-based programming language called C, we’ll use a graphical programming language called Scratch, where we’ll drag and drop blocks that contain instructions.

- Abstraction simplifies a more complex concept.
