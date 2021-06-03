# qts_immortals

This is a collection of Jupyter notebook files used for the article "Daoist immortals as a poetic image in Tang dynasty: a corpus study." (now in draft form).
___
Files in the repository:

- **collocations_immortals.ipynb**: code that was used to find collocates to _xian_ 仙 in QTS
- **levenstein_immortals.ipynb**: code that was used to find lines similar to ones that used _xian_ 仙 in QTS and filter out those that have _xian_ substituted with something else
- **2-word_dic_QTS.txt**: the file with tokenized QTS. 
- **QTS_JSON_CTEXT_clean_punc_no_comm_no_addnames.json**: file used for levenstein_immortals. Both variants of corpora used for this project are essentially the same, differences lying in markup and pre-processing.
- **thesis_environment.yml**: environment requirements to run the code. Since it was also used for other projects, it might contain more packages that were actually used for this project. 

___
For tokenization code, see https://github.com/mzorki/tutorials 
<br>
[Here is my short post with more detailed information on tokenization of Classical Chinese](https://digitalorientalist.com/2021/02/16/defining-word-boundaries-for-modern-and-classical-chinese/) <br>
The link above also contains a tutorial on how to run Jupyter notebooks in Google Colab without the need to install anything or extensive knowledge of programming – it can be followed to run the code from this repository as well.
