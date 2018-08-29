---
title: "Working with Objects Selection Method for Spy/Record Web" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/working-with-objects-selection-method-for-spyrecord-web.html 
redirect_from:
    - "/x/ZxlO"
description: 
---
Katalon Studio **Object Properties** makes Spying and Recording Web feature easier and more powerful. **Enhanced **Object Properties allows users to choose objects locating method with Basic or Advanced options, select only preferred object's properties, and manually input XPath or CSS locator. 

> *   Available since version 5.0
> *   Katalon Studio **Object Properties** has the capability to **auto-saved** the content of **Selector Editor** when switching between modes of **Selection Method**
> *   [Object Identification Best Practices](/display/KD/Optimizing+Object+Identification+and+Tools)

Basic Mode
----------

Katalon Studio set **Basic** as a **default** mode. If Basic mode is **selected**, Katalon Studio will automatically generate **XPath** locator **combined** with **selected** object **properties** to locate that object. 

![](../../images/katalon-studio/docs/working-with-objects-selection-method-for-spyrecord-web/image2017-10-16 16_39_1.png)

Users can check/uncheck preferred properties in the object **properties table**

![](../../images/katalon-studio/docs/working-with-objects-selection-method-for-spyrecord-web/image2017-10-16 16_39_40.png)

Verify and Highlight
--------------------

Katalon Studio **Object Properties** has a built-in **Verify and Highlight **feature to help users double-check if the web objects can be located. Katalon Studio will display the message on how many elements are **found** or **NOT** **found** with generated XPath locator. If the object is **found**, it will be highlighted with the **red **border. 

![](../../images/katalon-studio/docs/working-with-objects-selection-method-for-spyrecord-web/image2017-10-16 16_40_30.png)

Once finished, click **Save** to add the object to **Object Repository** as normal.

Advanced Mode (XPath/CSS)
-------------------------

Test engineers who wish to manually input their own **XPath** or **CSS** locator for test objects can select one of these two options. Once selected, object **properties table** will be **collapsed** and **Selector Editor** field becomes **editable**. 

![](../../images/katalon-studio/docs/working-with-objects-selection-method-for-spyrecord-web/image2017-10-16 16_41_25.png)

Next, enter the **XPath** or **CSS** locator in the Selector Editor text box. 

![](../../images/katalon-studio/docs/working-with-objects-selection-method-for-spyrecord-web/image2017-10-16 16_42_14.png)

Same as **Basic **mode, click on **Verify and Highlight** button to make sure Katalon Studio can locate the web objects. 

Katalon Studio will display the message on how many elements are **found** or **NOT** **found** with input XPath or CSS locator. If the object is **found**, it will be highlighted with the **red **border. 

![](../../images/katalon-studio/docs/working-with-objects-selection-method-for-spyrecord-web/image2017-10-16 16_43_21.png)

Once finished, click **Save** to add objects to **Object Repository** as normal.