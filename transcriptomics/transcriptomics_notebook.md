# Transcriptomics Notebook

**Course:** intro to ecological genomics - fall 2026

**Name:** Trevor Clark

------------------------------------------------------------------------

## 9/15/2026 - Setting up lab notebook and learning markdown

-   setting up transcriptomics notebook

-   learn how to take notes in markdown

-   Push notes to github

**working directory**

`/users/t/m/tmclark/projects/eco_genomics_2026/transcriptomics`

**Input files:**

`none`

**Output files:**

`/users/t/m/tmclark/projects/eco_genomics_2026/transcriptomics/transcriptomics_notebook.md`

**Programs and dependencies:**

-   `R version 4.5.1`

-   `R-studio`

**Code:**

``` r
print("Hello World")
```

Table:

| Col1     | Col2 | Col3 |
|----------|------|------|
|          |      |      |
| big soup |      |      |
|          |      |      |

**Image: (/image)**

![](images/markdown-syntax-cheatsheet.webp)

------------------------------------------------------------------------

## 9.17.2026 diving into code:

```{r}
cd
```

ll - long list of directory

cd [directory of choice]

zcat AA_F0_Rep1_2_clean.fq.gz \| head -n 100\
-this is printing the data of the "AA_F0_Rep1_2_clean.fq.gz" file and \| head -n 100 is asking to print the first 100 lines

\| wc -l // the word could on the lines

# 

## 9.22.2026, 9.24.2026

#### **BASH**

pwd // print working directory

cd // change directory

.. // move back in directory

. // from here, “this spot”

ls // list short “what’s here?”

ll // list long

zcat // print out file

head // just the top

history // all recent commands

cp // copy

rm // remove (carful!)

[arrow up] // prior command

[tab] // autofill file/confirmation of existence

\~ // home directory shortcut, jumps file pathway

---

/users/t/c/tmclark/projects/eco_genomics_2026/transcriptomics/ →

/mydata

/myresults

/myscripts

---

/gpfs1/cl/biol3990/ →

/transcriptomics/CountsMatrix

/ecogen/SW/setup.sh

----------------------------------------------

#### Git interaction (manually thru terminal)

```{r}
#checks the status of git of current working directory
git status
#adds "current ".gitignore" to staging, then commits it with the message in quotations, then pushes it, you'll be prompted for user and password
git add .gitignore
git commit -m "Ignore results directory"
git push
#problem diagnosing commands
git status
git branch
git remote -v
```
