# Generating English Poetry with Recurrent Neural Nets

 

 

After reading an awesome [post](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) by the great [Andrej Karpathy](http://cs.stanford.edu/people/karpathy/), I decided to give **Recurrent Neural nets (RNNs)** a try for a similar task of text generation. In his post, he tries to generate Shakespearean text by training a **Character-based RNN ** (where he doesn't sample words but just plain characters). Here's an example that he mentions in his post:

 

> PANDARUS:
>
> Alas, I think he shall be come approached and the day When
> little srain would be attain'd into being never fed, And who is but a
> chain and subjects of his death, I should not sleep.
>
> Second Senator: 
>
> They are away this miseries, produced upon my soul,
> Breaking and strongly should be buried, when I perish The earth and
> thoughts of many states.
> 
> DUKE VINCENTIO: 
>
> Well, your wit is in the care of side and that.
> 
> Second Lord: 
>
> They would be ruled after this chamber, and my fair nues
> begun out of the fact, to be conveyed, Whose noble souls I'll have the
> heart of the wars.
> 
> Clown: 
>
> Come, sir, I will make did behold your worship.
> 
> VIOLA: 
>
> I'll drink it.

 

He goes even further and uses the same technique to generate Wikipedia articles, Paul Graham's essays etc.

 