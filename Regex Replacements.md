a list of regex replacers i use to reformat each resource
```
Description: 
 \n

\] \*(.*)\* 
] $1

#[0-9]{4}


 - <
\n<

^(?!$)   (m)
> $&

> \[.*?]
>
```