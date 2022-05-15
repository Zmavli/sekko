# Claims of Existence
The most basic type of sentence is a claim of existence. In English, they are in the form of "There is/are X".

<gloss>
There is an apple.

{There is} {an apple.}

{∃x:} {apple(x)}

There exists X such that X is an apple.
</gloss>

Note that although the English translations and examples in this book will usually be in the singular, this is only because English mandates that words be inflected for number. Sekko does not mandate this, and so words may refer to one or more entities. Explicit declarations of number will be covered in [Numerals](numerals.md).

<spoiler>
What does **∃** or **apple(x)** mean?

In symbolic logic, **∃** represents the existential quantifier and means that there exists at least one thing which fulfills a certain predicate. **∃x:** means "There exists X such that...". The letter "x" is simply a term for a variable.
	
**apple()** represents a predicate. Variables are passed into predicates to signify that they fulfill the predicate. Therefore, **apple(x)** signifies that the variable X fulfills the property of "being an apple". It is possible for a predicate to accept multiple variables as arguments.
</spoiler>

Notice how in the original English sentence, there were two components: the noun phrase "an apple", and the verb "there is". In order to claim the existence of something, the noun phrase "an apple" must be passed into the verb. Sekko, in its attempt to hew closer to the underlying logical form of natural languages, existential variables are immediately assumed by default. Therefore, the following Sekko utterance is identical[^note] to the English sentence above.

<gloss>
seebo

{There is an apple.}
	
{∃x: apple(x)}
	
There exists X such that X is an apple.
</gloss>

Merely uttering a predicate in Sekko means asserting that there exists at least one thing which satisfies the predicate. This is the default behavior of Sekko predicates, but there are ways to change this which will be covered in further chapters. 

[^note]: The Sekko text is termed an "utterance" as it is not yet a sentence -- it has no illocutions, covered in the [illocutions chapter](illocutions.md). Further, as has been said, Sekko does not mandate inflection or agreement for number.

	