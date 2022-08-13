## Multimodal Dialogue
We take a step further to study an end-to-end multimodal dialogue model for vision, speech and text. Specifically, we introduce a new task called visual spoken dialogue, which aims to ground the spoken question in an image, infer textual context from history, then (1) perform automatic speech recognition, and (2) answer the question accurately simultaneously. We introduce VSDial, an English-Chinese bilingual dataset to study the visual spoken dialogue task.

### Tasks
Multimodal Automatic Speech Recognition (MASR)

Multimodal Dialogue Generation (MRG) 

### Provided Baseline Model: MultiDial
Figure: llustration of our proposed framework
![llustration of our proposed framework](https://raw.githubusercontent.com/multimodaldialogue/multimodaldialogue.github.io/main/data/framework.png)

### Results
Table 1: Performance on VSDial-EN

|Model| BLEU1 ↑| BLEU2 ↑| BLEU3 ↑| BLEU4 ↑| Rouge ↑| BERTScore ↑| WER ↓|
| :-----|  :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|BLIP (Li et al. 2022)| 35.56| 26.88| 15.07| 9.74| 37.29| 44.65| -|
|VLT5 (Cho, Lei et al. 2021)| 36.70| 27.90| 15.61| 9.70 |38.82| 46.17| -|
|XVLM (Zeng, Zhang, and Li 2021)| 37.13 |28.17 |15.40| 9.30| 39.78 |46.18| -|
|MultiDial-Sequential| 20.45| 13.14| 5.90| 2.38| 9.25| 22.73 |7.46|
|MultiDial (Prompt)| 39.10| 33.93 |19.36 |16.79 |41.46| 49.13 |5.90|


Table 2: Performance on VSDial-ZH

|Model| BLEU1 ↑ |BLEU2 ↑| BLEU3 ↑ |BLEU4 ↑ |Rouge ↑ |BERTScore ↑| CER ↓|
| :-----|  :----: | :----: | :----: | :----: | :----: | :----: | :----: |
|BLIP (Li et al. 2022)| 22.17 |18.98| 11.18 |7.60 |38.84 |45.27 -|
|XVLM (Zeng, Zhang, and Li 2021)| 24.99| 20.35| 10.96| 6.85| 39.49| 46.49 |-|
|VLT5 (Cho, Lei et al. 2021) |27.00 |22.58 |13.46| 9.32| 40.99| 47.22| -|
|MultiDial-Sequential |14.93| 9.64| 4.62| 2.35 |13.74| 23.97| 7.73|
|MultiDial (Prompt)| 36.41| 32.23| 23.15| 17.65| 45.39| 49.44 |6.81|



### Samples
You can download the Samples as follows:

[Images](https://drive.google.com/file/d/1y_z1nEIQvYNm2Q1UTpBt_47I9je_EY8A/view?usp=sharing)

[Speech](https://drive.google.com/file/d/11FUm0h1gf1a231aXeGp7jKQlVBJHlAKL/view?usp=sharing)

[Dialogue](https://drive.google.com/file/d/1eP6SJot1K5AFBOHWxZVCoVI4fafllUuQ/view?usp=sharing)

We will upload our full dataset as soon as possilble.

<!-- ### Datasets
You can download the datasets as follows:

[Training data]()

[Validation data]()

[Test v1]()

[Test v2]()

[Test v3]() -->


<!-- You can use the [editor on GitHub](https://github.com/multimodaldialogue/multimodaldialogue.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/multimodaldialogue/multimodaldialogue.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out. -->
