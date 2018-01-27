# Description

Samples for RPA courses on [AutomationAcademy.com](https://automationacademy.com/learn/my/).

# Project structure

Directory | Description | Business process(BP) analogue |
| :-: | --- | :---: |
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
    Updating field in datastore. *Note*: csv file in datastore folder won't change
    during execution in WF studio.
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
### [configs/rpa/selenese]() - .
### [configs/rpa/simplified]() - .
### [configs/rpa/starter_sample]() - .
### [configs/rpa/webharvest]() - .

* []() -
* []() -
* []() -
* []() -
* []() -
