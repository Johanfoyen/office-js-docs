## Excel JavaScript API Open Specification

_Applies to: Excel 2016, Excel Online, Excel for iOS, Excel for Mac_

This page describes the new set of Excel JavaScript APIs that are planned for future releases. It consists of APIs that are in `beta` stage and others that are still in the design phase. Please review and provide your feedback. One of the best ways you can provide input is to open a new issue in GitHub using the links available below.

_**Note**: The following features are still under design and review phase and not yet available as part of the product. The final design is subject to change. Once the feature is made available, the final specification will be published as part of the master repository._

> **Note**: Any API that is listed as **beta** is not ready for production usage. They are made available so that developers can try them out in test and development environments. They are not meant to be used against production/business critical documents. 

> For the requirement sets that are marked as *Beta*, use the specified (or later) version of Office and use the Beta library of the CDN: https://appsforoffice.microsoft.com/lib/beta/hosted/office.js. Entries not listed as *Beta* are generally available and you can continue to use Production CDN library: https://appsforoffice.microsoft.com/lib/1/hosted/office.js

# Announcements

1.8 was released to GA during Ignite, September 24<sup>th</sup>, 2018\. Check our all the details in our documentation.

New Beta APIs are ready for critique.

# What’s new in the Excel JavaScript Beta?

Here is a summary of the APIs and relevant pointers for content. Please give it a try and open issues to send us feedback.

Included in this release are more than 400 new APIs for Excel, please refer to a detailed list here.

| Feature Area | Description | Relevant Objects/Articles |
| --- | --- | --- |
| Shapes | Insert, position and format Images, Geometric Shapes and Text boxes. | ShapeCollectionShapeGeometricShapeImage |
| New Charts | Explore our new supported chart types. | Chart |
| Auto Filter | Add filters to ranges, sort, etc. | AutofilterRange |
| Areas | Finally, on the API we support discontinuous ranges! | RangeAreas |
| Special Cells |   | Range |
| Find |   | Range Worksheet |
| Copy Paste |   | Range |
| RangeFormat |   | Range |
| Workbook Save, Close |   | Workbook |
| Filter Events |   | AutoFilter |
| Data Change events |   | Range |
| Insert Workbook |   | Workbook |
| Calculation |   | Application |

## Give us feedback!

We need it, you want to give it. Feedback is much easier to give now that we're on GitHub. Check out the docs and let us know your thoughts by submitting [issues](https://github.com/OfficeDev/office-js-docs/issues) directly in this repository.

For API support, you can post questions to the community on [StackOverflow](http://stackoverflow.com/questions/tagged/office-js) and tag them with [office-js].
