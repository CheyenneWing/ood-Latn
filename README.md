# ood-Latn. Tohono O'odham G2P mapping and preprocessor for Alvarez-Hale and Saxton-Saxton writing systems. 

The Alvarez-Hale writing system has a direct G2P mapping and does not require pre or post processing.
The Saxton-Saxton writing system requires a preprocessor to insert glottal stops before word-initial vowels.

% Saxton and Saxton Writing System Preprocessor

% This preprocessor adds an apostrophe before word-initial vowels. The apostrophe is then mapped to /ʔ/.

::vowels:: a|e|i|o|u

0 -> ‘ / # _ (::vowels::)

Unstressed vowels are not represented orthographically in the Saxton and Saxton writing system
and do not appear in the phonetic transduction. In the Alvarez-Hale 
writing system unstressed vowels are represented with a breve  ̆ above the unstressed vowel, which also appears 
in the phonetic transduction.
 
