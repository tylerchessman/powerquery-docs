# Hello World Sample

This sample provides a simple data source extension that can be run in Visual Studio, and loaded in Power BI Desktop. As an overview, this sample shows the following:

* Exporting function (HelloWorld.Contents), which takes an option text parameter.
* Defining a data source kind that:
  * Declares that it uses Implicit (anonymous) authentication.
  * Uses string resources that allow for localization.
* Declaring UI metadata so the extension can show up in the Power BI Desktop Get Data dialog.

## Get Data dialog in Power BI Desktop

![GetData]

## Authentication dialog

![Auth]

## Query editor

![Query]

[GetData]: ../../images/helloworld1.png "Hello World in Get Data"
[Auth]: ../../images/helloworld2.png "Hello World authentication dialog"
[Query]: ../../images/helloworld3.png "Hello World in the query editor"