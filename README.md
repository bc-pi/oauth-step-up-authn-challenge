[Prospective draft] OAuth 2.0 Step-up Authentication Challenge Protocol


`main.md` is the source in markdown format.

To build the xml2rfc file and transform it into html (you'll need https://github.com/mmarkdown/mmark and https://pypi.org/project/xml2rfc/):

```bash
mmark main.md > draft.xml; xml2rfc --html draft.xml
```

or with the magic of Docker (thanks to Dr. Daniel Fett and https://github.com/oauthstuff/markdown2rfc): 

```bash
docker run -v `pwd`:/data danielfett/markdown2rfc main.md
```
