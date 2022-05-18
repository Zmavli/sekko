# Copular sentences
The second simplest type of sentence is the copular sentence, which in English takes on the form of "X is Y". Let us consider the following sentence.

<gloss>
An apple is red.

{seebo} {rubro}

{\\(∃x: apple(x),\\)} {\\(red(x)\\)}
	
There exists X such that X is an apple, and is red.
</gloss>

Notice that the same variable, \\(x\\) is being passed as an argument into both predicates. This permits us to make multiple claims on the same variable. We are claiming that \\(x\\) is *both* an apple *and* red.

The grammar of Sekko is different from that in English. Notice that there is no copula in the Sekko sentence -- there is no equivalent to "is". One of Sekko's goals is to have a grammar that has a more similar form to the underlying logical structure than natural languages. 

The way predicates work in Sekko is such that each predicate "expresses" variables on both its left (preceding) and right (succeeding) sides. Such variables are implicit and cannot be accessed directly. Variables which the predicate is in contact with will be passed into it as arguments. Both **seebo** and **rubro** are *intransitive* predicates, and express the same variable on both sides. Because of this, the sentence is the same even if the order of words is reversed. You may see this in the defitions of **seebo** and **rubro** -- they possess only Ⓛ (left) slots. We will see predicates with Ⓡ (right) slots in the next chapter. Predicates with only Ⓛ slots are intransitive, and express the same variable on the left and right slots.

The following sentence is identical to the one before. Here, how the implicit variables are handled is exposed to you.

<gloss>
A red thing is an apple.

{\\(x\\) rubro \\(x\\)} {\\(x\\) seebo \\(x\\)}

{\\(∃x: red(x),\\)} {\\(apple(x)\\)}
	
There exists X such that X is red, and is an apple.
</gloss>

In English, the sentences "An apple is red," and "A red thing is an apple," would be interpreted differently, because of how subjects and objects in English are treated as old and new information. This is covered in a later chapter. However, Sekko does not make the distinction between old and new information, and so considers both utterances to be the same.

It is permitted in Sekko to pass the same variable in as many predicates as is desired. So long as the implicit variable is in contact with the predicates, they will be passed into it.

<gloss>
An apple is red and delicious. 
	
{\\(x\\) seebo \\(x\\)} {\\(x\\) rubro \\(x\\)} {\\(x\\) bauko \\(x\\)}

{\\(∃x: apple(x),\\)} {\\(red(x),\\)} {\\(delicious(x)\\)}
	
There exists X such that X is an apple, is red, and is delicious.
</gloss>

As with the sentences above, the order of the predicates does not matter. 
