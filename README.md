# Bangla Writing in Overleaf
1. Create an account in [overleaf](www.overleaf.com) & then log in.

In this work, to write in bangla Avro phonetic open-source keyboard software is being used. Avro is developed by [OmicronLab](https://www.omicronlab.com/index.html). To write in overleaf, one can use any font from [OmicronLab](https://www.omicronlab.com/index.html). Font link is [here](https://www.omicronlab.com/bangla-fonts.html). There are several fonts like Kalpurush, Siyamrupali etc. Download any one of the fontfile like kalpurush.ttf, siyamrupali.ttf.

![alt text](https://github.com/SakibulIslamSazzad/bangla_writing_in_overleaf/blob/master/banglaoverleaf.png)


2. Create a new project in overleaf, then add the following document packages-


```
 \documentclass{article}
 \usepackage{fontspec} // package for font
 \usepackage{graphicx} // package for images
 \usepackage{float}
 \usepackage{amsmath} // package for mathematical experssions
 \graphicspath{{images/}} // all images are uploaded in a folder named *images* , you can name it anything
 \usepackage{caption} // package for image caption
 \usepackage{subcaption}
 \usepackage{array}
 \usepackage{tabu} // package for table
 \usepackage{cite} // package for hyperlink
 \usepackage{multirow}
 \usepackage{color}
 \setmainfont{Times New Roman} // font is used here Times New Roman

```

3. Upload the font file in blank project like kalpurish.ttf or siyamrupali.ttf. You can also download them from this repository.
Now write this line on project

```
\newfontface{\bn}{kalpurush.ttf} // if you use kalpurush font then write kalpurush.ttf otherwise it should be siyamrupali.ttf

```
4. Then from the *Menu* section change the compiler to **Xelatex** and keep everything like this

![alt text](https://github.com/SakibulIslamSazzad/bangla_writing_in_overleaf/blob/master/bangla2.png)

