# Testing and accessibility

## Code testing

![def_html_testing1](assets/images/def_html_testing1.PNG)
![def_html_testing2](assets/images/def_html_testing2.PNG)
![def_html_testing3](assets/images/def_html_testing3.PNG)

## CSS testing

![def_w3_css_validation](assets/images/def_w3_css_validation.PNG)

## Accessibility testing

![def_accessibility](assets/images/def_accessibility.PNG)

## Viewport testing

The pages have been tested on desktop computers and handheld devices for the viewport responsiveness. Laptops have not been taken in consideration due to the wide range of variables involved which may give unreliable results depending of the device's features, which may render the same result as a desktop computer or a horizontally held tablet. However, the tablet viewport have been tested in both landscape and portrait position

### Desktop Browser response

The rendering of the pages has been tested on the three main browser platforms:
- Chromium (Ungoogled Chromium)
- Gecko (Firefox)
- WebKit (Safari)

|Page|Chromium-based|Gecko-based|WebKit-based|
|----|--------------|-----------|------------|
|**INDEX:**<br><br>In full deployment there are no major difference <br>between the rendering of the Hompage in different browsers.<br>The differences of proportions in these screenshots are due <br>to the level of zoon needed to get a satisfying screenshot. <br>The only notable difference in the rendering is the superior quality of the graphics in WebKit based browsers.|![rm_index_on_chromium](assets/images/rm_index_on_chromium.png)|![rm_index_on_gecko](assets/images/rm_index_on_gecko.png)|![rm_index_on_safari](assets/images/rm_index_on_safari.png)|
|**INVESTORS**<BR><BR>The page doesn't show major changes from one rendering platform to the other.||||
|**CROWDFUNDING**<BR><BR>The page doesn't show major changes from one rendering platform to the other.||||
|**HOTELIERS**<BR><BR>The page doesn't show major changes from one rendering platform to the other.||||
|**ABOUT**<BR><BR>The page doesn't show major changes from one rendering platform to the other.||||
|**404**<BR><BR>The page doesn't show major changes from one rendering platform to the other.||||

![def_Browser_1](assets/images/def_Browser_1.PNG)
![def_Browser_2](assets/images/def_Browser_2.PNG)
![def_Browser_3](assets/images/def_Browser_3.PNG)

### Handheld devices response

The site has been tested on standard viewports of handheld devices. For smartphones, the viewport on iPhone SE (with DevTools) was used for being one of the smallest on the market. For tablets, both horizontal and vertical view were tested on iPad Pro 12.9". Exceptionally, for the vertical mosaic feature rendering of the index page was tested on Surface pro 7 (DevTools), to assess the overall layout effect under Windows.

|Page|Smartphone|Tablet horizontal|Tablet vertical|
|:---|:--------:|:---------------:|:-------------:|
|**INDEX:**<BR><BR>The layout of the Homepage is responsive as expected from the wireframes.<br> - The hero image is cropped as expected to adjust to the viewport of the device.<br>-The layout of the Mosaic in vertical tablet has been tested exceptionally as of Surface 7 pro in the DevTools.<br> - The Mosaic adapts in four different breakpoints, as of the BootStrap grid set up. <br> - The stack menu button in the smallest viewport works as expected.<br>- The footer, also with BootStrap grid, is also responsive as expected<br> stacking the content in column.|![rm_index_on_iphone_se1](assets/images/rm_index_on_iphone_se1.png)<br>![rm_index_on_iphone_se2](assets/images/rm_index_on_iphone_se2.png)<br>![rm_index_on_iphone_se3](assets/images/rm_index_on_iphone_se3.png)<br><br>|![rm_int_ipad_hor_index](assets/images/rm_int_ipad_hor_index.jpg)<br>![rm_int_ipad_hor_index_mosaic](assets/images/rm_int_ipad_hor_index_mosaic.jpg)|!![rm_int_ipad_ver_index](assets/images/rm_int_ipad_ver_index.jpg)<br>![rm_int_surfacepro7_ver_index_mosaic](assets/images/rm_int_surfacepro7_ver_index_mosaic.png)|
|**INVESTORS:**<BR><BR>The main interactive feature of the page is the cal.com appointment booking feature. <br>The responsiveness of the feature has been set app by the developers of the widget at the <br>commercial provider. However, it reacts satisfyingly with all expected breakpoints of the page.|![rm_investors_on_iphone_se1](assets/images/rm_investors_on_iphone_se1.png)<br>![rm_investors_on_iphone_se2](assets/images/rm_investors_on_iphone_se2.png)|![rm_int_ipad_hor_investors](assets/images/rm_int_ipad_hor_investors.jpg)|![rm_int_ipad_ver_investors](assets/images/rm_int_ipad_ver_investors.jpg)|
|**Crowdfunding:**<br><br>The page currently only contains one interactive feature:<br>- The "Buy me a coffee" widget. <br>The widget is quite whimsical, since the commercial promoter has designed it to stick to the bottom-right corner of the viewport. To have it feature prominently <br>under the text which refers to it, setting up an iframe containing an ancillary page - featuring the widget - was necessary. <br>The setup of the feature in different breakpoints has been the main complication of coding the page.|![rm_crowdfunding_on_iphone_se_bmc](assets/images/rm_crowdfunding_on_iphone_se_bmc.png)|![rm_int_ipad_hor_crowdfunding](assets/images/rm_int_ipad_hor_crowdfunding.jpg)|![rm_int_ipad_ver_crowdfunding](assets/images/rm_int_ipad_ver_crowdfunding.jpg)|


![def_testing_handheld](assets/images/def_testing_handheld.PNG)

