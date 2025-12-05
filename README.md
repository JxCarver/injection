# XML Injection Test

Use this site to test **XML injection** in Google Sheets.

## How to Test
Paste the following into a cell. If you see a fish on the document, you need to sanitize your inputs:

```text
=IMAGE(IMPORTXML("https://jxcarver.github.io/injection/inject.xml", "//image"), 4, 400, 400)
