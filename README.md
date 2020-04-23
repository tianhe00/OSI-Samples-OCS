# OSIsoft OCS Samples

OSIsoft Cloud Services ([OCS](https://www.osisoft.com/Solutions/OSIsoft-Cloud-Services/)) is a highly flexible cloud-based platform that provides scalable, elastic,
centralized environment to aggregate data for reporting, advanced analytics, and third-party applications. OCS is powered by OSIsoft's Sequential Data Store (SDS). In this GitHub repo, we provide samples which will help you get started with the [OCS API](https://ocs-docs.osisoft.com/) against your [OCS instance](https://cloud.osisoft.com/welcome).

If you are interested in other OSIsoft samples please see [OSIsoft Samples](https://github.com/osisoft/OSI-Samples).

There is currently one type of sample in the repo:

- <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon"> Getting Started - OCS focused samples for a task, usually implemented as a simple console app or single page application. There are also base libraries that may be used in other apps.

- <img src="./miscellaneous/images/ctp.png" alt="ctp icon"> This task and code uses services that are currently in preview. If you are interested in this functionality, please contact OCS support.

The official OCS samples are divided in multiple categories depending on the scenario and problem/task, accessible through the following table:

| Task                                                                                                                                                                                                                                    | Description                                                                                                                                                                                                                                                                                                                                                                                                                                   | Languages                                                                                                                                                                                                                                                                                                                                                                                                                                 | Test Status                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **<a href="basic_samples/Authentication/ClientCredentialFlow">Authentication - Client Credentials</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                                      | Click for <a href="basic_samples/Authentication/">details</a> on this type of authentication                                                                                                                                                                                                                                                                                                                                                  | <a href="basic_samples/Authentication/ClientCredentialFlow/DotNet/ClientCredentialFlow">.NET</a>                                                                                                                                                                                                                                                                                                                                          | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_CC_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=595&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **<a href="basic_samples/Authentication/HybridFlow/DotNet/HybridFlow">Authentication - Hybrid Flow</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                                     | Click for <a href="basic_samples/Authentication/">details</a> on this type of authentication                                                                                                                                                                                                                                                                                                                                                  | <a href="basic_samples/Authentication/HybridFlow/DotNet/HybridFlow">.NET</a>                                                                                                                                                                                                                                                                                                                                                              | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_Hybrid_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=847&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **<a href="basic_samples/Authentication/AuthorizationCodeFlow/DotNet/AuthorizationCodeFlow">Authentication - Authorization Code + PKCE</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon"> | Click for <a href="basic_samples/Authentication/">details</a> on this type of authentication                                                                                                                                                                                                                                                                                                                                                  | <a href="basic_samples/Authentication/AuthorizationCodeFlow/DotNet/AuthorizationCodeFlow">.NET</a> </br> <a href="basic_samples/Authentication/AuthorizationCodeFlow/JavaScript">JavaScript</a> </br> <a href="basic_samples/Authentication/AuthorizationCodeFlow/PowerBI">PowerBI</a> </br> <a href="basic_samples/Authentication/AuthorizationCodeFlow/Python">Python</a>                                                               | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=863&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_JavaScript?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=1203&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_PowerBI?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=996&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=1551&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **<a href="basic_samples/SDS">Types, Streams, and retrieving Data -- WaveForm</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                                                          | Covers some typical operations against the SDS, including client credential authentication, creating, updating, and deleting types, streams and events. This uses a non-time Series Type. Some tasks are different from the other "Types, Streams, and retrieving Data" task, so look at the task readme for details. This is a recommended starting example, and a good a base for all other Tasks. <a href="basic_samples/SDS">Details</a>  | <a href="basic_samples/SDS/DotNet/SdsClientLibraries/SdsClientLibraries">.NET Libraries</a><br /><a href="basic_samples/SDS/DotNet/SdsRestApiCore/SdsRestApiCore">.NET REST API</a><br /><a href="basic_samples/SDS/Java/sdsjava">Java</a><br /><a href="basic_samples/SDS/JavaScript/Angular">Angular</a><br /><a href="basic_samples/SDS/JavaScript/NodeJs">NodeJS</a><br /><a href="basic_samples/SDS/Python/SDSPy/Python3">Python</a> | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_DotNet_Libs?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=887&branchName=master) <br /> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_DotNet_REST?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=888&branchName=master) <br /> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_Java?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=920&branchName=master) <br /> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_Angular?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=921&branchName=master) <br /> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_NodeJs?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=924&branchName=master) <br /> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=925&branchName=master) |
| **<a href="basic_samples/SDS_TimeSeries">Types, Streams, and retrieving Data -- Time-Series</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                                            | Covers some typical operations against the SDS, including client credential authentication, creating, and deleting types and streams. This sample is based on Time-Series data. Some tasks are different from the other "Types, Streams, and retrieving Data" task, so look at the task readme for details. This is a recommended starting example, and a good a base for all other Tasks. <a href="basic_samples/SDS_TimeSeries">Details</a> | <a href="basic_samples/SDS_TimeSeries/Python">Python</a> <br /> <a href="basic_samples/SDS_TimeSeries/DotNet/Try">DotNet</a>                                                                                                                                                                                                                                                                                                              | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_TS_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=927&branchName=master) <br /> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_TS_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=926&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **<a href="advanced_samples/UomsSample/Dotnet/UomsSample/UomsSample">UOM</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                                                               | Covers the basic functionality of the UOM system on OCS                                                                                                                                                                                                                                                                                                                                                                                       | <a href="advanced_samples/UomsSample/Dotnet/UomsSample/UomsSample">.NET</a>                                                                                                                                                                                                                                                                                                                                                               | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/UOM_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=928&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **<a href="basic_samples/OmfIngress/DotNet/OmfIngressClientLibraries/OmfIngressClientLibraries">OMF Ingress</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                            | Covers the basic functionality of configuring and using the OMF Ingress                                                                                                                                                                                                                                                                                                                                                                       | <a href="basic_samples/OmfIngress/DotNet/OmfIngressClientLibraries/OmfIngressClientLibraries">.NET</a>                                                                                                                                                                                                                                                                                                                                    | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/OMF_Ing_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=886&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **<a href="library_samples/">Sample Libraries</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                                                                                          | These sample libraries are used as the base for the other samples. They are designed to be straightforward implementations of the REST APIs. They are for use in the samples. <a href="library_samples/">Details</a>                                                                                                                                                                                                                          | <a href="library_samples/Java/ocs_sample_library_preview/">Java</a><br /><a href="library_samples/Python3/">Python</a>                                                                                                                                                                                                                                                                                                                    | ~~~~~~~~~~~~~~~~~~~ <br /> ~~~~~~~~~~~~~~~~~~~                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| <img src="./miscellaneous/images/ctp.png" alt="ctp icon"> **<a href="basic_samples/DataViews/">Data Views</a>** <img src="./miscellaneous/images/app-type-getting-started.png" alt="getting-started icon">                              | These samples highlight basic operations of Data Views for OCS, including creation, updating, getting data from and deletion of Data Views. <a href="basic_samples/DataViews">Details</a>                                                                                                                                                                                                                                                     | <a href="basic_samples/DataViews/Java/dataviewjava">Java</a><br /><a href="basic_samples/DataViews/Python3">Python</a>                                                                                                                                                                                                                                                                                                                    | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/DataViews_Java?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=884&branchName=master) <br /> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/DataViews_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=885&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

~~ These libraries are tested by being used in other apps.

**Note**: Tests with automated UI browser components (such as Hybrid Authentication, Authorization Code Flow and Angular samples) fail intermittently due to automatation issues.

For OMF to OCS samples please see the OMF repository: [OSIsoft-Samples--OMF](https://github.com/osisoft/OSIsoft-Samples--OMF)

## Credentials

A credential file is used in the samples unless otherwise noted in the sample. The name and location of the credential file should be noted in the sample's readme.  
**Note**: This is not a secure way to store credentials. This is to be used at your own risk.  
You will need to modify these files locally when you run the samples.

## About this repo

The [style guide](https://github.com/osisoft/OSI-Samples/blob/master/STYLE_GUIDE.md) describes the organization of the repo and the code samples provided. The [test guide](https://github.com/osisoft/OSI-Samples/blob/master/TEST_GUIDE.md) goes into detail about the included automated tests. The [on prem testing](https://github.com/osisoft/OSI-Samples/blob/master/miscellaneous/ON_PREM_TESTING.md) document describes the software installed on our internal OSIsoft build agent.

## Feedback

If you have a need for a new sample; if there is a feature or capability that should be demonstrated; if there is an existing sample that should be in your favorite language; please reach out to us and give us feedback at https://feedback.osisoft.com under the OSIsoft GitHub Channel. [Feedback](https://feedback.osisoft.com/forums/922279-osisoft-github).

## Support

If your support question or issue is related to something with an OSIsoft product (an error message, a problem with product configuration, etc...), please open a case with OSIsoft Tech Support through myOSIsoft Customer Portal (https://my.osisoft.com).

If your support question or issue is related to a non-modified sample (or test) or documentation for the sample; please email Samples@osisoft.com.

## Contributions

If you wish to contribute please take a look at the [contribution guide](https://github.com/osisoft/OSI-Samples/blob/master/CONTRIBUTING.md).

## License

[OSI Samples](https://github.com/osisoft/OSI-Samples) are licensed under the [Apache 2 license](LICENSE).
