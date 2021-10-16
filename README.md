# Nomogram based on strain elastography radiomics for the differential diagnosis of breast masses: a prospective multicenter study

If you use this code in your research, consider citing:
```
@article{
  title={xxxx},
  author={xxxx},
  journal={xxxx},
  year={xxxx},
  publisher={xxxx}
}
```

## Prerequisites

- Windows 10
- R 3.6 with dependencies listed in the `renv.lock` file
```
   install.packages("renv")
   library("renv")
   renv::init()
   renv::restore(lockfile="renv.lock")
```


## Running

1. clone the repo to local directory
```cmd
   https://github.com/MedicalDataAI/Ebiomedicine
```

2. run code in Rstudio

- Predict batch sample dataset ("./sample") into "./sample result"
```
   Radiomic Nomogram Construction.Rmd
```   

- Predict single yourself dataset into "./sample result"
```
   Replaced the files in "./sample", and run
   Radiomic Nomogram Construction.Rmd
```

