# StudyGrouper
Content for the Front-End Challenge project entitled StudyGrouper

View online at http://coplex.github.io/study-grouper/

--

To generate `data` directory structure and update `index.html`, run:

```
node_modules/.bin/static-api -j study-grouper.json -f data -b false \
&& tree -H data data -T StudyGrouper > index.html
```
