# AutonomiqChropath
Use this repo to raise the issue/feature request related to ChroPath.

ChroPath generates unique relative xpath, absolute xpath, cssSelectors, linkText and partialLinkText just by one click. ChroPath can also be used as Editor for selectors. It makes easy to write, edit, extract, and evaluate XPath queries on any webpage. ChroPath also supports iframe and dynamic id.

Please contact Sanjay Kumar, ChroPath Product Evangelist at chropath@autonomiq.io for support.

How to use ChroPath-

1. Right-click on the web page, and then click Inspect.
2. In the right side of Elements tab, click on ChroPath tab. If it is not visible then please expand devtools.
3. To generate selectors, inspect element or click on any DOM node, it will generate the unique relative XPath/absolute XPath/CSS selector/linkText/partialLinkText.
4. To evaluate XPath/CSS, type the XPath/CSS query and press enter key.
	As you enter, it will query in DOM for the relevant element/node. You can view the matching node(s) and nodes value as per their sequential occurrence. A green colour outline appears around to highlight the first matching elements and rest in blue colour in the web page.
5. If you mouse hover on any matching node in the ChroPath tab, green/blue dashed outline will convert into dotted orange red to highlight the corresponding element in the webpage.
6. If the found element is not in visible area on webpage then mouse hover on found node in ChroPath panel will scroll that element in the visible area with dotted orange red outline.
7. If found element is not highlighted but visible then on mouse hover on matching node on ChroPath tab it will highlight element with dotted orange red outline.
8. copy the locators just by clicking on copy icon.
9. click on edit icon if want to edit any locator.

iframe feature-
*Supports only those iframe which has the same src. 
1. If element inside iframe, then it will highlight first matching element in orange dotted outline.
2. It will also add one 'if..' icon in input box of ChroPath tab to make it clear that element is inside iframe.
3. If you want to verify your selector inside iframe then 1st inspect any element inside that iframe so that it get the DOM of iframe and then verify the selector.
4. Again if you want to verify any selector for a element which is outside iframe then first inspect any element which is outside iframe so that it get the top DOM and then verify the selector.

Dynamic ID support-
1. To generate relative xpath without id, uncheck the checkbox there in relative xpath row.
2. To generate relative xpath with id, select the checkbox.

On/Off button-
1. If you don't want to generate selectors, turn off the button available in ChroPath tab.
2. Turn on the button to enable ChroPath again.

Dark Theme-
1. To use dark theme, go to devtools settings.
2. Change the Theme from Light to Dark.

Note: 
1. For one selector only, change the dropdown value from selectors to rel XPath/abs Xpath/CSS sel in header.
2. Tool will add xpath/css attribute to all the matching node(s) as per their sequential occurrence. For example, a matching node appearing second in the list will have xpath=2. And if verifying CSS then it will add css=2.
3. Supports only those iframe which has the same src.
Read less
