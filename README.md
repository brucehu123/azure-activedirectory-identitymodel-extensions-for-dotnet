Microsoft IdentityModel for .NET
===========
[![Nuget](https://img.shields.io/nuget/dt/System.IdentityModel.Tokens.Jwt?label=Total%20downloads)](https://www.nuget.org/packages/System.IdentityModel.Tokens.Jwt) [![Nuget](https://img.shields.io/nuget/v/Microsoft.IdentityModel.JsonWebTokens?label=Latest%20release)](https://www.nuget.org/packages/Microsoft.IdentityModel.JsonWebTokens/) [![Build Status](https://identitydivision.visualstudio.com/IDDP/_apis/build/status/CI/DotNet/Middleware%20Builds/Wilson-Nightly-Debug?branchName=dev)](https://identitydivision.visualstudio.com/IDDP/_build/latest?definitionId=392&branchName=dev5x) [![MyGet (with prereleases)](https://img.shields.io/myget/azureadwebstacknightly/vpre/Microsoft.IdentityModel.JsonWebTokens?label=Latest%20nightly%20build)](https://www.myget.org/feed/azureadwebstacknightly/package/nuget/Microsoft.IdentityModel.JsonWebTokens) [![License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://raw.githubusercontent.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet/dev/LICENSE.txt)

Microsoft IdentityModel for .NET SDK provide assemblies that are interesting for web developers that wish to use federated identity providers for establishing the callers identity. 

## Usage
If you are using Microsoft IdentityModel with ASP.NET, the following combinations are supported:
* **Microsoft IdentityModel for .NET 5.x**, **ASP.NET Core**, **Katana 4.x**
* **Microsoft IdentityModel for .NET 4.x**, **ASP.NET 4**, **Katana 3.x**
All other combinations aren't supported.

For more details see [migration notes](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet/wiki/Migrating-from-Katana-(OWIN)-3.x-to-4.x).

## Samples and Documentation

The scenarios supported by IdentityModel extensions for .NET are described in [Scenarios](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet/wiki/scenarios). The libraries are in particular used part of ASP.NET security to validate tokens in ASP.NET Web Apps and Web APIs. To learn more about token validation, and find samples, see:

- [Azure Active Directory with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/azure-active-directory/?view=aspnetcore-2.1)
- [Developing ASP.NET Apps with Azure Active Directory](https://docs.microsoft.com/en-us/aspnet/identity/overview/getting-started/developing-aspnet-apps-with-windows-azure-active-directory)
- [Validating tokens](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet/wiki/ValidatingTokens)
- more generally, the library's [Wiki](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet/wiki)
- the [reference documentation](https://docs.microsoft.com/en-us/dotnet/api/overview/azure/activedirectory/client?view=azure-dotnet) 



## Community Help and Support

We leverage [Stack Overflow](http://stackoverflow.com/) to work with the community on supporting Azure Active Directory and its SDKs, including this one! We highly recommend you ask your questions on Stack Overflow (we're all on there!) Also browse existing issues to see if someone has had your question before. 

We recommend you use the "microsoft-identitymodel" tag so we can see it! Here is the latest Q&A on Stack Overflow for ADAL: [http://stackoverflow.com/questions/tagged/microsoft-identitymodel](http://stackoverflow.com/questions/tagged/microsoft-identitymodel)

## Security Reporting

If you find a security issue with our libraries or services please report it to [secure@microsoft.com](mailto:secure@microsoft.com) with as much detail as possible. Your submission may be eligible for a bounty through the [Microsoft Bounty](http://aka.ms/bugbounty) program. Please do not post security issues to GitHub Issues or any other public site. We will contact you shortly upon receiving the information. We encourage you to get notifications of when security incidents occur by visiting [this page](https://technet.microsoft.com/en-us/security/dd252948) and subscribing to Security Advisory Alerts.

## Contributing

All code is licensed under the MIT license and we triage actively on GitHub. We enthusiastically welcome contributions and feedback. See [Contributing.md](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet/blob/master/Contributing.md) for guidelines, branch information, build instructions, and legalese. 


## License

Copyright (c) Microsoft Corporation.  All rights reserved. Licensed under the MIT License (the "License"); 

## We Value and Adhere to the Microsoft Open Source Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

