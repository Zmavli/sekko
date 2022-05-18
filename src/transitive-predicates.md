# Transitive predicates
We now get into the meat and potatoes of Sekko grammar. Transitive predicates, compared to intransitive predicates, do not express the same variable on both sides. Whereas intransitive predicates assert that the variable on both their sides are equal, transitive predicates assert that they are unequal. Let us see this in action.

<gloss>
I eat an apple.

{ko} {sedai} {seebo}

{\\(∃x∃y: me(x),\\)} {\\(eat(x,y),\\)} {\\(apple(y)\\)}

There exist \\(x\\) and \\(y\\) such that \\(x\\) is me, and eats \\(y\\), and \\(y\\) is eaten, and is an apple.
</gloss>

<gloss>
An apple eats me.
	
{seebo} {sedai} {ko}

{\\(∃x∃y: apple(x),\\) } {\\(eat(x,y),\\)} {\\(me(y)\\)}
	
There exist \\(x\\) and \\(y\\) such that \\(x\\) is an apple, and eats \\(y\\), and \\(y\\) is eaten, and is me.
</gloss>

<gloss>
An apple, who is me, eats (something).
	
{seebo} {ko} {sedai}

{\\(∃x∃y: me(x),\\) } {\\(apple(x),\\)} {\\(eat(x,y)\\)}
	
There exist \\(x\\) and \\(y\\) such that \\(x\\) is an apple, and me, and eats \\(y\\), and \\(y\\) is eaten.
</gloss>

The difference in the meanings of the sentences is because transitive predicates accept two variables rather than one. The variable on the left is treated differently from the variable on the right. This can be seen from the definition of **sedai**.

> sedai: Ⓛ eats Ⓡ.

**sedai** possesses both an Ⓛ slot and an Ⓡ slot -- it expresses two different variables on both sides. 

