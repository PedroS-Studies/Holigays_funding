# Testing and accessibility

## Code testing

![def_html_testing1](assets/images/def_html_testing1.PNG)
![def_html_testing2](assets/images/def_html_testing2.PNG)
![def_html_testing3](assets/images/def_html_testing3.PNG)

## CSS testing

![def_w3_css_validation](assets/images/def_w3_css_validation.PNG)

## Broken links

The footer on everypage contain a deliberate broken link. The purpose of the action is to mislead the possible trolls and haters to believing, that the form on the 404 page is only for the purpose of reporting an issue with a page. However, the form contains options for "contact request" and "General feedback", for the user who might be willing to investigate the feature further. An aria-label informs the users of the website about the purpose of the link and the use of the form.

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
|**INVESTORS**<BR><BR>The page doesn't show major changes from one rendering platform to the other.|![rm_investors_on_chromium](assets/images/rm_investors_on_chromium.png)|![rm_investors_on_gecko](assets/images/rm_investors_on_gecko.png)|![rm_investors_on_safari](assets/images/rm_investors_on_safari.png)|
|**CROWDFUNDING**<BR><BR>The page doesn't show major changes from one rendering platform to the other.|![rm_crowdfunding_on_chromium](assets/images/rm_crowdfunding_on_chromium.png)|![rm_crowdfunding_on_gecko](assets/images/rm_crowdfunding_on_gecko.png)|![rm_crowdfunding_on_safari](assets/images/rm_crowdfunding_on_safari.png)|
|**HOTELIERS**<BR><BR>The page doesn't show major changes from one rendering platform to the other.|![rm_hoteliers_on_chromium](assets/images/rm_hoteliers_on_chromium.PNG)|![rm_hoteliers_on_gecko](assets/images/rm_hoteliers_on_gecko.PNG)|![rm_hoteliers_on_safari](assets/images/rm_hoteliers_on_safari.png)|
|**ABOUT**<BR><BR>The page doesn't show major changes from one rendering platform to the other.|![rm_about_on_chromium](assets/images/rm_about_on_chromium.png)|![rm_about_on_gecko](assets/images/rm_about_on_gecko.png)|![rm_about_on_safari](assets/images/rm_about_on_safari.png)|
|**404**<BR><BR>The page doesn't show major changes from one rendering platform to the other.|![rm_404_on_chromium](assets/images/rm_404_on_chromium.PNG)|![rm_404_on_gecko](assets/images/rm_404_on_gecko.png)|![rm_404_on_safari](assets/images/rm_404_on_safari.png)|

### Handheld devices response

The site has been tested on standard viewports of handheld devices. For smartphones, the viewport on iPhone SE (with DevTools) was used for being one of the smallest on the market. For tablets, both horizontal and vertical view were tested on iPad Pro 12.9". Exceptionally, for the vertical mosaic feature rendering of the index page was tested on Surface pro 7 (DevTools), to assess the overall layout effect under Windows.

|Page|Smartphone|Tablet horizontal|Tablet vertical|
|:---|:--------:|:---------------:|:-------------:|
|**INDEX:**<BR><BR>The layout of the Homepage is responsive as expected from the wireframes.<br> - The hero image is cropped as expected to adjust to the viewport of the device.<br>-The layout of the Mosaic in vertical tablet has been tested exceptionally as of Surface 7 pro in the DevTools.<br> - The Mosaic adapts in four different breakpoints, as of the BootStrap grid set up. <br> - The stack menu button in the smallest viewport works as expected.<br>- The footer, also with BootStrap grid, is also responsive as expected<br> stacking the content in column.|![rm_index_on_iphone_se1](assets/images/rm_index_on_iphone_se1.png)<br>![rm_index_on_iphone_se2](assets/images/rm_index_on_iphone_se2.png)<br>![rm_index_on_iphone_se3](assets/images/rm_index_on_iphone_se3.png)<br><br>|![rm_int_ipad_hor_index](assets/images/rm_int_ipad_hor_index.jpg)<br>![rm_int_ipad_hor_index_mosaic](assets/images/rm_int_ipad_hor_index_mosaic.jpg)|!![rm_int_ipad_ver_index](assets/images/rm_int_ipad_ver_index.jpg)<br>![rm_int_surfacepro7_ver_index_mosaic](assets/images/rm_int_surfacepro7_ver_index_mosaic.png)|
|**INVESTORS:**<BR><BR>The main interactive feature of the page is the cal.com appointment booking feature. <br>The responsiveness of the feature has been set app by the developers of the widget at the <br>commercial provider. However, it reacts satisfyingly with all expected breakpoints of the page.|![rm_investors_on_iphone_se1](assets/images/rm_investors_on_iphone_se1.png)<br>![rm_investors_on_iphone_se2](assets/images/rm_investors_on_iphone_se2.png)|![rm_int_ipad_hor_investors](assets/images/rm_int_ipad_hor_investors.jpg)|![rm_int_ipad_ver_investors](assets/images/rm_int_ipad_ver_investors.jpg)|
|**CROWDFUNDING:**<br><br>The page currently only contains one interactive feature:<br>- The "Buy me a coffee" widget. <br>The widget is quite whimsical, since the commercial promoter has designed it to stick to the bottom-right corner of the viewport. To have it feature prominently <br>under the text which refers to it, setting up an iframe containing an ancillary page - featuring the widget - was necessary. <br>The setup of the feature in different breakpoints has been the main complication of coding the page.|![rm_crowdfunding_on_iphone_se_bmc](assets/images/rm_crowdfunding_on_iphone_se_bmc.png)|![rm_int_ipad_hor_crowdfunding](assets/images/rm_int_ipad_hor_crowdfunding.jpg)|![rm_int_ipad_ver_crowdfunding](assets/images/rm_int_ipad_ver_crowdfunding.jpg)|
|**HOTELIERS:**<br><br>|![rm_hoteliers_on_iphone_se](assets/images/rm_hoteliers_on_iphone_se.png)|![rm_int_ipad_hor_hoteliers](assets/images/rm_int_ipad_hor_hoteliers.jpg)|![rm_hoteliers_on_iphone_se](assets/images/rm_hoteliers_on_iphone_se.png)|
|**ABOUT:**<br><br>|![rm_about_on_iphone_se1](assets/images/rm_about_on_iphone_se1.png)<br>![rm_about_on_iphone_se2](assets/images/rm_about_on_iphone_se2.png)|![rm_int_ipad_hor_about](assets/images/rm_int_ipad_hor_about.jpg)|![rm_int_ipad_ver_about](assets/images/rm_int_ipad_ver_about.jpg)|
|**404:**<br><br>|![rm_404_on iphone_se](assets/images/rm_404_on_iphone_se.png)|![rm_int_ipad_hor_404](assets/images/rm_int_ipad_hor_404.jpg)|![rm_int_ipad_ver_404](assets/images/rm_int_ipad_ver_404.jpg)|



