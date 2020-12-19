**ASP.Net MVC client using Apero package Overview**<br/>

This a simple sample to use _PARSSO_ CAS with a  dotNet client

**Prerequisites**
- Enabled IIS
- Microsoft visual studio 2015 or upper version<br/>
after open this project on the IDE, install this package using _nuget_ package manger:
- DotNetCasClient

**Configuration** <br/>
In this project, all of the settings, set to work with _PARSSO_ CAS. if your server is different, please change these tages in the `web.config` file:
- loginUrl, casServerLoginUrl, casServerUrlPrefix : these tages state your CAS server<br/>
- serverName : this tag shows your client address

**Deploy**
If you open this project with its `*.sln` fie, you can see its configuration for deploy is > IIS; else you deploy it with an `IIS EXPRESS` configuration.



