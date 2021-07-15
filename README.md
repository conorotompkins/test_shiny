# test_shiny

This repo provides reproducible code for an issue I am having with `navbarPage()` and `tabPanel()`. Consider this structure:

* Tab 1, containing the Old Faithful histogram
* Tab 2, containing the stock rmarkdown document

When I open tab 1, the app presents as expected 



When I switch to tab 2, the document shows as expected.



When I go __back__ to tab 1, the margins of the page are much narrower. Tab 1 appears to now inherit the css from tab 2.
