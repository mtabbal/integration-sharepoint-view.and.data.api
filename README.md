#Autodesk View and Data API sample demos integration with sharepoint

The MIT License (MIT)

Copyright (c) 2014 Autodesk, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


##Description

*This sample is part of the [Developer-Autodesk/Autodesk-View-and-Data-API-Samples](https://github.com/Developer-Autodesk/autodesk-view-and-data-api-samples) repository.*

You can find a blog post about this here http://adndevblog.typepad.com/cloud_and_mobile/2014/06/integrate-viewer-with-sharepoint.html

This repo contains files that show how you can upload files and view them inside SharePoint using the Autodesk viewer.

There are three main parts to this:
- MyViewerPage.aspx: this html page uses the Autodesk Viewer to show the file whose urn is  passed to it in the URL as the urn parameter. It also requires the accessToken that you get when authenticating with the viewing service to be also passed in the URL
- MyVisualWebPart project: a C# Visual Web Part project which has a user control that can be used inside a SharePoint Web Part page. This will list all the files found in the Documents library of a SharePoint site and uses MyViewerPage.aspx inside an iframe to show the file in the viewer
- MyWebPart.aspx: this is the SharePoint page which embeds the above Visual Web part project's control that lists the SharePoint documents 


##Dependencies

None

##Setup/Usage Instructions

* Get your consumer key and secret key from http://developer.autodesk.com
* Todo 


##Written by 

Adam Nagy





    
