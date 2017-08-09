# A Proposal for Forth at PyConUK 2017

The PyCon UK 2017 CFP is here: http://2017.pyconuk.org/cfp/


## Technicalities

Now that I've logged into HQ,
I can see that the proposal is required to have:
- title, 60 characters;
- Subtitle, 120 characters;
- co-presenters
- "What is your session about", 300 words; published in programme.
- Notes to committee, 300 words.
- Suitable for: new programmers / teachers / data scientists


## What is my proposal?

Following the suggestions on that CFP,
a talk's title and subtitle might be

> What I learned building Forth in 64-bit Intel assembly
> 
> an excursion into what happens when
> one quirky language from the 1970s
> becomes a strange urge and a silly side-project.

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
and a little into 64-bit Intel Assembly.
Compared to Python,
Forth is a low-level language;
compared to Assembly,
Forth is a high-level language.

I'll talk about how we can implement
one language in terms of another,
by building _models_,
and how we can model languages
and model computational processes.

Forth is a tiny, but powerful, language.
Moore's insight was to discover a language that was:
- small;
- sufficient;
- easy to implement;
- extensible.

The result is that Forth implementations are
typically composed of a tiny nucleus (typically in Assembly)
surrounded by a larger amount of "Forth-in-Forth".

Come. Let's implement a language.


## Why should the committee be interested?

More people should know what's involved in implementing
a programming language.


## The chapter titles for a talk might be

- Forth
- Notation
- Expressing Problems
- Solving Problems using Suitable Notation
- What is a Computer?
- What is a Language?
- What does it mean to Implement a Language?
- A Model for Forth
- Implementing the Model
- Reflecting on the Model
- The Various Layers
- Moving between Layers
- The Bootstrap
- Strategies for Bootstrap
