# Installation #

The easiest way to install HttpClient is to add it as a project reference.  To do so, do the following:
  1. Download HttpClient and extract the files
  1. Drag the HttpClient.xcodproj file onto your project in Xcode.  Make sure Copy items is NOT checked.
  1. Select the HttpClient.xcodeproj file from the project explorer, and select the check box for libHttpClientLib.a
  1. Open the properties for your application target.  Click the + button to add a direct dependency, and select HttpClientLib.
  1. In the application target properties, you also need to add a linked library.  Click the + button, and select libz.dylib.
  1. In the Search Paths section of your application build properties, add a recursive reference to the HttpClient project folder in the Header Search Paths property.  For example: libraries/HttpClient/
  1. Now, to use HttpClient, simply type import "HttpClient.h" in any file you wish to use it!