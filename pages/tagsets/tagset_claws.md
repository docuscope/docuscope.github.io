---
title: CLAWS7 Tagset
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: July 3, 2016
summary: "Descriptions of the part-of-speech tags for all versions of the model."
sidebar: mydoc_sidebar
permalink: tagset_claws.html
folder: tagsets
---

## CLAWS7

CLAWS7 is robust part-of-speech tagset developed at Lancaster University. [(Try it!)](http://ucrel-api.lancaster.ac.uk/claws/free.html) It is used in the [BYU family of corpora](https://www.english-corpora.org/), a project headed by Mark Davies and in ongoing development. The popularity of those data sets partly motivated the choice to use this tagset -- as opposed to say the [Penn Treebank tagset](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html).

This allows users to compare their results directly to those from much larger corpora. The tradeoff, is that CLAWS7 has is large and relatively fine-grained, which can be challenging for users with less familiarity to English syntax.

### Tags table

| Tag   | Description                                                          | Examples                                                 |
|-------|----------------------------------------------------------------------|----------------------------------------------------------|
| APPGE | possessive pronoun, pre-nominal                                      | *my*, *your*, *our*                                      |
| AT    | article                                                              | *the*, *no*                                              |
| AT1   | singular article                                                     | *a*, *an*, *every*                                       |
| BCL   | before-clause marker                                                 | *in order* (that), *in order* (to)                       |
| CC    | coordinating conjunction                                             | *and*, *or*                                              |
| CCB   | adversative coordinating conjunction                                 | *but*                                                    |
| CS    | subordinating conjunction                                            | *if*, *because*, *unless*, *so*, *for*                   |
| CSA   | as as conjunction                                                    | *as*                                                     |
| CSN   | than as conjunction                                                  | *than*                                                   |
| CST   | that as conjunction                                                  | *that*                                                   |
| CSW   | whether as conjunction                                               | *whether*                                                |
| DA    | after-determiner or post-determiner capable of pronominal   function | *such*, *former*, *same*                                 |
| DA1   | singular after-determiner                                            | *little*, *much*                                         |
| DA2   | plural after-determiner                                              | *few*, *several*, *many*                                 |
| DAR   | comparative after-determiner                                         | *more*, *less*, *fewer*                                  |
| DAT   | superlative after-determiner                                         | *most*, *least*, *fewest*                                |
| DB    | before determiner or pre-determiner capable of pronominal   function | *all*, *half*                                            |
| DB2   | plural before-determiner                                             | *both*                                                   |
| DD    | determiner (capable of pronominal function)                          | *any*, *some*                                            |
| DD1   | singular determiner                                                  | *this*, *that*, *another*                                |
| DD2   | plural determiner                                                    | *these,those*                                            |
| DDQ   | wh-determiner                                                        | *which*, *what*                                          |
| DDQGE | wh-determiner, genitive                                              | *whose*                                                  |
| DDQV  | wh-ever determiner                                                   | *whichever*, *whatever*                                  |
| EX    | existential there                                                    | *there* (is), *there* (are)                              |
| FO    | formula                                                              |                                                          |
| FU    | unclassified word                                                    |                                                          |
| FW    | foreign word                                                         |                                                          |
| GE    | germanic genitive marker                                             | *'*, *'s*                                                |
| IF    | for (as preposition)                                                 | *for*                                                    |
| II    | general preposition                                                  | *about*, *on*                                            |
| IO    | of (as preposition)                                                  | *of*                                                     |
| IW    | with, without (as prepositions)                                      | *with*, *without*                                        |
| JJ    | general adjective                                                    | *nice*, *new*                                            |
| JJR   | general comparative adjective                                        | *older*, *better*, *stronger*                            |
| JJT   | general superlative adjective                                        | *oldest*, *best*, *strongest*                            |
| JK    | catenative adjective (able in be able to, willing in be   willing to | *able* (in *be able to*), *willing* (in *be willing to*) |
| MC    | cardinal number,neutral for number                                   | *two*, *three*                                           |
| MC1   | singular cardinal number                                             | *one*                                                    |
| MC2   | plural cardinal number                                               | *sixes*, *sevens*                                        |
| MCGE  | genitive cardinal number, neutral for number                         | *two's*, *100's*                                         |
| MCMC  | hyphenated number                                                    | *40-50*, *1770-1827*                                     |
| MD    | ordinal number                                                       | *first*, *second*, next, *last*                          |
| MF    | fraction,neutral for number                                          | *quarters*, *two-thirds*                                 |
| ND1   | singular noun of direction                                           | *north*, *southeast*                                     |
| NN    | common noun, neutral for number                                      | *sheep*, *cod*, *headquarters*                           |
| NN1   | singular common noun                                                 | *book*, *girl*                                           |
| NN2   | plural common noun                                                   | *books*, *girls*                                         |
| NNA   | following noun of title                                              | *M.A.*                                                   |
| NNB   | preceding noun of title                                              | *Mr.*, *Prof.*                                           |
| NNL1  | singular locative noun                                               | *Island*, *Street*                                       |
| NNL2  | plural locative noun                                                 | *Islands*, *Streets*                                     |
| NNO   | numeral noun, neutral for number                                     | *dozen*, *hundred*                                       |
| NNO2  | numeral noun, plural                                                 | *hundreds*, *thousands*                                  |
| NNT1  | temporal noun, singular                                              | *day*, *week*, *year*                                    |
| NNT2  | temporal noun, plural                                                | *days*, *weeks*, *years*                                 |
| NNU   | unit of measurement, neutral for number                              | *in*, *cc*                                               |
| NNU1  | singular unit of measurement                                         | *inch*, *centimetre*                                     |
| NNU2  | plural unit of measurement                                           | *ins.*, *feet*                                           |
| NP    | proper noun, neutral for number                                      | *IBM*, *Andes*                                           |
| NP1   | singular proper noun                                                 | *London*, *Jane*, *Frederick*                            |
| NP2   | plural proper noun                                                   | *Browns*, *Reagans*, *Koreas*                            |
| NPD1  | singular weekday noun                                                | *Sunday*                                                 |
| NPD2  | plural weekday noun                                                  | *Sundays*                                                |
| NPM1  | singular month noun                                                  | *October*                                                |
| NPM2  | plural month noun                                                    | *Octobers*                                               |
| PN    | indefinite pronoun, neutral for number                               | *none*                                                   |
| PN1   | indefinite pronoun, singular                                         | *anyone*, *everything*, *nobody*, *one*                  |
| PNQO  | objective wh-pronoun                                                 | *whom*                                                   |
| PNQS  | subjective wh-pronoun                                                | *who*                                                    |
| PNQV  | wh-ever pronoun                                                      | *whoever*                                                |
| PNX1  | reflexive indefinite pronoun                                         | *oneself*                                                |
| PPGE  | nominal possessive personal pronoun                                  | *mine*, *yours*                                          |
| PPH1  | 3rd person sing. neuter personal pronoun                             | *it*                                                     |
| PPHO1 | 3rd person sing. objective personal pronoun                          | *him*, *her*                                             |
| PPHO2 | 3rd person plural objective personal pronoun                         | *them*                                                   |
| PPHS1 | 3rd person sing. subjective personal pronoun                         | *her*, *she*                                             |
| PPHS2 | 3rd person plural subjective personal pronoun                        | *they*                                                   |
| PPIO1 | 1st person sing. objective personal pronoun                          | *me*                                                     |
| PPIO2 | 1st person plural objective personal pronoun                         | *us*                                                     |
| PPIS1 | 1st person sing. subjective personal pronoun                         | *I*                                                      |
| PPIS2 | 1st person plural subjective personal pronoun                        | *we*                                                     |
| PPX1  | singular reflexive personal pronoun                                  | *yourself*, *itself*                                     |
| PPX2  | plural reflexive personal pronoun                                    | *yourselves*, *themselves*                               |
| PPY   | 2nd person personal pronoun                                          | *you*                                                    |
| RA    | adverb, after nominal head                                           | *else*, *galore*                                         |
| REX   | adverb introducing appositional constructions                        | *namely*, *e.g.*                                         |
| RG    | degree adverb                                                        | *very*, *so*, *too*                                      |
| RGQ   | wh- degree adverb                                                    | *how*                                                    |
| RGQV  | wh-ever degree adverb                                                | *however*                                                |
| RGR   | comparative degree adverb                                            | *more*, *less*                                           |
| RGT   | superlative degree adverb (most, least                               |                                                          |
| RL    | locative adverb                                                      | *alongside*, *forward*                                   |
| RP    | prep. adverb, particle                                               | *about*, *in*                                            |
| RPK   | prep. adv., catenative                                               | *about* (in *be about to*)                               |
| RR    | general adverb                                                       | *quietly*, *importanlty*                                 |
| RRQ   | wh- general adverb                                                   | *where*, *when*, why, *how*                              |
| RRQV  | wh-ever general adverb                                               | *wherever*, *whenever*                                   |
| RRR   | comparative general adverb                                           | *better*, *longer*                                       |
| RRT   | superlative general adverb                                           | *best*, *longest*                                        |
| RT    | quasi-nominal adverb of time                                         | *now*, *tomorrow*                                        |
| TO    | infinitive marker                                                    | *to*                                                     |
| UH    | interjection                                                         | *oh*, *yes*, *um*                                        |
| VB0   | be, base form (finite i.e. imperative, subjunctive)                  | *be*                                                     |
| VBDR  | were                                                                 | *were*                                                   |
| VBDZ  | was                                                                  | *was*                                                    |
| VBG   | being                                                                | *being*                                                  |
| VBI   | be, infinitive                                                       | *be* (in *to be or not...*  or in   *it will be...*)     |
| VBM   | am                                                                   | *am*                                                     |
| VBN   | been                                                                 | *been*                                                   |
| VBR   | are                                                                  | *are*                                                    |
| VBZ   | is                                                                   | *is*                                                     |
| VD0   | do, base form (finite                                                | *do*                                                     |
| VDD   | did                                                                  | *did*                                                    |
| VDG   | doing                                                                | *doing*                                                  |
| VDI   | do, infinitive                                                       | *do* (in *I may do...* or in *to do...*)                 |
| VDN   | done                                                                 | *done*                                                   |
| VDZ   | does                                                                 | *does*                                                   |
| VH0   | have, base form (finite                                              | *have*                                                   |
| VHD   | had (past tense)                                                     | *had*                                                    |
| VHG   | having                                                               | *having*                                                 |
| VHI   | have, infinitive                                                     | *have*                                                   |
| VHN   | had (past participle)                                                | *had*                                                    |
| VHZ   | has                                                                  | *has*                                                    |
| VM    | modal auxiliary                                                      | *can*, *will*, *would*                                   |
| VMK   | modal catenative                                                     | *ought*, *used*                                          |
| VV0   | base form of lexical verb                                            | *give*, *work*                                           |
| VVD   | past tense of lexical verb                                           | *gave*, *worked*                                         |
| VVG   | -ing participle of lexical verb                                      | *giving*, *working*                                      |
| VVGK  | -ing participle catenative                                           | *going* (in *be going to*)                               |
| VVI   | infinitive                                                           | *to give...* *It will work...*                           |
| VVN   | past participle of lexical verb                                      | *given*, *worked*                                        |
| VVNK  | past participle catenative                                           | *bound* (in *be bound to*)                               |
| VVZ   | -s form of lexical verb                                              | *gives*, *works*                                         |
| XX    | not, n't                                                             | *not*, *n't*                                             |
| ZZ1   | singular letter of the alphabet                                      | *A,b*                                                    |
| ZZ2   | plural letter of the alphabet                                        | *A's*, *b's*                                             |
{% include links.html %}
