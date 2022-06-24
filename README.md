# statlexfun

A lame analogue of Google n-grams on a custom dataset

What it is:

Well, I was just bored and wanted to toy with multiprocessing (okay, that's not true, in fact I'm a graphomaniac and I wanted to know which words are my top ones, and how big my vocabulary is), so I, well, toyed with multiprocessing and RNNMorph in order to parse 20 years of (electronic) paper waste and create a frequency dictionary based on which one can draw pretty (but not too true) plots by year. You probably may use it with your own dataset, there's just one condition: all files must be .docx and contain a year of creation in their last paragraph (or you may rewrite the function that does year-extracting).

Dependencies:

    pip install rnnmorph
    pip install colorama
    pip install razdel
    pip install docx

I think any version of those will do.