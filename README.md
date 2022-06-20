# useful-regex
Some useful regular expressions I've used

## Find/Replace programming

### Avoiding 32-bit overflow for multiplications involving nrs->fieldOffset/nrs->cubatureOffset

```
malloc\((.+?)\*.s*(cubatureOffset|fieldOffset|nrs->cubatureOffset|nrs->fieldOffset)(.+?)(wordSize|sizeof\(dfloat\))
```
