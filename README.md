# test_shiny

This repo provides reproducible code for an issue I am having with `navbarPage()` and `tabPanel()`. Consider this structure:

* Tab 1, containing the Old Faithful histogram
* Tab 2, containing the stock rmarkdown document

When I open tab 1, the app presents as expected
<img width="1313" alt="shiny_screenshot_1" src="https://user-images.githubusercontent.com/20938344/125853370-8904ca14-2fd2-4224-b73f-d931a493426a.png">

When I switch to tab 2, the document shows as expected
<img width="1313" alt="shiny_screenshot_2" src="https://user-images.githubusercontent.com/20938344/125853388-798886bf-ac3a-4a97-8641-23cba85f306a.png">

When I go __back__ to tab 1, the margins of the page are much narrower. Tab 1 appears to now inherit the css from tab 2.
<img width="1313" alt="shiny_screenshot_3" src="https://user-images.githubusercontent.com/20938344/125853435-fa931d29-707d-488e-b4f4-21d5bb4f4243.png">

This altered width of tab 1 persists until I restart the session.
