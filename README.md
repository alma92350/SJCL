# mySJCL.github.io

The objective is to allow an AppInventor 2 applications to perform strong cryptogaphic processing using the Standford SJCL.js library locally.
The challenges were:
  1-To integrate the sjcl.js library in a local html file
  2-To develop the interface of communication between the APPInv2 and the sjcl wrapper using the webViewString feature

In order to streamline the development of the HTML file, the SJCL Html file was put on a github server. This avoided numerous upload to the application.

In order to pass multiple parameters from the App and the Javascript in the Html file within a string, the '&' was used as separator.
Specific uriEncode and uriDecode were developped to escape % and & characters.
