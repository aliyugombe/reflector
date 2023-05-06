# Reflector
Reflector is cli tool written using golang to test for reflected parameters in list of urls to test for reflected xss

# How to Use?
`echo domain | waybackurls | qsreplace abcd1234 | reflector | tee -a reflector.txt`
and you can use `reflector.txt` result to test for xss manually or using dalfox

# How to Install?
```
go install -v github.com/aliyugombe/reflector@latest
```
