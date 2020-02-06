# Dictionarium Gallovidii Linguae Latinae

**A concise Latin-English dictionary**

Once upon a time, I was learning Latin and having a grand
old time.  Latin, being rather a difficult endeavour,
necessitated that I compile a collection of reference
sheets for the words and concepts that I was wrestling
with understanding and remembering.  One such document for
Latin nouns, one such for verbs, which makes sense.  As the
language to which I was being indroduced grew in
complexity, so too did the number of reference sheets---
adverbs, adjectives, pronouns, prepositions--- as did
their size.  I then came upon a stupid idea.  "What if I
were to take all these references and combine them into a
single reference?"  Well then I guess I would have a
dictionary.

Here then, is *Dictionarium Gallovidii Linguae Latinae*,
a Latin-English dictionary written from the perspective of
an English-speaking person (engineer?) learning the Latin 
language from a small number of primary sources and a 
larger number of literary secondary sources.

The document is not yet finished, but I am pretty
determined to learn this stuff, so expect actual progress
to be made relatively frequently.

## Usage

If you're really interested in how far along this project
is, I suppose you can compile it.  I dunno why you'd do
this before any actual releases exist.  Don't let me catch
you printing it.

```Shell
git clone https://github.com/jwrg/dictionarium.git
pdflatex dictionarium.tex
```

## Sources

We would get nowhere without standing on the shoulders of
giants.  This project is a distillation of other sources on
the Latin language.

### Primary Sources

The document considers the following primary sources:

- Molinarius (TTC's The Great Courses)
- Wheelock

### Secondary Sources

The document considers the following secondary sources:

- Levy's *A Latin Reader for Colleges*

## LaTeX Class and Packages

The document makes use of custom LaTeX packages, which are
collected under the Capiar project.

- dictionarium (class)
- dictionarium (package)
- inscription (package)

## Roadmap

In the future, the following will be added:

- Deponent verbs
- A proper preface
- Tables that stick together
