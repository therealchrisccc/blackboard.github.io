---
layout: learn
parent: soap
category: tutorials-soap
---
# Tutorial: Build The C# SOAP Sample Client
*Author: Scott Hurrey*  
*Categories: ['Getting Started', 'SOAP Web Services', 'Tutorials']*  
*Tags: ['web services', 'soap', 'tutorial', 'blackboard learn', 'sample code', 'sample client', 'developer']*  
<hr />
The Blackboard Learn sample code contains a fully-functional client that
provides form-based interaction with all of the available SOAP-based Web
Services. This allows a Developer to interact with any of the Web Services,
see what data is required, try different combinations and permutations and
inspect the code behind it. This is a great tool to use to assist in designing
your Web Services integration, and even to troubleshoot an existing
integration from release-to-release.

This help article assumes that you have downloaded the [Web Services Sample
Code](About%20Web%20Services%20Sample%20Code.html) and that you have built
the [.NET Web Services Library](Tutorial%20-%20Build%The%20C%23%20SOAP%20Sample%20Library.html).

### How to Build

Building the .NET Sample Client is really quite simple, once you have
generated and built the Web Services Library. The solution has already been
created, and lives in the **_<top level of client.zip>/qa/dotnet/wsagent_**
directory. The easiest way to build it, is to open Microsoft Visual Studio
Express 2010 for C# and open the solution containing the .NET library. With
this loaded, click **File->Add...->Existing Project**. Navigate to the wsagent
directory, select wsagent2010 project, and click Open. This will add the
sample client to the existing project.

Now simply click **Debug->Build** and build the project. This will place an
executable called wsagent.exe in the _**<top level of
client.zip>/qa/dotnet/wsagent/bin/Debug**_ directory. You can add a link to
your desktop, start menu, or quick launch bar and launch the tool whenever you
need it.

