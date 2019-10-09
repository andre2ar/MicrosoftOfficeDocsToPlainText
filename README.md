# Microsoft Office Documents to plain text

This is a PHP class to extract Microsoft office documents text. This extractor will works with:
  - Word
  - Excel
  - PowerPoint

### How to use this class?

First make PHP require to add class file to your projet. After, you need to create an OfficeDocumentToPlainText object with file path as below:

```sh

$reader = new OfficeDocumentToPlainText($filePath); 

```
Now, it's just to call the method getDocumentText as below:

```sh

$text = $reader->getDocumentText();

```

