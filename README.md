
# Getting started

**oligotm.js** is an open source JavaScript library for calculating Tm using Primer3 algorithm.

## Usage

`git clone https://github.com/Kazuki-Nakamae/oligotmJS.git`
`cd oligotmJS`

#### Run oligotm.js in a browser
```html
<script src="./oligotm.js"></script>

<script>
  var instance = new oligotm();
  var Tmvalue = instance.oligotm("ATTTGCGCGAATGCAATCGG", 50, 50, 0, 0, 0, 0) // primer3 default setting
  console.log(Tmvalue)
</script>
```
```
68.302986
```

## LICENCE
GNU GENERAL PUBLIC LICENSE Version 2