# DITA Bootstrap

DITA Bootstrap is a series of plug-ins for [DITA Open Toolkit][1] that extend HTML and PDF output with [Bootstrap][2] templating;
alternate [Bootswatch][3] themes are also supported.

```console
dita --input=path/to/your.ditamap \
     --format=[html5-bootstrap|pdf-bootstrap] \
     --args.hdr=path/to/your-header.xml \
     --bootstrap.theme=<theme-name>
```

[1]: http://www.dita-ot.org
[2]: https://getbootstrap.com/docs/5.3
[3]: https://bootswatch.com
