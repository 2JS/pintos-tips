# pintos-tips
A set of tips and recommendations for anyone learning pintos.

## Motive
At the end of 2019, about a year after I've finished the last project of PintOS, I came up with an idea that parallel compiling and testing will extremely help reducing time of software development. Short after I started to google about running shell scripts parallelly, I found 'make' will do the jobs with only '-j' option. I compared build time and the result was unbelievable!

```bash
$ time make     # real  0m23.978s
$ time make -j  # real  0m6.358s
# Project 3 compling test on Ubuntu 18.04.3 LTS Docker container, Macbook Pro 15 inch 2018 with Intel Core i7 Coffee Lake (8750H), up to 4.1 GHz
```

I expect similar time difference for testing. I'm impressed! 73% saving on compling, then how it would be for testing? Sadly I can't test it for now.

I think it would be much better if anyone had told me this earlier. Actually there was several other similar things. To help people learning pintos, I created this repository.

## Rationale

### PLARIARISM-FREE
