# Mendix-Klippa-OCR-API

:rocket: *Create smart document processes in Mendix using the Klippa OCR API* :rocket:

**The source code of the Mendix Klippa OCR module to do document parsing directly from Mendix.**

## Module usage

You will need an API key to use this module. If you would like to use our API, please contact us [here](https://www.klippa.com/en/ocr/ocr-api).

## How to use the module

1. Import the module into your Mendix project
2. Create a **Config** object that contains your API Key
3. Create a new **ParseDocumentRequest** object that holds the request data, you can supply either the URL or the Document as a **System.FileDocument**.
4. Call the Microflow **ParseDocument** with the created **Config** and **ParseDocumentRequest** as parameters
5. The response will be a **ParseDocumentWrapper** that contains either the success result or the error result. The object also contains the response status and body.

## About Klippa

[Klippa](https://www.klippa.com/en) is a scale-up from [Groningen, The Netherlands](https://goo.gl/maps/CcCGaPTBz3u8noSd6) and was founded in 2015 by six Dutch IT specialists with the goal to digitize paper processes with modern technologies.

We help clients enhance the effectiveness of their organization by using machine learning and OCR. Since 2015 more than a 1000 happy clients have been served with a variety of the software solutions that Klippa offers. Our passion is to help our clients to digitize paper processes by using smart apps, accounts payable software and data extraction by using OCR.

## License

The MIT License (MIT)


