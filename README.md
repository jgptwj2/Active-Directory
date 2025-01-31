<h1> Analyzing HTTP Traffic with Wireshark LAB</h1>

<h2>Description</h2>
This guide walks you through analyzing HTTP traffic with wireshark. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch Wireshark and capture HTTP Traffic. Once open select the network that connects to the internet then click the start capture button (Blue Icon) Open a web browser and enter a website that uses HTTP. Once the page loads stop the capture on wireshark (Red Icon). Once this is done successfully you will now a have a capture filec that contains network traffic as well as the HTTP responses and requests <br/>

<br />
<br />
Next, in order to view the HTTP traffic you will see a filter bar at the top. Type http in the filter box and press enter. Once done you will only see HTTP Traffic from the capture since it has been filtered. <br/>

<br />
<br />
At this point you are now ready to analyze the HTTP requests. The first step here is locating an HTTP "GET" request once located click the GET REQUEST to view the details in the packet pane (Bottom left). Expand the HTTP (HYPERTEXT TRANSFER PROTOCOL) section and view the detailed information about the request.
<br/>

<br />
<br />
Next is to anaylze the HTTP responses. In the filtered HTTP traffic locate HTTP Response for the GET request. Click on the response to view the details in the packet pane. Again we are going to expand the HTTP (HYPERTEXT TRANSFER PROTOCOL) section to see the detailed information about the response. You can view the content type, headers, and status code.  <br/>

<br />
<br />
To extract and examine the payload data navigate back to the HTTP response details and right click on the response packet select Follow then select TCP stream to view everything going on. Examine the payload data in the TCP stream window to analyze the content being transferred.  <br/>

<br />
<br />
Finally once this has been finished you will have an understanding on how to capture, filter, and analyze HTTP traffic by using Wireshark. It is not adviseable to share this information with a third party if the capture was done via your wifi network as it contains sensitive details that can be mishandled.  <br/>

<br />
<br />
 <br/>
 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
