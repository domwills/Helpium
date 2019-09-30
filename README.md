# Helpium
A GUI helper for finding and interacting with web elements.
## Background
A simple GUI was created to help creating automated scripts and debugging any issues you may encounter. This takes away the need to keep re-running your scripts and setting numerous debug points. 
## Usage
Helpium will connect with Google Chrome via the debugging port, and run the Selenium commands without the need for an IDE. You will be able to find elements by using the Selenium selectors:
* ClassName
* CssSelector
* Id
* LinkText
* Name
* PartialLinkText
* TagName
* XPath

If the element is found, it will add a red border to the element. It will also feedback and let you know how many elements were found with the given selector.

You can also use the standard methods with a web element:
* Clear
* Click
* GetAttribute
* GetCssValue
* SendKeys
* Submit

## Documentaion
Documentation can be found here
