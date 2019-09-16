# 자연어처리 튜토리얼  by  Jin-Hwan CHO

### 2019년 9월 17일(화) @한국외국어대학교
### https://github.com/chofchof/nlp-tutorial




# Lesson 1: 개발 환경

## Conda, GitHub & Jupyter Lab

### A. Anaconda = `conda` + `python` + packages
### https://www.anaconda.com/distribution/

![Anaconda Distribution](images/distro-01-1.png)

![Anaconda Windows Installer](images/Anaconda_2019.07_for_Windows_Installer.png)



### B. Miniconda = `conda` + `python`

### https://docs.conda.io/en/latest/miniconda.html

![Miniconda](images/Miniconda.png)

### https://repo.anaconda.com/miniconda/

![Miniconda installer archive](images/Miniconda_installer_archive.png)



### C. [Getting started with conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html)

![Anaconda Prompt](images/Anaconda_Prompt.png)

```bash
conda --version
conda --help
conda info
```

```bash
conda info --envs
conda create --name nlp_tutorial python=3.7 jupyterlab
```

```bash
conda info --envs
conda activate nlp_tutorial
jupyter lab
```

```bash
conda deactivate
conda remove --name nlp_tutorial --all
conda info --envs
```

```bash
conda search git
conda install git
```

[Conda Cheat sheet (PDF)](https://docs.conda.io/projects/conda/en/latest/_downloads/1f5ecf5a87b1c1a8aaf5a7ab8a7a0ff7/conda-cheatsheet.pdf)



### D. Linux utilities with conda

```bash
conda search grep
conda install m2-grep
conda list | grep git

copy con CP949.txt
이것은 한글 연습이다.
^Z

type CP949.txt
iconv -f CP949 -t UTF-8 CP949.txt > UTF-8.txt
type UTF-8.txt

conda install m2-dos2unix
dir
dos2unix CP949.txt UTF-8.txt
dir
conda remove m2-grep m2-dos2unix
```



### E. GitHub

```bash
git clone https://github.com/chofchof/nlp-tutorial.git
```



# Lesson 2: 형태소 분석

## Mecab, Mecab & Mecab

### [Tutorial Video](https://www.youtube.com/watch?v=5rNu16O3YNE&list=PLYx7XA2nY5GcDQblpQ_M1V3PQPoLWiDAC&index=32&t=8365s)
### [Jupyter Notebooks & Data](https://github.com/chendaniely/scipy-2019-pandas)



# Lesson 3: NLP 맛보기

## VOCA & TF-IDF

