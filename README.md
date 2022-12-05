# ukrepl
**the unicode verkrepeler(tm)**

transforms your totally fine ascii text to utf-8 "special" text
## usage

```
$ ukrepl h
usage: ukrepl [modes]

modes:
  c -- cyrillic replace
  f -- fixed width
  p -- replace punctuation
  H -- replace with historic latin chars
  h -- this message
```

## Example

```
$ echo 'Hahaha ! ( viel spaß mit deinem Legacy Mail programm)' | ./ukrepl pHcf
Наｈаｈа ǃ （ ｖіеｌ ｓраß ｍіｔ ｄеіｎеｍ Ｌеｇасｙ Маіｌрｒơｇｒаｍｍ）
```
