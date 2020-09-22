<div align="center">

## Intro to the ASP Object Model


</div>

### Description

A brief overview of the ASP object model. I will be submitting more tutorials on each object in future submissions.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Brad Hess from http://www\.4aspdev\.com](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/brad-hess-from-http-www-4aspdev-com.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[ASP Server Object Model](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/asp-server-object-model__4-32.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/brad-hess-from-http-www-4aspdev-com-intro-to-the-asp-object-model__4-6167/archive/master.zip)





### Source Code

<table>
 <tr>
 <td></td>
 </tr>
 <tr>
 <td>
  <p><font face="Verdana">Alright we have now written a very simple ASP
  page, but lets take some time and explore some of the built in features of
  ASP. The first thing that we should take a look at are the five intrinsic
  objects that are part of the ASP Scripting Context (an important note is
  that there is a sixth object which will be covered later). The diagram
  below shows the five main objects. They are the Request, Response,
  Application, Session, and Server. </font><center><map name="FPMap0">
  <area coords="105,39,198,64" href="http://www.planet-source-code.com/vb/tutorial/asp/default.asp?ID=8" shape="RECT">
  <area coords="106,73,195,95" href="http://www.planet-source-code.com/vb/tutorial/asp/default.asp?ID=9" shape="RECT">
  <area coords="106,103,199,127" href="http://www.planet-source-code.com/vb/tutorial/asp/default.asp?id=10" shape="RECT">
  <area coords="106,138,199,162" href="http://www.planet-source-code.com/vb/tutorial/asp/default.asp?ID=11" shape="RECT"></map><font face="Verdana"><img border="0" height="200" src="http://www.planet-source-code.com/vb/tutorial/asp/images/object.gif" useMap="#FPMap0" width="200"></font>
  <p> </p>
  </center>
  <p><font face="Verdana">Each of these objects has there its own methods
  and properties that the following sections are going to cover. To give a
  rough outline.</font>
  <ul>
  <li><font face="Verdana"><b>Request:</b> This object exposes the
   properties of the HTTP request. A request is what is sent to the
   server when the browser asks for a particular action. For instance
   typing <a href="http://www.4aspdev.com/contact.asp">http://www.4aspdev.com/contact.asp</a>
   is a request to the 4aspdev server for the contact.asp page. There is
   a lot more to it than that, but for now let's leave it at that.<br>
   </font>
  <li><font face="Verdana"><b>Response:</b> The response object exposes
   the properties of the server response. The response is what the server
   sends to the browser after a request is made. The response object
   allows you to:</font>
   <ul>
   <li><font face="Verdana">Control what data is sent in the header of
    the HTTP response (don't worry if you don't know what a header is
    I will get to that later)</font>
   <li><font face="Verdana">Control what data is sent to the client in
    the <:body> of the HTTP response</font>
   <li><font face="Verdana">Control when and how the data is sent</font></li>
   </ul>
   <br>
  <li><font face="Verdana"><b>Application:</b> This object allow you to
   manipulate the properties of the application. In ASP an application is
   all the files in a virtual directory and its subdirectories.
   Application scope covers all users of the web site so if you set an
   application level variable or setting it will effect everyone that
   uses the site.<br>
   </font>
  <li><font face="Verdana"><b>Session:</b> This object allows you to
   control the properties on an individual user session. A session starts
   when a user first comes to you site and ends either when they leave,
   close their browser, or at a set timeout. Any variables or settings
   that are made using the session object are on an individual basis.<br>
   </font>
  <li><font face="Verdana"><b>Server:</b> This object effects the Server
   itself. This object allows you to control certain aspects of the
   server such as script timeout. Which is the time that a script is
   allowed to process.</font></li>
  </ul>
 </td>
 </tr>
</table>

