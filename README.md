# XML Injection Test

Use this site to test **XML injection** in Google Sheets.

## How to Test
Paste the following into a cell:

```text
=IMAGE(IMPORTXML("https://jxcarver.github.io/injection/inject.xml", "//image"), 4, 400, 400)
