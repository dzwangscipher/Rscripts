Last updated date: 09/15/2022

# Regular expression

```
> data=data.frame(Accession=c(1,2,3,4,5), "A1-123"=c(1,2,3,4,5))
> data
  Accession A1.123
1         1      1
2         2      2
3         3      3
4         4      4
5         5      5
> grep("^[A-Z]1", colnames(data))
[1] 2
> grepl("^[A-Z]1", colnames(data))
[1] FALSE  TRUE

```
