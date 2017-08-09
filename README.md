# A Proposal for Forth at PyConUK 2017

The PyCon UK 2017 CFP is here: http://2017.pyconuk.org/cfp/

Following the suggestions on that CFP,
a talk's title and subtitle might be

> What I learned building Forth in 64-bit Intel assembly
> 
> an excursion into why we make languages,
> how they help us solve problems,
> and how we implement them on computers.

(as per the CFP) The goals of this talk are to:
- teach the conference something;
- make the conference laugh;
- broaden the conference's horizons.

It might be described in 300 words thus:

The computer programming language Forth
was invented by Charles H. Moore
in 1970.
Forth is famous for being _stack based_ and using
_reverse polish notation_:
the _operators_ come after their _operands_.
A Forth program to convert
from Fahrenheit to Celsius (C = (F-32) × 5/9) is:

`32 - 5 * 9 /`

On 23rd August 2016 I had an urge
to write a Forth system
in 64-bit Intel Assembly.
This talk is about what happens next.

In it I unpack what it means to implement a language.
I dig a little into a lower-level description
of typical computer hardware,
and how we can use that to create a model
of a computational process.

I'll reflect on why there are different programming languages,
and the "power" that different programming languages have.
Programming languages as a social construct
that we use to solve problems,
but, much more importantly, to share and discuss problems.



## Technicalities

Now that I've logged into HQ,
I can see that the proposal is required to have:
- title, 60 characters;
- Subtitle, 120 characters;
- co-presenters
- "What is your session about", 300 words; published in programme.
- Notes to committee, 300 words.
- Suitable for: new programmers / teachers / data scientists


## The chapter titles for a talk might be

Forth
Notation
Expressing Problems
Solving Problems using Suitable Notation
What is a Computer?
What is a Language?
What does it mean to Implement a Language?
A Model for Forth
Implementing the Model
Reflecting on the Model
The Various Layers
Moving between Layers
The Bootstrap
Strategies for Bootstrap
