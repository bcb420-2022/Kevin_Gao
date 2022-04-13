# Kevin_Gao
repository for bcb420-2022 for Kevin Gao

# Assignment 1

## HTML Notebook File
https://github.com/bcb420-2022/Kevin_Gao/blob/main/A1_KevinGao.html

Direct preview:
http://htmlpreview.github.io/?https://github.com/bcb420-2022/Kevin_Gao/blob/main/A1_KevinGao.html

## Journal
https://github.com/bcb420-2022/Kevin_Gao/wiki/Assignment-1


# Assignment 2

## HTML Notebook File
https://github.com/bcb420-2022/Kevin_Gao/blob/main/A2_KevinGao.html

Direct preview:
http://htmlpreview.github.io/?https://github.com/bcb420-2022/Kevin_Gao/blob/main/A2_KevinGao.html

## Journal
https://github.com/bcb420-2022/Kevin_Gao/wiki/Assignment-2

# Assignment 3

## HTML Notebook File
https://github.com/bcb420-2022/Kevin_Gao/blob/main/A3_KevinGao.html

Direct preview:
http://htmlpreview.github.io/?https://github.com/bcb420-2022/Kevin_Gao/blob/main/A3_KevinGao.html

Note: To compile the notebook file properly, you need to have a version of GSEA (command-line version) at the root directory located at `~/GSEA_xxx` and the folder must contain `gsea-cli.sh` as the notebook will attempt to run GSEA directly from R. Also make sure that the figures are in the folder `a3figs`.

To compile using docker, run the following command
```shell
docker run --rm -it -v "$(pwd)":/home/rstudio/projects --user rstudio risserlin/em_base_image /usr/local/bin/R -e "rmarkdown::render('/home/rstudio/projects/assignment3.Rmd',output_file='/home/rstudio/projects/assignment3.test.html')"
```


## Journal
https://github.com/bcb420-2022/Kevin_Gao/wiki/Assignment-3
