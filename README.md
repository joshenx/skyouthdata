# skyouthdata

## Introduction

This data set is extracted from http://kaggle.com/miroslavsabo/young-people-survey.
The Jupyter Notebook file, `Music Genre Preferences in Slovakian Youth.ipynb`,
details my analysis of the data, in order to discover correlations between music genre
preferences, happiness, as well as demographics.

In 2013, students of the Statistics class at FSEV UK were asked to invite their friends to
participate in this survey.

* The data file (selectedresponses.csv) consists of 1010 rows and 32 columns (26
integer and 6 categorical).
* For convenience, the original variable names were shortened in the
data file. However, they can be easily inferenced from the order of the questions below.
* The data contain missing values.
* The survey was presented to participants in both electronic and written form.
* The original questionnaire was in Slovak language and was later translated
into English.
* All participants were of Slovakian nationality, aged between 15-30.

## Questions

The modified dataset comprises of these questions:

1. MUSIC PREFERENCE + APTITUDE

    1. I enjoy listening to music.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    2. I prefer.: Slow paced music 1-2-3-4-5 Fast paced music (integer)
    3. Dance, Disco, Funk: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    4. Folk music: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    5. Country: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    6. Classical: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    7. Musicals: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    8. Pop: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    9. Rock: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    10. Metal, Hard rock: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    11. Punk: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    12. Hip hop, Rap: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    13. Reggae, Ska: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    14. Swing, Jazz: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    15. Rock n Roll: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    16. Alternative music: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    17. Latin: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    18. Techno, Trance: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    19. Opera: Don't enjoy at all 1-2-3-4-5 Enjoy very much (integer)
    20. Playing musical instruments: Not interested 1-2-3-4-5 Very interested (integer)

2. HAPPINESS
    1. I am 100% happy with my life.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    2. I am always full of life and energy.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    
3. DEMOGRAPHICS
    1. Age: (integer)
    2. Height: (integer)
    3. Weight: (integer)
    4. How many siblings do you have?: (integer)
    5. Gender: Female - Male (categorical)
    6. I am: Left handed - Right handed (categorical)
    7. Highest education achieved: Currently a Primary school pupil - Primary school - Secondary school - College/Bachelor degree (categorical)
    8. I am the only child: No - Yes (categorical)
    9. I spent most of my childhood in a: City - village (categorical)
    10. I lived most of my childhood in a: house/bungalow - block of flats (categorical)
    
