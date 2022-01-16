---
title: Language Rules
layout: default
---
#Syntax / Language stuff
##Avoid NOT ( ! )
If empty set null else deserialise
Rather than
If not empty deserialise else set to null

##Avoid relying on implicit language behaviours

$foo = null;

**Dont do**
```
$foo ? ‘is not null’ : ‘is null’
```
**Do**
```
is_null($foo) or $foo === null ? ‘is null’ : ‘is not null’
```
