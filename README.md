# Exploring politeness control for Spanish
On this repository, you will find a parallel corpus from English to Spanish with tags added to each segment stating the 'politeness level' of such segment. The corpus contains over 9M sentences extracted from the Open Corpus of Subtitles available at https://opus.nlpl.eu/OpenSubtitles2016.php.
This corpus is intended to be used for training register-aware MT systems and NLP applcation and it can serve as well as a corpus for a more linguistic-focused research.

The corpus looks something like this:

| id | src | tgt | tag | politeness_level|
| --- | ---  | ---  | ---  |----------------- |
|   0 | I'll give you more.  | Te pondré más | lexical_forms  | informal|
|   5200000  | I'm starting to pity you.| Empiezo a tener lástima de usted | lexical_forms | formal| 
| 5300000 | They call him the Maestro. |- Él se hace llamar "el Maestro".| - | neutral |
|8300000 | What are you grinning about? | ¿Por qué tienes esa sonrisa? | only_grammatical_forms | informal |
| 9000000 | The Colonel's usual, if you please. | Para el coronel lo de costumbre, si es tan amable. | only_grammatical_forms | formal |
|9900000| I'm the fiancee. | Y yo soy el prometido. | - | neutral|





<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
