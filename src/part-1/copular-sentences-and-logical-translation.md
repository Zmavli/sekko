# Copular sentences and logical translation

In this chapter, one shall finally learn how to say something in Eberban. We
shall consider only the simplest type of sentence here -- copular sentences. One
will also learn personal pronouns of class MI. 

Copular sentences in English are of the form "X is Y", such as "This is an
apple," or "I am happy". 

Eberban does not have a copula particle like in English, being that it has no
distinction between verbs, nouns and adjectives formally. Certain words are used
very similarly to how verbs, nouns and adjectives are used in English, yes, but
underneath, the grammar is all the same -- they are all predicates. Let us
consider the sentence "This is an apple" again. One could define "this" and
"apple" thusly:

> this: P is this.
> apple: P is an apple.

And then construct the sentence like so:

> **this is an apple**
> 
> - P is this
> - P is an apple

One could actually break down virtually all English sentences like this. Here is
another, more complex example.

> **I go to the market.**
> 
> - P is me (I)
> - P goes to Q (go to)
> - Q is the market. (the market)

This is the core of Eberban grammar. All root words are predicates. To ensure
that it will be understood, we will have an exercise in the middle of the
lesson.

## Decomposition of English sentences

Decompose the following sentences into the Eberban predicate style, similar to
what is shown above.

<spoiler>
I look at you.

- P is me (I)
- P looks at Q. (look at)
- Q is you. (you)
</spoiler>

<spoiler>
Someone eats an apple.

- P is someone. (someone)
- P eats Q. (eats)
- Q is an apple. (an apple)
</spoiler>

<spoiler>
I go from the mall to the office.

- P is me. (I)
- P goes from Q to R. (go from ... to ...)
- Q is the mall. (the mall)
- R is the office. (the office)
</spoiler>

<spoiler>
I am sad.

- P is me. (I)
- P is sad. (am sad)
``
</spoiler>

Eberban treats **existential variables** as "first-class citizens" -- they are
the linchpin from which all other grammar derives. Given that Eberban is a
logical language, it makes sense that sentences should be easy to translate into
formal logic. Specifically, Eberban uses second-order logic. When one says **mei
menoe**, one is actually saying

<gloss>
mei menoe

mei menoe

{X is something near the speaker} {X is an apple}

There exists X such that X is something near the speaker and X is an apple.
</gloss>

Reciprocally, when one says **mei menoe**, one is not only saying "There is
something near (the speaker) that is an apple," but also "There is an apple that
is near (the speaker)".