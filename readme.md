# Description

Samples for RPA courses on [AutomationAcademy.com](https://automationacademy.com/learn/my/).

# Installation

You should have account on [WorkFusion Knowledge Base](https://kb.workfusion.com/display/START/WorkFusion+Knowledge+Base) to access these links.
* [WF Studio installation](https://kb.workfusion.com/display/WF/Installation+and+Update)
* [Importing project into WF Studio](https://kb.workfusion.com/display/WF/Setup+WorkFusion+Samples+Project+from+GitHub)
* [RPA installation](https://kb.workfusion.com/display/RPA/RPA+Environment+Setup)


# Project structure

Directory | Description | Business process(BP) analogue |
| :-----: | :--------: | :--------: |
|configs | directory for scripts| Bot Task
|datastore | csv files scripts can access| Datastores
|input | csv files, which are used as input for BP| "Data" tab in BP definition|
|output | config generated csv | "Data" section in "Result" tab |

# Samples

## [configs/webharvest](https://github.com/WFAutomationAcademy/RPA-Samples/tree/master/configs/webharvest) - Samples of webharvest library using

* [configs/webharvest/bindingAndDefineVariable.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/bindingAndDefineVariable.xml) -
    How to access `java/groovy` variable with web-harvest command.
* [configs/webharvest/create-file-s3put.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/create-file-s3put.xml) -
    Creating plain text file and uploading it to S3.
* [configs/webharvest/db-select.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/db-select.xml) -
    Reading datastore and logging its fields.
* [configs/webharvest/ftp_sample.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/ftp_sample.xml) -
    Accessing ftp-server and logging its content (files, directories, links).
* [configs/webharvest/groovy-loop.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/groovy-loop.xml) -
    Creating hash-map(dictionary) and output its content with [```<multi-column>```](https://kb.workfusion.com/display/WF/export#export-multi-column).
* [configs/webharvest/groovy-tests.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/groovy-tests.xml) -
    Simple example, that teaches you how to read datastore, create and export variable.
    You can use it later as starter code.
* [configs/webharvest/holidays-US-export.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/holidays-US-export.xml) -
    Getting the list with [US national holidays](https://www.timeanddate.com/holidays/us/2013#!hol=9568127) and logging them.
    This sample teaches you how to scrap data for immediate processing.
* [configs/webharvest/holidays-US-export2.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/holidays-US-export2.xml) -
    Getting the list with US national holidays and exporting them.
    This sample teaches you how to scrap data and save them for batch processing.
* [configs/webharvest/JSON-to-excel.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/JSON-to-excel.xml) -
    Creating hash-map(dictionary) converting it to [JSON](https://www.json.org/) format for
    writing it to [excel](https://products.office.com/en/excel) file. Syntax for exporting
    hash-maps differs from syntax for writing it to excel. This sample helps you to be familiar
    with it.
* [configs/webharvest/read-Excel_file.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/read-Excel_file.xml) -
    Reading excel file and logging its content.
* [configs/webharvest/recursive_call_function_withparameters.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/recursive_call_function_withparameters.xml) -
    Creating folder and subfolders/files in it. This sample teaches you how to call
    functions recursively.
* [configs/webharvest/set-flag.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/set-flag.xml) -
    Updating field in datastore.
    *Note: csv file in datastore folder won't change during execution in WF studio.*
* [configs/webharvest/split_text_by_webharvest.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/split_text_by_webharvest.xml) -
    Splitting text with [```<split>```](https://kb.workfusion.com/display/WF/split) command.
* [configs/webharvest/test-ds.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/test-ds.xml) -
    Uploading datastore as csv to S3. You can add some processing if needed.
* [configs/webharvest/translate_with_groovy.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/translate_with_groovy.xml) -
    Translating text with [Yandex API](https://tech.yandex.com/translate/). Do not use this API
    for first assignment, you should use [MS API](https://www.microsoft.com/en-us/translator/translatorapi.aspx) there.
* [configs/webharvest/validate-url.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/webharvest/validate-url.xml) -
    Checking site status with [```<url-validator>```](https://kb.workfusion.com/display/WF/url-validator).

## [configs/rpa](https://github.com/WFAutomationAcademy/RPA-Samples/tree/master/configs/rpa) - Samples of RPA automation.

### [configs/rpa/selenese](https://github.com/WFAutomationAcademy/RPA-Samples/tree/master/configs/rpa/selenese) -  Using [```<selenese>```](https://kb.workfusion.com/display/RPA/%5B8.2%5D+-+Selenium+Plugins#id-[8.2]-SeleniumPlugins-capability) command.

* [configs/rpa/selenese/selenese-example.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/selenese/selenese-example.xml) -
    Searching in web by Google search engine.

### [configs/rpa/simplified](https://github.com/WFAutomationAcademy/RPA-Samples/tree/master/configs/rpa/simplified) - Samples of [simplified](https://kb.workfusion.com/display/RPA/Simplified+Robotics+API) syntax.
* [configs/rpa/simplified/ajax.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/ajax.xml) -
	Using ```switchTo().frame()``` and ```shouldHave()``` methods.
* [configs/rpa/simplified/alerts-popups-js.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/alerts-popups-js.xml) -
	Processing js-popups (`alert`, `confirm`, `prompt`).
* [configs/rpa/simplified/app-jar-swing-table.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/app-jar-swing-table.xml) -
	Filling table in `swing` app. *Note: you should manually add site and app to security exceptions.*
* [configs/rpa/simplified/app-jar-swing-tree.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/app-jar-swing-tree.xml) -
	Processing tree UI-component in `swing` app, separated bot for web and desktop applications.
	*Note: you should manually add site and app to security exceptions.*
* [configs/rpa/simplified/applet-simple.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/applet-simple.xml) -
	Simple sample with ```sendKeys()``` and working with clipboard.
	*Note: you should manually add site and app to security exceptions.*
* [configs/rpa/simplified/applet-swing-dropdown.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/applet-swing-dropdown.xml) -
	Processing drop-down UI-component in `swing` app.
	*Note: you should manually add site and app to security exceptions.*
* [configs/rpa/simplified/applet-swing-tree-universal.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/applet-swing-tree-universal.xml) -
	Processing tree UI-component in `swing` app with
	[`universal`](https://kb.workfusion.com/display/RPA/Universal+RPA+Driver) driver.
	*Note: you should manually add site and app to security exceptions.*
* [configs/rpa/simplified/basic-auth-autoit.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/basic-auth-autoit.xml) -
	Implementing [basic html authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)
    with separated bot for web and desktop applications.
    Also there is a hack to process with [```click()``` bug](https://github.com/SeleniumHQ/selenium/issues/4292) in `selenium` for `IE`.
* [configs/rpa/simplified/basic-auth-universal.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/basic-auth-universal.xml) -
	Implementing [basic html authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)
    with [`universal`](https://kb.workfusion.com/display/RPA/Universal+RPA+Driver) driver.
* [configs/rpa/simplified/calculator-desktop.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/calculator-desktop.xml) -
	Automating old(before win10) Windows calculator.
* [configs/rpa/simplified/checkbox-radiobutton.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/checkbox-radiobutton.xml) -
	Selecting html checkboxes and radiobuttons.
* [configs/rpa/simplified/chrome-file-download.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/chrome-file-download.xml) -
	Automating file downloading for `Chrome` browser.
* [configs/rpa/simplified/console-ping.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/console-ping.xml) -
	Pinging domains and exporting results.
* [configs/rpa/simplified/drag-and-drop.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/drag-and-drop.xml) -
	Automated drag-and-dropping on web-page.
* [configs/rpa/simplified/excel-2.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/excel-2.xml) -
	Copying from one excel file to another.
* [configs/rpa/simplified/excel.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/excel.xml) -
	Getting data from excel file and exporting it.
* [configs/rpa/simplified/file-upload-universal.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/file-upload-universal.xml) -
	Attaching file to email with [`universal`](https://kb.workfusion.com/display/RPA/Universal+RPA+Driver) driver..
* [configs/rpa/simplified/file-upload.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/file-upload.xml) -
	Attaching file to email with separated bot for web and desktop applications..
* [configs/rpa/simplified/gmail-sample.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/gmail-sample.xml) -
	Automating emailing with Gmail web-application.
* [configs/rpa/simplified/hover.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/hover.xml) -
	Howering html-items.
* [configs/rpa/simplified/ie-save-as.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/ie-save-as.xml) -
	Automating file downloading with IE browser.
* [configs/rpa/simplified/iframes-count.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/iframes-count.xml) -
	Calculating number of iframes.
* [configs/rpa/simplified/iframes-switch.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/iframes-switch.xml) -
	Switching between frames.
* [configs/rpa/simplified/invoiceplane-simplified.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/invoiceplane-simplified.xml) -
	Automating [invoiceplane](https://invoiceplane.workfusion.com) application.
* [configs/rpa/simplified/js-async-bug.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/js-async-bug.xml) -
	Executing JS for web page.
* [configs/rpa/simplified/js-executor.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/js-executor.xml) -
	Executing JS for web page.
* [configs/rpa/simplified/notepad-clipboard.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/notepad-clipboard.xml) -
	Automating notepad Windows application using clipboard.
* [configs/rpa/simplified/notepad-save-as.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/notepad-save-as.xml) -
	Automating notepad Windows application and `Save as` dialog.
* [configs/rpa/simplified/open-link-new-tab.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/open-link-new-tab.xml) -
	Opening link in a different tab.
* [configs/rpa/simplified/putty-vim.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/putty-vim.xml) -
	Automating [putty](https://www.putty.org/) [ssh](https://www.ssh.com/ssh/protocol/)-client.
* [configs/rpa/simplified/resource-check-append-read.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/resource-check-append-read.xml) -
	Appending information from web page to existed file.
* [configs/rpa/simplified/resource-check.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/resource-check.xml) -
	Checking if resource is exist.
* [configs/rpa/simplified/resource-list-move-copy.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/resource-list-move-copy.xml) -
	Filtering and moving files from one folder to another.
	*Note: Create new folder and fill them with some file, do not use it on your system foldes to
	prevent moving sensitive data.*
* [configs/rpa/simplified/screenshot-browser-complicated.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/screenshot-browser-complicated.xml) -
	Taking browser screenshot with usual syntax.
* [configs/rpa/simplified/screenshot-browser.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/screenshot-browser.xml) -
	Taking browser screenshot with simplified syntax.
* [configs/rpa/simplified/screenshot-desktop-autoit.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/screenshot-desktop-autoit.xml) -
	Taking desktop screenshot with autoit driver.
* [configs/rpa/simplified/screenshot-desktop-java.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/screenshot-desktop-java.xml) -
	Taking desktop screenshot with java.
* [configs/rpa/simplified/screenshot-desktop-sikuli.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/screenshot-desktop-sikuli.xml) -
	Taking desktop screenshot with sikuli library.
* [configs/rpa/simplified/select-dropdown.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/select-dropdown.xml) -
	Selecting multiple items of drop-down html-element.
* [configs/rpa/simplified/sikuli-calc.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/sikuli-calc.xml) -
	Image-based automation.
	*Note: actual coordinates and image depand on screen resolution and window size.*
* [configs/rpa/simplified/sikuli-getmethod.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/sikuli-getmethod.xml) -
    Image-based automation.
	*Note: actual coordinates and image depand on screen resolution and window size.*
* [configs/rpa/simplified/switch-to-window.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/switch-to-window.xml) -
	Switching between tabs in browser.
* [configs/rpa/simplified/table-scraping-webharvest.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/table-scraping-webharvest.xml) -
	Table scraping with `webharvest` and `selenium`. It is the same as
	[configs/rpa/webharvest/page-source.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/webharvest/page-source.xml),
	but using simplified syntax.
* [configs/rpa/simplified/table-scraping.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/table-scraping.xml) -
	Table scraping with `groovy` in `robot` context.
* [configs/rpa/simplified/universal-drive.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/universal-drive.xml) -
	Searching in [Wikipedia](https://www.wikipedia.org/) and typing found data in notepad.

### [configs/rpa/starter_sample](https://github.com/WFAutomationAcademy/RPA-Samples/tree/master/configs/rpa/starter_sample) - The sample you can start your own automation with.

* [configs/rpa/starter_sample/rpa-starter-sample.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/starter_sample/rpa-starter-sample.xml).

### [configs/rpa/webharvest](https://github.com/WFAutomationAcademy/RPA-Samples/tree/master/configs/rpa/webharvest) - Mixing Selenium and Webhervest to parse html-page.

* [configs/rpa/webharvest/page-source.xml](https://github.com/WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/webharvest/page-source.xml) -
    Scrapping web-table content. You can find simplified version in
    [configs/rpa/simplified/table-scraping-webharvest.xml](https://github.com//WFAutomationAcademy/RPA-Samples/blob/master/configs/rpa/simplified/table-scraping-webharvest.xml).

