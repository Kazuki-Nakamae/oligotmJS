
# Getting started

**oligotm.js** is an open source JavaScript library for calculating Tm using Primer3 algorithm.

## Usage
```bash
git clone https://github.com/Kazuki-Nakamae/oligotmJS.git;
cd oligotmJS;
```
#### Run oligotm.js in a browser
```html
<script src="./oligotm.js"></script>

<script>
    var instance = new oligotm();
    /*
    oligotm(Sequence,
            DNA concentration,
            Concentration of salt,
            Salt concentration (mM),
            Concentration of dNTPs (mM),
            tm_method_type({ breslauer_auto: 0, santalucia_auto: 1 }),
            salt_correction_type({ schildkraut: 0, santalucia: 1, owczarzy: 2 })
    */
    var Tmvalue = instance.oligotm("ATTTGCGCGAATGCAATCGG", 50, 50, 0, 0, 0, 0) // primer3 default setting
    console.log(Tmvalue)
</script>
```
```
68.302986
```

## LICENCE
GNU GENERAL PUBLIC LICENSE Version 2