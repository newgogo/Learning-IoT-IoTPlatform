Learning-IoT-IoTPlatform
========================

Source code for the Internet of Things service platforms chapter of the book "Learning Internet of Things".

This chapter covers the basics of how to build services on the Internet of Things service platform Clayster. It shows this by reimplementing the **controller** project, and shows what benefits there are using such a platform.

The source code contains the following projects:

|Project                          | Description|
|:------------------------------- |:---------- |
|**Controller2**                   | The controller project, reimplemented to run under the Clayster Internet of Things service platform. It Controls the actuator based on input received from the sensor.|

The project is developed in C# and compiled using [Xamarin](http://xamarin.com/). It is executed on a Raspberry Pi using [MONO](http://www.mono-project.com/). The project does not use any code specific to the Raspberry Pi, and can therefore be run on any system executing .NET code.

To compile, the project needs you to download a distribution of [ClaysterSmall](http://www.clayster.com/downloads) platform and install it in `C:\Downloads\ClaysterSmall`. If you install it anywhere else, you must update and external references found in the `Controller2\Controller2.csproj` project file locally.

Chapters of the book:

| Chapter | Title                         | Source Code |
| -------:|:----------------------------- |:-----------:|
|         | Preface                       | N/A |
| 1       | Preparing our IoT projects    | N/A |
| 2       | The HTTP Protocol             | [Learning-IoT-HTTP](https://github.com/Clayster/Learning-IoT-HTTP) |
| 3       | The UPnP Protocol             | [Learning-IoT-UPnP](https://github.com/Clayster/Learning-IoT-UPnP) |
| 4       | The CoAP Protocol             | [Learning-IoT-CoAP](https://github.com/Clayster/Learning-IoT-CoAP) |
| 5       | The MQTT Protocol             | [Learning-IoT-MQTT](https://github.com/Clayster/Learning-IoT-MQTT) |
| 6       | The XMPP Protocol             | [Learning-IoT-XMPP](https://github.com/Clayster/Learning-IoT-XMPP) |
| 7       | Using an IoT Service Platform | [Learning-IoT-IoTPlatform](https://github.com/Clayster/Learning-IoT-IoTPlatform) |
| 8       | Creating protocol gateways    | [Learning-IoT-Gateway](https://github.com/Clayster/Learning-IoT-Gateway) |
| 9       | Security and Interoperability | N/A |
