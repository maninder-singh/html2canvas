## html2canvas ( version 0.5.0-beta4 )

### List of Changes to original library

* ####Svg text doubling <br>
**Issue** - Text node inside svg tag when rendering are shown twice.  <br>
**Commit url** - https://git1.affinnova.com/ConceptStudio1/html2canvas/commit/43be9d74f9bde8c2c3af66de7e606572702e1c59

* ####Vertical scrolling with capture  <br>
**Issue** - When page has vertical scrolling and webpage is capture from start of scroll position. <br>
**Fix** - Assing width and heigth of complete HTML document while capturing.  <br>
**Commit url** - https://git1.affinnova.com/ConceptStudio1/html2canvas/commit/b26fbc6fb7d9878cbefa891838fb6ba29aadbb5c

* ####Callback after DOM cloning   <br>
**Issue** - Webpage with large DOM content become unresponsive till cloning of DOM is not done.  <br>
**Fix** - Callback when DOM cloning is done. <br>
**Commit url** - https://git1.affinnova.com/ConceptStudio1/html2canvas/commit/a9391945aa7ff5d2bbf07eb78e1d664239bd13d1
