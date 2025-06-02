## TES Name Generator

This generator was built to support creative projects for Skyrim modding, but should apply to any Elder Scrolls game. Other generators are available online, and are worth checking out too because they'll produce different results. In actuality this is actually a series of generators, some a little better than others. The hope is that even if you don't see a name that suits what you want, you'll get ideas you can build on for yourself.

To use the generator, just choose the race from the dropdown, and click a button for the gender. A list of names will appear. Click any name to copy it to your clipboard. I recommend keeping a file of "good idea" names that struck your fancy for later use. In its current iteration this generator will not save names for you.

## The Markov chain generator

Most of the genertors use a Markov chain model, using names sourced from the games as input. A Markov chain uses its input to build a probability list. For any given sequence of N characters, it chooses the next letter based on weighted probability. The Markov chain is order 4, meaning it uses 4-character sequences, but for sequences with extremely limited outcomes, it supplements with order-3 chains. The generator is further constrained by trying to reach a predetermined target length (probabilistic, based on source names).

An unfortunate limitation of Markov chains is that they tend to "overfit", reproducing their input data, so the generator tries to reject names found in its source list. After a number of repeated failures however it will give up and move on, so occasionally you'll see a name from the source list included in the output, and you'll see them marked specially.

## The compound generator

Nord surnames and Argonian Tamrielic names use a different kind of generator, based on patterns of words. A common pattern for Nord surnames for instance is noun-verber, for instance, so it has a list of nouns and a list of verbs in the "-er" form. Also it might have adjective-noun (Cruel-Sea), or aspect-bodypart (Ironhammer). The compound generator doesn't use source names to compare (it might in a future update), so it can produce known names.

Because it doesn't always know if two words work properly together, it may also produce some really wild output. The Argonian Tamrielic generator is the most complex, using a wide variety of word types, so it's prone to making very little sense. Sometimes these results can be hilariously bad, but hopefully even the bad ones serve as creative fodder.

## Notes on races

* **Altmer** surnames are actually very complex and therefore hardly ever appear. The source data of shortened surnames is therefore very slim.
* **Argonian** names come in Jel and Tamrielic variants.
* **Bosmer** and **Khajiit** don't use surnames.
* **Dunmer** names come in mainland and Ashlander variants. About 15% of Dunmer are Ashlanders.
* **Redguard** surnames almost always are in the form of at-Person or af-Person indicating a familial relationship, or al-Place for a place of origin, but there are some exceptions that were included as source names. A list of possible places has been included for al- names, even where those names don't appear in source.

## Source names

The source names for the Markov generators were based on uesp.net's list of names for each race. All Elder Scrolls games were included, except sometimes when older games' more simplistic generation skewed the Markov chains too badly. Out-of-game books were also excluded as sources, even though they're largely considered canon. In cases where a name is believed or known to originate from a different race (e.g., Brand-Shei was named by Argonians), that name has been excluded also.

(I wish we had more Dwemer names to draw from. A Dwemer place name generator would still be very interesting. I might add one in the future, if I expand into place names.)
