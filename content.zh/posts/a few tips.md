## Covert Notes

convert word meanings from `.Rmd` to the new style:
```
\s*([\u4e00-\u9fa5]+)\s*`r\s(n)\("(.+?)"\)`\s*
```
to
```
[$1 [$3]{.$2}]{.l}
```