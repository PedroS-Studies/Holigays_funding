# Testing and accessibility

<!--STart ToC-->
## Table of contents
<ul>
    <details>
        <summary><a href="#code-testing">Code testing</a></summary>
        <ul>
            <li><a href="#html-validation">HTML validation</a></li>
        </ul>
    </details>
    <details>
        <summary><a href="#css-testing">CSS testing</a></summary>
        <ul>
            <li><a href="#font-optical-resizing">Font optical resizing</a></li>
            <li><a href="#font-variation-settings">Font variation settings</a></li>
        </ul>
    </details>
    <li><a href="#broken-links">Broken links</a></li>
    <details>
        <summary><a href="#accessibility-testing">Accessibility testing</a></summary>
        <ul>
            <li><a href="#homepage">Homepage</a></li>
            <li><a href="#investors">Investors</a></li>
            <li><a href="#support">Support</a></li>
            <li><a href="#hoteliers">Hoteliers</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#404-page">404 page</a></li>
            <li><a href="#unexpected-issues">Unexpected issues in intermediate accessibility testing</a></li>
            <li><a href="#pagespeed-insights">About the other tests of PageSpeed insights</a></li>
        </ul>
    </details>
    <details>
        <summary><a href="#viewport-testing">Viewport testing</a></summary>
        <ul>
            <li><a href="#desktop-response">Desktop Browser response</a></li>
            <li><a href="#handheld-response">Handheld devices response</a></li>
        </ul>
    </details>
    <details>
        <summary><a href="#debugging">Debugging</a></summary>
        <ul>
            <li><a href="#known-bugs">Known bugs</a></li>
        </ul>
    </details>
    <li><a href="#ongoing-testing">Ongoing testing</a></li>
</ul>
<!--End of ToC-->

## Code testing

### HTML validation

The W3C html validation didn't find any errors in the code of the website.

![rm_w3c_html_validation](assets/images/rm_w3c_html_validation.png)

## CSS testing

The W3C stubbornly returns two errors regarding font values and properties:

![rm_css_w3c_20250611](assets/images/rm_css_w3c_20250611.png)

However, these elements don't hinder the proper rendering of the pages and are admissible according to the Mozilla Foundation.

### Font optical resizing

Though W3C css testing doesn't recognise the attribute, the Mozilla foundation recognises it as acceptable, as well as all its values and parameters:

![rm_mozilla_ref_font-optical-sizing](assets/images/rm_mozilla_ref_font-optical-sizing.png)

### Font variation settings

Though W3C css testing doesn't recognise the attribute, the Mozilla foundation recognises it as acceptable, as well as all its values and parameters:

![rm_mozilla_ref_font-variation-settings](assets/images/rm_mozilla_ref_font-variation-settings.png)

## Broken links

![rm_w3c_broken_links](rm_w3c_broken_links.png)

The footer on every page contain a deliberate broken link. The purpose of the action is to mislead the possible trolls and haters to believing, that the form on the 404 page is only for the purpose of reporting an issue with a page. However, the form contains options for "contact request" and "General feedback", for the user who might be willing to investigate the feature further. An aria-label informs the users of the website about the purpose of the link and the use of the form.

The second link noted by the validator relates to LinkedIn, which however isn't broken but inaccessible for robots.

## Accessibility testing

All the pages of the website passed the PageSpeed testing for accessibility with 100% of validation.

### Homepage

**Desktop:**

![rm_pagespeed_index_desktop](assets/images/rm_pagespeed_index_desktop.png)

**Mobile:**

![rm_pagespeed_index_mobile](assets/images/rm_pagespeed_index_mobile.png)

### Investors

**Desktop:**

![rm_pagespeed_investors_desktop](assets/images/rm_pagespeed_investors_desktop.png)

**Mobile:**

![rm_pagespeed_investors_mobile](assets/images/rm_pagespeed_investors_mobile.png)

### Support

**Desktop:**

![rm_pagespeed_support_desktop](assets/images/rm_pagespeed_support_desktop.png)

**Mobile:**

![rm_pagespeed_support_mobile](assets/images/rm_pagespeed_support_mobile.png)

### Hoteliers

**Desktop:**

![rm_pagespeed_hoteliers_desktop](assets/images/rm_pagespeed_hoteliers_desktop.png)

**Mobile:**

![rm_pagespeed_hoteliers_mobile](assets/images/rm_pagespeed_hoteliers_mobile.png)

### About 

**Desktop:**

![rm_pagespeed_about_desktop](assets/images/rm_pagespeed_about_desktop.png)

**Mobile:**

![rm_pagespeed_about_mobile](assets/images/rm_pagespeed_about_mobile.PNG)

### 404 page

**Desktop:**

![rm_pagespeed_404_desktop](assets/images/rm_pagespeed_404_desktop.png)

**Mobile:**

![rm_pagespeed_404_mobile](assets/images/rm_pagespeed_404_mobile.png)

### Unexpected issues in intermediate accessibility testing

The intermediate HTML testing produced a warning of a possible abusive aria-label in the footer:

![rm_html_warning_misuse_aria-labels](assets/images/rm_html_warning_misuse_aria-labels.png)

The aria-label has been momentarily deleted, but flagged for reinstatement in the future with further testing with WAVE to confirm.

Also to comply with the intermediate testing, it was necessary to replace "disabled" class with BootStrap class "active" of the active navbar link for foreground and background not having enough contrast for accessibility test.

### About the other tests of PageSpeed insights

Though Accessibility and Best practice received top validation, SEO score was kept low for the presence of "noindex" and "nofollow" robots-metatags on all the pages. This is however a provisory situation until further implementation has been done.

The Performance also scored lousy results, especially for handheld devices for the high-quality assets and the presence of 3rd party cookies due to the embedded widgets.

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

## Debugging

### Known bugs

The JavaScript validation code for the "submit button" on 404 page doesn't send the form data to EmailJS as expected. This might however be due to the lack of backend verifcation of the reCAPTCHA code, which would need a backend. Since the requirements for the current project don't require a functioning POST method for the fieldset elements, it might be love's labour lost trying to fix this issue without having all the resources and remedies at hand.

## Ongoing testing

This version is not final or otherwise suitable for end-user testing, to gauge user stories in real life. Some features won't be reliably tested until there can be a backend for the implementation.

Further performance refinements are needed before a release in alpha, including rethinking of the most voluminous assets. However, this would be premature before all the final landing pages of the external links have been set up. 

Accessibility will also be tested with more depth with Lynx as well as with WAVE by AIM.
