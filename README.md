# jekyll-sheets
google sheets + google forms + jekyll = :)

For a public, open data site, jekyll-sheets is potentially the perfect way to create a maintainable static site with a client-friendly database –> google sheets!

First, a Google Form will need to be created that autogenerates a Sheet. Then we publish that sheet. After, we can [use JavaScript to reference that sheet's data](https://github.com/mikeymckay/google-spreadsheet-javascript) and save it as a Jekyll object that can be manipulated with Liquid.

References
* [referencing a google spreadsheet with js](https://github.com/mikeymckay/google-spreadsheet-javascript)
* [basic implimentation](http://mikeymckay.github.io/google-spreadsheet-javascript/sample.html)
