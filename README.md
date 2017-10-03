# ITCompetenciesDocument

The IT Competencies Document is a work in progress in ```IT_Competencies_Document.md```. 

## Editing the document

- editing Markdown
- flavour of Markdown
- special features (footnotes etc.) that are not supported in all Markdown flavours

## Publishing the document

- generating simple HTML with [pandoc](https://pandoc.org/):

```
pandoc -s --toc IT_Competencies_Document.md  -o IT_Competencies_Document.html
```

- [GitHub Pages](https://pages.github.com/)

## Managing the process

- GitHub basics
- [Using Pull Requests](https://guides.github.com/introduction/flow/) to submit changes (for "code" read "text")