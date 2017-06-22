# dtd-utils

documents needed for dealing with dtds

to create an xsd from a dtd:

```
$ perl dtd2xsd.pl filename > newfile.xsd
```

create java objects from xsd:

```
$xjc newfile.xsd
```
