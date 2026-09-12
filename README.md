[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/uhub-awesome-c-sharp-badge.png)](https://mseep.ai/app/uhub-awesome-c-sharp)

# awesome-c-sharp

A curated list of awesome C# frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
	* [Version Control](#version-control)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Computer Vision](#computer-vision)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Date and Time](#date-and-time)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Systems and Hardware
	* [Embedded and Firmware](#embedded-and-firmware)
* Business and Domain
	* [Finance and Trading](#finance-and-trading)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [krahets/hello-algo](https://github.com/krahets/hello-algo) - 《Hello 算法》：动画图解、一键运行的数据结构与算法教程。支持简中、繁中、English、日本語，提供 Python, Java, C++, C, C#, JS, Go, Swift, Rust, Ruby, Kotlin, TS, Dart 等代码实现
* [dotnet/AspNetCore.Docs](https://github.com/dotnet/AspNetCore.Docs) - Documentation for ASP.NET Core
* [coding-horror/basic-computer-games](https://github.com/coding-horror/basic-computer-games) - An updated version of the classic "Basic Computer Games" book, with well-written examples in a variety of common MEMORY SAFE, SCRIPTING programming languages. See https://coding-horror.github.io/basic-computer-games/
* [YSGStudyHards/DotNetGuide](https://github.com/YSGStudyHards/DotNetGuide) - 🌈【C#/.NET/.NET Core学习、工作、面试指南】记录、收集和总结C#/.NET/.NET Core基础知识、学习路线、开发实战、编程技巧练习、学习视频、文章、书籍、项目框架、社区组织、开发必备工具、技术前沿周刊、常见面试题、面试须知、简历模板、人才招聘、以及自己在学习和工作中的一些微薄见解。希望能和大家一起学习，共同进步。如果本知识库能为您提供帮助，别忘了给予支持哦(关注、点赞、分享)💖。
* [davidfowl/AspNetCoreDiagnosticScenarios](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios) - This repository has examples of broken patterns in ASP.NET Core applications
* [thangchung/clean-code-dotnet](https://github.com/thangchung/clean-code-dotnet) - :bathtub: Clean Code concepts and tools adapted for .NET
* [mouredev/one-day-one-language](https://github.com/mouredev/one-day-one-language) - Cómo dar en un día tus primeros pasos en cada lenguaje de programación. Introducción, configuración e instalación, usos habituales, fundamentos, sintaxis y próximos pasos.
* [oskardudycz/EventSourcing.NetCore](https://github.com/oskardudycz/EventSourcing.NetCore) - Examples and Tutorials of Event Sourcing in .NET
* [evolutionary-architecture/evolutionary-architecture-by-example](https://github.com/evolutionary-architecture/evolutionary-architecture-by-example) - Navigate the complex landscape of .NET software architecture with our step-by-step, story-like guide. Unpack the interplay between modular monoliths, microservices, domain-driven design, and various architectural patterns. Go beyond the one-size-fits-all solutions and understand how to blend these approaches based on your unique needs.
* [microsoft/Generative-AI-for-beginners-dotnet](https://github.com/microsoft/Generative-AI-for-beginners-dotnet) - Five lessons, learn how to really apply AI to your .NET Applications
* [MicrosoftLearning/AZ-204-DevelopingSolutionsforMicrosoftAzure](https://github.com/MicrosoftLearning/AZ-204-DevelopingSolutionsforMicrosoftAzure) - AZ-204: Developing solutions for Microsoft Azure *(archived)*
* [sidristij/dotnetbook](https://github.com/sidristij/dotnetbook) - .NET Platform Architecture book (English, Chinese, Russian)
* [dotnet-presentations/dotnet-maui-workshop](https://github.com/dotnet-presentations/dotnet-maui-workshop) - A full day workshop (.NET MAUI Workshop in a Box) on how to build apps with .NET MAUI for iOS, Android, macOS, and Windows
* [microsoft/WhatTheHack](https://github.com/microsoft/WhatTheHack) - A collection of challenge based hack-a-thons including student guide, coach guide, lecture presentations, sample/instructional code and templates. Please visit the What The Hack website at: https://aka.ms/wth
* [Almantask/CSharp-From-Zero-To-Hero](https://github.com/Almantask/CSharp-From-Zero-To-Hero) - C# boot camp
* [stella3d/job-system-cookbook](https://github.com/stella3d/job-system-cookbook) - this is a guide to the Unity job system circa 2019
* [mvelazc0/defcon27_csharp_workshop](https://github.com/mvelazc0/defcon27_csharp_workshop) - Writing custom backdoor payloads with C# - Defcon 27 Workshop
* [swharden/Csharp-Data-Visualization](https://github.com/swharden/Csharp-Data-Visualization) - Resources for visualizing data using C# and the .NET platform
* [CodeMazeBlog/CodeMazeGuides](https://github.com/CodeMazeBlog/CodeMazeGuides) - The main repository for all the Code Maze guides
* [head-first-csharp/fourth-edition](https://github.com/head-first-csharp/fourth-edition) - Code and graphics for the projects in the 4th edition of Head First C#
* [dotnetzoom/AspNetCore-WebApi-Course](https://github.com/dotnetzoom/AspNetCore-WebApi-Course) - 🥇 Professional REST API design with ASP.NET Core WebAPI
* [OfficeDev/TrainingContent](https://github.com/OfficeDev/TrainingContent) - Training Content used for developer.microsoft.com/office *(archived)*
* [markjprice/cs10dotnet6](https://github.com/markjprice/cs10dotnet6) - Repository for the Packt Publishing book titled "C# 10 and .NET 6 - Modern Cross-Platform Development" by Mark J. Price
* [dotnet/csharpstandard](https://github.com/dotnet/csharpstandard) - Working space for ECMA-TC49-TG2, the C# standard committee.
* [markjprice/cs12dotnet8](https://github.com/markjprice/cs12dotnet8) - Repository for the Packt Publishing book titled "C# 12 and .NET 8 - Modern Cross-Platform Development Fundamentals" by Mark J. Price
* [MinaPecheux/UnityTutorials-RTS](https://github.com/MinaPecheux/UnityTutorials-RTS) - The code for my series of tutorials on how to make a real-time stategy (RTS) game in the well-know Unity game engine (with C# scripting)!
* [dotnet/intro-to-dotnet-web-dev](https://github.com/dotnet/intro-to-dotnet-web-dev) - Get Started as a Web Developer with .NET, C#, and ASP.NET Core
* [csharpfritz/csharp_with_csharpfritz](https://github.com/csharpfritz/csharp_with_csharpfritz) - Show notes, slides, and samples from the CSharp with CSharpFritz show
* [PacktPublishing/Hands-On-Domain-Driven-Design-with-.NET-Core](https://github.com/PacktPublishing/Hands-On-Domain-Driven-Design-with-.NET-Core) - Hands-On Domain-Driven Design with .NET Core, published by Packt
* [binarythistle/S04E03---.NET-Microservices-Course-](https://github.com/binarythistle/S04E03---.NET-Microservices-Course-) - Code for the Introduction to .NET Microservices
* [exceptionnotfound/DesignPatterns](https://github.com/exceptionnotfound/DesignPatterns) - Come learn about all the Gang of Four patterns (e.g. Adapter, Facade, Strategy, Mediator, Command and more) with C# and food examples!
* [la-yumba/functional-csharp-code](https://github.com/la-yumba/functional-csharp-code) - Code samples for Functional Programming in C#
* [dotnetcore/aspnetcore-doc-cn](https://github.com/dotnetcore/aspnetcore-doc-cn) - The Simplified Chinese edition of Microsoft ASP.NET Core documentation, translated by .NET Core Community and .NET China Community.

### Examples and Exercises

* [dotnet-architecture/eShopOnContainers](https://github.com/dotnet-architecture/eShopOnContainers) - Cross-platform .NET sample microservices and container based application that runs on Linux Windows and macOS. Powered by .NET 7, Docker Containers and Azure Kubernetes Services. Supports Visual Studio, VS for Mac and CLI based environments with Docker CLI, dotnet CLI, VS Code or any other code editor. Moved to https://github.com/dotnet/eShop. *(archived)*
* [jasontaylordev/CleanArchitecture](https://github.com/jasontaylordev/CleanArchitecture) - Clean Architecture Solution Template for ASP.NET Core
* [ardalis/CleanArchitecture](https://github.com/ardalis/CleanArchitecture) - Clean Architecture Solution Template: A proven Clean Architecture Template for ASP.NET Core 10
* [kgrzybek/modular-monolith-with-ddd](https://github.com/kgrzybek/modular-monolith-with-ddd) - Full Modular Monolith application with Domain-Driven Design approach.
* [dotnet/eShop](https://github.com/dotnet/eShop) - A reference .NET application implementing an eCommerce site
* [dotnet-architecture/eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - Sample ASP.NET Core 8.0 reference application, now community supported: https://github.com/NimblePros/eShopOnWeb *(archived)*
* [dodyg/practical-aspnetcore](https://github.com/dodyg/practical-aspnetcore) - Practical samples of ASP.NET Core 11, 10, 9, 8.0, 7.0, 6.0, 5.0, 3.1, 2.2, and 2.1,projects you can use. Readme contains explanations on all projects.
* [XINCGer/Unity3DTraining](https://github.com/XINCGer/Unity3DTraining) - 【Unity杂货铺】unity大杂烩~
* [TheAlgorithms/C-Sharp](https://github.com/TheAlgorithms/C-Sharp) - All algorithms implemented in C#.
* [Unity-Technologies/EntityComponentSystemSamples](https://github.com/Unity-Technologies/EntityComponentSystemSamples)
* [microsoft/ailab](https://github.com/microsoft/ailab) - Experience, Learn and Code the latest breakthrough innovations with Microsoft AI
* [EduardoPires/EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - Web Application ASP.NET 9 using Clean Architecture, DDD, CQRS, Event Sourcing and a lot of good practices
* [fullstackhero/dotnet-starter-kit](https://github.com/fullstackhero/dotnet-starter-kit) - Production Grade Cloud-Ready .NET 10 Starter Kit (Web API + React Client) with Multitenancy Support, and Clean/Modular Architecture that saves roughly 200+ Development Hours! All Batteries Included.
* [aalhour/C-Sharp-Algorithms](https://github.com/aalhour/C-Sharp-Algorithms) - :books: :chart_with_upwards_trend: Plug-and-play class-library project of standard Data Structures and Algorithms in C#
* [dockersamples/example-voting-app](https://github.com/dockersamples/example-voting-app) - Example distributed app composed of multiple containers for Docker, Compose, Swarm, and Kubernetes
* [microsoft/WPF-Samples](https://github.com/microsoft/WPF-Samples) - Repository for WPF related samples
* [anjoy8/Blog.Core](https://github.com/anjoy8/Blog.Core) - 💖 ASP.NET Core 8.0 全家桶教程，前后端分离后端接口，vue教程姊妹篇，官方文档：
* [Unity-Technologies/FPSSample](https://github.com/Unity-Technologies/FPSSample) - A first person multiplayer shooter example project in Unity
* [jasontaylordev/NorthwindTraders](https://github.com/jasontaylordev/NorthwindTraders) - Northwind Traders is a sample application built using ASP.NET Core and Entity Framework Core. *(archived)*
* [QianMo/Unity-Design-Pattern](https://github.com/QianMo/Unity-Design-Pattern) - :tea: All Gang of Four Design Patterns written in Unity C# with many examples. And some Game Programming Patterns written in Unity C#. | 各种设计模式的Unity3D C#版本实现
* [UnityCommunity/UnityLibrary](https://github.com/UnityCommunity/UnityLibrary) - :books: Library of all kind of scripts, snippets & shaders for Unity
* [ivanpaulovich/clean-architecture-manga](https://github.com/ivanpaulovich/clean-architecture-manga) - :cyclone: Clean Architecture with .NET6, C#10 and React+Redux. Use cases as central organizing structure, completely testable, decoupled from frameworks
* [xamarin/xamarin-forms-samples](https://github.com/xamarin/xamarin-forms-samples) - Sample apps built using the Xamarin.Forms framework *(archived)*
* [dotnet/samples](https://github.com/dotnet/samples) - Sample code referenced by the .NET documentation
* [dotnet/maui-samples](https://github.com/dotnet/maui-samples) - Samples for .NET Multi-Platform App UI (.NET MAUI)
* [microsoft/WinUI-Gallery](https://github.com/microsoft/WinUI-Gallery) - This app demonstrates the controls available in WinUI and the Fluent Design System.
* [fullstackhero/blazor-starter-kit](https://github.com/fullstackhero/blazor-starter-kit) - Clean Architecture Template for Blazor WebAssembly Built with MudBlazor Components.
* [Dotnet-Boxed/Templates](https://github.com/Dotnet-Boxed/Templates) - .NET project templates with batteries included, providing the minimum amount of code required to get you going faster.
* [Azure-Samples/cognitive-services-speech-sdk](https://github.com/Azure-Samples/cognitive-services-speech-sdk) - Sample code for the Microsoft Cognitive Services Speech SDK
* [microsoft/referencesource](https://github.com/microsoft/referencesource) - Source from the Microsoft .NET Reference Source that represent a subset of the .NET Framework
* [Unity-Technologies/arfoundation-samples](https://github.com/Unity-Technologies/arfoundation-samples) - Example content for Unity projects based on AR Foundation
* [rafaelfgx/Architecture](https://github.com/rafaelfgx/Architecture) - .NET 10, Angular 22, Clean Architecture, Clean Code, SOLID, KISS, DRY, Mediator Pattern, Folder-by-Feature Structure
* [aspnetrun/run-aspnetcore-microservices](https://github.com/aspnetrun/run-aspnetcore-microservices) - Microservices on .NET platforms used ASP.NET Web API, Docker, RabbitMQ, MassTransit, Grpc, Yarp API Gateway, PostgreSQL, Redis, SQLite, SqlServer, Marten, Entity Framework Core, CQRS, MediatR, DDD, Vertical and Clean Architecture implementation with using latest features of .NET 8 and C# 12
* [davidfowl/TodoApp](https://github.com/davidfowl/TodoApp) - Todo application with ASP.NET Core Blazor WASM, Minimal APIs and Authentication
* [kgrzybek/sample-dotnet-core-cqrs-api](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - Sample .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.
* [abishekaditya/DesignPatterns](https://github.com/abishekaditya/DesignPatterns) - Project : Design Patterns Examples in C#
* [Unity-Technologies/BoatAttack](https://github.com/Unity-Technologies/BoatAttack) - Demo Project using the Universal RP from Unity3D
* [microsoft/dotnet-podcasts](https://github.com/microsoft/dotnet-podcasts) - .NET reference application shown at .NET Conf featuring ASP.NET Core, Blazor, .NET MAUI, Microservices, Orleans, Playwright, and more! *(archived)*
* [lerocha/chinook-database](https://github.com/lerocha/chinook-database) - Sample database for SQL Server, Oracle, MySQL, PostgreSQL, SQLite, DB2
* [LazoVelko/Windows-Hacks](https://github.com/LazoVelko/Windows-Hacks) - Creative and unusual things that can be done with the Windows API.
* [vietnam-devs/coolstore-microservices](https://github.com/vietnam-devs/coolstore-microservices) - A full-stack .NET microservices build on Dapr and Tye
* [phongnguyend/Practical.CleanArchitecture](https://github.com/phongnguyend/Practical.CleanArchitecture) - Full-stack .Net 10 Clean Architecture (Microservices, Modular Monolith, Monolith), Blazor, Angular 22, React 19, Vue 3.5, BFF with YARP, NextJs 16, Domain-Driven Design, CQRS, SOLID, Asp.Net Core Identity Custom Storage, OpenID Connect, EF Core, OpenTelemetry, SignalR, Background Services, Health Checks, Rate Limiting, Clouds (Azure, AWS, GCP), ...
* [wesdoyle/design-patterns-explained-with-food](https://github.com/wesdoyle/design-patterns-explained-with-food) - GoF Design Patterns with "Real-World" examples involving Food-Related Businesses and mock dependencies
* [Unity-Technologies/UniversalRenderingExamples](https://github.com/Unity-Technologies/UniversalRenderingExamples) - This project contains a collection of Custom Renderer examples. This will be updated as we refine the feature and add more options.
* [dotnet/android-samples](https://github.com/dotnet/android-samples) - A collection of .NET for Android sample projects
* [gregoryyoung/m-r](https://github.com/gregoryyoung/m-r) - Simple CQRS example
* [nemanjarogic/DesignPatternsLibrary](https://github.com/nemanjarogic/DesignPatternsLibrary) - A comprehensive design patterns library implemented in C#, which covers various design patterns from the most commonly used ones to the lesser-known ones. Get familiar with and learn design patterns through moderately realistic examples.
* [maniero/SOpt](https://github.com/maniero/SOpt) - Códigos soltos usados em respostas minhas no Stack Overflow em português
* [MichalStrehovsky/zerosharp](https://github.com/MichalStrehovsky/zerosharp) - Demo of the potential of C# for systems programming with the .NET native ahead-of-time compilation technology.
* [Unity-Technologies/VisualEffectGraph-Samples](https://github.com/Unity-Technologies/VisualEffectGraph-Samples) - Visual Effect Graph - Samples Project
* [DrFlower/TowerDefense-GameFramework-Demo](https://github.com/DrFlower/TowerDefense-GameFramework-Demo) - 基于Unity开源框架GameFramewrk实现的一款塔防游戏Demo
* [Habrador/Unity-Programming-Patterns](https://github.com/Habrador/Unity-Programming-Patterns) - Implementations of programming design patterns in Unity with examples in C# when to use them.
* [realworld-apps/aspnetcore-realworld-example-app](https://github.com/realworld-apps/aspnetcore-realworld-example-app) - ASP.NET Core backend implementation for RealWorld
* [Unity-Technologies/com.unity.multiplayer.samples.coop](https://github.com/Unity-Technologies/com.unity.multiplayer.samples.coop) - A small-scale cooperative game sample built on the new, Unity networking framework to teach developers about creating a similar multiplayer game.
* [keijiro/Voxelman](https://github.com/keijiro/Voxelman) - Unity DOTS/ECS example
* [microsoft/PowerApps-Samples](https://github.com/microsoft/PowerApps-Samples) - Sample code for Power Apps, including Dataverse, model-driven apps, canvas apps, Power Apps component framework, portals, and AI Builder.
* [amantinband/clean-architecture](https://github.com/amantinband/clean-architecture) - The ultimate clean architecture template for .NET applications 💪
* [pnp/PnP](https://github.com/pnp/PnP) - SharePoint / Office 365 Developer Patterns and Practices - Archived older solutions. Please see https://aka.ms/m365pnp for updated guidance *(archived)*
* [XINCGer/UnityToolchainsTrick](https://github.com/XINCGer/UnityToolchainsTrick) - 提供一些UnityEditor工具链开发的常用小技巧与示例(Provides some common tips and examples for developing the UnityEditor toolchain)
* [zkavtaskin/Domain-Driven-Design-Example](https://github.com/zkavtaskin/Domain-Driven-Design-Example) - Blog series supplementary domain-driven design C# repository that (hopefully) actually makes sense.
* [jbogard/ContosoUniversityDotNetCore-Pages](https://github.com/jbogard/ContosoUniversityDotNetCore-Pages) - With Razor Pages
* [fullstackproltd/AspNetCoreSpa](https://github.com/fullstackproltd/AspNetCoreSpa) - Asp.Net 7.0 & Angular 15 SPA Fullstack application with plenty of examples. Live demo:
* [iammukeshm/CleanArchitecture.WebApi](https://github.com/iammukeshm/CleanArchitecture.WebApi) - An implementation of Clean Architecture for ASP.NET Core 3.1 WebAPI. Built with loosely coupled architecture and clean-code practices in mind.
* [chvancooten/OSEP-Code-Snippets](https://github.com/chvancooten/OSEP-Code-Snippets) - A repository with my notable code snippets for Offensive Security's PEN-300 (OSEP) course.
* [dathlin/ClientServerProject](https://github.com/dathlin/ClientServerProject) - 一个C-S模版，该模版由三部分的程序组成，一个服务端运行的程序，一个客户端运行的程序，还有一个公共的组件，实现了基础的账户管理功能，版本控制，软件升级，公告管理，消息群发，共享文件上传下载，批量文件传送功能。具体的操作方法见演示就行。本项目的一个目标是：提供一个基础的中小型系统的C-S框架，客户端有三种模式，无缝集成访问，winform版本，wpf版本，asp.net mvc版本，方便企业进行中小型系统的二次开发和个人学习。同时网络组件方便的支持读写三菱和西门子PLC的数据，详细见Readme
* [OfficeDev/Microsoft-Teams-Samples](https://github.com/OfficeDev/Microsoft-Teams-Samples) - Welcome to the Microsoft Teams samples repository. Here you will find task-focused samples in C#, JavaScript and TypeScript to help you get started with the Microsoft Teams App!
* [microsoftarchive/cqrs-journey](https://github.com/microsoftarchive/cqrs-journey) - Microsoft patterns & pratices CQRS Journey sample application *(archived)*
* [meysamhadeli/booking-microservices](https://github.com/meysamhadeli/booking-microservices) - A practical microservices with the latest technologies and architectures like Vertical Slice Architecture, Event Sourcing, CQRS, DDD, gRpc, MongoDB, RabbitMq, Wolverine, and Aspire in .Net 10.
* [thangchung/clean-architecture-dotnet](https://github.com/thangchung/clean-architecture-dotnet) - 🕸 Yet Another .NET Clean Architecture, but for Microservices project. It uses Minimal Clean Architecture with DDD-lite, CQRS-lite, and just enough Cloud-native patterns apply on the simple eCommerce sample and run on Tye with Dapr extension 🍻
* [unity3d-jp/unitychan-crs](https://github.com/unity3d-jp/unitychan-crs) - Unity-Chan "Candy Rock Star" Live Demo
* [neozhu/CleanArchitectureWithBlazorServer](https://github.com/neozhu/CleanArchitectureWithBlazorServer) - This repository is designed to create an enterprise Blazor Server application that follows the principles of Clean Architecture and implements Blazor Clean Architecture best practices for scalability, maintainability, and testability.
* [matthewrenze/clean-architecture-demo](https://github.com/matthewrenze/clean-architecture-demo) - A sample app for my online course "Clean Architecture: Patterns, Practices, and Principles"
* [Naphier/unity-design-patterns](https://github.com/Naphier/unity-design-patterns) - Examples of programming design patterns in Unity C#
* [NikolayIT/ASP.NET-Core-Template](https://github.com/NikolayIT/ASP.NET-Core-Template) - A ready-to-use template for ASP.NET Core with repositories, services, models mapping, DI and StyleCop warnings fixed.
* [microsoft/WindowsCompositionSamples](https://github.com/microsoft/WindowsCompositionSamples) - The Windows Composition Samples have moved here: https://github.com/microsoft/WindowsAppSDK-Samples/tree/main/Samples/SceneGraph *(archived)*
* [sheng-jie/Design-Pattern](https://github.com/sheng-jie/Design-Pattern) - 设计模式 C# 版（ .NET 6），有系列文章讲解
* [microsoft/Cognitive-Samples-IntelligentKiosk](https://github.com/microsoft/Cognitive-Samples-IntelligentKiosk) - Welcome to the Intelligent Kiosk Sample! Here you will find several demos showcasing workflows and experiences built on top of the Microsoft Cognitive Services. *(archived)*
* [dotnet/dotnet-console-games](https://github.com/dotnet/dotnet-console-games) - Game examples implemented as .NET console applications primarily for providing education and inspiration. :)
* [Azure-Samples/Cognitive-Speech-TTS](https://github.com/Azure-Samples/Cognitive-Speech-TTS) - Microsoft Text-to-Speech API sample code in several languages, part of Cognitive Services.
* [RefactoringGuru/design-patterns-csharp](https://github.com/RefactoringGuru/design-patterns-csharp) - Design Pattern Examples in C#
* [aspnetboilerplate/module-zero-core-template](https://github.com/aspnetboilerplate/module-zero-core-template) - ASP.NET Core MVC / Angular Startup Project For ASP.NET Boilerplate
* [VaughnVernon/IDDD_Samples_NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon: http://vaughnvernon.co/?page_id=168
* [Amitpnk/Onion-architecture-ASP.NET-Core](https://github.com/Amitpnk/Onion-architecture-ASP.NET-Core) - WhiteApp API solution template which is built on Onion Architecture with all essential feature using .NET 8!
* [ntxinh/AspNetCore-DDD](https://github.com/ntxinh/AspNetCore-DDD) - Full ASP.NET Core 10.0 LTS application with DDD, CQRS and Event Sourcing
* [Azure-Samples/cloud-design-patterns](https://github.com/Azure-Samples/cloud-design-patterns) - Sample implementations for cloud design patterns found in the Azure Architecture Center.
* [Azure-Samples/azure-search-openai-demo-csharp](https://github.com/Azure-Samples/azure-search-openai-demo-csharp) - A sample app for the Retrieval-Augmented Generation pattern running in Azure, using Azure Cognitive Search for retrieval and Azure OpenAI large language models to power ChatGPT-style and Q&A experiences.
* [SteveSandersonMS/CarChecker](https://github.com/SteveSandersonMS/CarChecker) - A sample Blazor WebAssembly application that includes authentication, in-browser data storage, offline support, localization, responsive layouts, and more. For a video walkthrough, see this link:
* [ardalis/CleanArchitecture.WorkerService](https://github.com/ardalis/CleanArchitecture.WorkerService) - A solution template using Clean Architecture for building a .NET Core Worker Service.
* [mixandjam/Celeste-Movement](https://github.com/mixandjam/Celeste-Movement) - Recreating the movement and feel from Celeste
* [ellioman/Indirect-Rendering-With-Compute-Shaders](https://github.com/ellioman/Indirect-Rendering-With-Compute-Shaders) - An example of drawing numerous instances using Unity3D, compute shaders and Graphics.DrawMeshInstancedIndirect with Frustum & Occlusion culling and LOD'ing.
* [ardalis/kata-catalog](https://github.com/ardalis/kata-catalog) - My list of code katas
* [iayti/CleanArchitecture](https://github.com/iayti/CleanArchitecture) - ASP.NET Core 6 Web API Clean Architecture Solution Template
* [dathlin/HslControlsDemo](https://github.com/dathlin/HslControlsDemo) - HslControls控件库的使用demo，HslControls是一个工业物联网的控件库，基于C#开发，配套HslCommunication组件可以实现工业上位机软件的快速开发，支持常用的工业图形化控件，快速的集成界面开发。 主要包含了按钮，开关，进度条，信号灯，数码管，时钟，曲线显示控件，仪表盘控件，管道控件，瓶子控件，饼图控件，传送带控件，温度计控件，鼓风机控件，阀门控件，电池控件等等。
* [garora/TDD-Katas](https://github.com/garora/TDD-Katas) - This repository contains Hands on Test Driven Development Katas (C#)
* [xamarinhq/app-conference](https://github.com/xamarinhq/app-conference) - Pre-build conference application built with Xamarin *(archived)*
* [TelegramBots/Telegram.Bot.Examples](https://github.com/TelegramBots/Telegram.Bot.Examples) - Examples for the Telegram.Bot C# Library
* [anjoy8/ChristDDD](https://github.com/anjoy8/ChristDDD) - 🙌 ASP.NET Core 3.1 应用, 包含 DDD、CQRS、EDA 和ES事件回溯
* [madslundt/NetCoreMicroservicesSample](https://github.com/madslundt/NetCoreMicroservicesSample) - Sample using micro services in .NET Core 3.1 Focusing on clean code
* [Elfocrash/clean-minimal-api](https://github.com/Elfocrash/clean-minimal-api) - A project showcasing how you can build a clean Minimal API using FastEndpoints
* [cinight/CustomSRP](https://github.com/cinight/CustomSRP) - Many mini-custom-SRPs showing how to achieve different things when creating your own SRP. Only SRP Core package is needed.
* [cornflourblue/aspnet-core-3-jwt-authentication-api](https://github.com/cornflourblue/aspnet-core-3-jwt-authentication-api) - ASP.NET Core 3.1 JWT Authentication API
* [bradymholt/aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) - ASP.NET Core 3.1 / React SPA Template App
* [yilezhu/Czar.Cms](https://github.com/yilezhu/Czar.Cms) - .NET Core实战项目之CMS系列教程的源码，精简而又功能丰富的权限设计，内容管理设计让你轻松搭建一个ASP.NET Core2.2的网站系统.此项目准备用EFCore进行重构，敬请期待

## Language and Tooling

### Compilers and Interpreters

* [dotnet/roslyn](https://github.com/dotnet/roslyn) - The Roslyn .NET compiler provides C# and Visual Basic languages with rich code analysis APIs.
* [dotnet/runtime](https://github.com/dotnet/runtime) - .NET is a cross-platform runtime for cloud, mobile, desktop, and IoT apps.
* [dotnet/csharplang](https://github.com/dotnet/csharplang) - The official repo for the design of the C# programming language
* [mono/mono](https://github.com/mono/mono) - Mono open source ECMA CLI, C# and .NET implementation.
* [pythonnet/pythonnet](https://github.com/pythonnet/pythonnet) - Python for .NET is a package that gives Python programmers nearly seamless integration with the .NET Common Language Runtime (CLR) and provides a powerful application scripting tool for .NET developers.
* [inkle/ink](https://github.com/inkle/ink) - inkle's open source scripting language for writing interactive narrative.
* [sebastienros/jint](https://github.com/sebastienros/jint) - Javascript Interpreter for .NET
* [bflattened/bflat](https://github.com/bflattened/bflat) - C# as you know it but with Go-inspired tooling (small, selfcontained, and native executables)
* [mono/CppSharp](https://github.com/mono/CppSharp) - Tools and libraries to glue C/C++ APIs to high-level languages
* [microsoft/Power-Fx](https://github.com/microsoft/Power-Fx) - Power Fx low-code programming language
* [waf/CSharpRepl](https://github.com/waf/CSharpRepl) - A command line C# REPL with syntax highlighting – explore the language, libraries and nuget packages interactively.
* [Ourpalm/ILRuntime](https://github.com/Ourpalm/ILRuntime) - Pure C# IL Intepreter Runtime, which is fast and reliable for scripting requirement on enviorments, where jitting isn't possible.
* [topameng/tolua](https://github.com/topameng/tolua) - The fastest unity lua binding solution
* [jbevain/cecil](https://github.com/jbevain/cecil) - Cecil is a library to inspect, modify and create .NET programs and libraries.
* [ashmind/SharpLab](https://github.com/ashmind/SharpLab) - .NET language playground
* [TheBerkin/rant3](https://github.com/TheBerkin/rant3) - (Obsolete) Archive of Rant 3.x. *(archived)*
* [dotnet/corert](https://github.com/dotnet/corert) - This repo contains CoreRT, an experimental .NET Core runtime optimized for AOT (ahead of time compilation) scenarios, with the accompanying compiler toolchain. *(archived)*
* [IronLanguages/ironpython3](https://github.com/IronLanguages/ironpython3) - Implementation of Python 3.x for .NET Framework that is built on top of the Dynamic Language Runtime.
* [peachpiecompiler/peachpie](https://github.com/peachpiecompiler/peachpie) - PeachPie - the PHP compiler and runtime for .NET and .NET Core
* [NLua/NLua](https://github.com/NLua/NLua) - Bridge between Lua and the .NET.
* [dynamicexpresso/DynamicExpresso](https://github.com/dynamicexpresso/DynamicExpresso) - C# expressions interpreter
* [ClearFoundry/ClearScript](https://github.com/ClearFoundry/ClearScript) - A library for adding scripting to .NET applications. Supports V8 (Windows, Linux, macOS) and JScript/VBScript (Windows).
* [fusionlanguage/fut](https://github.com/fusionlanguage/fut) - Fusion programming language. Transpiling to C, C++, C#, D, Java, JavaScript, Python, Swift, TypeScript and OpenCL C.
* [clojure/clojure-clr](https://github.com/clojure/clojure-clr) - A port of Clojure to the CLR, part of the Clojure project
* [moonsharp-devs/moonsharp](https://github.com/moonsharp-devs/moonsharp) - An interpreter for the Lua language, written entirely in C# for the .NET, Mono, Xamarin and Unity3D platforms, including handy remote debugger facilities.
* [dotnetcore/Natasha](https://github.com/dotnetcore/Natasha) - 基于 Roslyn 的 C# 动态程序集构建库，该库允许开发者在运行时使用 C# 代码构建域 / 程序集 / 类 / 结构体 / 枚举 / 接口 / 方法等，使得程序在运行的时候可以增加新的模块及功能。Natasha 集成了域管理/插件管理，可以实现域隔离，域卸载，热拔插等功能。 该库遵循完整的编译流程，提供完整的错误提示， 可自动添加引用，完善的数据结构构建模板让开发者只专注于程序集脚本的编写，兼容 stanadard2.0 / netcoreapp3.0+, 跨平台，统一、简便的链式 API。 且我们会尽快修复您的问题及回复您的 issue.
* [yanghuan/CSharp.lua](https://github.com/yanghuan/CSharp.lua) - The C# to Lua compiler
* [dotnet/ClangSharp](https://github.com/dotnet/ClangSharp) - Clang bindings for .NET written in C#
* [terrajobst/minsk](https://github.com/terrajobst/minsk) - This repo contains Minsk, a handwritten compiler in C#. It illustrates basic concepts of compiler construction and how one can tool the language inside of an IDE by exposing APIs for parsing and type checking.
* [xebecnan/UniLua](https://github.com/xebecnan/UniLua) - A pure c# implementation of Lua 5.2 focus on compatibility with Unity
* [tonybaloney/CSnakes](https://github.com/tonybaloney/CSnakes) - Embed Python in .NET
* [KirillOsenkov/RoslynQuoter](https://github.com/KirillOsenkov/RoslynQuoter) - Roslyn tool that for a given C# program shows syntax tree API calls to construct its syntax tree
* [dotnet/LLVMSharp](https://github.com/dotnet/LLVMSharp) - LLVM bindings for .NET Standard written in C# using ClangSharp
* [icsharpcode/CodeConverter](https://github.com/icsharpcode/CodeConverter) - Convert code from C# to VB.NET and vice versa using Roslyn
* [elringus/bootsharp](https://github.com/elringus/bootsharp) - Use C# in web apps with comfort
* [mono/Embeddinator-4000](https://github.com/mono/Embeddinator-4000) - Tools to turn .NET libraries into native libraries that can be consumed on Android, iOS, Mac, Linux and other platforms. *(archived)*
* [MerlinVR/UdonSharp](https://github.com/MerlinVR/UdonSharp) - An experimental compiler for compiling C# to Udon assembly
* [antiufo/roslyn-linq-rewrite](https://github.com/antiufo/roslyn-linq-rewrite) - Compiles C# code by first rewriting the syntax trees of LINQ expressions using plain procedural code, minimizing allocations and dynamic dispatch.
* [microsoft/qsharp-compiler](https://github.com/microsoft/qsharp-compiler) - Q# compiler, command line tool, and Q# language server *(archived)*
* [nikhilk/scriptsharp](https://github.com/nikhilk/scriptsharp) - Script# Project - a C# to JavaScript compiler, to power your HTML5 and Node.js web development.
* [codingseb/ExpressionEvaluator](https://github.com/codingseb/ExpressionEvaluator) - A Simple Math and Pseudo C# Expression Evaluator in One C# File. Can also execute small C# like scripts
* [anydream/il2cpp](https://github.com/anydream/il2cpp) - A MSIL/C# to C++ converter. Faster than CoreCLR with low memory overhead.(已弃坑.C#是个好语言,然而.NET不是一个干净的平台)

### Build Systems

* [dotnet/msbuild](https://github.com/dotnet/msbuild) - The Microsoft Build Engine (MSBuild) is the build platform for .NET and Visual Studio.
* [Fody/Fody](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies
* [cake-build/cake](https://github.com/cake-build/cake) - :cake: Cake (C# Make) is a cross platform build automation system.
* [nuke-build/nuke](https://github.com/nuke-build/nuke) - 🏗 The AKEless Build System for C#/.NET
* [dotnet/sdk](https://github.com/dotnet/sdk) - Core functionality needed to create .NET Core projects, that is shared between Visual Studio and CLI
* [Fody/Costura](https://github.com/Fody/Costura) - Embed references as resources
* [EWSoftware/SHFB](https://github.com/EWSoftware/SHFB) - Sandcastle Help File Builder (SHFB). A standalone GUI, Visual Studio integration package, and MSBuild tasks providing full configuration and extensibility for building help files with the Sandcastle tools.
* [dotnet/try-convert](https://github.com/dotnet/try-convert) - Helping .NET developers port their projects to .NET Core! *(archived)*
* [ubisoft/Sharpmake](https://github.com/ubisoft/Sharpmake) - Sharpmake is an open-source C#-based solution for generating project definition files, such as Visual Studio projects and solutions, GNU makefiles, Xcode projects, etc.
* [hvanbakel/CsprojToVs2017](https://github.com/hvanbakel/CsprojToVs2017) - Tooling for converting pre 2017 project to the new Visual Studio 2017 format.
* [dotnetcore/FlubuCore](https://github.com/dotnetcore/FlubuCore) - A cross platform build and deployment automation system for building projects and executing deployment scripts using C# code.
* [daveaglick/Scripty](https://github.com/daveaglick/Scripty) - Tools to let you use Roslyn-powered C# scripts for code generation
* [umeng/umeng-muti-channel-build-tool](https://github.com/umeng/umeng-muti-channel-build-tool) - 友盟渠道打包工具(windows .net 4.0)
* [dotnetcore/SmartCode](https://github.com/dotnetcore/SmartCode) - SmartCode = IDataSource -> IBuildTask -> IOutput => Build Everything!!!
* [frhagn/Typewriter](https://github.com/frhagn/Typewriter) - Automatic TypeScript template generation from C# source files
* [andrewdavey/cassette](https://github.com/andrewdavey/cassette) - Manages .NET web application assets (scripts, css and templates)

### Package Management

* [Devolutions/UniGetUI](https://github.com/Devolutions/UniGetUI) - UniGetUI: The Graphical Interface for your package managers. Could be terribly described as a package manager manager to manage your package managers
* [chocolatey/choco](https://github.com/chocolatey/choco) - Chocolatey - the package manager for Windows
* [GlitchEnzo/NuGetForUnity](https://github.com/GlitchEnzo/NuGetForUnity) - A NuGet Package Manager for Unity
* [ravibpatel/AutoUpdater.NET](https://github.com/ravibpatel/AutoUpdater.NET) - AutoUpdater.NET is a class library that allows .NET developers to easily add auto update functionality to their classic desktop application projects.
* [loic-sharma/BaGet](https://github.com/loic-sharma/BaGet) - A lightweight NuGet and symbol server
* [NuGetPackageExplorer/NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - Create, update and deploy Nuget Packages with a GUI
* [wixtoolset/wix3](https://github.com/wixtoolset/wix3) - WiX Toolset v3.x *(archived)*
* [OneGet/oneget](https://github.com/OneGet/oneget) - PackageManagement (aka OneGet) is a package manager for Windows
* [velopack/velopack](https://github.com/velopack/velopack) - Installer and automatic update framework for cross-platform desktop applications
* [oleg-shilo/wixsharp](https://github.com/oleg-shilo/wixsharp) - Framework for building a complete MSI or WiX source code by using script files written with C# syntax.
* [microsoft/artifacts-credprovider](https://github.com/microsoft/artifacts-credprovider) - The Azure Artifacts Credential Provider enables dotnet, NuGet.exe, and MSBuild to interactively acquire credentials for Azure Artifacts feeds.
* [NuGet/NuGet.Client](https://github.com/NuGet/NuGet.Client) - Client Tools for NuGet - including Visual Studio extensions, command line tools, and msbuild support. (Open issues on https://github.com/nuget/home/issues)
* [dotnet/cli-lab](https://github.com/dotnet/cli-lab) - A guided tool will be provided to enable the controlled clean up of a system such that only the desired versions of the Runtime and SDKs remain.

### Linters and Formatters

* [dotnet/roslynator](https://github.com/dotnet/roslynator) - Roslynator is a set of code analysis tools for C#, powered by Roslyn.
* [DotNetAnalyzers/StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - An implementation of StyleCop rules using the .NET Compiler Platform
* [belav/csharpier](https://github.com/belav/csharpier) - CSharpier is an opinionated code formatter for c#.
* [PowerShell/PSScriptAnalyzer](https://github.com/PowerShell/PSScriptAnalyzer) - Download ScriptAnalyzer from PowerShellGallery
* [StyleCop/StyleCop](https://github.com/StyleCop/StyleCop) - Analyzes C# source code to enforce a set of style and consistency rules.
* [dotnet/codeformatter](https://github.com/dotnet/codeformatter) - Tool that uses Roslyn to automatically rewrite the source to follow our coding styles *(archived)*
* [meziantou/Meziantou.Analyzer](https://github.com/meziantou/Meziantou.Analyzer) - A powerful C# Roslyn analyzer that uses static analysis to detect bugs, surface security issues, and enforce best practices—helping developers and AI write more reliable code.
* [code-cracker/code-cracker](https://github.com/code-cracker/code-cracker) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
* [SergeyTeplyakov/ErrorProne.NET](https://github.com/SergeyTeplyakov/ErrorProne.NET) - Set of roslyn-based analyzers for catching common C# errors (inspired by Google's error-prone)
* [SonarSource/sonar-dotnet](https://github.com/SonarSource/sonar-dotnet) - Code analyzer for C# and VB.NET projects
* [pierre3/PlantUmlClassDiagramGenerator](https://github.com/pierre3/PlantUmlClassDiagramGenerator) - This is a generator to create a class-diagram of PlantUML from the C# source code.
* [microsoft/infersharp](https://github.com/microsoft/infersharp) - Infer# is an interprocedural and scalable static code analyzer for C#. Via the capabilities of Facebook's Infer, this tool detects null dereferences, resource leaks, and thread-safety violations. It also performs taint flow tracking to detect critical security vulnerabilities like SQL injections.
* [icsharpcode/NRefactory](https://github.com/icsharpcode/NRefactory) - NRefactory - Refactoring Your C# Code *(archived)*
* [microsoft/RoslynClrHeapAllocationAnalyzer](https://github.com/microsoft/RoslynClrHeapAllocationAnalyzer) - Roslyn based C# heap allocation diagnostic analyzer that can detect explicit and many implicit allocations like boxing, display classes a.k.a closures, implicit delegate creations, etc. *(archived)*

### Debugging and Profiling

* [lucasg/Dependencies](https://github.com/lucasg/Dependencies) - A rewrite of the old legacy software "depends.exe" in C# for Windows devs to troubleshoot dll load dependencies issues.
* [microsoft/perfview](https://github.com/microsoft/perfview) - PerfView is a CPU and memory performance-analysis tool
* [bombomby/optick](https://github.com/bombomby/optick) - C++ Profiler For Games
* [MiniProfiler/dotnet](https://github.com/MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET (and Core) websites
* [Tayx94/graphy](https://github.com/Tayx94/graphy) - Graphy is the ultimate, easy to use, feature packed FPS counter, stats monitor and debugger for your Unity project.
* [benaadams/Ben.Demystifier](https://github.com/benaadams/Ben.Demystifier) - High performance understanding for stack traces (Make error logs more productive)
* [snoopwpf/snoopwpf](https://github.com/snoopwpf/snoopwpf) - Snoop - The WPF Spy Utility
* [Glimpse/Glimpse](https://github.com/Glimpse/Glimpse) - The open source diagnostics platform for the web *(archived)*
* [leinlin/Miku-LuaProfiler](https://github.com/leinlin/Miku-LuaProfiler)
* [microsoft/clrmd](https://github.com/microsoft/clrmd) - Microsoft.Diagnostics.Runtime is a set of APIs for introspecting processes and dumps.
* [needle-tools/compilation-visualizer](https://github.com/needle-tools/compilation-visualizer) - Unity Tool showing a timeline of assembly compilation. This is especially helpful when trying to optimize compile times and dependencies between assemblies. Besides showing a graphical view of compilation, selecting an assembly shows both dependencies and dependents of that assembly.

### Editor and IDE Support

* [HJLebbink/asm-dude](https://github.com/HJLebbink/asm-dude) - Visual Studio extension for assembly syntax highlighting and code completion in assembly files and the disassembly window
* [elvirbrk/NoteHighlight2016](https://github.com/elvirbrk/NoteHighlight2016) - Source code syntax highlighting for OneNote 2016 and OneNote for O365 . NoteHighlight 2013 port for OneNote 2016 (32-bit and 64-bit)
* [MattParkerDev/SharpIDE](https://github.com/MattParkerDev/SharpIDE) - A modern, cross platform IDE for .NET, built with .NET & Godot
* [VsVim/VsVim](https://github.com/VsVim/VsVim) - Vim Emulator Plugin for Visual Studio 2015+
* [mono/monodevelop](https://github.com/mono/monodevelop) - MonoDevelop is a cross platform .NET IDE *(archived)*
* [microsoft/PTVS](https://github.com/microsoft/PTVS) - Python Tools for Visual Studio
* [icsharpcode/SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - #develop (short for SharpDevelop) is a free IDE for .NET programming languages. *(archived)*
* [rubberduck-vba/Rubberduck](https://github.com/rubberduck-vba/Rubberduck) - Every programmer needs a rubberduck. COM add-in for the VBA & VB6 IDE (VBE). *(archived)*
* [icsharpcode/AvalonEdit](https://github.com/icsharpcode/AvalonEdit) - The WPF-based text editor component used in SharpDevelop
* [OmniSharp/omnisharp-roslyn](https://github.com/OmniSharp/omnisharp-roslyn) - OmniSharp server (HTTP, STDIO) based on Roslyn workspaces
* [codecadwallader/codemaid](https://github.com/codecadwallader/codemaid) - CodeMaid is an open source Visual Studio extension to cleanup and simplify our C#, C++, F#, VB, PHP, PowerShell, JSON, XAML, XML, ASP, HTML, CSS, LESS, SCSS, JavaScript and TypeScript coding.
* [BAndysc/AvaloniaVisualBasic6](https://github.com/BAndysc/AvaloniaVisualBasic6) - A recreation of the classic Visual Basic 6 IDE and language in C# with Avalonia
* [Monnoroch/ColorHighlighter](https://github.com/Monnoroch/ColorHighlighter) - ColorHighlighter - is a plugin for the Sublime text 2 and 3, which underlays selected hexadecimal colorcodes (like "#FFFFFF", "rgb(255,255,255)", "white", etc.) with their real color. Also, plugin adds color picker to easily modify colors. Documentation: https://monnoroch.github.io/ColorHighlighter.
* [ErikEJ/SqlCeToolbox](https://github.com/ErikEJ/SqlCeToolbox) - SQLite & SQL Server Compact Toolbox extension for Visual Studio, SSMS (and stand alone)
* [buchizo/ClaudiaIDE](https://github.com/buchizo/ClaudiaIDE) - This extension can change easily the background image of editor window in Visual Studio.
* [lukebuehler/CShell](https://github.com/lukebuehler/CShell) - A simple, yet powerful, C# scripting IDE and REPL

### Version Control

* [gitextensions/gitextensions](https://github.com/gitextensions/gitextensions) - Git Extensions is a standalone UI tool for managing git repositories. It also integrates with Windows Explorer and Microsoft Visual Studio (2015/2017/2019).
* [microsoft/VFSForGit](https://github.com/microsoft/VFSForGit) - Virtual File System for Git: Enable Git at Enterprise Scale
* [sourcegit-scm/sourcegit](https://github.com/sourcegit-scm/sourcegit) - Windows/macOS/Linux GUI client for GIT users
* [libgit2/libgit2sharp](https://github.com/libgit2/libgit2sharp) - Git + .NET = ❤
* [github-for-unity/Unity](https://github.com/github-for-unity/Unity) - GitHub for Unity *(archived)*
* [GitTools/GitVersion](https://github.com/GitTools/GitVersion) - From git log to SemVer in no time
* [octokit/octokit.net](https://github.com/octokit/octokit.net) - A GitHub API client library for .NET
* [github/VisualStudio](https://github.com/github/VisualStudio) - GitHub Extension for Visual Studio *(archived)*
* [git-tfs/git-tfs](https://github.com/git-tfs/git-tfs) - A Git/TFS bridge, similar to git-svn

## Web

### Web Frameworks

* [dotnet/aspnetcore](https://github.com/dotnet/aspnetcore) - ASP.NET Core is a cross-platform .NET framework for building modern cloud-based web applications on Windows, Mac, or Linux.
* [abpframework/abp](https://github.com/abpframework/abp) - Open-source web application framework for ASP.NET Core! Offers an opinionated architecture to build enterprise software solutions with best practices on top of the .NET. Provides the fundamental infrastructure, cross-cutting-concern implementations, startup templates, application modules, UI themes, tooling and documentation.
* [aspnetboilerplate/aspnetboilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate - Web Application Framework
* [nopSolutions/nopCommerce](https://github.com/nopSolutions/nopCommerce) - ASP.NET Core eCommerce software. nopCommerce is a free and open-source shopping cart.
* [OrchardCMS/OrchardCore](https://github.com/OrchardCMS/OrchardCore) - Orchard Core is an open-source modular and multi-tenant application framework built with ASP.NET Core, and a content management system (CMS) built on top of that framework.
* [NancyFx/Nancy](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono *(archived)*
* [aspnet/Mvc](https://github.com/aspnet/Mvc) - [Archived] ASP.NET Core MVC is a model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor. Project moved to https://github.com/aspnet/AspNetCore *(archived)*
* [ServiceStack/ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all
* [umbraco/Umbraco-CMS](https://github.com/umbraco/Umbraco-CMS) - Umbraco is a free and open source .NET content management system helping you deliver delightful digital experiences.
* [dotnetcore/Util](https://github.com/dotnetcore/Util) - Util是一个.Net平台下的应用框架，旨在提升中小团队的开发能力，由工具类、分层架构基类、Ui组件，配套代码生成模板，权限等组成。
* [simplcommerce/SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - A simple, cross platform, modulith ecommerce system built on .NET
* [dotnetcore/WTM](https://github.com/dotnetcore/WTM) - Use WTM to write .netcore app fast !!!
* [cq-panda/Vue.NetCore](https://github.com/cq-panda/Vue.NetCore) - (已支持sqlsugar).NetCore、.Net6、Vue2、Vue3、Vite、TypeScript、Element plus+uniapp前后端分离，全自动生成代码；支持移动端(ios/android/h5/微信小程序。http://www.volcore.xyz/
* [stefanprodan/AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) - ASP.NET Core rate limiting middleware
* [aspnet/JavaScriptServices](https://github.com/aspnet/JavaScriptServices) - [Archived] This repository has been archived *(archived)*
* [dotnetcore/osharp](https://github.com/dotnetcore/osharp) - OSharp是一个基于.Net6.0的快速开发框架，框架对 AspNetCore 的配置、依赖注入、日志、缓存、实体框架、Mvc(WebApi)、身份认证、功能权限、数据权限等模块进行更高一级的自动化封装，并规范了一套业务实现的代码结构与操作流程，使 .Net 框架更易于应用到实际项目开发中。
* [serenity-is/Serenity](https://github.com/serenity-is/Serenity) - Business Apps Made Simple with Asp.Net Core MVC / TypeScript
* [liukuo362573/YiShaAdmin](https://github.com/liukuo362573/YiShaAdmin) - 基于 .NET Core MVC 的权限管理系统，代码易读易懂、界面简洁美观
* [eventflow/EventFlow](https://github.com/eventflow/EventFlow) - Async/await first CQRS+ES and DDD framework for .NET
* [CarterCommunity/Carter](https://github.com/CarterCommunity/Carter) - Carter is framework that is a thin layer of extension methods and functionality over ASP.NET Core allowing code to be more explicit and most importantly more enjoyable.
* [oqtane/oqtane.framework](https://github.com/oqtane/oqtane.framework) - Oqtane is an open-source developer productivity platform for building modern .NET applications and websites that run on Web, Desktop and Mobile.
* [monksoul/Furion](https://github.com/monksoul/Furion) - 让 .NET 开发更简单，更通用，更流行。
* [PiranhaCMS/piranha.core](https://github.com/PiranhaCMS/piranha.core) - Piranha CMS is the friendly editor-focused CMS for .NET that can be used both as an integrated CMS or as a headless API.
* [enkodellc/blazorboilerplate](https://github.com/enkodellc/blazorboilerplate) - Blazor Boilerplate / Starter Template with MudBlazor
* [servicetitan/Stl.Fusion](https://github.com/servicetitan/Stl.Fusion) - Build real-time apps (Blazor included) with less than 1% of extra code responsible for real-time updates. Host 10-1000x faster APIs relying on transparent and nearly 100% consistent caching. We call it DREAM, or Distributed REActive Memoization, and it's here to turn real-time on!
* [Coldairarrow/Colder.Admin.AntdVue](https://github.com/Coldairarrow/Colder.Admin.AntdVue) - Admin Fx Based On .NET 5 + Ant Design Vue
* [cofoundry-cms/cofoundry](https://github.com/cofoundry-cms/cofoundry) - Cofoundry is an extensible and flexible .NET Core CMS & application framework focusing on code first development
* [mixcore/mix.core](https://github.com/mixcore/mix.core) - 🚀 A future-proof enterprise web CMS supporting both headless and decoupled approaches. Build any type of app with customizable APIs on ASP.NET Core/.NET Core. Completely open-source and designed for flexibility. Since 2018.
* [luoyunchong/lin-cms-dotnetcore](https://github.com/luoyunchong/lin-cms-dotnetcore) - 😃A simple and practical CMS implemented by .NET + FreeSql；前后端分离、Docker部署、OAtuh2授权登录、自动化部署DevOps、自动同步至Gitee、代码生成器、仿掘金专栏
* [ExtCore/ExtCore](https://github.com/ExtCore/ExtCore) - Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core
* [edandersen/core-admin](https://github.com/edandersen/core-admin) - Fully automatic admin site CRUD UI generator for ASP.NET Core and .NET 10
* [revoframework/Revo](https://github.com/revoframework/Revo) - Event Sourcing, CQRS and DDD framework for C#/.NET Core.

### HTTP and Networking Clients

* [restsharp/RestSharp](https://github.com/restsharp/RestSharp) - Simple REST and HTTP API Client for .NET
* [reactiveui/refit](https://github.com/reactiveui/refit) - The automatic type-safe REST library for .NET Core, Xamarin and .NET. Heavily inspired by Square's Retrofit library, Refit turns your REST API into a live interface.
* [JeffreySu/WeiXinMPSDK](https://github.com/JeffreySu/WeiXinMPSDK) - 微信全平台 .NET SDK， Senparc.Weixin for C#，支持 .NET Framework 及 .NET Core、.NET 10.0。已支持微信公众号、小程序、小游戏、微信支付、企业微信/企业号、开放平台、JSSDK、微信周边等全平台。 WeChat SDK for C#.
* [tmenier/Flurl](https://github.com/tmenier/Flurl) - Fluent URL builder and testable HTTP client for .NET
* [Tyrrrz/YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) - Abstraction layer over YouTube's internal API
* [dotnetcore/WebApiClient](https://github.com/dotnetcore/WebApiClient) - A REST API library with better functionality, performance, and scalability than refit
* [fudiwei/DotNetCore.SKIT.FlurlHttpClient.Wechat](https://github.com/fudiwei/DotNetCore.SKIT.FlurlHttpClient.Wechat) - 可能是全网最完整的 C# 版微信 SDK，封装全部已知的微信 OpenAPI，包含微信公众平台（订阅号+服务号+小程序+小游戏+小商店+视频号）、微信开放平台、微信商户平台（微信支付+微企付）、企业微信、微信广告平台、微信智能对话开放平台等模块，可跨平台。持续随官方更新，欢迎 Star/Fork/PR。QQ 交流群 875580418【满】、930461548【满】、611974621。
* [JohnnyCrazy/SpotifyAPI-NET](https://github.com/JohnnyCrazy/SpotifyAPI-NET) - :sound: A Client for the Spotify Web API, written in C#/.NET
* [googleapis/google-api-dotnet-client](https://github.com/googleapis/google-api-dotnet-client) - Google APIs Client Library for .NET
* [wiz0u/WTelegramClient](https://github.com/wiz0u/WTelegramClient) - Telegram Client API (MTProto) library written 100% in C# and .NET
* [proyecto26/RestClient](https://github.com/proyecto26/RestClient) - 🦄 A Promise based REST and HTTP client for Unity 🎮
* [JKorf/Binance.Net](https://github.com/JKorf/Binance.Net) - C#/.NET client library for the Binance.com cryptocurrency exchange REST and WebSocket APIs, supporting Spot and Futures trading and market data with strongly typed models.
* [sendgrid/sendgrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - The Official Twilio SendGrid C#, .NetStandard, .NetCore API Library
* [loklak/loklak_dotnet_api](https://github.com/loklak/loklak_dotnet_api) - A C#.NET Wrapper for Loklak to be used with Windows applications
* [linvi/tweetinvi](https://github.com/linvi/tweetinvi) - Tweetinvi, an intuitive Twitter C# library for the REST and Stream API. It supports .NET, .NETCore, UAP (Xamarin)...
* [EasyHttp/EasyHttp](https://github.com/EasyHttp/EasyHttp) - Http Library for C#
* [sochix/TLSharp](https://github.com/sochix/TLSharp) - Telegram client library implemented in C# *(archived)*
* [ramtinak/InstagramApiSharp](https://github.com/ramtinak/InstagramApiSharp) - A complete Private Instagram API for .NET (C#, VB.NET).
* [facebook-csharp-sdk/facebook-csharp-sdk](https://github.com/facebook-csharp-sdk/facebook-csharp-sdk) - Facebook SDK for .NET
* [dotnetcore/Alipay.AopSdk.Core](https://github.com/dotnetcore/Alipay.AopSdk.Core) - 支付宝（Alipay）服务端SDK，采用.NET Standard 2.0，支持.NET Core >=2.0，与官方SDK接口完全相同。完全可以按照官方文档进行开发。除了支持支付以外，官方SDK支持的功能本SDK全部支持，比如生活号、服务窗、行业合作等，且用法几乎一样，代码都可参考官方文档代码。 *(archived)*
* [DigitalRuby/ExchangeSharp](https://github.com/DigitalRuby/ExchangeSharp) - ExchangeSharp is a powerful, fast and easy to use .NET/C# API for interfacing with many crypto currency exchanges. REST and web sockets are supported.
* [twilio/twilio-csharp](https://github.com/twilio/twilio-csharp) - Twilio C#/.NET Helper Library for .NET6+.
* [anaisbetts/ModernHttpClient](https://github.com/anaisbetts/ModernHttpClient) - HttpClient implementations that use platform-native HTTP clients for :rocket:

### API and GraphQL

* [RicoSuter/NSwag](https://github.com/RicoSuter/NSwag) - The Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript.
* [FastEndpoints/FastEndpoints](https://github.com/FastEndpoints/FastEndpoints) - A light-weight REST API development framework for ASP.NET 8 and newer.
* [graphql-dotnet/graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET
* [ChilliCream/graphql-platform](https://github.com/ChilliCream/graphql-platform) - Welcome to the home of the Hot Chocolate GraphQL server for .NET, the Strawberry Shake GraphQL client for .NET and Nitro the awesome Monaco based GraphQL IDE.
* [domaindrivendev/Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - Swagger tools for documenting API's built on ASP.NET Core
* [microsoft/kiota](https://github.com/microsoft/kiota) - OpenAPI based HTTP Client code generator
* [dotnet/aspnet-api-versioning](https://github.com/dotnet/aspnet-api-versioning) - Provides a set of libraries which add service API versioning to ASP.NET Core Minimal APIs, Controllers, gRPC, OData, and Web API (Classic).
* [ardalis/ApiEndpoints](https://github.com/ardalis/ApiEndpoints) - A project for supporting API Endpoints in ASP.NET Core web applications.
* [domaindrivendev/Swashbuckle.WebApi](https://github.com/domaindrivendev/Swashbuckle.WebApi) - Seamlessly adds a swagger to WebApi projects!
* [DigDes/SoapCore](https://github.com/DigDes/SoapCore) - SOAP extension for ASP.NET Core
* [json-api-dotnet/JsonApiDotNetCore](https://github.com/json-api-dotnet/JsonApiDotNetCore) - A framework for building JSON:API compliant REST APIs using ASP.NET and Entity Framework Core.
* [graphql-dotnet/graphql-client](https://github.com/graphql-dotnet/graphql-client) - A GraphQL Client for .NET Standard

### Frontend and UI Components

* [MudBlazor/MudBlazor](https://github.com/MudBlazor/MudBlazor) - Blazor Component Library based on Material Design principles. Do more with Blazor, utilizing CSS and keeping JavaScript to a bare minimum.
* [ant-design-blazor/ant-design-blazor](https://github.com/ant-design-blazor/ant-design-blazor) - 🌈A rich set of enterprise-class UI components based on Ant Design and Blazor.
* [AngleSharp/AngleSharp](https://github.com/AngleSharp/AngleSharp) - :angel: The ultimate angle brackets parser library parsing HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specifications.
* [dotnetcore/BootstrapBlazor](https://github.com/dotnetcore/BootstrapBlazor) - Bootstrap Blazor is an enterprise-level UI component library based on Bootstrap and Blazor.
* [microsoft/fluentui-blazor](https://github.com/microsoft/fluentui-blazor) - Microsoft Fluent UI Blazor components library. For use with ASP.NET Core Blazor applications
* [radzenhq/radzen-blazor](https://github.com/radzenhq/radzen-blazor) - Radzen Blazor is the most sophisticated free UI component library for Blazor, featuring 145+ native components including DataGrid, Scheduler, Charts, and advanced theming with full support for Material Design and Fluent UI. If Radzen Blazor is useful to you, a ⭐ on GitHub helps other Blazor developers find it.
* [Megabit/Blazorise](https://github.com/Megabit/Blazorise) - Blazorise is a component library built on top of Blazor with support for CSS frameworks like Bootstrap, Tailwind, Bulma, AntDesign, and Material.
* [ArgoZhang/BootstrapAdmin](https://github.com/ArgoZhang/BootstrapAdmin) - BootstrapAdmin - Free Premium Admin control Panel Based On Bootstrap 4.x
* [reactjs/React.NET](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components
* [apexcharts/Blazor-ApexCharts](https://github.com/apexcharts/Blazor-ApexCharts) - A blazor wrapper for ApexCharts.js
* [mariusmuntean/ChartJs.Blazor](https://github.com/mariusmuntean/ChartJs.Blazor) - Brings Chart.js charts to Blazor
* [milkshakesoftware/PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [BlazorExtensions/Canvas](https://github.com/BlazorExtensions/Canvas) - HTML5 Canvas API implementation for Microsoft Blazor

### Scraping and Crawling

* [dotnetcore/DotnetSpider](https://github.com/dotnetcore/DotnetSpider) - DotnetSpider, a .NET standard web crawling library. It is lightweight, efficient and fast high-level web crawling & scraping framework
* [hardkoded/puppeteer-sharp](https://github.com/hardkoded/puppeteer-sharp) - Headless Chrome .NET API
* [JavScraper/Emby.Plugins.JavScraper](https://github.com/JavScraper/Emby.Plugins.JavScraper) - Emby/Jellyfin 的一个日本电影刮削器插件，可以从某些网站抓取影片信息。
* [ferventdesert/Hawk](https://github.com/ferventdesert/Hawk) - visualized crawler & ETL IDE written with C#/WPF
* [microsoft/playwright-dotnet](https://github.com/microsoft/playwright-dotnet) - .NET version of the Playwright testing and automation library.
* [zzzprojects/html-agility-pack](https://github.com/zzzprojects/html-agility-pack) - Html Agility Pack (HAP) is a free and open-source HTML parser written in C# to read/write DOM and supports plain XPATH or XSLT. It is a .NET code library that allows you to parse "out of the web" HTML files.
* [sjdirect/abot](https://github.com/sjdirect/abot) - Cross Platform C# web crawler framework built for speed and flexibility. Please star this project! +1.

## Data and Storage

### Databases

* [litedb-org/LiteDB](https://github.com/litedb-org/LiteDB) - LiteDB - A .NET NoSQL Document Store in a single data file
* [microsoft/FASTER](https://github.com/microsoft/FASTER) - Fast persistent recoverable log and key-value store + cache, in C# and C++.
* [kurrent-io/KurrentDB](https://github.com/kurrent-io/KurrentDB) - KurrentDB is a database that's engineered for modern software applications and event-driven architectures. Its event-native design simplifies data modeling and preserves data integrity while the integrated streaming engine solves distributed messaging challenges and ensures data consistency.
* [redis-windows/redis-windows](https://github.com/redis-windows/redis-windows) - Redis 6.0.20 6.2.18 7.0.15 7.2.8 7.4.3 8.0.0 for Windows
* [ravendb/ravendb](https://github.com/ravendb/ravendb) - ACID Document Database
* [microsoft/GraphEngine](https://github.com/microsoft/GraphEngine) - Microsoft Graph Engine

### Database Clients and ORMs

* [DapperLib/Dapper](https://github.com/DapperLib/Dapper) - Dapper - a simple object mapper for .Net
* [dotnet/efcore](https://github.com/dotnet/efcore) - EF Core is a modern object-database mapper for .NET. It supports LINQ queries, change tracking, updates, and schema migrations.
* [StackExchange/StackExchange.Redis](https://github.com/StackExchange/StackExchange.Redis) - The Redis client for .NET
* [DotNetNext/SqlSugar](https://github.com/DotNetNext/SqlSugar) - .Net aot ORM SqlServer ORM Mongodb ORM MySql 瀚高 Postgresql ORM DB2 Hana 高斯 Duckdb C# VB.NET Sqlite ORM Oracle ORM Mysql Orm 虚谷数据库 达梦 ORM 人大金仓 ORM 神通ORM C# ORM , C# ORM .NET ORM NET9 ORM .NET8 ORM ClickHouse ORM QuestDb ,TDengine ORM,OceanBase ORM,GaussDB ORM,Tidb ORM Object/Relational Mapping
* [praeclarum/sqlite-net](https://github.com/praeclarum/sqlite-net) - Simple, powerful, cross-platform SQLite client and ORM for .NET
* [dotnetcore/FreeSql](https://github.com/dotnetcore/FreeSql) - .NET aot orm, VB.NET/C# orm, Mysql/PostgreSQL/SqlServer/Oracle orm, Sqlite/Firebird/Clickhouse/DuckDB orm, 达梦/金仓/虚谷/翰高/高斯 orm, 神通 orm, 南大通用 orm, 国产 orm, TDengine orm, QuestDB orm, MsAccess orm.
* [borisdj/EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) - Entity Framework EF Core efcore Bulk Batch Extensions with BulkCopy in .Net for Insert Update Delete Read (CRUD), Truncate and SaveChanges operations on SQL Server, PostgreSQL, MySQL, SQLite, Oracle
* [npgsql/npgsql](https://github.com/npgsql/npgsql) - Npgsql is the .NET data provider for PostgreSQL.
* [elastic/elasticsearch-net](https://github.com/elastic/elasticsearch-net) - This strongly-typed, client library enables working with Elasticsearch. It is the official client maintained and supported by Elastic.
* [fluentmigrator/fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) - Fluent migrations framework for .NET
* [JasperFx/marten](https://github.com/JasperFx/marten) - .NET Transactional Document DB and Event Store on PostgreSQL
* [sqlkata/querybuilder](https://github.com/sqlkata/querybuilder) - SQL query builder, written in c#, helps you build complex queries easily, supports SqlServer, MySql, PostgreSql, Oracle, Sqlite and Firebird
* [linq2db/linq2db](https://github.com/linq2db/linq2db) - Linq to database provider.
* [mongodb/mongo-csharp-driver](https://github.com/mongodb/mongo-csharp-driver) - The Official C# .NET Driver for MongoDB
* [PomeloFoundation/Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - Entity Framework Core provider for MySQL and MariaDB built on top of MySqlConnector
* [DbUp/DbUp](https://github.com/DbUp/DbUp) - DbUp is a .NET library that helps you to deploy changes to SQL Server databases. It tracks which SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date.
* [ErikEJ/EFCorePowerTools](https://github.com/ErikEJ/EFCorePowerTools) - Entity Framework Core Power Tools - reverse engineering, migrations and model visualization in Visual Studio & CLI
* [zzzprojects/EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) - Entity Framework Plus extends your DbContext with must-haves features: Include Filter, Auditing, Caching, Query Future, Batch Delete, Batch Update, and more
* [ServiceStack/ServiceStack.Redis](https://github.com/ServiceStack/ServiceStack.Redis) - .NET's leading C# Redis Client *(archived)*
* [ardalis/Specification](https://github.com/ardalis/Specification) - Base class with tests for adding specifications to a DDD model
* [nhibernate/nhibernate-core](https://github.com/nhibernate/nhibernate-core) - NHibernate Object Relational Mapper
* [CollaboratingPlatypus/PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) - Official PetaPoco, A tiny ORM-ish thing for your POCO's
* [2881099/csredis](https://github.com/2881099/csredis) - .NET Core or .NET Framework 4.0+ client for Redis and Redis Sentinel (2.8) and Cluster. Includes both synchronous and asynchronous clients.
* [mikependon/RepoDB](https://github.com/mikependon/RepoDB) - A production-ready data access platform for .NET applications.
* [shuxinqin/Chloe](https://github.com/shuxinqin/Chloe) - A lightweight and high-performance Object/Relational Mapping(ORM) library for .NET --C#
* [mysql-net/MySqlConnector](https://github.com/mysql-net/MySqlConnector) - MySQL Connector for .NET
* [ThatRendle/Simple.Data](https://github.com/ThatRendle/Simple.Data) - A light-weight, dynamic data access component for C# 4.0
* [dotnetcore/sharding-core](https://github.com/dotnetcore/sharding-core) - high performance lightweight solution for efcore sharding table and sharding database support read-write-separation .一款ef-core下高性能、轻量级针对分表分库读写分离的解决方案，具有零依赖、零学习成本、零业务代码入侵
* [ericdc1/Dapper.SimpleCRUD](https://github.com/ericdc1/Dapper.SimpleCRUD) - Who wants to write basic read/insert/update/delete statements? SimpleCRUD provides simple CRUD helpers for Dapper.
* [dotnetcore/SmartSql](https://github.com/dotnetcore/SmartSql) - SmartSql = MyBatis in C# + .NET Core+ Cache(Memory | Redis) + R/W Splitting + PropertyChangedTrack +Dynamic Repository + InvokeSync + Diagnostics
* [dotnet/SqlClient](https://github.com/dotnet/SqlClient) - Microsoft.Data.SqlClient provides database connectivity to SQL Server for .NET applications.
* [efcore/EFCore.NamingConventions](https://github.com/efcore/EFCore.NamingConventions) - Entity Framework Core plugin to apply naming conventions to table and column names (e.g. snake_case)
* [Azure/azure-cosmos-dotnet-v3](https://github.com/Azure/azure-cosmos-dotnet-v3) - .NET SDK for Azure Cosmos DB for the core SQL API
* [VictorTzeng/Zxw.Framework.NetCore](https://github.com/VictorTzeng/Zxw.Framework.NetCore) - 基于EF Core的Code First模式的DotNetCore快速开发框架，其中包括DBContext、IOC组件autofac和AspectCore.Injector、代码生成器（也支持DB First）、基于AspectCore的memcache和Redis缓存组件，以及基于ICanPay的支付库和一些日常用的方法和扩展，比如批量插入、更新、删除以及触发器支持，当然还有demo。欢迎提交各种建议、意见和pr~
* [sjh37/EntityFramework-Reverse-POCO-Code-First-Generator](https://github.com/sjh37/EntityFramework-Reverse-POCO-Code-First-Generator) - EntityFramework Reverse POCO Code First Generator - Beautifully generated code that is fully customisable. This generator creates code as if you reverse engineered a database and lovingly created the code by hand. It is free to academics, commercial use requires a paid licence. Obtain your licence from:
* [supabase-community/supabase-csharp](https://github.com/supabase-community/supabase-csharp) - A C# Client library for Supabase
* [cyq1162/cyqdata](https://github.com/cyq1162/cyqdata) - cyq.data is a high-performance and the most powerful orm.（.NET 最好用的ORM数据层框架，木有之一！支持.NET所有版本、支持.NET Core所有版本）Support：Mssql、Mysql、Oracle、Sybase、Postgres、DB2、FireBird、Sqlite、DaMeng（达梦）、KingBaseES（人大金仓）、Txt、Xml、Access、Excel、FoxPro、Redis、MemCache。
* [datastax/csharp-driver](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra
* [step-up-labs/firebase-database-dotnet](https://github.com/step-up-labs/firebase-database-dotnet) - C# library for Firebase Realtime Database.
* [IsNemoEqualTrue/monitor-table-change-with-sqltabledependency](https://github.com/IsNemoEqualTrue/monitor-table-change-with-sqltabledependency) - Get SQL Server notification on record table change
* [SharpRepository/SharpRepository](https://github.com/SharpRepository/SharpRepository) - C# Generic Repository for use with Entity Framework, RavenDB and more with built-in caching options.
* [mehdime/DbContextScope](https://github.com/mehdime/DbContextScope) - A simple and flexible way to manage your Entity Framework DbContext instances
* [msallin/SQLiteCodeFirst](https://github.com/msallin/SQLiteCodeFirst) - Creates a SQLite Database based on a EdmModel by using Entity Framework CodeFirst.
* [JonPSmith/EfCore.GenericServices](https://github.com/JonPSmith/EfCore.GenericServices) - A library to help you quickly code CRUD accesses for a web/mobile/desktop application using EF Core.
* [dotnetcore/CanalSharp](https://github.com/dotnetcore/CanalSharp) - Alibaba mysql database binlog subscription & consumer components Canal's .NET client.
* [samus/mongodb-csharp](https://github.com/samus/mongodb-csharp) - A driver written in c# to connect to the MongoDB document oriented database. *(archived)*

### Serialization and Formats

* [JamesNK/Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - Json.NET is a popular high-performance JSON framework for .NET
* [MessagePack-CSharp/MessagePack-CSharp](https://github.com/MessagePack-CSharp/MessagePack-CSharp) - Extremely Fast MessagePack Serializer for C#(.NET, .NET Core, Unity, Xamarin). / msgpack.org[C#]
* [nissl-lab/npoi](https://github.com/nissl-lab/npoi) - a .NET library that can read/write Office formats without Microsoft Office installed. No COM+, no interop.
* [ClosedXML/ClosedXML](https://github.com/ClosedXML/ClosedXML) - ClosedXML is a .NET library for reading, manipulating and writing Excel 2007+ (.xlsx, .xlsm) files. It aims to provide an intuitive and user-friendly interface to dealing with the underlying OpenXML API.
* [JoshClose/CsvHelper](https://github.com/JoshClose/CsvHelper) - Library to help reading and writing CSV files
* [protobuf-net/protobuf-net](https://github.com/protobuf-net/protobuf-net) - Protocol Buffers library for idiomatic .NET
* [Cysharp/MemoryPack](https://github.com/Cysharp/MemoryPack) - Zero encoding extreme performance binary serializer for C# and Unity.
* [dotnet/Open-XML-SDK](https://github.com/dotnet/Open-XML-SDK) - Open XML SDK by Microsoft
* [ExcelDataReader/ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files
* [JanKallman/EPPlus](https://github.com/JanKallman/EPPlus) - Create advanced Excel spreadsheets using .NET *(archived)*
* [mini-software/MiniExcel](https://github.com/mini-software/MiniExcel) - Lightweight, fast and simple cross-platform processing tool for importing and exporting spreadsheet documents. Built in .NET.
* [aaubry/YamlDotNet](https://github.com/aaubry/YamlDotNet) - YamlDotNet is a .NET library for YAML
* [neuecc/ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - Infinitely Fast Deserializer for .NET, .NET Core and Unity. *(archived)*
* [neuecc/Utf8Json](https://github.com/neuecc/Utf8Json) - Definitely Fastest and Zero Allocation JSON Serializer for C#(NET, .NET Core, Unity, Xamarin). *(archived)*
* [dotnetcore/Magicodes.IE](https://github.com/dotnetcore/Magicodes.IE) - Import and export general library, support Dto import and export, template export, fancy export and dynamic export, support Excel, Csv, Word, Pdf and Html.
* [6over3/bebop](https://github.com/6over3/bebop) - 🎷No ceremony, just code. Blazing fast, typesafe binary serialization.
* [kevin-montrose/Jil](https://github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil
* [EPPlusSoftware/EPPlus](https://github.com/EPPlusSoftware/EPPlus) - EPPlus-Excel spreadsheets for .NET
* [jstedfast/MimeKit](https://github.com/jstedfast/MimeKit) - A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [dotnetcore/NPOI](https://github.com/dotnetcore/NPOI) - A .NET library for reading and writing Microsoft Office binary and OOXML file formats. *(archived)*
* [itext/itext-dotnet](https://github.com/itext/itext-dotnet) - iText for .NET is the .NET version of the iText library, formerly known as iTextSharp, which it replaces. iText represents the next level of SDKs for developers that want to take advantage of the benefits PDF can bring. Equipped with a better document engine, high and low-level programming capabilities and the ability to create, edit and enha
* [xceedsoftware/DocX](https://github.com/xceedsoftware/DocX) - Fast and easy to use .NET library that creates or modifies Microsoft Word files without installing Word.
* [TeamSirenix/odin-serializer](https://github.com/TeamSirenix/odin-serializer) - Fast, robust, powerful and extendible .NET serializer built for Unity
* [neil3d/excel2json](https://github.com/neil3d/excel2json) - 把Excel表转换成json对象，并保存到一个文本文件中。
* [Cinchoo/ChoETL](https://github.com/Cinchoo/ChoETL) - ETL framework for .NET (Parser / Writer for CSV, Flat, Xml, JSON, Key-Value, Parquet, Yaml, Avro formatted files)
* [msgpack/msgpack-cli](https://github.com/msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure / msgpack.org[C#]
* [Bunny83/SimpleJSON](https://github.com/Bunny83/SimpleJSON) - A simple JSON parser in C#
* [RehanSaeed/Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page.
* [EgorBo/SimdJsonSharp](https://github.com/EgorBo/SimdJsonSharp) - C# bindings for lemire/simdjson (and full C# port)

### Caching and Queues

* [microsoft/garnet](https://github.com/microsoft/garnet) - Garnet is a remote cache-store from Microsoft Research that offers strong performance (throughput and latency), scalability, storage, recovery, cluster sharding, key migration, and replication features. Garnet can work with existing Redis clients.
* [HangfireIO/Hangfire](https://github.com/HangfireIO/Hangfire) - An easy way to perform background job processing in .NET and .NET Core applications. No Windows Service or separate process required
* [ZiggyCreatures/FusionCache](https://github.com/ZiggyCreatures/FusionCache) - FusionCache is an easy to use, fast and robust hybrid cache with advanced resiliency features.
* [EasyNetQ/EasyNetQ](https://github.com/EasyNetQ/EasyNetQ) - An easy to use .NET API for RabbitMQ
* [reactiveui/Akavache](https://github.com/reactiveui/Akavache) - An asynchronous, persistent key-value store created for writing desktop and mobile applications, based on SQLite3. Akavache is great for both storing important data as well as cached local data that expires.
* [MichaCo/CacheManager](https://github.com/MichaCo/CacheManager) - CacheManager is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.
* [rabbitmq/rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client for .NET Standard 2.0+ and .NET 4.6.2+
* [dotnetcore/EasyCaching](https://github.com/dotnetcore/EasyCaching) - :boom: EasyCaching is an open source caching library that contains basic usages and some advanced usages of caching which can help us to handle caching more easier!
* [alastairtree/LazyCache](https://github.com/alastairtree/LazyCache) - An easy to use thread safe in-memory caching service with a simple developer friendly API for c#
* [VahidN/EFCoreSecondLevelCacheInterceptor](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor) - EF Core Second Level Cache Interceptor
* [filipw/Strathweb.CacheOutput](https://github.com/filipw/Strathweb.CacheOutput) - ASP.NET Web API CacheOutput - library to allow you to cache the output of ApiControllers
* [aliostad/CacheCow](https://github.com/aliostad/CacheCow) - An implementation of HTTP Caching in .NET Core and 4.5.2+ for both the client and the server
* [jamesmontemagno/monkey-cache](https://github.com/jamesmontemagno/monkey-cache) - Easily cache any data structure for a specific amount of time in any .NET application.
* [TurnerSoftware/CacheTower](https://github.com/TurnerSoftware/CacheTower) - An efficient multi-layered caching system for .NET
* [tangxuehua/equeue](https://github.com/tangxuehua/equeue) - a distributed mq written by c#.
* [enyim/EnyimMemcached](https://github.com/enyim/EnyimMemcached) - C# Memcached client *(archived)*
* [confluentinc/confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) - Confluent's Apache Kafka .NET client

## Machine Learning and AI

### LLM and Inference

* [dotnet/skills](https://github.com/dotnet/skills) - Repository for skills to assist AI coding agents with .NET and C#
* [modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk) - The official C# SDK for Model Context Protocol servers and clients. Maintained in collaboration with Microsoft.
* [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) - AI Skills, MCP Tools, and CLI for Unity Engine. Full AI develop and test loop. Use cli for quick setup. Efficient token usage, advanced tools. Any C# method may be turned into a tool by a single line. Works with Claude Code, Gemini, Copilot, Cursor and any other absolutely for free.
* [keijiro/AICommand](https://github.com/keijiro/AICommand) - ChatGPT integration with Unity Editor
* [SciSharp/LLamaSharp](https://github.com/SciSharp/LLamaSharp) - A C#/.NET library to run LLM (🦙LLaMA/LLaVA) on your local device efficiently.
* [AIDotNet/OpenDeepWiki](https://github.com/AIDotNet/OpenDeepWiki) - OpenDeepWiki is the open-source version of the DeepWiki project, aiming to provide a powerful knowledge management and collaboration platform. The project is mainly developed using C# and TypeScript, supporting modular design, and is easy to expand and customize.
* [SciSharp/BotSharp](https://github.com/SciSharp/BotSharp) - AI Multi-Agent Framework in .NET
* [betalgo/openai](https://github.com/betalgo/openai) - .NET library for the OpenAI service API by Betalgo Ranul
* [openai/openai-dotnet](https://github.com/openai/openai-dotnet) - The official .NET library for the OpenAI API
* [keijiro/AIShader](https://github.com/keijiro/AIShader) - ChatGPT-powered shader generator for Unity
* [win4r/AISuperDomain](https://github.com/win4r/AISuperDomain) - Aila(AI超元域): The premier AI integration tool for Windows, macOS, and Android. Ask once, get answers from 10+ AIs like ChatGPT, Gemini, Claude3, Copilot, Poe, perplexity and more. Features customizable AI and prompts.
* [OkGoDoIt/OpenAI-API-dotnet](https://github.com/OkGoDoIt/OpenAI-API-dotnet) - An unofficial C#/.NET SDK for accessing the OpenAI GPT-3 API
* [StartupHakk/OpenMonoAgent.ai](https://github.com/StartupHakk/OpenMonoAgent.ai) - (BETA) AI shouldn't have a meter. Unlimited tokens. Forever. Your machine. Your agent. Use it from anywhere. Terminal-native coding agent powered by local LLMs — 100% open source, free forever, and installed with a single command. Proudly built on C#/.NET, because AI tooling should be infrastructure, not a subscription.
* [uezo/ChatdollKit](https://github.com/uezo/ChatdollKit) - ChatdollKit enables you to make your 3D model into a chatbot
* [tryAGI/LangChain](https://github.com/tryAGI/LangChain) - C# implementation of LangChain. We try to be as close to the original as possible in terms of abstractions, but are open to new entities.
* [getcellm/cellm](https://github.com/getcellm/cellm) - Use LLMs in Excel formulas
* [Navi-Studio/Virtual-Human-for-Chatting](https://github.com/Navi-Studio/Virtual-Human-for-Chatting) - Live2D Virtual Human for Chatting based on Unity
* [SkyWorkAIGC/SkyChat-Chinese-Chatbot-GPT3](https://github.com/SkyWorkAIGC/SkyChat-Chinese-Chatbot-GPT3) - SkyChat是一款基于中文GPT-3 api的聊天机器人项目。它可以像chatGPT一样，实现人机聊天、问答、中英文互译、对对联、写古诗等任务。| SkyChat is a Chatbot project based on Chinese GPT3 API. Like chatGPT, it can do human-machine chat, question and answer, and can also complete tasks such as Chinese-English or English-Chinese translation, content continuation, couplets, and Chinese ancient poems writing.
* [re4/LibreCode](https://github.com/re4/LibreCode) - LibreCode - A Ollama cursor like coding / Reversing Interface

### Machine Learning Frameworks

* [Unity-Technologies/ml-agents](https://github.com/Unity-Technologies/ml-agents) - The Unity Machine Learning Agents Toolkit (ML-Agents) is an open-source project that enables games and simulations to serve as environments for training intelligent agents using deep reinforcement learning and imitation learning.
* [dotnet/machinelearning](https://github.com/dotnet/machinelearning) - ML.NET is an open source and cross-platform machine learning framework for .NET.
* [accord-net/framework](https://github.com/accord-net/framework) - Machine learning, computer vision, statistics and general scientific computing for .NET *(archived)*
* [SciSharp/TensorFlow.NET](https://github.com/SciSharp/TensorFlow.NET) - .NET Standard bindings for Google's TensorFlow for developing, training and deploying Machine Learning models in C# and F#.
* [migueldeicaza/TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) - TensorFlow API for .NET languages *(archived)*
* [giacomelli/GeneticSharp](https://github.com/giacomelli/GeneticSharp) - GeneticSharp is a fast, extensible, multi-platform and multithreading C# Genetic Algorithm library that simplifies the development of applications using Genetic Algorithms (GAs).
* [codeproject/CodeProject.AI-Server](https://github.com/codeproject/CodeProject.AI-Server) - CodeProject.AI Server is a self contained service that software developers can include in, and distribute with, their applications in order to augment their apps with the power of AI.
* [SciSharp/Keras.NET](https://github.com/SciSharp/Keras.NET) - Keras.NET is a high-level neural networks API for C# and F#, with Python Binding and capable of running on top of TensorFlow, CNTK, or Theano.

### Computer Vision

* [shimat/opencvsharp](https://github.com/shimat/opencvsharp) - OpenCV wrapper for .NET
* [homuler/MediaPipeUnityPlugin](https://github.com/homuler/MediaPipeUnityPlugin) - Unity plugin to run MediaPipe
* [charlesw/tesseract](https://github.com/charlesw/tesseract) - A .Net wrapper for tesseract-ocr
* [emgucv/emgucv](https://github.com/emgucv/emgucv) - Emgu CV is a cross platform .Net wrapper to the OpenCV image processing library.
* [sdcb/PaddleSharp](https://github.com/sdcb/PaddleSharp) - .NET/C# binding for Baidu paddle inference library and PaddleOCR
* [andrewkirillov/AForge.NET](https://github.com/andrewkirillov/AForge.NET) - AForge.NET Framework is a C# framework designed for developers and researchers in the fields of Computer Vision and Artificial Intelligence - image processing, neural networks, genetic algorithms, machine learning, robotics, etc.
* [ViewFaceCore/ViewFaceCore](https://github.com/ViewFaceCore/ViewFaceCore) - C# 超简单的离线人脸识别库。( 基于 SeetaFace6 )
* [Unity-Technologies/com.unity.perception](https://github.com/Unity-Technologies/com.unity.perception) - Perception toolkit for sim2real training and validation in Unity

### Data Science and Analytics

* [ScottPlot/ScottPlot](https://github.com/ScottPlot/ScottPlot) - Interactive plotting library for .NET
* [Live-Charts/Live-Charts](https://github.com/Live-Charts/Live-Charts) - Simple, flexible, interactive & powerful charts, maps and gauges for .Net *(archived)*
* [Live-Charts/LiveCharts2](https://github.com/Live-Charts/LiveCharts2) - Beautiful, interactive charts, maps, and gauges. One API for every .NET UI framework.
* [XCharts-Team/XCharts](https://github.com/XCharts-Team/XCharts) - A charting and data visualization library for Unity. Unity数据可视化图表插件。
* [oxyplot/oxyplot](https://github.com/oxyplot/oxyplot) - A cross-platform plotting library for .NET
* [dotnet/interactive](https://github.com/dotnet/interactive) - .NET Interactive combines the power of .NET with many other languages to create notebooks, REPLs, and embedded coding experiences. Share code, explore data, write, and learn across your apps in ways you couldn't before. *(archived)*
* [dotnet/spark](https://github.com/dotnet/spark) - .NET for Apache® Spark™ makes Apache Spark™ easily accessible to .NET developers.
* [starik222/BooruDatasetTagManager](https://github.com/starik222/BooruDatasetTagManager)
* [microsoft/CDM](https://github.com/microsoft/CDM) - The Common Data Model (CDM) is a standard and extensible collection of schemas (entities, attributes, relationships) that represents business concepts and activities with well-defined semantics, to facilitate data interoperability. Examples of entities include: Account, Contact, Lead, Opportunity, Product, etc.
* [facioquo/stock-indicators-dotnet](https://github.com/facioquo/stock-indicators-dotnet) - Stock Indicators for .NET is a C# NuGet package that transforms raw equity, commodity, forex, or cryptocurrency financial market price quotes into technical indicators and trading insights. You'll need this essential data in the investment tools that you're building for algorithmic trading, technical analysis, machine learning, or visual charting.
* [microsoft/Mobius](https://github.com/microsoft/Mobius) - C# and F# language binding and extensions to Apache Spark
* [microsoft/PowerBI-CSharp](https://github.com/microsoft/PowerBI-CSharp) - Welcome to the .NET developer community for Power BI. Here you will find resources for the .NET SDKs for Power BI Embedded V2.0.0
* [SciSharp/Pandas.NET](https://github.com/SciSharp/Pandas.NET) - Pandas port for C# and F#, data analysis tool, process multi-dim array in DataFrame.

## Networking and Distributed

### Networking

* [2dust/v2rayN](https://github.com/2dust/v2rayN) - A GUI client for Windows, Linux and macOS, support Xray and sing-box and others
* [netchx/netch](https://github.com/netchx/netch) - A simple proxy client
* [TechnitiumSoftware/DnsServer](https://github.com/TechnitiumSoftware/DnsServer) - Technitium DNS Server
* [BornToBeRoot/NETworkManager](https://github.com/BornToBeRoot/NETworkManager) - A powerful open-source tool for managing networks and troubleshooting network problems!
* [HMBSbige/ShadowsocksR-Windows](https://github.com/HMBSbige/ShadowsocksR-Windows) - Ship of Theseus *(archived)*
* [jstedfast/MailKit](https://github.com/jstedfast/MailKit) - A cross-platform .NET library for IMAP, POP3, and SMTP.
* [InterceptSuite/ProxyBridge](https://github.com/InterceptSuite/ProxyBridge) - Proxifier Alternative to redirect any Windows/MacOS/Linux TCP and UDP traffic to HTTP/Socks5 proxy
* [sta/websocket-sharp](https://github.com/sta/websocket-sharp) - A C# implementation of the WebSocket protocol client and server
* [proxysu/ProxySU](https://github.com/proxysu/ProxySU) - Xray,V2ray，Trojan，NaiveProxy, Trojan-Go, ShadowsocksR(SSR),Shadowsocks-libev及相关插件,MTProto+TLS 一键安装工具，windows下用（一键科学上网）
* [HMBSbige/NatTypeTester](https://github.com/HMBSbige/NatTypeTester) - 测试当前网络的 NAT 类型（STUN）
* [shadowsocksr-backup/shadowsocksr-csharp](https://github.com/shadowsocksr-backup/shadowsocksr-csharp)
* [Archeb/opentrace](https://github.com/Archeb/opentrace) - Open Source Visualized Route Tracing Tool for macOS, Windows, and Linux.
* [sshnet/SSH.NET](https://github.com/sshnet/SSH.NET) - SSH.NET is a Secure Shell (SSH) library for .NET, optimized for parallelism.
* [Azure/DotNetty](https://github.com/Azure/DotNetty) - DotNetty project – a port of netty, event-driven asynchronous network application framework
* [kerryjiang/SuperSocket](https://github.com/kerryjiang/SuperSocket) - SuperSocket is a high-performance, extensible socket server application framework for .NET. It provides a robust architecture for building custom network communication applications with support for multiple protocols including TCP, UDP, and WebSocket.
* [RevenantX/LiteNetLib](https://github.com/RevenantX/LiteNetLib) - Lite reliable UDP library for Mono and .NET
* [robinrodricks/FluentFTP](https://github.com/robinrodricks/FluentFTP) - An FTP and FTPS client for .NET & .NET Standard, optimized for speed. Provides extensive FTP commands, File uploads/downloads, SSL/TLS connections, Automatic directory listing parsing, File hashing/checksums, File permissions/CHMOD, FTP proxies, FXP support, UTF-8 support, Async/await support, Powershell support and more. Written entirely in C#.
* [lukencode/FluentEmail](https://github.com/lukencode/FluentEmail) - All in one email sender for .NET. Supports popular senders (SendGrid, MailGun, etc) and Razor templates.
* [SteamRE/SteamKit](https://github.com/SteamRE/SteamKit) - SteamKit2 is a .NET library designed to interoperate with Valve's Steam network. It aims to provide a simple, yet extensible, interface to perform various actions on the network.
* [chronoxor/NetCoreServer](https://github.com/chronoxor/NetCoreServer) - Ultra fast and low latency asynchronous socket server & client C# .NET Core library with support TCP, SSL, UDP, HTTP, HTTPS, WebSocket protocols and 10K connections problem solution
* [LagrangeDev/Lagrange.Core](https://github.com/LagrangeDev/Lagrange.Core) - An Implementation of NTQQ Protocol, with Pure C#, Derived from Konata.Core
* [statianzo/Fleck](https://github.com/statianzo/Fleck) - C# Websocket Implementation
* [OPCFoundation/UA-.NETStandard](https://github.com/OPCFoundation/UA-.NETStandard) - OPC Unified Architecture .NET Standard
* [vpnhood/VpnHood](https://github.com/vpnhood/VpnHood) - Undetectable, Fast, Cross-Platform, Free VPN
* [dathlin/HslCommunication](https://github.com/dathlin/HslCommunication) - A very popular industrial Internet of Things communication plug-in. Using this dll can be very convenient, stable, and fast to obtain data from PLC equipment of multiple brands, and also supports redis, mqtt, websocket, etc., which can let your data on the network Free transmission, reducing enterprise development costs.
* [myrtille-rdp/myrtille](https://github.com/myrtille-rdp/myrtille) - A native HTML4 / HTML5 Remote Desktop Protocol and SSH client
* [sipsorcery-org/sipsorcery](https://github.com/sipsorcery-org/sipsorcery) - A WebRTC, SIP and VoIP library for C# and .NET. Designed for real-time communications apps.
* [MortezaBashsiz/CFScanner](https://github.com/MortezaBashsiz/CFScanner) - Cloudflare scanner
* [RiptideNetworking/Riptide](https://github.com/RiptideNetworking/Riptide) - Lightweight C# networking solution for multiplayer games.
* [RRQM/TouchSocket](https://github.com/RRQM/TouchSocket) - TouchSocket is an integrated .NET networking framework that includes modules for socket, TCP, UDP, SSL, named pipes, HTTP, WebSocket, RPC, and more. It offers a one-stop solution for TCP packet issues and enables quick implementation of custom data message parsing using protocol templates.
* [MirrorNetworking/Telepathy](https://github.com/MirrorNetworking/Telepathy) - Simple, message based, MMO Scale TCP networking in C#. And no magic.
* [NModbus/NModbus](https://github.com/NModbus/NModbus) - NModbus is a C# implementation of the Modbus protocol.
* [KumoKyaku/kcp](https://github.com/KumoKyaku/kcp) - KCP C#版。线程安全，运行时无alloc，对gc无压力。
* [NModbus4/NModbus4](https://github.com/NModbus4/NModbus4) - NModbus4 is a C# implementation of the Modbus protocol. This project is archived in favor of https://github.com/NModbus/NModbus *(archived)*
* [MichaCo/DnsClient.NET](https://github.com/MichaCo/DnsClient.NET) - DnsClient.NET is a simple yet very powerful and high performant open source library for the .NET Framework to do DNS lookups
* [InvisibleManVPN/InvisibleMan-XRayClient](https://github.com/InvisibleManVPN/InvisibleMan-XRayClient) - A client for xray core
* [cosullivan/SmtpServer](https://github.com/cosullivan/SmtpServer) - A SMTP Server component written in C#
* [doghappy/socket.io-client-csharp](https://github.com/doghappy/socket.io-client-csharp) - socket.io-client implemention for .NET
* [Quobject/SocketIoClientDotNet](https://github.com/Quobject/SocketIoClientDotNet) - Socket.IO Client Library for .Net
* [BogdanovKirill/RtspClientSharp](https://github.com/BogdanovKirill/RtspClientSharp) - Pure C# RTSP client for .NET Standard without external dependencies and with true async nature. I welcome contributions.
* [Marfusios/websocket-client](https://github.com/Marfusios/websocket-client) - 🔧 .NET/C# websocket client library
* [dotnet/WatsonTcp](https://github.com/dotnet/WatsonTcp) - WatsonTcp is the easiest way to build TCP-based clients and servers in C#.
* [PcapDotNet/Pcap.Net](https://github.com/PcapDotNet/Pcap.Net) - .NET wrapper for WinPcap written in C++/CLI and C#, which features almost all WinPcap features and includes a packet interpretation framework.
* [MarcFletcher/NetworkComms.Net](https://github.com/MarcFletcher/NetworkComms.Net) - NetworkComms.Net is a high performance cross-platform network library written in C#.

### RPC and Messaging

* [SignalR/SignalR](https://github.com/SignalR/SignalR) - Incredibly simple real-time web for .NET
* [MassTransit/MassTransit](https://github.com/MassTransit/MassTransit) - Distributed Application Framework for .NET
* [dotnetcore/CAP](https://github.com/dotnetcore/CAP) - Distributed transaction solution in micro-service base on eventually consistency, also an eventbus with Outbox pattern
* [dotnet/MQTTnet](https://github.com/dotnet/MQTTnet) - MQTTnet is a high performance .NET library for MQTT based communication. It provides a MQTT client and a MQTT server (broker). The implementation is based on the documentation from http://mqtt.org/.
* [grpc/grpc-dotnet](https://github.com/grpc/grpc-dotnet) - gRPC for .NET
* [Cysharp/MagicOnion](https://github.com/Cysharp/MagicOnion) - Unified Realtime/API framework for .NET platform and Unity.
* [Redth/PushSharp](https://github.com/Redth/PushSharp) - A server-side library for sending Push Notifications to iOS (iPhone/iPad APNS), Android (C2DM and GCM - Google Cloud Message), Windows Phone, Windows 8, Amazon, Blackberry, and (soon) FirefoxOS devices!
* [martinothamar/Mediator](https://github.com/martinothamar/Mediator) - A high performance implementation of Mediator pattern in .NET using source generators.
* [microsurging/surging](https://github.com/microsurging/surging) - Surging is a micro-service engine that provides a lightweight, high-performance, modular RPC request pipeline. support Event-based Asynchronous Pattern and reactive programming.
* [zeromq/netmq](https://github.com/zeromq/netmq) - A 100% native C# implementation of ZeroMQ for .NET
* [rebus-org/Rebus](https://github.com/rebus-org/Rebus) - :bus: Simple and lean service bus implementation for .NET
* [BrighterCommand/Brighter](https://github.com/BrighterCommand/Brighter) - A framework for building messaging apps with .NET and C#.
* [aspnet/SignalR](https://github.com/aspnet/SignalR) - [Archived] Incredibly simple real-time web for ASP.NET Core. Project moved to https://github.com/aspnet/AspNetCore *(archived)*
* [JasperFx/wolverine](https://github.com/JasperFx/wolverine) - Supercharged .NET server side development!
* [Particular/NServiceBus](https://github.com/Particular/NServiceBus) - The gold standard for async .NET microservices on Azure, AWS and on-prem
* [Cysharp/MessagePipe](https://github.com/Cysharp/MessagePipe) - High performance in-memory/distributed messaging pipeline for .NET and Unity.
* [CoreWCF/CoreWCF](https://github.com/CoreWCF/CoreWCF) - Main repository for the Core WCF project
* [gautema/CQRSlite](https://github.com/gautema/CQRSlite) - A lightweight framework to help creating CQRS and Eventsourcing applications in C#
* [Lachee/discord-rpc-csharp](https://github.com/Lachee/discord-rpc-csharp) - C# custom implementation for Discord Rich Presence. Not deprecated and still available!
* [nats-io/nats.net.v1](https://github.com/nats-io/nats.net.v1) - The official C# Client for NATS
* [nats-io/nats.net](https://github.com/nats-io/nats.net) - Async .NET client for NATS: pub/sub, request/reply, JetStream, KV, Object Store, Services

### Distributed Systems

* [dotnet/orleans](https://github.com/dotnet/orleans) - Cloud Native application framework for .NET
* [dvf/blockchain](https://github.com/dvf/blockchain) - A simple Blockchain in Python
* [neo-project/neo](https://github.com/neo-project/neo) - NEO Smart Economy
* [madelson/DistributedLock](https://github.com/madelson/DistributedLock) - A .NET library for distributed synchronization
* [Nethereum/Nethereum](https://github.com/Nethereum/Nethereum) - Ethereum .Net cross platform integration library
* [FoundatioFx/Foundatio](https://github.com/FoundatioFx/Foundatio) - Pluggable foundation blocks for building distributed apps.
* [MetacoSA/NBitcoin](https://github.com/MetacoSA/NBitcoin) - Comprehensive Bitcoin library for the .NET framework.
* [samcook/RedLock.net](https://github.com/samcook/RedLock.net) - An implementation of the Redlock algorithm in C#
* [snatch-dev/Convey](https://github.com/snatch-dev/Convey) - A simple recipe for .NET Core microservices. *(archived)*
* [bonesoul/CoiniumServ](https://github.com/bonesoul/CoiniumServ) - Next-gen crypto currency mining pool software
* [stratisproject/StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) - Bitcoin full node in C# *(archived)*
* [PlayFab/consuldotnet](https://github.com/PlayFab/consuldotnet) - .NET API for Consul (http://www.consul.io/) *(archived)*

### Cloud and Infrastructure

* [microsoft/aspire](https://github.com/microsoft/aspire) - Aspire is the tool for code-first, extensible, observable dev and deploy.
* [actions/runner](https://github.com/actions/runner) - The Runner for GitHub Actions :rocket:
* [Azure/azure-sdk-for-net](https://github.com/Azure/azure-sdk-for-net) - This repository is for active development of the Azure SDK for .NET. For consumers of the SDK we recommend visiting our public developer docs at https://learn.microsoft.com/dotnet/azure/ or our versioned developer docs at https://azure.github.io/azure-sdk-for-net.
* [lambci/docker-lambda](https://github.com/lambci/docker-lambda) - Docker images and test runners that replicate the live AWS Lambda environment *(archived)*
* [dotnet/tye](https://github.com/dotnet/tye) - Tye is a tool that makes developing, testing, and deploying microservices and distributed applications easier. Project Tye includes a local orchestrator to make developing microservices easier and the ability to deploy microservices to Kubernetes with minimal configuration. *(archived)*
* [Azure/azure-powershell](https://github.com/Azure/azure-powershell) - Microsoft Azure PowerShell
* [projectkudu/kudu](https://github.com/projectkudu/kudu) - Kudu is the engine behind git/hg deployments, WebJobs, and various other features in Azure Web Sites. It can also run outside of Azure. *(archived)*
* [dotnet/Docker.DotNet](https://github.com/dotnet/Docker.DotNet) - :whale: .NET (C#) Client Library for Docker API
* [Azure/azure-functions-host](https://github.com/Azure/azure-functions-host) - The host/runtime that powers Azure Functions
* [microsoft/azure-pipelines-agent](https://github.com/microsoft/azure-pipelines-agent) - Azure Pipelines Agent 🚀
* [Azure/azure-functions-core-tools](https://github.com/Azure/azure-functions-core-tools) - Command line tools for Azure Functions
* [kubernetes-client/csharp](https://github.com/kubernetes-client/csharp) - Officially supported dotnet Kubernetes Client library
* [mivano/azure-cost-cli](https://github.com/mivano/azure-cost-cli) - CLI tool to perform cost analysis on your Azure subscription
* [googleapis/google-cloud-dotnet](https://github.com/googleapis/google-cloud-dotnet) - Google Cloud Client Libraries for .NET
* [NetSparkleUpdater/NetSparkle](https://github.com/NetSparkleUpdater/NetSparkle) - NetSparkle is a C#, cross-platform, highly-configurable software update framework with pre-built UI for .NET developers compatible with .NET 4.6.2/.NET 6+, WinForms, WPF, and Avalonia; uses Ed25519 signatures. View basic usage here in the README and try the samples for yourself.

### Monitoring and Observability

* [opserver/Opserver](https://github.com/opserver/Opserver) - Stack Exchange's Monitoring System
* [Xabaril/AspNetCore.Diagnostics.HealthChecks](https://github.com/Xabaril/AspNetCore.Diagnostics.HealthChecks) - Enterprise HealthChecks for ASP.NET Core Diagnostics Package
* [open-telemetry/opentelemetry-dotnet](https://github.com/open-telemetry/opentelemetry-dotnet) - The OpenTelemetry .NET Client
* [exceptionless/Exceptionless](https://github.com/exceptionless/Exceptionless) - Exceptionless application
* [AppMetrics/AppMetrics](https://github.com/AppMetrics/AppMetrics) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application.
* [prometheus-net/prometheus-net](https://github.com/prometheus-net/prometheus-net) - .NET library to instrument your code with Prometheus metrics
* [open-telemetry/community](https://github.com/open-telemetry/community) - OpenTelemetry community content
* [opentracing/opentracing-csharp](https://github.com/opentracing/opentracing-csharp) - OpenTracing API for C# (.NET). 🛑 This library is DEPRECATED! https://github.com/opentracing/specification/issues/163 *(archived)*

## User Interface

### GUI Toolkits

* [AvaloniaUI/Avalonia](https://github.com/AvaloniaUI/Avalonia) - Develop Desktop, Embedded, Mobile and WebAssembly apps with C# and XAML. The future of .NET UI
* [MaterialDesignInXAML/MaterialDesignInXamlToolkit](https://github.com/MaterialDesignInXAML/MaterialDesignInXamlToolkit) - Google's Material Design in XAML & WPF, for C# & VB.Net.
* [cefsharp/CefSharp](https://github.com/cefsharp/CefSharp) - .NET (WPF and Windows Forms) bindings for the Chromium Embedded Framework
* [unoplatform/uno](https://github.com/unoplatform/uno) - Open-source platform for building cross-platform native Mobile, Web, Desktop, and Embedded apps from a single C#/XAML codebase. Work from any IDE/CLI with Hot Reload, Visual Designer, MCPs, and Skills built for modern .NET workflows. 200M+ NuGet downloads.
* [MahApps/MahApps.Metro](https://github.com/MahApps/MahApps.Metro) - A framework that allows developers to cobble together a better UI for their own WPF applications with minimal effort.
* [lepoco/wpfui](https://github.com/lepoco/wpfui) - WPF UI provides the Fluent experience in your known and loved WPF framework. Intuitive design, themes, navigation and new immersive controls. All natively and effortlessly.
* [reactiveui/ReactiveUI](https://github.com/reactiveui/ReactiveUI) - An advanced, composable, functional reactive model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming. ReactiveUI allows you to abstract mutable state away from your user interfaces, express the idea around a feature in one readable place and improve the testability of your application.
* [dotnet/wpf](https://github.com/dotnet/wpf) - WPF is a .NET Core UI framework for building Windows desktop applications.
* [ElectronNET/Electron.NET](https://github.com/ElectronNET/Electron.NET) - :electron: Build cross platform desktop apps with ASP.NET Core (Razor Pages, MVC, Blazor).
* [HandyOrg/HandyControl](https://github.com/HandyOrg/HandyControl) - Contains some simple and commonly used WPF controls
* [PrismLibrary/Prism](https://github.com/PrismLibrary/Prism) - Prism is a framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Xamarin Forms, and Uno / Win UI Applications..
* [CommunityToolkit/WindowsCommunityToolkit](https://github.com/CommunityToolkit/WindowsCommunityToolkit) - ARCHIVE - New Repo: https://aka.ms/toolkit/windows *(archived)*
* [Kinnara/ModernWpf](https://github.com/Kinnara/ModernWpf) - Modern styles and controls for your WPF applications
* [dotnet/winforms](https://github.com/dotnet/winforms) - Windows Forms is a .NET UI framework for building Windows desktop applications.
* [pojala/electrino](https://github.com/pojala/electrino) - Desktop runtime for apps built on web technologies, using the system's own web browser engine
* [xceedsoftware/wpftoolkit](https://github.com/xceedsoftware/wpftoolkit) - All the controls missing in WPF. Over 1 million downloads.
* [picoe/Eto](https://github.com/picoe/Eto) - Cross platform GUI framework for desktop and mobile applications in .NET
* [MvvmCross/MvvmCross](https://github.com/MvvmCross/MvvmCross) - The .NET MVVM framework for cross-platform solutions, including Android, iOS, MacCatalyst, macOS, tvOS, WPF, WinUI
* [XuanchenLin/NanUI](https://github.com/XuanchenLin/NanUI) - NanUI is an open source .NET project for developers who want to create Windows desktop applications with HTML, CSS and JavaScript.
* [IgnaceMaes/MaterialSkin](https://github.com/IgnaceMaes/MaterialSkin) - Theming .NET WinForms, C# or VB.Net, to Google's Material Design Principles.
* [chromelyapps/Chromely](https://github.com/chromelyapps/Chromely) - Build Cross Platform HTML Desktop Apps on .NET using native GUI, HTML5, JavaScript, CSS, Owin, AspNetCore (MVC, RazorPages, Blazor) *(archived)*
* [Caliburn-Micro/Caliburn.Micro](https://github.com/Caliburn-Micro/Caliburn.Micro) - A small, yet powerful framework, designed for building applications across all XAML platforms. Its strong support for MV* patterns will enable you to build your solution quickly, without the need to sacrifice code quality or testability.
* [fluentribbon/Fluent.Ribbon](https://github.com/fluentribbon/Fluent.Ribbon) - WPF Ribbon control like in Office
* [kikipoulet/SukiUI](https://github.com/kikipoulet/SukiUI) - UI Theme for AvaloniaUI
* [kozw/mui](https://github.com/kozw/mui) - Modern UI for WPF *(archived)*
* [yhuse/SunnyUI](https://github.com/yhuse/SunnyUI) - SunnyUI.NET 是基于.NET Framework 4.0+、.NET6、.NET8、.NET9 框架的 C# WinForm UI、开源控件库、工具类库、扩展类库、多页面开发框架。
* [punker76/gong-wpf-dragdrop](https://github.com/punker76/gong-wpf-dragdrop) - The GongSolutions.WPF.DragDrop library is a drag'n'drop framework for WPF
* [gkngkc/UnityStandaloneFileBrowser](https://github.com/gkngkc/UnityStandaloneFileBrowser) - A native file browser for unity standalone platforms
* [kwwwvagaa/NetWinformControl](https://github.com/kwwwvagaa/NetWinformControl) - HZHControls,c#winfrom custom control, has better operation support for touch screen, the project is based on framework4.0, completely native control development, do not use any third-party controls, you can use it safely in your project (winfromcontrol/winformcontrol/.net).There are more abundant industrial controls that continue to increase in the ~~~
* [ButchersBoy/Dragablz](https://github.com/ButchersBoy/Dragablz) - Dragable and tearable tab control for WPF
* [ImGuiNET/ImGui.NET](https://github.com/ImGuiNET/ImGui.NET) - An ImGui wrapper for .NET.
* [Taiizor/ReaLTaiizor](https://github.com/Taiizor/ReaLTaiizor) - ReaLTaiizor is a .NET WinForms control library that offers a wide range of components and is user-friendly and design-focused.
* [aduskin/AduSkin](https://github.com/aduskin/AduSkin) - A Beautiful WPF Control UI
* [ComponentFactory/Krypton](https://github.com/ComponentFactory/Krypton) - Krypton WinForms components for .NET
* [microcharts-dotnet/Microcharts](https://github.com/microcharts-dotnet/Microcharts) - Simple, cross-platform chart library for .NET
* [miroiu/nodify](https://github.com/miroiu/nodify) - Highly performant and modular controls for node-based editors designed for data-binding and MVVM.
* [microsoft/AdaptiveCards](https://github.com/microsoft/AdaptiveCards) - A new way for developers to exchange card content in a common and consistent way.
* [MahApps/MahApps.Metro.IconPacks](https://github.com/MahApps/MahApps.Metro.IconPacks) - Awesome icon packs for WPF and UWP in one library
* [UnityTech/UIWidgets](https://github.com/UnityTech/UIWidgets) - UIWidget is a Unity Package which helps developers to create, debug and deploy efficient, cross-platform Apps. *(archived)*
* [irihitech/Semi.Avalonia](https://github.com/irihitech/Semi.Avalonia) - Avalonia theme inspired by Semi Design
* [SonyWWS/ATF](https://github.com/SonyWWS/ATF) - Authoring Tools Framework (ATF) is a set of C#/.NET components for making tools on Windows. ATF has been in continuous development in Sony Computer Entertainment's (SCE) Worldwide Studios central tools group since early 2005. ATF has been used by most SCE first party studios to make many custom tools such as Naughty Dog’s level editor and shader editor for The Last of Us, Guerrilla Games’ sequence editor for Killzone games (including the Killzone: Shadow Fall PS4 launch title), an animation blending tool at Santa Monica Studio, a level editor at Bend Studio, a visual state machine editor for Quantic Dream, sound editing tools, and many others.
* [WPFDevelopersOrg/WPFDevelopers](https://github.com/WPFDevelopersOrg/WPFDevelopers) - 🎉 Welcome to follow the official account of "WPFDevelopers"! It covers the basic controls and custom control library (screenshot controls) of WPF. This project will be constantly updated, welcome to us ⭐ ️
* [dockpanelsuite/dockpanelsuite](https://github.com/dockpanelsuite/dockpanelsuite) - DockPanel Suite - The Visual Studio inspired docking library for .NET WinForms
* [benruehl/adonis-ui](https://github.com/benruehl/adonis-ui) - Lightweight UI toolkit for WPF applications offering classic but enhanced windows visuals
* [dotnet/Comet](https://github.com/dotnet/Comet) - Comet is an MVU UIToolkit written in C# *(archived)*
* [ArthurHub/HTML-Renderer](https://github.com/ArthurHub/HTML-Renderer) - Cross framework (WinForms/WPF/PDF/Metro/Mono/etc.), Multipurpose (UI Controls / Image generation / PDF generation / etc.), 100% managed (C#), High performance HTML Rendering library.
* [ghost1372/HandyControls](https://github.com/ghost1372/HandyControls) - Contains some simple and commonly used WPF controls based on HandyControl
* [PavelTorgashov/FastColoredTextBox](https://github.com/PavelTorgashov/FastColoredTextBox) - Fast Colored TextBox for Syntax Highlighting. The text editor component for .NET.
* [OpenSilver/OpenSilver](https://github.com/OpenSilver/OpenSilver) - Build Cross-Platform Apps with C#, VB.NET, or F# and XAML. One codebase. Six platforms. Powered by WebAssembly and .NET.
* [ControlzEx/ControlzEx](https://github.com/ControlzEx/ControlzEx) - Shared Controlz for WPF and ... more
* [Wouterdek/NodeNetwork](https://github.com/Wouterdek/NodeNetwork) - A C# library with a WPF node editor component based on ReactiveUI
* [Catel/Catel](https://github.com/Catel/Catel) - An application development platform
* [VincentH-Net/CSharpForMarkup](https://github.com/VincentH-Net/CSharpForMarkup) - Concise, declarative C# UI markup for .NET browser / native UI frameworks
* [HeBianGu/WPF-ControlBase](https://github.com/HeBianGu/WPF-ControlBase) - Wpf封装的自定义控件资源库
* [dwmkerr/consolecontrol](https://github.com/dwmkerr/consolecontrol) - ConsoleControl is a C# class library that lets you embed a console in a WinForms or WPF application.
* [lolp1/Overlay.NET](https://github.com/lolp1/Overlay.NET) - An easy-to-use overlay library written in C# by Jacob Kemple.
* [Alex141/CalcBinding](https://github.com/Alex141/CalcBinding) - Advanced WPF Binding which supports expressions in Path property and other features
* [kwonganding/winform.controls](https://github.com/kwonganding/winform.controls) - 分享几年前开发的一套winform控件库。当时主要为开发公司内部ERP系统，重新设计实现了所有用到的Winform组建，包括Form窗体组建6个（支持换肤），基础控件25个。其中有很多参考借鉴其他开源组件，也有几个是集成的别人的组件，然后做了些调整。 现在已经好几年不做Winform开发了，整理一下共享出来，希望能够给需要的朋友一些帮助。
* [Unity-Technologies/com.unity.uiwidgets](https://github.com/Unity-Technologies/com.unity.uiwidgets) - UIWidgets is a Unity Package which helps developers to create, debug and deploy efficient, cross-platform Apps. *(archived)*

### Terminal and Console UI

* [spectreconsole/spectre.console](https://github.com/spectreconsole/spectre.console) - A .NET library that makes it easier to create beautiful console applications.
* [tui-cs/Terminal.Gui](https://github.com/tui-cs/Terminal.Gui) - Cross Platform Terminal UI toolkit for .NET
* [RazorConsole/RazorConsole](https://github.com/RazorConsole/RazorConsole) - Build agentic TUI applications with .NET Razor and Spectre.Console
* [tomakita/Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your .NET console output!
* [TomaszRewak/C-sharp-console-gui-framework](https://github.com/TomaszRewak/C-sharp-console-gui-framework) - A GUI framework for C# console applications
* [khalidabuhakmeh/ConsoleTables](https://github.com/khalidabuhakmeh/ConsoleTables) - Print out a nicely formatted table in a console application C#
* [PowerShell/ConsoleGuiTools](https://github.com/PowerShell/ConsoleGuiTools) - Modules that mix PowerShell and GUIs/CUIs! *(archived)*
* [shibayan/Sharprompt](https://github.com/shibayan/Sharprompt) - Interactive command-line based application framework for C#
* [tonerdo/readline](https://github.com/tonerdo/readline) - A Pure C# GNU-Readline like library for .NET/.NET Core
* [goblinfactory/konsole](https://github.com/goblinfactory/konsole) - Home of the simple console library consisting of ProgressBar, Window, Form, Draw & MockConsole (C# console progress bar with support for single or multithreaded progress updates) Window is a 100%-ish console compatible window, supporting all normal console writing to a windowed section of the screen, supporting scrolling and clipping of console output.
* [igor-kostromin/consoleframework](https://github.com/igor-kostromin/consoleframework) - Cross-platform toolkit for easy development of TUI applications.

### Mobile

* [dotnet/maui](https://github.com/dotnet/maui) - .NET MAUI is the .NET Multi-platform App UI, a framework for building native device applications spanning mobile, tablet, and desktop.
* [xamarin/Xamarin.Forms](https://github.com/xamarin/Xamarin.Forms) - Xamarin.Forms is no longer supported. Migrate your apps to .NET MAUI. *(archived)*
* [dotnet/macios](https://github.com/dotnet/macios) - .NET for iOS, Mac Catalyst, macOS, and tvOS provide open-source bindings of the Apple SDKs for use with .NET managed languages such as C#
* [CommunityToolkit/Maui](https://github.com/CommunityToolkit/Maui) - The .NET MAUI Community Toolkit is a community-created library that contains .NET MAUI Extensions, Advanced UI/UX Controls, and Behaviors to help make your life as a .NET MAUI developer easier
* [dotnet/android](https://github.com/dotnet/android) - .NET for Android provides open-source bindings of the Android SDK for use with .NET managed languages such as C#
* [xamarin/XamarinComponents](https://github.com/xamarin/XamarinComponents) - Plugins for Xamarin *(archived)*
* [xamarin/XamarinCommunityToolkit](https://github.com/xamarin/XamarinCommunityToolkit) - The Xamarin Community Toolkit is a collection of Animations, Behaviors, Converters, and Effects for mobile development with Xamarin.Forms. It simplifies and demonstrates common developer tasks building iOS, Android, and UWP apps with Xamarin.Forms. *(archived)*
* [yasirkula/UnityNativeCamera](https://github.com/yasirkula/UnityNativeCamera) - A native Unity plugin to take pictures/record videos with device camera on Android & iOS
* [AndreiMisiukevich/CardView](https://github.com/AndreiMisiukevich/CardView) - CardsView | CarouselView | CoverflowView | CubeView for Xamarin.Forms
* [dotnet/Microsoft.Maui.Graphics.Controls](https://github.com/dotnet/Microsoft.Maui.Graphics.Controls) - Experimental Microsoft.Maui.Graphics.Controls - Build drawn controls (Cupertino, Fluent and Material) *(archived)*

### Applications and End User Tools

* [shadowsocks/shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows) - A C# port of shadowsocks
* [jellyfin/jellyfin](https://github.com/jellyfin/jellyfin) - The Free Software Media System - Server Backend & API
* [files-community/Files](https://github.com/files-community/Files) - A modern file manager that helps users organize their files and folders.
* [ShareX/ShareX](https://github.com/ShareX/ShareX) - ShareX is a free and open-source application that enables users to capture or record any area of their screen with a single keystroke. It also supports uploading images, text, and various file types to a wide range of destinations.
* [huiyadanli/RevokeMsgPatcher](https://github.com/huiyadanli/RevokeMsgPatcher) - :trollface: A hex editor for WeChat/QQ/TIM - PC版微信/QQ/TIM防撤回补丁（我已经看到了，撤回也没用了）
* [DevToys-app/DevToys](https://github.com/DevToys-app/DevToys) - A Swiss Army knife for developers.
* [microsoft/calculator](https://github.com/microsoft/calculator) - Windows Calculator: A simple yet powerful calculator that ships with Windows
* [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) - OfficeCLI is the first and best Office suite purpose-built for AI agents to read, edit, and automate Word, Excel, and PowerPoint files. Free, open-source, single binary, no Office installation required.
* [NickeManarin/ScreenToGif](https://github.com/NickeManarin/ScreenToGif) - 🎬 ScreenToGif allows you to record a selected area of your screen, edit and save it as a gif or video.
* [BeyondDimension/SteamTools](https://github.com/BeyondDimension/SteamTools) - 🛠「Watt Toolkit」是一个开源跨平台的多功能 Steam 工具箱。
* [k1tbyte/Wand-Enhancer](https://github.com/k1tbyte/Wand-Enhancer) - Advanced UX and interoperability extension for Wand (WeMod) app
* [QL-Win/QuickLook](https://github.com/QL-Win/QuickLook) - Bring macOS “Quick Look” feature to Windows
* [CodeHubApp/CodeHub](https://github.com/CodeHubApp/CodeHub) - CodeHub is an iOS application written using Xamarin *(archived)*
* [QuantConnect/Lean](https://github.com/QuantConnect/Lean) - Lean Algorithmic Trading Engine by QuantConnect (Python, C#)
* [BCUninstaller/Bulk-Crap-Uninstaller](https://github.com/BCUninstaller/Bulk-Crap-Uninstaller) - Remove large amounts of unwanted applications quickly.
* [BluePointLilac/ContextMenuManager](https://github.com/BluePointLilac/ContextMenuManager) - 🖱️ 纯粹的Windows右键菜单管理程序
* [rocksdanister/lively](https://github.com/rocksdanister/lively) - Free and open-source software that allows users to set animated desktop wallpapers and screensavers powered by WinUI 3.
* [TGSAN/CMWTAT_Digital_Edition](https://github.com/TGSAN/CMWTAT_Digital_Edition) - CloudMoe Windows 10/11 Activation Toolkit get digital license, the best open source Win 10/11 activator in GitHub. GitHub 上最棒的开源 Win10/Win11 数字权利（数字许可证）激活工具！
* [hellzerg/optimizer](https://github.com/hellzerg/optimizer) - The finest Windows Optimizer *(archived)*
* [Tyrrrz/YoutubeDownloader](https://github.com/Tyrrrz/YoutubeDownloader) - Downloads videos and playlists from YouTube
* [nilaoda/N_m3u8DL-CLI](https://github.com/nilaoda/N_m3u8DL-CLI) - [.NET] m3u8 downloader 开源的命令行m3u8/HLS/dash下载器，支持普通AES-128-CBC解密，多线程，自定义请求头等. 支持简体中文,繁体中文和英文. English Supported.
* [Jackett/Jackett](https://github.com/Jackett/Jackett) - API Support for your favorite torrent trackers
* [Flow-Launcher/Flow.Launcher](https://github.com/Flow-Launcher/Flow.Launcher) - :mag: Quick file search & app launcher for Windows with community-made plugins
* [Sonarr/Sonarr](https://github.com/Sonarr/Sonarr) - Smart PVR for newsgroup and bittorrent users.
* [Tichau/FileConverter](https://github.com/Tichau/FileConverter) - File Converter is a very simple tool which allows you to convert and compress files using the context menu in windows explorer.
* [seerge/g-helper](https://github.com/seerge/g-helper) - Lightweight Armoury Crate alternative for Asus laptops with nearly the same functionality. Works with ROG Zephyrus, Flow, TUF, Strix, Scar, ProArt, Vivobook, Zenbook, Expertbook, ROG Ally, and more.
* [duplicati/duplicati](https://github.com/duplicati/duplicati) - Store securely encrypted backups in the cloud!
* [d2phap/ImageGlass](https://github.com/d2phap/ImageGlass) - 🏞 A fast, open-source, modern image viewer for 90+ formats – including WEBP, GIF, SVG, AVIF, JXL, HEIC and more – built for smooth browsing across Windows, macOS, and Linux.
* [Radarr/Radarr](https://github.com/Radarr/Radarr) - Movie organizer/manager for usenet and torrent users.
* [SubtitleEdit/subtitleedit](https://github.com/SubtitleEdit/subtitleedit) - the subtitle editor :)
* [JosefNemec/Playnite](https://github.com/JosefNemec/Playnite) - Video game library manager with support for wide range of 3rd party libraries and game emulation support, providing one unified interface for your games.
* [nilaoda/BBDown](https://github.com/nilaoda/BBDown) - Bilibili Downloader. 一个命令行式哔哩哔哩下载器. *(archived)*
* [JustArchiNET/ArchiSteamFarm](https://github.com/JustArchiNET/ArchiSteamFarm) - C# application with primary purpose of farming Steam cards from multiple accounts simultaneously.
* [memstechtips/Winhance](https://github.com/memstechtips/Winhance) - Application designed to optimize, customize and enhance your Windows experience.
* [wmjordan/PDFPatcher](https://github.com/wmjordan/PDFPatcher) - PDF补丁丁——PDF工具箱，可以编辑书签、剪裁旋转页面、解除限制、提取或合并文档，探查文档结构，提取图片、转成图片等等
* [OdysseusYuan/LKY_OfficeTools](https://github.com/OdysseusYuan/LKY_OfficeTools) - 一键自动化 下载、安装、激活 Office 的利器。
* [Tyrrrz/DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter) - Saves Discord chat logs to a file
* [xupefei/Locale-Emulator](https://github.com/xupefei/Locale-Emulator) - Yet Another System Region and Language Simulator *(archived)*
* [Kareadita/Kavita](https://github.com/Kareadita/Kavita) - Kavita is a fast, feature rich, cross platform reading server. Built with the goal of being a full solution for all your reading needs. Setup your own server and share your reading collection with your friends and family.
* [lostindark/DriverStoreExplorer](https://github.com/lostindark/DriverStoreExplorer) - Driver Store Explorer
* [File-New-Project/EarTrumpet](https://github.com/File-New-Project/EarTrumpet) - EarTrumpet - Volume Control for Windows
* [mRemoteNG/mRemoteNG](https://github.com/mRemoteNG/mRemoteNG) - mRemoteNG is the next generation of mRemote, open source, tabbed, multi-protocol, remote connections manager.
* [MathewSachin/Captura](https://github.com/MathewSachin/Captura) - Capture Screen, Audio, Cursor, Mouse Clicks and Keystrokes
* [studyzy/imewlconverter](https://github.com/studyzy/imewlconverter) - ”深蓝词库转换“ 一款开源免费的输入法词库转换程序
* [runcat-dev/RunCat365](https://github.com/runcat-dev/RunCat365) - A cute running cat animation on your windows taskbar.
* [0x7c13/Notepads](https://github.com/0x7c13/Notepads) - A modern, lightweight text editor with a minimalist design.
* [AutoDarkMode/Windows-Auto-Night-Mode](https://github.com/AutoDarkMode/Windows-Auto-Night-Mode) - Automatically switches between the dark and light theme of Windows 10 and Windows 11
* [felixse/FluentTerminal](https://github.com/felixse/FluentTerminal) - A Terminal Emulator based on UWP and web technologies.
* [itsfatduck/optimizerDuck](https://github.com/itsfatduck/optimizerDuck) - Free, open-source Windows optimization tool for performance, privacy, and simplicity.
* [gibbed/SteamAchievementManager](https://github.com/gibbed/SteamAchievementManager) - A manager for game achievements in Steam.
* [LibreHardwareMonitor/LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) - Libre Hardware Monitor is free software that can monitor the temperature sensors, fan speeds, voltages, load and clock speeds of your computer.
* [LykosAI/StabilityMatrix](https://github.com/LykosAI/StabilityMatrix) - Multi-Platform Package Manager for Stable Diffusion
* [nilaoda/N_m3u8DL-RE](https://github.com/nilaoda/N_m3u8DL-RE) - Cross-Platform, modern and powerful stream downloader for MPD/M3U8/ISM. English/简体中文/繁體中文.
* [ZyperWave/ZyperWinOptimize](https://github.com/ZyperWave/ZyperWinOptimize) - ZyperWin++是一个轻便的Windows优化工具，适用于Win7-Win11最新版的优化，包括性能优化、服务项优化、垃圾清理等操作，还支持系统激活和Office快速安装。
* [Richasy/Bili.Uwp](https://github.com/Richasy/Bili.Uwp) - 适用于新系统UI的哔哩 *(archived)*
* [PixiEditor/PixiEditor](https://github.com/PixiEditor/PixiEditor) - PixiEditor is a Universal Editor for all your 2D needs
* [STranslate/STranslate](https://github.com/STranslate/STranslate) - A ready-to-go translation ocr tool developed with WPF/WPF 开发的一款即用即走的翻译、OCR工具
* [subhra74/xdm](https://github.com/subhra74/xdm) - Powerfull download accelerator and video downloader
* [BartoszCichecki/LenovoLegionToolkit](https://github.com/BartoszCichecki/LenovoLegionToolkit) - Lightweight Lenovo Vantage and Hotkeys replacement for Lenovo Legion laptops. *(archived)*
* [xM4ddy/OFGB](https://github.com/xM4ddy/OFGB) - GUI Tool To Remove Ads From Various Places Around Windows 11
* [builtbybel/FlyOOBE](https://github.com/builtbybel/FlyOOBE) - Fly through your Windows 11 setup 🐝
* [beeradmoore/dlss-swapper](https://github.com/beeradmoore/dlss-swapper)
* [Orbmu2k/nvidiaProfileInspector](https://github.com/Orbmu2k/nvidiaProfileInspector)
* [Prowlarr/Prowlarr](https://github.com/Prowlarr/Prowlarr) - Prowlarr is an indexer manager/proxy built on the popular *arr .net/reactjs base stack to integrate with your various PVR apps, supporting management of both Torrent Trackers and Usenet Indexers.
* [NickvisionApps/Parabolic](https://github.com/NickvisionApps/Parabolic) - Download web video and audio
* [randyrants/sharpkeys](https://github.com/randyrants/sharpkeys) - SharpKeys is a utility that manages a Registry key that allows Windows to remap one key to any other key.
* [LorisYounger/VPet](https://github.com/LorisYounger/VPet) - 虚拟桌宠模拟器 一个开源的桌宠软件, 可以内置到任何WPF应用程序
* [mgth/LittleBigMouse](https://github.com/mgth/LittleBigMouse) - DPI Aware mouse move across screens
* [andrewmd5/Borderless-Gaming](https://github.com/andrewmd5/Borderless-Gaming) - Play your favorite games in a borderless window; no more time consuming alt-tabs.
* [openhardwaremonitor/openhardwaremonitor](https://github.com/openhardwaremonitor/openhardwaremonitor) - Open Hardware Monitor
* [Diorser/LiteMonitor](https://github.com/Diorser/LiteMonitor) - 一款轻量级、高度可定制的 Windows桌面和任务栏硬件性能监控工具，支持监测 CPU、GPU、内存、磁盘、网速、FPS 计数、插件扩展及内存清理。A lightweight, customizable hardware monitor for the Windows desktop & taskbar. Features CPU/GPU/RAM/Network monitoring, FPS counter, plugin support, and memory optimization.
* [canton7/SyncTrayzor](https://github.com/canton7/SyncTrayzor) - Windows tray utility / filesystem watcher / launcher for Syncthing *(archived)*
* [rmcrackan/Libation](https://github.com/rmcrackan/Libation) - Libation: Liberate your Library
* [1Remote/1Remote](https://github.com/1Remote/1Remote) - One Remote Access Manager to Rule Them All
* [builtbybel/FluentCleaner](https://github.com/builtbybel/FluentCleaner) - FluentCleaner is the transparent, community-powered CCleaner alternative for Windows.
* [hanmin0822/MisakaTranslator](https://github.com/hanmin0822/MisakaTranslator) - 御坂翻译器—Galgame/文字游戏/漫画多语种实时机翻工具
* [ramjke/Translumo](https://github.com/ramjke/Translumo) - Advanced real-time screen translator for games, hardcoded subtitles in videos, static text and etc.
* [Lidarr/Lidarr](https://github.com/Lidarr/Lidarr) - Looks and smells like Sonarr but made for music.
* [builtbybel/Bloatynosy](https://github.com/builtbybel/Bloatynosy) - The Bloaty and the Nosy: No Bloat, No Problem!
* [rayenghanmi/RyTuneX](https://github.com/rayenghanmi/RyTuneX) - RyTuneX is a cutting-edge optimizer built with the WinUI 3 framework, designed to amplify the performance of Windows devices. Crafted for both Windows 10 and 11.
* [UnigramDev/Unigram](https://github.com/UnigramDev/Unigram) - Telegram for Windows
* [mpvnet-player/mpv.net](https://github.com/mpvnet-player/mpv.net) - 🎞 mpv.net is a media player for Windows with a modern GUI.
* [Mzying2001/CefFlashBrowser](https://github.com/Mzying2001/CefFlashBrowser) - Flash浏览器 / Flash Browser
* [Richasy/Bili.Copilot](https://github.com/Richasy/Bili.Copilot) - B站第三方 Windows 桌面客户端，使用 Windows App SDK 构建的原生应用
* [MicaForEveryone/MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone) - Mica For Everyone is a tool to enable backdrop effects on the title bars of Win32 apps on Windows 11.
* [timschneeb/GalaxyBudsClient](https://github.com/timschneeb/GalaxyBudsClient) - Unofficial Galaxy Buds Manager for Windows, macOS, Linux, and Android
* [builtbybel/ThisIsWin11](https://github.com/builtbybel/ThisIsWin11) - The real PowerToys for Windows 11 *(archived)*
* [Sophia-Community/SophiApp](https://github.com/Sophia-Community/SophiApp) - :zap: The most powerful open source tweaker on GitHub for fine-tuning Windows 10 & Windows 11
* [SpaceTimee/Sheas-Cealer](https://github.com/SpaceTimee/Sheas-Cealer) - Just Ceal It (可用于无代理合法抵御网络监听和开展网络研究)
* [greenshot/greenshot](https://github.com/greenshot/greenshot) - Greenshot for Windows - for more information look here:
* [Ponderfly/GoogleTranslateIpCheck](https://github.com/Ponderfly/GoogleTranslateIpCheck) - 扫描国内可用的谷歌翻译IP
* [kwsch/PKHeX](https://github.com/kwsch/PKHeX) - Pokémon Save File Editor
* [Planshit/Tai](https://github.com/Planshit/Tai) - 👻 在Windows上统计软件使用时长和网站浏览时长
* [immense/Remotely](https://github.com/immense/Remotely) - A remote control and remote scripting solution, built with .NET 8, Blazor, and SignalR.
* [t1m0thyj/WinDynamicDesktop](https://github.com/t1m0thyj/WinDynamicDesktop) - Port of macOS Mojave Dynamic Desktop feature to Windows
* [IgorMundstein/WinMemoryCleaner](https://github.com/IgorMundstein/WinMemoryCleaner) - This free RAM cleaner uses native Windows features to optimize memory areas. It's a compact, portable, and smart application.
* [2dust/clashN](https://github.com/2dust/clashN) - A clash client for Windows, support Mihomo
* [TheJoeFin/Text-Grab](https://github.com/TheJoeFin/Text-Grab) - Use OCR in Windows quickly and easily with Text Grab. With optional background process and notifications.
* [hbons/SparkleShare](https://github.com/hbons/SparkleShare) - Share and collaborate by syncing with any Git repository instantly. Linux, macOS, and Windows
* [Jeric-X/SyncClipboard](https://github.com/Jeric-X/SyncClipboard) - 跨平台剪贴板同步、历史记录管理工具 / Cross-platform cipboard syncing, history management tool
* [MediaBrowser/Emby](https://github.com/MediaBrowser/Emby) - Emby Server is a personal media server with apps on just about every device.
* [Stability-AI/StableSwarmUI](https://github.com/Stability-AI/StableSwarmUI) - StableSwarmUI, A Modular Stable Diffusion Web-User-Interface, with an emphasis on making powertools easily accessible, high performance, and extensibility.
* [HearthSim/Hearthstone-Deck-Tracker](https://github.com/HearthSim/Hearthstone-Deck-Tracker) - A deck tracker and deck manager for Hearthstone on Windows
* [indiff/qttabbar](https://github.com/indiff/qttabbar) - QTTabBar is a small tool that allows you to use tab multi label function in Windows Explorer. https://www.yuque.com/indiff/qttabbar
* [BililiveRecorder/BililiveRecorder](https://github.com/BililiveRecorder/BililiveRecorder) - 录播姬 | mikufans 生放送录制
* [emoacht/Monitorian](https://github.com/emoacht/Monitorian) - A Windows desktop tool to adjust the brightness of multiple monitors with ease
* [Code52/carnac](https://github.com/Code52/carnac) - A utility to give some insight into how you use your keyboard
* [cmliu/SubsCheck-Win-GUI](https://github.com/cmliu/SubsCheck-Win-GUI) - SubsCheck 为 Windows 用户设计的 GUI 程序界面。
* [mcmonkeyprojects/SwarmUI](https://github.com/mcmonkeyprojects/SwarmUI) - SwarmUI (formerly StableSwarmUI), A Modular Stable Diffusion Web-User-Interface, with an emphasis on making powertools easily accessible, high performance, and extensibility.
* [Scighost/Starward](https://github.com/Scighost/Starward) - Game Launcher for miHoYo - 米家游戏启动器
* [cyanfish/naps2](https://github.com/cyanfish/naps2) - Scan documents to PDF and more, as simply as possible.
* [metatube-community/jellyfin-plugin-metatube](https://github.com/metatube-community/jellyfin-plugin-metatube) - MetaTube Plugin for Jellyfin/Emby
* [OptiKey/OptiKey](https://github.com/OptiKey/OptiKey) - OptiKey - Full computer control and speech with your eyes
* [dremin/RetroBar](https://github.com/dremin/RetroBar) - Classic Windows 95, 98, Me, 2000, XP, Vista taskbar for modern versions of Windows
* [unchihugo/FluentFlyout](https://github.com/unchihugo/FluentFlyout) - The modern Flyout app for Windows 11, built with Fluent 2 Design principles. Media Flyouts, Taskbar Widgets and more.
* [PCL-Community/PCL-CE](https://github.com/PCL-Community/PCL-CE) - PCL 社区版 由社区开发者维护与管理
* [huynhsontung/Screenbox](https://github.com/huynhsontung/Screenbox) - LibVLC-based media player for the Universal Windows Platform
* [umlx5h/LLPlayer](https://github.com/umlx5h/LLPlayer) - The media player for language learning, with dual subtitles, AI-generated subtitles, real-time translation, and more!
* [Ombi-app/Ombi](https://github.com/Ombi-app/Ombi) - Want a Movie or TV Show on Plex/Emby/Jellyfin? Use Ombi!
* [jitwxs/163MusicLyrics](https://github.com/jitwxs/163MusicLyrics) - 云音乐歌词获取处理工具【网易云、QQ音乐】
* [miroslavpejic85/p2p](https://github.com/miroslavpejic85/p2p) - 🖥️ P2P Remote Desktop - Portable peer-to-peer remote desktop with no installation required.
* [ModernFlyouts-Community/ModernFlyouts](https://github.com/ModernFlyouts-Community/ModernFlyouts) - A modern Fluent Design replacement for the old Metro themed flyouts present in Windows. *(archived)*
* [PintaProject/Pinta](https://github.com/PintaProject/Pinta) - Simple GTK Paint Program
* [microsoft/VisualStudioUninstaller](https://github.com/microsoft/VisualStudioUninstaller) - Visual Studio Uninstallation sometimes can be unreliable and often leave out a lot of unwanted artifacts. Visual Studio Uninstaller is designed to thoroughly and reliably remove these unwanted artifacts. *(archived)*
* [rnwood/smtp4dev](https://github.com/rnwood/smtp4dev) - smtp4dev - the fake smtp email server for development and testing
* [lay295/TwitchDownloader](https://github.com/lay295/TwitchDownloader) - Twitch VOD/Clip Downloader - Chat Download/Render/Replay
* [slskd/slskd](https://github.com/slskd/slskd) - A modern client-server application for the Soulseek file sharing network.
* [skydevil88/XboxDownload](https://github.com/skydevil88/XboxDownload) - Xbox Download Assistant (Xbox下载助手) — Supports download acceleration for Xbox, Microsoft Store, PlayStation, Nintendo Switch, EA App, Battle.net, Epic Games, Ubisoft Connect, Riot Games, and Rockstar Games, and fixes access issues for Steam Store & Community and GitHub.
* [SteveTheKiller/KillerPDF](https://github.com/SteveTheKiller/KillerPDF) - Free and open-source PDF editor for Windows with a built-in PDF 2.0 engine. View, annotate, OCR, merge, split, crop, rotate, compare, edit text, draw, sign, fill forms, print, flatten, and open password-protected PDFs without a subscription.
* [SuxueCode/WechatBakTool](https://github.com/SuxueCode/WechatBakTool) - 基于C#的微信PC版聊天记录备份工具，提供图形界面，解密微信数据库并导出聊天记录。
* [SakiRinn/LiveCaptions-Translator](https://github.com/SakiRinn/LiveCaptions-Translator) - Lightweight and powerful real-time audio/speech translation tool based on Windows LiveCaptions.
* [0x90d/videoduplicatefinder](https://github.com/0x90d/videoduplicatefinder) - Video Duplicate Finder - Crossplatform
* [luolangaga/tubatools](https://github.com/luolangaga/tubatools) - 图吧工具箱 winUI3 版
* [Ruben2776/PicView](https://github.com/Ruben2776/PicView) - Fast, free and customizable picture viewer
* [builtbybel/FluentTweaker](https://github.com/builtbybel/FluentTweaker)
* [Tianyu199509/DeskBox](https://github.com/Tianyu199509/DeskBox) - A free, open-source Windows desktop organizer with native-feeling WinUI 3 widgets.
* [Readarr/Readarr](https://github.com/Readarr/Readarr) - Book Manager and Automation (Sonarr for Ebooks) *(archived)*
* [stevencohn/OneMore](https://github.com/stevencohn/OneMore) - A OneNote add-in with simple, yet powerful and useful features
* [LorenzCK/OnTopReplica](https://github.com/LorenzCK/OnTopReplica) - A real-time always-on-top “replica” of a window of your choice (on Windows).
* [Belphemur/SoundSwitch](https://github.com/Belphemur/SoundSwitch) - C# application to switch default playing device. Download: https://soundswitch.aaflalo.me/
* [lin-ycv/EverythingPowerToys](https://github.com/lin-ycv/EverythingPowerToys) - Everything search plugin for PowerToys Run
* [cairoshell/cairoshell](https://github.com/cairoshell/cairoshell) - Cairo is a customizable, intuitive desktop environment for Windows.
* [SteamRE/DepotDownloader](https://github.com/SteamRE/DepotDownloader) - Steam depot downloader utilizing the SteamKit2 library.
* [Dailin521/codex-provider-sync](https://github.com/Dailin521/codex-provider-sync) - Synchronize Codex session provider metadata across rollout files and SQLite state.
* [ChangemakerStudios/Papercut-SMTP](https://github.com/ChangemakerStudios/Papercut-SMTP) - Papercut SMTP -- The Simple Desktop Email Server
* [PLFJY/ContextMenuMgr](https://github.com/PLFJY/ContextMenuMgr) - Context Menu Manager Plus 是一个强大的实用程序，它可帮助您管理 Windows 上的右键菜单，并避免第三方向你的右键菜单里塞屎
* [AlexanderPro/SmartSystemMenu](https://github.com/AlexanderPro/SmartSystemMenu) - SmartSystemMenu extends system menu of all windows in the system
* [SteamAutoCracks/Steam-auto-crack](https://github.com/SteamAutoCracks/Steam-auto-crack) - Steam Game Automatic Cracker
* [intel/acat](https://github.com/intel/acat) - Assistive Context-Aware Toolkit (ACAT)
* [hirschmann/nbfc](https://github.com/hirschmann/nbfc) - NoteBook FanControl
* [ONLYOFFICE/CommunityServer](https://github.com/ONLYOFFICE/CommunityServer) - Free open source office suite with business productivity tools: document and project management, CRM, mail aggregator.
* [goatcorp/FFXIVQuickLauncher](https://github.com/goatcorp/FFXIVQuickLauncher) - Custom launcher for FFXIV
* [bloxstraplabs/bloxstrap](https://github.com/bloxstraplabs/bloxstrap) - An alternative bootstrapper for Roblox with a bunch of extra features.
* [Pixeval/Pixeval](https://github.com/Pixeval/Pixeval) - Wow. Yet another Pixiv client!
* [RoundedTB/RoundedTB](https://github.com/RoundedTB/RoundedTB) - Add margins, rounded corners and segments to your taskbars! *(archived)*
* [shaked6540/YoutubePlaylistDownloader](https://github.com/shaked6540/YoutubePlaylistDownloader) - A tool to download whole playlists, channels or single videos from youtube and also optionally convert them to almost any format you would like
* [1357310795/MyComputerManager](https://github.com/1357310795/MyComputerManager) - 管理“此电脑”里删不掉的流氓“快捷方式”（包括侧边栏），同时可自己添加这类“快捷方式”
* [Jays2Kings/DS4Windows](https://github.com/Jays2Kings/DS4Windows) - Like those other ds4tools, but sexier *(archived)*
* [jaquadro/NBTExplorer](https://github.com/jaquadro/NBTExplorer) - A graphical NBT editor for all Minecraft NBT data sources
* [kenvix/USBCopyer](https://github.com/kenvix/USBCopyer) - 😉 用于在插上U盘后自动按需复制该U盘的文件。”备份&偷U盘文件的神器”（写作USBCopyer，读作USBCopier）
* [Accelerider/BaiduPanDownloadWinform](https://github.com/Accelerider/BaiduPanDownloadWinform) - 百度网盘不限速下载工具 *(archived)*
* [ErsatzTV/legacy](https://github.com/ErsatzTV/legacy) - Open-source platform that transforms your personal media library into live, custom TV channels.
* [samhocevar/wincompose](https://github.com/samhocevar/wincompose) - 🔣 Compose Key for Windows
* [ClusterM/hakchi2](https://github.com/ClusterM/hakchi2) - Tool that allows you to add more games to your NES/SNES Classic Mini. WARNING: hakchi2 is no longer supported. Please use hakchi2 CE. *(archived)*
* [shrimqy/Sefirah](https://github.com/shrimqy/Sefirah) - Phone Link / KDE Connect alternative
* [w4po/ExplorerTabUtility](https://github.com/w4po/ExplorerTabUtility) - 🚀 Supercharge Windows 11's File Explorer: Auto-convert windows to tabs, duplicate tabs, reopen closed ones, and more!
* [x360ce/x360ce](https://github.com/x360ce/x360ce) - Primary repository for the x360ce library, front-end and tools.
* [ikas-mc/ContextMenuForWindows11](https://github.com/ikas-mc/ContextMenuForWindows11) - Add Custom Context Menu For Windows11
* [SeriaWei/ZKEACMS](https://github.com/SeriaWei/ZKEACMS) - ZKEACMS build with .Net 8 (.Net CMS)可视化设计在线编辑内容管理系统
* [roslynpad/roslynpad](https://github.com/roslynpad/roslynpad) - Cross-platform C# editor based on Roslyn
* [BookerLiu/GeekDesk](https://github.com/BookerLiu/GeekDesk) - 🔥小巧、美观的桌面快速启动工具 Small, beautiful desktop quickstart management tool with integrated Everything search
* [Franiac/TwitchLeecher](https://github.com/Franiac/TwitchLeecher) - Twitch Leecher - The Broadcast Downloader
* [hitchao/Jvedio](https://github.com/hitchao/Jvedio) - Jvedio 是本地视频管理软件，支持扫描本地视频并导入软件，建立视频库， 提取出视频的 唯一识别码，自动分类视频， 添加标签管理视频，使用人工智能识别演员，支持翻译信息， 基于 FFmpeg 截取视频图片，Window 桌面端流畅美观的应用软件 *(archived)*
* [tjackenpacken/taskbar-groups](https://github.com/tjackenpacken/taskbar-groups) - Lightweight utility for organizing the taskbar through groups
* [Tyrrrz/LightBulb](https://github.com/Tyrrrz/LightBulb) - Reduces eye strain by adjusting screen gamma based on the current time
* [ClassIsland/ClassIsland](https://github.com/ClassIsland/ClassIsland) - 一款功能强、可定制、跨平台，适用于班级多媒体屏幕的课表信息显示工具，可以一目了然地显示各种信息。
* [boy1dr/SpleeterGui](https://github.com/boy1dr/SpleeterGui) - Windows desktop front end for Spleeter - AI source separation
* [intro-skipper/intro-skipper](https://github.com/intro-skipper/intro-skipper) - Automatically detect and skip intro/credit sequences in Jellyfin
* [Uotan-Dev/UotanToolboxNT](https://github.com/Uotan-Dev/UotanToolboxNT) - 现代化 Android & OpenHarmony 工具箱 | A Modern Toolbox for Android & OpenHarmony Devices
* [Coolapk-UWP/Coolapk-UWP](https://github.com/Coolapk-UWP/Coolapk-UWP) - 一个基于 UWP 平台的第三方酷安客户端
* [KSP-CKAN/CKAN](https://github.com/KSP-CKAN/CKAN) - The Comprehensive Kerbal Archive Network
* [bsmg/ModAssistant](https://github.com/bsmg/ModAssistant) - Simple Beat Saber Mod Installer
* [geovens/gInk](https://github.com/geovens/gInk) - An easy to use on-screen annotation software inspired by Epic Pen.
* [kannagi0303/yt-dlp-gui](https://github.com/kannagi0303/yt-dlp-gui) - Windows GUI for yt-dlp
* [ArcadeRenegade/SidebarDiagnostics](https://github.com/ArcadeRenegade/SidebarDiagnostics) - A simple sidebar for Windows desktop that displays hardware diagnostic information.
* [Achuan-2/SlideSCI](https://github.com/Achuan-2/SlideSCI) - PPT插件，支持素材库、AI助手、一键添加图片标题，复制粘贴位置、一键图片对齐、一键插入Markdown（加粗、超链接等行内样式、代码块、LaTeX等块级样式）、便捷导出图片！
* [91270/MeiamSubtitles](https://github.com/91270/MeiamSubtitles) - Emby Server / Jellyfin Server 端字幕插件 ，使用 迅雷影音、 射手网 接口精准匹配视频字幕
* [OpenLiveWriter/OpenLiveWriter](https://github.com/OpenLiveWriter/OpenLiveWriter) - An open source fork of Windows Live Writer
* [Cleanuparr/Cleanuparr](https://github.com/Cleanuparr/Cleanuparr) - Advanced download manager for the Servarr ecosystem
* [Squidex/squidex](https://github.com/Squidex/squidex) - Headless CMS and Content Managment Hub
* [ProtonVPN/win-app](https://github.com/ProtonVPN/win-app) - Official ProtonVPN Windows app
* [builtbybel/CrapFixer](https://github.com/builtbybel/CrapFixer) - Cr*ap Fixer
* [DNSCrypt/SimpleDnsCrypt](https://github.com/DNSCrypt/SimpleDnsCrypt) - A simple management tool for dnscrypt-proxy
* [OrchardCMS/Orchard](https://github.com/OrchardCMS/Orchard) - Orchard is a free, open source, community-focused Content Management System built on the ASP.NET MVC platform. Check out the next generation of this software built on ASP.NET Core: https://github.com/OrchardCMS/OrchardCore
* [jwallet/spy-spotify](https://github.com/jwallet/spy-spotify) - 🎤 Records Spotify to mp3 without ads and adds media tags to the files 🎵
* [ArduPilot/MissionPlanner](https://github.com/ArduPilot/MissionPlanner) - Mission Planner Ground Control Station for ArduPilot (c# .net)
* [imbushuo/EnergyStar](https://github.com/imbushuo/EnergyStar) - A terrible application setting SV2 Efficiency Mode for inactive Windows apps and user background apps
* [pdone/FreeControl](https://github.com/pdone/FreeControl) - 在PC上控制Android设备
* [n00mkrad/cupscale](https://github.com/n00mkrad/cupscale) - Image Upscaling GUI based on ESRGAN
* [immichFrame/ImmichFrame](https://github.com/immichFrame/ImmichFrame)
* [snownico0722/PaperTodo](https://github.com/snownico0722/PaperTodo) - 极简 Windows 桌面便签工具。让桌面上有几张安静、可用、不会打扰人的纸。WPF 原生，支持待办与 Markdown。——A minimalist Windows desktop sticky note tool. It puts a few quiet, usable, and unobtrusive sheets of paper on your desktop. Native WPF, with support for to-dos and Markdown.
* [tareqimbasher/NetPad](https://github.com/tareqimbasher/NetPad) - A cross-platform C# editor and playground.
* [googlevr/tilt-brush](https://github.com/googlevr/tilt-brush) - *(archived)*
* [Cinchoo/ChoEazyCopy](https://github.com/Cinchoo/ChoEazyCopy) - Simple and powerful RoboCopy GUI
* [RolandPheasant/TailBlazer](https://github.com/RolandPheasant/TailBlazer) - A modern file tail utility based on Rx.Net which show cases reactive programming and Dynamic Data (see https://github.com/RolandPheasant/DynamicData)
* [imDema/FreeMove](https://github.com/imDema/FreeMove) - Move directories without breaking shortcuts or installations
* [jenius-apps/ambie](https://github.com/jenius-apps/ambie) - An app that uses white noise, nature sounds, and focus features to boost your productivity.
* [paolosalvatori/ServiceBusExplorer](https://github.com/paolosalvatori/ServiceBusExplorer) - The Service Bus Explorer allows users to connect to a Service Bus namespace and administer messaging entities in an easy manner. The tool provides advanced features like import/export functionality or the ability to test topic, queues, subscriptions, relay services, notification hubs and events hubs.
* [adirh3/Fluent-Search](https://github.com/adirh3/Fluent-Search) - Official repository for Fluent Search, use to report issues or ask for a new feature
* [dnGrep/dnGrep](https://github.com/dnGrep/dnGrep) - Graphical GREP tool for Windows
* [jayfunc/BetterLyrics](https://github.com/jayfunc/BetterLyrics) - An elegant and deeply customizable lyrics visualizer & versatile music player, built with WinUI3/Win2D | 一款优雅且高度自定义的歌词可视化与全能音乐播放应用，基于 WinUI3/Win2D 构建
* [jadepeng/XMusicDownloader](https://github.com/jadepeng/XMusicDownloader) - 一款 支持从百度、网易、qq、酷狗、咪咕等音乐网站搜索并下载歌曲的程序，支持下载无损音乐
* [phw198/OutlookGoogleCalendarSync](https://github.com/phw198/OutlookGoogleCalendarSync) - Sync your Outlook and Google calendars
* [s1t5/mail-archiver](https://github.com/s1t5/mail-archiver) - Mail-Archiver is a web application for archiving, searching, and exporting emails from multiple accounts. Featuring folder sync, attachment support, mailbox migration and a dashboard.
* [digimezzo/dopamine-windows](https://github.com/digimezzo/dopamine-windows) - Audio player which tries to make organizing and listening to music as simple and pretty as possible.
* [jimradford/superputty](https://github.com/jimradford/superputty) - The SuperPuTTY Window Manager for putty sessions
* [Nexus-Mods/NexusMods.App](https://github.com/Nexus-Mods/NexusMods.App) - Home of the development of the Nexus Mods App *(archived)*
* [kangyu-california/PersistentWindows](https://github.com/kangyu-california/PersistentWindows) - fork of http://www.ninjacrab.com/persistent-windows/ with windows 10 update
* [FufuLauncher/FufuLauncher](https://github.com/FufuLauncher/FufuLauncher) - A third-party launcher for Genshin Impact that supports game injection, automatic check-in, and some useful small features.
* [Cenmrev/V2RayW](https://github.com/Cenmrev/V2RayW) - GUI for v2ray-core on Windows *(archived)*
* [BrianLima/UWPHook](https://github.com/BrianLima/UWPHook) - 🔗 Add your Windows Store or UWP games to Steam
* [LenovoLegionToolkit-Team/LenovoLegionToolkit](https://github.com/LenovoLegionToolkit-Team/LenovoLegionToolkit) - Lenovo Legion Toolkit (LLT) is a Windows desktop utility created for Lenovo gaming laptops that replaces Lenovo Vantage, Legion Zone, and Legion Space.
* [flytkgl/PDFQFZ](https://github.com/flytkgl/PDFQFZ) - PDF加盖骑缝章的小工具
* [jie65535/GrasscutterCommandGenerator](https://github.com/jie65535/GrasscutterCommandGenerator) - Command Generator and Gacha Banner Editor
* [Codeusa/SteamCleaner](https://github.com/Codeusa/SteamCleaner) - :us: A PC utility for restoring disk space from various game clients like Origin, Steam, Uplay, Battle.net, GoG and Nexon :us: *(archived)*
* [cDima/Aerial](https://github.com/cDima/Aerial) - Aerial Apple TV screen saver for Windows
* [GermanCoding/SyncTrayzor](https://github.com/GermanCoding/SyncTrayzor) - Windows tray utility / launcher for Syncthing (v2 continued)
* [Apps2Samsung/Apps2Samsung](https://github.com/Apps2Samsung/Apps2Samsung) - One-click app installer for Samsung TVs, projectors and smart monitors (Tizen) — Jellyfin, Moonlight, and the whole community catalog.
* [clawsoftware/clawPDF](https://github.com/clawsoftware/clawPDF) - Open Source Virtual (Network) Printer for Windows that allows you to create PDFs, OCR text, and print images, with advanced features usually available only in enterprise solutions.
* [zsh2401/AutumnBox](https://github.com/zsh2401/AutumnBox) - 图形化ADB工具箱 *(archived)*
* [LAB02-Research/HASS.Agent](https://github.com/LAB02-Research/HASS.Agent) - Windows-based client for Home Assistant. Provides notifications, quick actions, commands, sensors and more.
* [libgenapps/LibgenDesktop](https://github.com/libgenapps/LibgenDesktop)
* [Abdelrhman-AK/WinPaletter](https://github.com/Abdelrhman-AK/WinPaletter) - Advanced Windows Appearance Editor
* [audiamus/AaxAudioConverter](https://github.com/audiamus/AaxAudioConverter) - Convert Audible aax files to mp3 and m4a/m4b
* [HawaiiBeach/TinyNvidiaUpdateChecker](https://github.com/HawaiiBeach/TinyNvidiaUpdateChecker) - The best NVIDIA GPU update checker for Windows power users/gamers. Fully open sourced and lightweight.
* [chocolatey/ChocolateyGUI](https://github.com/chocolatey/ChocolateyGUI) - A delicious GUI for Chocolatey
* [CollapseLauncher/Collapse](https://github.com/CollapseLauncher/Collapse) - An Advanced Launcher for miHoYo/HoYoverse Games
* [zhontai/Admin.Core](https://github.com/zhontai/Admin.Core) - 中台Admin 基于 .NET10 、Vue3、uniapp、element-plus开发的前后端分离的权限管理系统。通过项目模板快速搭建项目框架、网关、接口、im即时通讯服务端等项目。支持代码生成器、多租户、数据权限、动态Api、任务调度、打印设计、OSS文件上传、滑块拼图验证、动态高级查询。集成认证授权、事件总线、国际化、数据验证、分布式Id、分布式缓存、分布式事务、全Api鉴权、接口文档等。
* [Maassoft/ColorControl](https://github.com/Maassoft/ColorControl) - Easily change NVIDIA display settings and/or control LG TV's
* [Valkirie/HandheldCompanion](https://github.com/Valkirie/HandheldCompanion) - A touch optimized GUI to increase your handheld gaming computer experience.
* [yingDev/WGestures](https://github.com/yingDev/WGestures) - Modern mouse gestures for Windows. (C#)
* [rogerfar/rdt-client](https://github.com/rogerfar/rdt-client) - Real-Debrid Client Proxy
* [Babyhamsta/Aimmy](https://github.com/Babyhamsta/Aimmy) - Universal Second Eye for Gamers with Impairments (Universal AI Aim Aligner (AI Aimbot) - ONNX/YOLOv8 - C#)
* [madskristensen/Miniblog.Core](https://github.com/madskristensen/Miniblog.Core) - An ASP.NET Core blogging engine
* [SuperStudio/SuperCom](https://github.com/SuperStudio/SuperCom) - SuperCom 是一款串口调试工具
* [wieslawsoltes/ChatGPT](https://github.com/wieslawsoltes/ChatGPT) - A ChatGPT C# client for MacOS, Windows, Linux, Android, iOS and Browser. Powered by Avalonia UI framework.
* [yaronzz/Tidal-Media-Downloader-PRO](https://github.com/yaronzz/Tidal-Media-Downloader-PRO) - Download 'TIDAL' Music On Windows/Linux/MacOs (PYTHON/C#)
* [cmliu/CFnat-Windows-GUI](https://github.com/cmliu/CFnat-Windows-GUI) - CFnat 为 Windows 用户设计的 GUI 程序界面。
* [CoreUnion/CoreShop](https://github.com/CoreUnion/CoreShop) - 基于 Asp.Net Core 9.0、Uni-App开发，支持可视化布局的小程序商城系统，前后端分离，支持分布式部署，跨平台运行，拥有分销、代理、团购、拼团、秒杀、直播、优惠券、自定义表单等众多营销功能，拥有完整SKU、下单、售后、物流流程。支持一套代码编译发布微信小程序版、H5版、Android版、iOS版、支付宝小程序版、字节跳动小程序版、QQ小程序版等共10个平台。
* [lalakii/MouseClickTool](https://github.com/lalakii/MouseClickTool) - 简单好用的鼠标连点器，体积小巧，性能好好的~鼠标连点器。当前版本体积18KB，在线版(minimal)体积仅5KB。
* [wangfreexx/wangfreexx-tianruoocr-cl-paddle](https://github.com/wangfreexx/wangfreexx-tianruoocr-cl-paddle) - 天若ocr开源版本的本地版，采用Chinese-lite和paddleocr识别框架
* [go2ismail/Asp.Net-Core-Inventory-Order-Management-System](https://github.com/go2ismail/Asp.Net-Core-Inventory-Order-Management-System) - Now upgraded to .NET 9, this project is a super-fast, completely headless API powered by Clean Architecture, CQRS, and MediatR. It includes an ASP.NET Core Razor Pages implementation for inventory order management, combined with Vue.js for a dynamic, responsive UI. Powerful WMS solution. Demo (username:admin@root.com / pwd:123456)
* [CXWorld/CapFrameX](https://github.com/CXWorld/CapFrameX) - Frametime capture and analysis tool
* [ShirasawaSama/CefDetector](https://github.com/ShirasawaSama/CefDetector) - Check how many CEFs are on your computer. 检测你电脑上有几个CEF.
* [robvdpol/RaceControl](https://github.com/robvdpol/RaceControl) - Race Control is a standalone, open source F1TV client for Windows, written in C# on the .NET platform. *(archived)*
* [visualHFT/VisualHFT](https://github.com/visualHFT/VisualHFT) - Open-source desktop application for real-time market microstructure analysis. Explore live Level 2 order books, trades, liquidity, and built-in studies.
* [bp2008/BetterClearTypeTuner](https://github.com/bp2008/BetterClearTypeTuner) - A better way to configure ClearType font smoothing on Windows 10.
* [ldqk/Masuit.MyBlogs](https://github.com/ldqk/Masuit.MyBlogs) - 基于C#/.NET9+vue3的 masuit.org个人博客站项目源码，https://masuit.org ，供参考、学习、引用、非商业性质的部署。
* [wieslawsoltes/Core2D](https://github.com/wieslawsoltes/Core2D) - A multi-platform data driven 2D diagram editor.
* [cuiliang/ClickShow](https://github.com/cuiliang/ClickShow) - 鼠标点击特效 *(archived)*
* [FreneticLLC/KeyboardChatterBlocker](https://github.com/FreneticLLC/KeyboardChatterBlocker) - A handy quick tool for blocking mechanical keyboard chatter.
* [audiamus/BookLibConnect](https://github.com/audiamus/BookLibConnect) - A standalone Audible downloader and decrypter
* [baffler/Transparent-Twitch-Chat-Overlay](https://github.com/baffler/Transparent-Twitch-Chat-Overlay) - Twitch chat on top of windowed games for single monitor streamers
* [yourtablecloth/TableCloth](https://github.com/yourtablecloth/TableCloth) - 식탁보 프로젝트
* [arcusmaximus/YTSubConverter](https://github.com/arcusmaximus/YTSubConverter) - A tool for creating styled YouTube subtitles
* [PredatH0r/ChanSort](https://github.com/PredatH0r/ChanSort) - TV channel list editor for Samsung, LG, Sony, Hisense, Panasonic, Philips, Sharp, Toshiba and MANY more.
* [sharpbrowser/SharpBrowser](https://github.com/sharpbrowser/SharpBrowser) - A full featured web-browser built using C# and CefSharp
* [CopyPlusPlus/CopyPlusPlus](https://github.com/CopyPlusPlus/CopyPlusPlus) - 让复制更加简单！
* [maximmax42/Discord-CustomRP](https://github.com/maximmax42/Discord-CustomRP) - Simple custom Rich Presence manager (Playing status) for Discord. Only supports Windows 7 and above. Features running on startup and minimizing to tray. Translated to multiple languages.
* [opendns/dnscrypt-win-client](https://github.com/opendns/dnscrypt-win-client) - Windows front end for DNSCrypt Proxy *(archived)*
* [Grabacr07/KanColleViewer](https://github.com/Grabacr07/KanColleViewer) - 艦これブラウザーのようなもの
* [kengwang/BiliDuang](https://github.com/kengwang/BiliDuang) - (暂停维护) Bilibili 哔哩哔哩视频下载 C# GUI版 - 支持BV 支持4K 支持地区限制下载 支持互动视频 支持无水印 支持弹幕/字幕下载转换 支持课程下载
* [AlbertMN/AssistantComputerControl](https://github.com/AlbertMN/AssistantComputerControl) - Control your computer with your Google Home or Amazon Alexa assistant!
* [maxim-saplin/CrossPlatformDiskTest](https://github.com/maxim-saplin/CrossPlatformDiskTest) - Windows, macOS and Android storage (HDD, SSD, RAM) speed testing/performance benchmarking app
* [mdhiggins/CenterTaskbar](https://github.com/mdhiggins/CenterTaskbar) - Center Windows Taskbar Icons *(archived)*
* [RandomEngy/VidCoder](https://github.com/RandomEngy/VidCoder) - A Blu-ray, DVD and video file transcoder for Windows.
* [OSTooling/UUPMediaCreator](https://github.com/OSTooling/UUPMediaCreator) - An utility to create Windows Media files (.ISO, .WIM, .VHD) from Unified Update Platform files
* [jenius-apps/nightingale-rest-api-client](https://github.com/jenius-apps/nightingale-rest-api-client) - A modern, resource-efficient REST API client for Windows
* [sh-akira/VirtualMotionCapture](https://github.com/sh-akira/VirtualMotionCapture) - VRゲーム中にモデルをコントロール
* [character-map-uwp/Character-Map-UWP](https://github.com/character-map-uwp/Character-Map-UWP) - A modern, native UWP replacement for the Win32 Character Map and Windows Font Viewer with flawless high DPI and touch support.
* [laochiangx/ABP-ASP.NET-Boilerplate-Project-CMS](https://github.com/laochiangx/ABP-ASP.NET-Boilerplate-Project-CMS) - ABP module-zero +AdminLTE+Bootstrap Table+jQuery+Redis + sql server+quartz+hangfire权限管理系统
* [jgosar/mine-city-2000](https://github.com/jgosar/mine-city-2000) - A program that converts SimCity 2000 cities into Minecraft worlds
* [dukus/digiCamControl](https://github.com/dukus/digiCamControl) - DSLR camera remote control open source software
* [damienhaynes/TraktRater](https://github.com/damienhaynes/TraktRater) - TraktRater is a tool written in C# to help users transfer user episode, show and movie user ratings and watchlists from multiple media database sites around the web.
* [iccb1013/Sheng.WeixinConstruction](https://github.com/iccb1013/Sheng.WeixinConstruction) - 升讯威微信营销系统（第三方微信平台）完整源代码。包括了面向线下商家的诸多营销功能。【吸粉】 投票、定期抽奖、聚人气抽奖、摇一摇抽奖、粉丝海报、1元夺宝、发红包、在线捐款 等 【持续变现】 微官网、微会员、积分商城、卡券、微信支付、分类信息、电影排片 等 【管理考核】 电脑手机双后台、营销二维码、后台用户管理、操作日志 等。
* [zetaloop/PowerToys-CN](https://github.com/zetaloop/PowerToys-CN) - PowerToys Simplified Chinese Translation 微软增强工具箱 自制汉化
* [Krutonium/Windows-10-Login-Background-Changer](https://github.com/Krutonium/Windows-10-Login-Background-Changer) - Changes the Windows 10 Login Screen Background *(archived)*
* [HeyM1ke/Assist](https://github.com/HeyM1ke/Assist) - C# Valorant Thirdparty Launcher
* [chummer5a/chummer5a](https://github.com/chummer5a/chummer5a) - Character generator for Shadowrun 5th edition
* [magicdict/MongoCola](https://github.com/magicdict/MongoCola) - A MongoDB Administration Tool

## Graphics and Media

### Graphics and Rendering

* [mono/SkiaSharp](https://github.com/mono/SkiaSharp) - SkiaSharp is a cross-platform 2D graphics API for .NET platforms based on Google's Skia Graphics Library. It provides a comprehensive 2D API that can be used across mobile, server and desktop models to render images.
* [dotnet/Silk.NET](https://github.com/dotnet/Silk.NET) - The high-speed OpenGL, OpenCL, OpenAL, OpenXR, GLFW, SDL, Vulkan, Assimp, WebGPU, and DirectX bindings library your mother warned you about.
* [tixl3d/tixl](https://github.com/tixl3d/tixl) - TiXL is an open source software to create realtime motion graphics.
* [wave-harmonic/crest](https://github.com/wave-harmonic/crest) - A class-leading water system implemented in Unity
* [Unity-Technologies/PostProcessing](https://github.com/Unity-Technologies/PostProcessing) - Post Processing Stack *(archived)*
* [keenanwoodall/Deform](https://github.com/keenanwoodall/Deform) - A fully-featured deformer system for Unity that lets you stack effects to animate models in real-time
* [keijiro/Skinner](https://github.com/keijiro/Skinner) - Special Effects with Skinned Mesh in Unity
* [QianMo/X-PostProcessing-Library](https://github.com/QianMo/X-PostProcessing-Library) - Unity Post Processing Stack Library | Unity引擎的高品质后处理库
* [opentk/opentk](https://github.com/opentk/opentk) - The Open Toolkit library is a fast, low-level C# wrapper for OpenGL, OpenAL & OpenCL. It also includes windowing, mouse, keyboard and joystick input and a robust and fast math library, giving you everything you need to write your own renderer or game engine. OpenTK can be used standalone or inside a GUI on Windows, Linux, Mac.
* [Auburn/FastNoiseLite](https://github.com/Auburn/FastNoiseLite) - Fast Portable Noise Library - C# C++ C Java HLSL GLSL JavaScript Rust Go
* [scrtwpns/mixbox](https://github.com/scrtwpns/mixbox) - Mixbox is a library for natural color mixing based on real pigments.
* [aras-p/UnityGaussianSplatting](https://github.com/aras-p/UnityGaussianSplatting) - Toy Gaussian Splatting visualization in Unity
* [vrm-c/UniVRM](https://github.com/vrm-c/UniVRM) - UniVRM is a gltf-based VRM format implementation for Unity. English is here https://vrm.dev/en/ . 日本語 はこちら https://vrm.dev/
* [2Retr0/GodotOceanWaves](https://github.com/2Retr0/GodotOceanWaves) - FFT-based ocean-wave rendering, implemented in Godot
* [Unity-Technologies/Graphics](https://github.com/Unity-Technologies/Graphics) - Unity Graphics - Including Scriptable Render Pipeline
* [keijiro/KinoGlitch](https://github.com/keijiro/KinoGlitch) - Video glitch effects for Unity
* [FreyaHolmer/ShaderForge](https://github.com/FreyaHolmer/ShaderForge) - A Shader Editor for Unity
* [veldrid/veldrid](https://github.com/veldrid/veldrid) - A low-level, portable graphics library for .NET.
* [keijiro/Kino](https://github.com/keijiro/Kino) - A collection of custom post processing effects for Unity
* [helix-toolkit/helix-toolkit](https://github.com/helix-toolkit/helix-toolkit) - Helix Toolkit is a collection of 3D components for .NET.
* [KhronosGroup/UnityGLTF](https://github.com/KhronosGroup/UnityGLTF) - Runtime glTF 2.0 Loader for Unity3D
* [JasonMa0012/JTRP](https://github.com/JasonMa0012/JTRP) - JTRP : Unity HDRP ToonShading Render Pipeline (Preview)
* [SlightlyMad/VolumetricLights](https://github.com/SlightlyMad/VolumetricLights) - Volumetric Lights for Unity
* [Whinarn/UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier) - Mesh simplification for Unity.
* [keijiro/Klak](https://github.com/keijiro/Klak) - Creative coding library for Unity
* [playdeadgames/temporal](https://github.com/playdeadgames/temporal) - Temporal Reprojection Anti-Aliasing for Unity 5.0+
* [chenjd/Render-Crowd-Of-Animated-Characters](https://github.com/chenjd/Render-Crowd-Of-Animated-Characters) - Animation Baker and Instancing for Animated Characters: Using GPU to implement large-amount animation characters rendering. The animation map for vertex shader to modify the vertex position of the mesh at runtime. Using GPU instancing to reduce draw calls.
* [Unity-Technologies/com.unity.toonshader](https://github.com/Unity-Technologies/com.unity.toonshader) - Unity Toon Shader
* [alelievr/HDRP-Custom-Passes](https://github.com/alelievr/HDRP-Custom-Passes) - A bunch of custom passes made for HDRP
* [SebLague/Marching-Cubes](https://github.com/SebLague/Marching-Cubes) - Coding Adventure
* [Scrawk/Ceto](https://github.com/Scrawk/Ceto) - Ceto: Ocean system for Unity
* [eliasts/Ocean_Community_Next_Gen](https://github.com/eliasts/Ocean_Community_Next_Gen) - Next gen iteration of the unity community ocean shader
* [SebLague/Clouds](https://github.com/SebLague/Clouds) - Cloud rendering test
* [Unity-Technologies/com.unity.demoteam.hair](https://github.com/Unity-Technologies/com.unity.demoteam.hair) - An integrated solution for authoring / importing / simulating / rendering strand-based hair in Unity.
* [ElinamLLC/SharpVectors](https://github.com/ElinamLLC/SharpVectors) - SharpVectors - SVG# Reloaded: SVG DOM and Rendering in C# for the .Net.
* [Unity-Technologies/com.unity.formats.alembic](https://github.com/Unity-Technologies/com.unity.formats.alembic) - Alembic importer and exporter plugin for Unity
* [Unity-Technologies/com.unity.demoteam.mesh-to-sdf](https://github.com/Unity-Technologies/com.unity.demoteam.mesh-to-sdf) - A light and fast real-time SDF generator, primarily for animated characters. The dynamic SDF can be used for all sorts of VFX. Also enables hair-to-character collisions in the new hair package.
* [karl-/pb_CSG](https://github.com/karl-/pb_CSG) - A C# port of CSG.js by Evan W (http://evanw.github.io/csg.js/).
* [yangrc1234/VolumeCloud](https://github.com/yangrc1234/VolumeCloud) - Volume cloud for Unity3D
* [luca-piccioni/OpenGL.Net](https://github.com/luca-piccioni/OpenGL.Net) - Modern OpenGL bindings for C#.
* [microsoft/MixedRealityCompanionKit](https://github.com/microsoft/MixedRealityCompanionKit) - This is a MixedRealityToolkit style repository for code bits and components that may not run directly on Microsoft HoloLens or immersive headsets but instead pair with them to build experiences. *(archived)*
* [bitzhuwei/CSharpGL](https://github.com/bitzhuwei/CSharpGL) - :green_apple:Object Oriented OpenGL in C#.

### Game Development

* [mxgmn/WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) - Bitmap & tilemap generation from a single example with the help of ideas from quantum mechanics
* [ppy/osu](https://github.com/ppy/osu) - rhythm is just a *click* away!
* [OpenRA/OpenRA](https://github.com/OpenRA/OpenRA) - Open Source real-time strategy game engine for early Westwood games such as Command & Conquer: Red Alert written in C# using SDL and OpenGL. Runs on Windows, Linux, *BSD and Mac OS X.
* [Perfare/AssetStudio](https://github.com/Perfare/AssetStudio) - AssetStudio is a tool for exploring, extracting and exporting assets and assetbundles. *(archived)*
* [MonoGame/MonoGame](https://github.com/MonoGame/MonoGame) - One framework for creating powerful cross-platform games.
* [Unity-Technologies/UnityCsReference](https://github.com/Unity-Technologies/UnityCsReference) - Unity C# reference source code.
* [egametang/ET](https://github.com/egametang/ET) - Unity3D Client And C# Server Framework
* [jynew/jynew](https://github.com/jynew/jynew) - JinYongLegend-like RPG Game Framework with full Modding support and 10+ hours playable samples of game.
* [BepInEx/BepInEx](https://github.com/BepInEx/BepInEx) - Unity / XNA game patcher and plugin framework
* [AssetRipper/AssetRipper](https://github.com/AssetRipper/AssetRipper) - GUI application to analyze game files
* [mxgmn/MarkovJunior](https://github.com/mxgmn/MarkovJunior) - Probabilistic language based on pattern matching and constraint propagation, 153 examples
* [stride3d/stride](https://github.com/stride3d/stride) - Stride (formerly Xenko), a free and open-source cross-platform C# game engine.
* [sschmid/Entitas](https://github.com/sschmid/Entitas) - Entitas is a super fast Entity Component System (ECS) Framework specifically made for C# and Unity
* [mob-sakai/UIEffect](https://github.com/mob-sakai/UIEffect) - UIEffect is an open-source package that allows you to intuitively apply rich UI effects directly from the Inspector or via code. Combine various filters, such as grayscale, blur, and dissolve, to decorate your UI with a unique visual style!
* [EllanJiang/GameFramework](https://github.com/EllanJiang/GameFramework) - This is literally a game framework, based on Unity game engine. It encapsulates commonly used game modules during development, and, to a large degree, standardises the process, enhances the development speed and ensures the product quality.
* [Facepunch/sbox-public](https://github.com/Facepunch/sbox-public) - s&box is a modern game engine, built on Valve's Source 2 and the latest .NET technology, it provides a modern intuitive editor for creating games
* [MirrorNetworking/Mirror](https://github.com/MirrorNetworking/Mirror) - #1 Open Source Unity Networking Library
* [UnityTechnologies/open-project-1](https://github.com/UnityTechnologies/open-project-1) - Unity Open Project #1: Chop Chop
* [VeriorPies/ParrelSync](https://github.com/VeriorPies/ParrelSync) - (Unity3D) Test multiplayer without building
* [microsoft/MixedRealityToolkit-Unity](https://github.com/microsoft/MixedRealityToolkit-Unity) - This repository is for the legacy Mixed Reality Toolkit (MRTK) v2. For the latest version of the MRTK please visit https://github.com/MixedRealityToolkit/MixedRealityToolkit-Unity
* [mob-sakai/ParticleEffectForUGUI](https://github.com/mob-sakai/ParticleEffectForUGUI) - Render particle effect in UnityUI(uGUI). Maskable, sortable, and no extra Camera/RenderTexture/Canvas.
* [tModLoader/tModLoader](https://github.com/tModLoader/tModLoader) - A mod to make and play Terraria mods. Supports Terraria 1.4 (and earlier) installations
* [liangxiegame/QFramework](https://github.com/liangxiegame/QFramework) - Godot/Unity3D System Design Architecture
* [sharpemu/sharpemu](https://github.com/sharpemu/sharpemu) - An experimental PlayStation 5 emulator for Windows, Linux and macOS.
* [dbrizov/NaughtyAttributes](https://github.com/dbrizov/NaughtyAttributes) - Attribute Extensions for Unity
* [marian42/wavefunctioncollapse](https://github.com/marian42/wavefunctioncollapse) - Walk through an infinite, procedurally generated city
* [focus-creative-games/luban](https://github.com/focus-creative-games/luban) - luban是一个强大、易用、优雅、稳定的游戏配置解决方案。luban is a powerful, easy-to-use, elegant and stable game configuration solution.
* [LavaGang/MelonLoader](https://github.com/LavaGang/MelonLoader) - The World's First Universal Mod Loader for Unity Games compatible with both Il2Cpp and Mono
* [NoelFB/Celeste](https://github.com/NoelFB/Celeste) - Celeste Bugs & Issue Tracker + some Source Code *(archived)*
* [space-wizards/space-station-14](https://github.com/space-wizards/space-station-14) - A multiplayer game about paranoia and chaos on a space station. Remake of the cult-classic Space Station 13.
* [SmartlyDressedGames/U3-SDK](https://github.com/SmartlyDressedGames/U3-SDK) - Source code for Unturned, a free open-world zombie survival sandbox game.
* [Facepunch/Facepunch.Steamworks](https://github.com/Facepunch/Facepunch.Steamworks) - Another fucking c# Steamworks implementation
* [Siccity/xNode](https://github.com/Siccity/xNode) - Unity Node Editor: Lets you view and edit node graphs inside Unity
* [ExtendRealityLtd/VRTK](https://github.com/ExtendRealityLtd/VRTK) - An example of how to use the Tilia packages to create great content with VRTK v4.
* [Revolutionary-Games/Thrive](https://github.com/Revolutionary-Games/Thrive) - The main repository for the development of the evolution game Thrive.
* [Sanakan8472/copy-dialog-lunar-lander](https://github.com/Sanakan8472/copy-dialog-lunar-lander) - Play lunar lander in you windows file copy dialog
* [SebLague/Geographical-Adventures](https://github.com/SebLague/Geographical-Adventures)
* [playgameservices/play-games-plugin-for-unity](https://github.com/playgameservices/play-games-plugin-for-unity) - Google Play Games plugin for Unity
* [rlabrecque/Steamworks.NET](https://github.com/rlabrecque/Steamworks.NET) - Steamworks wrapper for Unity / C#
* [setchi/FancyScrollView](https://github.com/setchi/FancyScrollView) - A versatile Unity scroll view component that enables highly flexible animations.
* [Interkarma/daggerfall-unity](https://github.com/Interkarma/daggerfall-unity) - Open source recreation of Daggerfall in the Unity engine
* [bbepis/XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator)
* [tuyoogame/YooAsset](https://github.com/tuyoogame/YooAsset) - unity3d resources management system
* [isadorasophia/murder](https://github.com/isadorasophia/murder) - Murder is a pixel art ECS game engine.
* [nxrighthere/UnrealCLR](https://github.com/nxrighthere/UnrealCLR) - Unreal Engine .NET 6 integration
* [sinai-dev/UnityExplorer](https://github.com/sinai-dev/UnityExplorer) - An in-game UI for exploring, debugging and modifying IL2CPP and Mono Unity games. *(archived)*
* [Unity-Technologies/NavMeshComponents](https://github.com/Unity-Technologies/NavMeshComponents) - High Level API Components for Runtime NavMesh Building
* [Tencent/behaviac](https://github.com/Tencent/behaviac) - behaviac is a framework of the game AI development, and it also can be used as a rapid game prototype design tool. behaviac supports the behavior tree, finite state machine and hierarchical task network(BT, FSM, HTN)
* [FNA-XNA/FNA](https://github.com/FNA-XNA/FNA) - FNA - Accuracy-focused XNA4 reimplementation for open platforms
* [KeenSoftwareHouse/SpaceEngineers](https://github.com/KeenSoftwareHouse/SpaceEngineers) - *(archived)*
* [fairygui/FairyGUI-unity](https://github.com/fairygui/FairyGUI-unity) - A flexible UI framework for Unity
* [bepu/bepuphysics2](https://github.com/bepu/bepuphysics2) - Pure C# 3D real time physics simulation library, now with a higher version number.
* [Syomus/ProceduralToolkit](https://github.com/Syomus/ProceduralToolkit) - Procedural generation library for Unity
* [Pryaxis/TShock](https://github.com/Pryaxis/TShock) - ☕️⚡️TShock provides Terraria servers with server-side characters, anti-cheat, and community management tools.
* [YarnSpinnerTool/YarnSpinner](https://github.com/YarnSpinnerTool/YarnSpinner) - The core compiler and engine-agnostic components for Yarn Spinner, the friendly dialogue tool.
* [qiankanglai/LoopScrollRect](https://github.com/qiankanglai/LoopScrollRect) - These scripts will make your UGUI ScrollRect reusing cells, to improve performance, loading time and draw calls.
* [TASEmulators/BizHawk](https://github.com/TASEmulators/BizHawk) - BizHawk is a multi-system emulator written in C#. BizHawk provides nice features for casual gamers such as full screen, and joypad support in addition to full rerecording and debugging tools for all system cores.
* [yasirkula/UnityIngameDebugConsole](https://github.com/yasirkula/UnityIngameDebugConsole) - A uGUI based console to see debug messages and execute commands during gameplay in Unity
* [googlevr/gvr-unity-sdk](https://github.com/googlevr/gvr-unity-sdk) - Google VR SDK for Unity *(archived)*
* [Pathoschild/SMAPI](https://github.com/Pathoschild/SMAPI) - The modding API for Stardew Valley.
* [yimengfan/BDFramework.Core](https://github.com/yimengfan/BDFramework.Core) - Simple and powerful Unity3d game workflow! 简单、高效、高度工业化的商业级unity3d 工作流。
* [xasset/xasset](https://github.com/xasset/xasset) - 提升你的生产力。
* [alelievr/NodeGraphProcessor](https://github.com/alelievr/NodeGraphProcessor) - Node graph editor framework focused on data processing using Unity UIElements and C# 4.6
* [Demigiant/dotween](https://github.com/Demigiant/dotween) - A Unity C# animation engine. HOTween v2
* [in0finite/SanAndreasUnity](https://github.com/in0finite/SanAndreasUnity) - Open source reimplementation of GTA San Andreas game engine in Unity
* [EllanJiang/UnityGameFramework](https://github.com/EllanJiang/UnityGameFramework) - This is literally a game framework, based on Unity game engine. It encapsulates commonly used game modules during development, and, to a large degree, standardises the process, enhances the development speed and ensures the product quality.
* [ddevault/TrueCraft](https://github.com/ddevault/TrueCraft) - Minecraft for hipsters *(archived)*
* [nesrak1/UABEA](https://github.com/nesrak1/UABEA) - c# uabe for newer versions of unity
* [Unity-Technologies/AssetBundles-Browser](https://github.com/Unity-Technologies/AssetBundles-Browser) - Editor tool for viewing and debugging asset bundle contents before and after builds
* [m969/EGamePlay](https://github.com/m969/EGamePlay) - 一个基于Entity-Component模式的灵活、通用、可扩展的轻量战斗（技能）框架，配置可选使用ScriptableObject或是Excel表格. A flexible, generic, easy to extend, lightweight combat (skills) framework based on Entity-Component pattern. Configuration can choose to use ScriptableObject or Excel tables.
* [Impostor/Impostor](https://github.com/Impostor/Impostor) - Impostor - An open source reimplementation of the Among Us Server
* [h8man/NavMeshPlus](https://github.com/h8man/NavMeshPlus) - Unity NavMesh 2D Pathfinding
* [Alex-Rachel/TEngine](https://github.com/Alex-Rachel/TEngine) - Unity 商用级别开发框架，原生内置 AI 工作流支持，集成 HybridCLR 高性能热更、Obfuz 代码混淆加固、YooAssets 企业级资源管理方案，构建高效、安全、可扩展的工业化开发底座。
* [Unity-Technologies/com.unity.netcode.gameobjects](https://github.com/Unity-Technologies/com.unity.netcode.gameobjects) - Netcode for GameObjects is a high-level netcode SDK that provides networking capabilities to GameObject/MonoBehaviour workflows within Unity and sits on top of underlying transport layer.
* [annulusgames/LitMotion](https://github.com/annulusgames/LitMotion) - Lightning-fast and Zero Allocation Tween Library for Unity.
* [DavidArayan/ezy-slice](https://github.com/DavidArayan/ezy-slice) - An open source mesh slicer framework for Unity3D Game Engine. Written in C#.
* [handzlikchris/FastScriptReload](https://github.com/handzlikchris/FastScriptReload) - Hot Reload implementation for Unity. Iterate on code insanely fast without breaking play session. Supports any editor. 1. Play 2. Make change 3. See results
* [JasonXuDeveloper/JEngine](https://github.com/JasonXuDeveloper/JEngine) - The solution that allows unity games to update in runtime. 使Unity开发的游戏支持热更新的解决方案。
* [vovgou/loxodon-framework](https://github.com/vovgou/loxodon-framework) - An MVVM & Databinding framework that can use C# and Lua to develop games
* [FakeFishGames/Barotrauma](https://github.com/FakeFishGames/Barotrauma) - A 2D online multiplayer game taking place in a submarine travelling through the icy depths of Jupiter's moon Europa.
* [andrumak/MyBox](https://github.com/andrumak/MyBox) - MyBox is a set of attributes, tools and extensions for Unity
* [kisence-mian/MyUnityFrameWork](https://github.com/kisence-mian/MyUnityFrameWork) - 我的Unity框架，包含资源加载，配置加载，数据加载，UI管理，日志管理，动画系统，特效系统
* [TEdit/Terraria-Map-Editor](https://github.com/TEdit/Terraria-Map-Editor) - TEdit - Terraria Map Editor - TEdit is a stand alone, open source map editor for Terraria. It lets you edit maps just like (almost) paint! It also lets you change world settings (time, bosses downed etc), edit chests and change sign, make epic dungeons, castles, cities, and add rewards for your adventurers!
* [Matthew-J-Spencer/Ultimate-2D-Controller](https://github.com/Matthew-J-Spencer/Ultimate-2D-Controller) - A great starting point for your 2D controller. Making use of all the hidden tricks like coyote, buffered actions, speedy apex, anti grav apex, etc
* [yasirkula/UnityRuntimeInspector](https://github.com/yasirkula/UnityRuntimeInspector) - Runtime Inspector and Hierarchy solution for Unity for debugging and runtime editing purposes
* [sturdyspoon/unity-movement-ai](https://github.com/sturdyspoon/unity-movement-ai) - A Unity library for common movement AI
* [SebLague/Path-Creator](https://github.com/SebLague/Path-Creator) - Path creation asset for Unity game development
* [SubnauticaNitrox/Nitrox](https://github.com/SubnauticaNitrox/Nitrox) - An open-source, multiplayer modification for the game Subnautica.
* [prime31/Nez](https://github.com/prime31/Nez) - Nez is a free 2D focused framework that works with MonoGame and FNA
* [Tencent/InjectFix](https://github.com/Tencent/InjectFix) - InjectFix is a hot-fix solution library for Unity
* [Unity-Technologies/AutoLOD](https://github.com/Unity-Technologies/AutoLOD) - Automatic LOD generation + scene optimization
* [yasirkula/UnityAssetUsageDetector](https://github.com/yasirkula/UnityAssetUsageDetector) - Find usages of the selected asset(s) and/or Object(s) in your Unity project, i.e. list the objects that refer to them
* [FirstGearGames/FishNet](https://github.com/FirstGearGames/FishNet) - FishNet: Unity Networking Evolved.
* [UnderminersTeam/UndertaleModTool](https://github.com/UnderminersTeam/UndertaleModTool) - The most complete tool for modding, decompiling and unpacking Undertale (and other GameMaker games!)
* [EXOK/Celeste64](https://github.com/EXOK/Celeste64) - A game made by the Celeste developers in a week(ish, closer to 2)
* [PokemonUnity/PokemonUnity](https://github.com/PokemonUnity/PokemonUnity) - A LEGACY Unity project to help build Pokémon-esque RPG games.
* [Seneral/Node_Editor_Framework](https://github.com/Seneral/Node_Editor_Framework) - A flexible and modular Node Editor Framework for creating node based displays and editors in Unity *(archived)*
* [ppy/osu-framework](https://github.com/ppy/osu-framework) - A game framework written with osu! in mind.
* [KyryloKuzyk/PrimeTween](https://github.com/KyryloKuzyk/PrimeTween) - High-performance, allocation-free tween library for Unity. Create animations, delays, and sequences in one line of code.
* [arimger/Unity-Editor-Toolbox](https://github.com/arimger/Unity-Editor-Toolbox) - Tools, custom attributes, drawers, hierarchy overlay, and other extensions for the Unity Editor.
* [snozbot/fungus](https://github.com/snozbot/fungus) - An easy to use Unity 3D library for creating illustrated Interactive Fiction games and more.
* [marijnz/unity-toolbar-extender](https://github.com/marijnz/unity-toolbar-extender) - Extend the Unity Toolbar with your own Editor UI code.
* [UnrealSharp/UnrealSharp](https://github.com/UnrealSharp/UnrealSharp) - UnrealSharp is a plugin to Unreal Engine 5, which enables developers to create games using C# (.NET10) with Hot Reload
* [jarjin/LuaFramework_UGUI](https://github.com/jarjin/LuaFramework_UGUI) - 请移步新版地址https://github.com/jarjin/LuaFramework_UGUI_V2 支持安卓ARM64【已停止更新】
* [flibitijibibo/RogueLegacy1](https://github.com/flibitijibibo/RogueLegacy1) - Rogue Legacy Source Code
* [2394425147/astrodx](https://github.com/2394425147/astrodx)
* [TastSong/CrazyCar](https://github.com/TastSong/CrazyCar) - 网络联机游戏解决方案---Unity制作的联机赛车游戏，服务端为SpringBoot + Mybatis Plus；后台为Vue + Element；游戏端采用QFramework框架，Addressable+HybridCLR实现热更新，支持KCP和WebSocket网络。
* [genaray/Arch](https://github.com/genaray/Arch) - A high-performance C# based Archetype & Chunks Entity Component System (ECS) with optional multithreading.
* [SebLague/Chess-Challenge](https://github.com/SebLague/Chess-Challenge) - Create your own tiny chess bot!
* [PixelVision8/PixelVision8](https://github.com/PixelVision8/PixelVision8) - Pixel Vision 8's core philosophy is to teach retro game development with streamlined workflows. PV8 is also a platform that standardizes 8-bit fantasy console limitations built on top of the open-source C# game engine based on MonoGame. *(archived)*
* [kirevdokimov/Unity-UI-Rounded-Corners](https://github.com/kirevdokimov/Unity-UI-Rounded-Corners) - These components and shaders allow you to add rounded corners to UI elements!
* [Unity-UI-Extensions/com.unity.uiextensions](https://github.com/Unity-UI-Extensions/com.unity.uiextensions) - The Unity UI library of controls, components and other useful features for extending the Unity UI solution for Unity
* [Suprcode/Crystal](https://github.com/Suprcode/Crystal) - Legend of Mir 2 - Official Public Crystal Source
* [OpenSAGE/OpenSAGE](https://github.com/OpenSAGE/OpenSAGE) - OpenSAGE is a free, open source re-implementation of SAGE, the 3D real time strategy (RTS) engine used in Command & Conquer: Generals and other RTS titles from EA Pacific. Written in C#. Not affiliated with EA.
* [SebLague/Chess-Coding-Adventure](https://github.com/SebLague/Chess-Coding-Adventure) - A work-in-progress chess bot written in C#
* [sabresaurus/SabreCSG](https://github.com/sabresaurus/SabreCSG) - Level design tools for Unity *(archived)*
* [raylib-cs/raylib-cs](https://github.com/raylib-cs/raylib-cs) - C# bindings for raylib, a simple and easy-to-use library to learn videogames programming
* [qq362946/Fantasy](https://github.com/qq362946/Fantasy) - C # Game Framework, but not limited to games. Can be used for non game business development
* [Thraka/SadConsole](https://github.com/Thraka/SadConsole) - A .NET ascii/ansi console engine written in C# for MonoGame and SFML. Create your own text roguelike (or other) games!
* [jacksondunstan/UnityNativeScripting](https://github.com/jacksondunstan/UnityNativeScripting) - Unity Scripting in C++
* [sebas77/Svelto.ECS](https://github.com/sebas77/Svelto.ECS) - Svelto ECS C# Entity Component System
* [roflmuffin/CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp) - CounterStrikeSharp allows you to write server plugins in C# for Counter-Strike 2/Source2/CS2
* [ScutGame/Scut](https://github.com/ScutGame/Scut) - Scut is a free, open source, stable game server framework, which support C#/Python/Lua script, and support Unity3d, Cocos2dx, FlashAir client access.
* [Brackeys/2D-Character-Controller](https://github.com/Brackeys/2D-Character-Controller) - Free 2D Character Controller for Unity.
* [Cytoid/Cytoid](https://github.com/Cytoid/Cytoid) - A community-driven touchscreen music game.
* [luxkun/ReGoap](https://github.com/luxkun/ReGoap) - Generic C# GOAP (Goal Oriented Action Planning) library with Unity3d examples
* [flibitijibibo/SDL2-CS](https://github.com/flibitijibibo/SDL2-CS) - SDL2# - C# Wrapper for SDL2 *(archived)*
* [Dandarawy/UnityBookPageCurl](https://github.com/Dandarawy/UnityBookPageCurl) - Page curl effect for Unity3d using UGUI
* [BluestormDNA/ProjectPSX](https://github.com/BluestormDNA/ProjectPSX) - Experimental C# Playstation Emulator
* [dbrizov/Unity-CharacterController](https://github.com/dbrizov/Unity-CharacterController) - Third Person Controller for Unity
* [0x7c13/Pal3.Unity](https://github.com/0x7c13/Pal3.Unity) - The Legend of Sword and Fairy 3 (仙剑奇侠传三) & The Legend of Sword and Fairy 3 Gaiden: Wenqing Pian (仙剑奇侠传三外传：问情篇) re-implementation using C#/Unity
* [handcircus/Unity-Resource-Checker](https://github.com/handcircus/Unity-Resource-Checker) - Editor utility for unity to help check resources in the current scene (including active textures, their sizes, materials, meshes and which objects are using them)
* [AnyRPG/AnyRPGCore](https://github.com/AnyRPG/AnyRPGCore) - Open source Role Playing Game engine for Unity 3D written in C#.
* [LogicalError/realtime-CSG-for-unity](https://github.com/LogicalError/realtime-CSG-for-unity) - Realtime-CSG, CSG level editor for Unity
* [Nition/UnityOctree](https://github.com/Nition/UnityOctree) - A dynamic, loose octree implementation for Unity written in C# *(archived)*
* [cjddmut/Unity-2D-Platformer-Controller](https://github.com/cjddmut/Unity-2D-Platformer-Controller) - A customizable 2D platformer motor that handles mechanics such as double jumps, wall jumps, and corner grabs. Includes a player controlled prefab that can be dropped into any scene for immediate support.
* [ikpil/DotRecast](https://github.com/ikpil/DotRecast) - DotRecast - a C# port of Recast & Detour, Industry-standard navigation mesh toolset for .NET, Unity3D, games, servers
* [FlameskyDexive/Legends-Of-Heroes](https://github.com/FlameskyDexive/Legends-Of-Heroes) - A battle of balls game, lol style, AI Agents base, support agent skills & unityMCP. 基于ET 10的双端C#游戏框架(.net10 + Unity2022.3.62, EUI+Luban+YooAsset)，包含战斗系统（技能/buff/行为树），内置LOL风格球球大战demo
* [spr1ngd/UnityCodes](https://github.com/spr1ngd/UnityCodes) - SpringGUI是对UGUI的拓展，提供十多种UI组件用于快速开发。
* [mminer/consolation](https://github.com/mminer/consolation) - In-game debug console for Unity.
* [NiclasOlofsson/MiNET](https://github.com/NiclasOlofsson/MiNET) - A (not so) basic Minecraft Pocket Edition server written in C#
* [ProwlEngine/Prowl](https://github.com/ProwlEngine/Prowl) - An Open Source C# 3D Game Engine under MIT license, inspired by Unity and featuring a complete editor
* [FosterFramework/Foster](https://github.com/FosterFramework/Foster) - A small C# game framework
* [fydar/RPGCore](https://github.com/fydar/RPGCore) - RPGCore is a toolkit for producing games and mechanics in C#.
* [cmilr/Unity2D-Components](https://github.com/cmilr/Unity2D-Components) - A constantly evolving array of Unity C# components for 2D games, including classes for pixel art cameras, events & messaging, saving & loading game data, collision handlers, object pools, and more.
* [dotnetGame/MineCase](https://github.com/dotnetGame/MineCase) - Minecraft server based on Orleans
* [CitiesSkylinesMultiplayer/CSM](https://github.com/CitiesSkylinesMultiplayer/CSM) - Source code for the Cities: Skylines Multiplayer mod (CSM)
* [IronWarrior/SuperCharacterController](https://github.com/IronWarrior/SuperCharacterController) - Unity custom character controller *(archived)*
* [ServUO/ServUO](https://github.com/ServUO/ServUO) - An Ultima Online server emulator written in C# .NET
* [delmarle/RPG-Core](https://github.com/delmarle/RPG-Core) - UNITY engine RPG framework
* [ClassicUO/ClassicUO](https://github.com/ClassicUO/ClassicUO) - ClassicUO - an open source implementation of the Ultima Online Classic Client.
* [pbhogan/InControl](https://github.com/pbhogan/InControl) - An input manager for Unity that tames the cross-platform controller beast.
* [febucci/unitypackage-custom-hierarchy](https://github.com/febucci/unitypackage-custom-hierarchy) - Unity package to help having a clearer Hierarchy view, organizing everything in a “tree view” and including extra informations like Components Icons and groups/divisors.
* [Unity-Technologies/com.unity.cinemachine](https://github.com/Unity-Technologies/com.unity.cinemachine) - Smart camera tools for passionate creators
* [smkplus/CustomToolbar](https://github.com/smkplus/CustomToolbar) - CustomToolbar
* [MichalStrehovsky/SeeSharpSnake](https://github.com/MichalStrehovsky/SeeSharpSnake) - Self-contained C# game in 8 kB
* [MaKiPL/OpenVIII-monogame](https://github.com/MaKiPL/OpenVIII-monogame) - Open source Final Fantasy VIII engine implementation in C# working on Windows and Linux (Android and iOS planned too!) [Monogame] *(archived)*
* [hugoscurti/mesh-cutter](https://github.com/hugoscurti/mesh-cutter) - Simple mesh cutting algorithm that works on simple 3d manifold objects with genus 0
* [Zonciu/Box2DSharp](https://github.com/Zonciu/Box2DSharp) - A C# port of Box2D
* [Unity-Technologies/Standard-Assets-Characters](https://github.com/Unity-Technologies/Standard-Assets-Characters) - Unity Standard Asset Controllers
* [ConcreteMC/Alex](https://github.com/ConcreteMC/Alex) - A Minecraft client written in C# aimed at compatibility with MC:Java & MC:Bedrock
* [UltravioletFramework/ultraviolet](https://github.com/UltravioletFramework/ultraviolet) - The Ultraviolet Framework is a .NET game development framework written in C#.

### Audio

* [naudio/NAudio](https://github.com/naudio/NAudio) - Audio and MIDI library for .NET
* [openutau/OpenUtau](https://github.com/openutau/OpenUtau) - Open singing synthesis platform / Open source UTAU successor
* [filoe/cscore](https://github.com/filoe/cscore) - An advanced audio library, written in C#. Provides tons of features. From playing/recording audio to decoding/encoding audio streams/files to processing audio data in realtime (e.g. applying custom effects during playback, create visualizations,...). The possibilities are nearly unlimited.
* [BleuBleu/FamiStudio](https://github.com/BleuBleu/FamiStudio) - FamiStudio NES Music Editor
* [AnyListen/YaVipCore](https://github.com/AnyListen/YaVipCore) - Net Core Music Interface
* [AddictedCS/soundfingerprinting](https://github.com/AddictedCS/soundfingerprinting) - Open source audio fingerprinting in .NET. An efficient algorithm for acoustic fingerprinting written purely in C#.

### Image and Video

* [SixLabors/ImageSharp](https://github.com/SixLabors/ImageSharp) - A modern, cross-platform, 2D Graphics library for .NET
* [Shane32/QRCoder](https://github.com/Shane32/QRCoder) - A pure C# Open Source QR Code implementation
* [dlemstra/Magick.NET](https://github.com/dlemstra/Magick.NET) - The .NET library for ImageMagick
* [micjahn/ZXing.Net](https://github.com/micjahn/ZXing.Net) - .Net port of the original java-based barcode reader and generator library zxing
* [JimBobSquarePants/ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - :camera: A fluent wrapper around System.Drawing for the processing of image files. *(archived)*
* [cxfksword/jellyfin-plugin-metashark](https://github.com/cxfksword/jellyfin-plugin-metashark) - jellyfin电影元数据插件
* [rosenbjerg/FFMpegCore](https://github.com/rosenbjerg/FFMpegCore) - A .NET FFMpeg/FFProbe wrapper for easily integrating media analysis and conversion into your C# applications
* [Ruslan-B/FFmpeg.AutoGen](https://github.com/Ruslan-B/FFmpeg.AutoGen) - FFmpeg auto generated unsafe bindings for C#/.NET and Core (Linux, MacOS and Mono).
* [ToaHartor/GI-cutscenes](https://github.com/ToaHartor/GI-cutscenes) - A command line program playing with the cutscenes files (USM) from Genshin Impact.
* [barnhill/barcodelib](https://github.com/barnhill/barcodelib) - C# Barcode Image Generation Library
* [mxgmn/ConvChain](https://github.com/mxgmn/ConvChain) - Bitmap generation from a single example with convolutions and MCMC

## Security

### Security Tools

* [peass-ng/PEASS-ng](https://github.com/peass-ng/PEASS-ng) - PEASS - Privilege Escalation Awesome Scripts SUITE (with colors)
* [quasar/Quasar](https://github.com/quasar/Quasar) - Remote Administration Tool for Windows *(archived)*
* [the1812/Malware-Patch](https://github.com/the1812/Malware-Patch) - 通过 UAC 阻止流氓软件的管理员授权. / Prevent UAC authorization of malware.
* [k8gege/Ladon](https://github.com/k8gege/Ladon) - Ladon大型内网渗透扫描器，PowerShell、Cobalt Strike插件、内存加载、无文件扫描。含端口扫描、服务识别、网络资产探测、密码审计、高危漏洞检测、漏洞利用、密码读取以及一键GetShell，支持批量A段/B段/C段以及跨网段扫描，支持URL、主机、域名列表扫描等。网络资产探测32种协议(ICMP\NBT\DNS\MAC\SMB\WMI\SSH\HTTP\HTTPS\Exchange\mssql\FTP\RDP)或方法快速获取目标网络存活主机IP、计算机名、工作组、共享资源、网卡地址、操作系统版本、网站、子域名、中间件、开放服务、路由器、交换机、数据库、打印机等，大量高危漏洞检测模块MS17010、Zimbra、Exchange
* [GhostPack/Rubeus](https://github.com/GhostPack/Rubeus) - Trying to tame the three-headed dog.
* [cobbr/Covenant](https://github.com/cobbr/Covenant) - Covenant is a collaborative .NET C2 framework for red teamers.
* [HotCakeX/Harden-Windows-Security](https://github.com/HotCakeX/Harden-Windows-Security) - Harden Windows Safely, Securely using Official Supported Microsoft methods and proper explanation | Always up-to-date and works with the latest build of Windows | Provides tools and Guides for Personal, Enterprise, Government and Military security levels | SLSA Level 3 Compliant for Secure Development and Build Process | Apps Available on MS Store✨
* [GhostPack/Seatbelt](https://github.com/GhostPack/Seatbelt) - Seatbelt is a C# project that performs a number of security oriented host-survey "safety checks" relevant from both offensive and defensive security perspectives.
* [microsoft/ApplicationInspector](https://github.com/microsoft/ApplicationInspector) - A source code analyzer built for surfacing features of interest and other characteristics to answer the question 'What's in the code?' quickly using static analysis with a json based rules engine. Ideal for scanning components before use or detecting feature level changes.
* [pwntester/ysoserial.net](https://github.com/pwntester/ysoserial.net) - Deserialization payload generator for a variety of .NET formatters
* [yck1509/ConfuserEx](https://github.com/yck1509/ConfuserEx) - An open-source, free protector for .NET applications *(archived)*
* [builtbybel/privatezilla](https://github.com/builtbybel/privatezilla) - 👀👮🐢🔥Performs a privacy & security check of Windows 10
* [ElevenPaths/FOCA](https://github.com/ElevenPaths/FOCA) - Tool to find metadata and hidden information in the documents.
* [odedshimon/BruteShark](https://github.com/odedshimon/BruteShark) - Network Analysis Tool
* [obfuscar/obfuscar](https://github.com/obfuscar/obfuscar) - Open source obfuscation tool for .NET assemblies
* [Kevin-Robertson/Inveigh](https://github.com/Kevin-Robertson/Inveigh) - .NET IPv4/IPv6 machine-in-the-middle tool for penetration testers
* [NYAN-x-CAT/AsyncRAT-C-Sharp](https://github.com/NYAN-x-CAT/AsyncRAT-C-Sharp) - Open-Source Remote Administration Tool For Windows C# (RAT)
* [NewEraCracker/LOIC](https://github.com/NewEraCracker/LOIC) - Deprecated - Low Orbit Ion Cannon - An open source network stress tool, written in C#. Based on Praetox's LOIC project. USE ON YOUR OWN RISK. WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES. IF YOU GET V& IT IS YOUR FAULT. *(archived)*
* [microsoft/AttackSurfaceAnalyzer](https://github.com/microsoft/AttackSurfaceAnalyzer) - Attack Surface Analyzer can help you analyze your operating system's security configuration for changes during software installation.
* [netwrix/pingcastle](https://github.com/netwrix/pingcastle) - PingCastle - Get Active Directory Security at 80% in 20% of the time
* [SnaffCon/Snaffler](https://github.com/SnaffCon/Snaffler) - a tool for pentesters to help find delicious candy, by @l0ss and @Sh3r4 ( Twitter: @/mikeloss and @/sh3r4_hax )
* [microsoft/onefuzz](https://github.com/microsoft/onefuzz) - A self-hosted Fuzzing-As-A-Service platform *(archived)*
* [1y0n/AV_Evasion_Tool](https://github.com/1y0n/AV_Evasion_Tool) - 掩日 - 免杀执行器生成工具
* [shack2/SNETCracker](https://github.com/shack2/SNETCracker) - 超级弱口令检查工具是一款Windows平台的弱口令审计工具，支持批量多线程检查，可快速发现弱密码、弱口令账号，密码支持和用户名结合进行检查，大大提高成功率，支持自定义服务端口和字典。
* [matterpreter/DefenderCheck](https://github.com/matterpreter/DefenderCheck) - Identifies the bytes that Microsoft Defender flags on.
* [openbullet/OpenBullet2](https://github.com/openbullet/OpenBullet2) - OpenBullet reinvented
* [googleprojectzero/sandbox-attacksurface-analysis-tools](https://github.com/googleprojectzero/sandbox-attacksurface-analysis-tools) - Set of tools to analyze Windows sandboxes for exposed attack surface.
* [BeichenDream/GodPotato](https://github.com/BeichenDream/GodPotato)
* [outflanknl/EvilClippy](https://github.com/outflanknl/EvilClippy) - A cross-platform assistant for creating malicious MS Office documents. Can hide VBA macros, stomp VBA code (via P-Code) and confuse macro analysis tools. Runs on Linux, OSX and Windows.
* [DigitalRuby/IPBan](https://github.com/DigitalRuby/IPBan) - Since 2011, IPBan is the worlds most trusted, free security software to block hackers and botnets. With both Windows and Linux support, IPBan has your dedicated or cloud server protected. Upgrade to IPBan Pro today and get a discount. Learn more at ↓
* [microsoft/sbom-tool](https://github.com/microsoft/sbom-tool) - The SBOM tool is a highly scalable and enterprise ready tool to create SPDX 2.2 compatible SBOMs for any variety of artifacts.
* [massgravel/TSforge](https://github.com/massgravel/TSforge) - A collection of activation/evaluation extension methods for Windows Vista through 11.
* [GhostPack/Certify](https://github.com/GhostPack/Certify) - Active Directory certificate abuse.
* [cube0x0/CVE-2021-1675](https://github.com/cube0x0/CVE-2021-1675) - C# and Impacket implementation of PrintNightmare CVE-2021-1675/CVE-2021-34527
* [MichaelGrafnetter/DSInternals](https://github.com/MichaelGrafnetter/DSInternals) - Directory Services Internals (DSInternals) PowerShell Module and Framework
* [cobbr/SharpSploit](https://github.com/cobbr/SharpSploit) - SharpSploit is a .NET post-exploitation library written in C#
* [moom825/xeno-rat](https://github.com/moom825/xeno-rat) - Xeno-RAT is an open-source remote access tool (RAT) developed in C#, providing a comprehensive set of features for remote system management. Has features such as HVNC, live microphone, reverse proxy, and much much more!
* [GhostPack/SharpUp](https://github.com/GhostPack/SharpUp) - SharpUp is a C# port of various PowerUp functionality.
* [matterpreter/OffensiveCSharp](https://github.com/matterpreter/OffensiveCSharp) - Collection of Offensive C# Tooling
* [GhostPack/SharpDPAPI](https://github.com/GhostPack/SharpDPAPI) - SharpDPAPI is a C# port of some Mimikatz DPAPI functionality.
* [antonioCoco/RunasCs](https://github.com/antonioCoco/RunasCs) - RunasCs - Csharp and open version of windows builtin runas.exe
* [SamuelTulach/VirusTotalUploader](https://github.com/SamuelTulach/VirusTotalUploader) - C# Open-Source Winforms application for uploading files to VirusTotal
* [ReversecLabs/SharpGPOAbuse](https://github.com/ReversecLabs/SharpGPOAbuse) - SharpGPOAbuse is a .NET application written in C# that can be used to take advantage of a user's edit rights on a Group Policy Object (GPO) in order to compromise the objects that are controlled by that GPO.
* [SpecterOps/SharpHound](https://github.com/SpecterOps/SharpHound) - C# Data Collector for BloodHound
* [shack2/SuperSQLInjectionV1](https://github.com/shack2/SuperSQLInjectionV1) - 超级SQL注入工具（SSQLInjection）是一款基于HTTP协议自组包的SQL注入工具,采用C#开发，直接操作TCP会话来进行HTTP交互，支持出现在HTTP协议任意位置的SQL注入，支持各种类型的SQL注入，支持HTTPS模式注入；支持以盲注、错误显示、Union注入等方式来获取数据；支持Access/MySQL/SQLServer/Oracle/PostgreSQL/DB2/SQLite/Informix等数据库；支持手动灵活的进行SQL注入绕过，可自定义进行字符替换等绕过注入防护。本工具为渗透测试人员、信息安全工程师等掌握SQL注入技能的人员设计，需要使用人员对SQL注入有一定了解。
* [tevora-threat/SharpView](https://github.com/tevora-threat/SharpView) - C# implementation of harmj0y's PowerView
* [bitsadmin/nopowershell](https://github.com/bitsadmin/nopowershell) - PowerShell rebuilt in C# for Red Teaming purposes
* [DragoQCC/CrucibleC2](https://github.com/DragoQCC/CrucibleC2) - A C# Command & Control framework
* [qwqdanchun/DcRat](https://github.com/qwqdanchun/DcRat) - A simple remote tool in C#. *(archived)*
* [security-code-scan/security-code-scan](https://github.com/security-code-scan/security-code-scan) - Vulnerability Patterns Detector for C# and VB.NET
* [eladshamir/Whisker](https://github.com/eladshamir/Whisker) - Whisker is a C# tool for taking over Active Directory user and computer accounts by manipulating their msDS-KeyCredentialLink attribute, effectively adding "Shadow Credentials" to the target account.
* [Apr4h/CobaltStrikeScan](https://github.com/Apr4h/CobaltStrikeScan) - Scan files or process memory for CobaltStrike beacons and parse their configuration
* [andrewlock/NetEscapades.AspNetCore.SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) - Small package to allow adding security headers to ASP.NET Core websites
* [Flangvik/NetLoader](https://github.com/Flangvik/NetLoader) - Loads any C# binary in mem, patching AMSI + ETW.
* [mvelazc0/PurpleSharp](https://github.com/mvelazc0/PurpleSharp) - PurpleSharp is a C# adversary simulation tool that executes adversary techniques with the purpose of generating attack telemetry in monitored Windows environments
* [0xb11a1/yetAnotherObfuscator](https://github.com/0xb11a1/yetAnotherObfuscator) - C# obfuscator that bypass windows defender
* [Aetsu/OffensivePipeline](https://github.com/Aetsu/OffensivePipeline) - OfensivePipeline allows you to download and build C# tools, applying certain modifications in order to improve their evasion for Red Team exercises.
* [skahwah/SQLRecon](https://github.com/skahwah/SQLRecon) - A C# MS SQL toolkit designed for offensive reconnaissance and post-exploitation.
* [AlmondOffSec/PassTheCert](https://github.com/AlmondOffSec/PassTheCert) - Proof-of-Concept tool to authenticate to an LDAP/S server with a certificate through Schannel
* [GhostPack/SharpWMI](https://github.com/GhostPack/SharpWMI) - SharpWMI is a C# implementation of various WMI functionality.
* [djhohnstein/SharpChromium](https://github.com/djhohnstein/SharpChromium) - .NET 4.0 CLR Project to retrieve Chromium data, such as cookies, history and saved logins.
* [klezVirus/CheeseTools](https://github.com/klezVirus/CheeseTools) - Self-developed tools for Lateral Movement/Code Execution
* [Mr-Un1k0d3r/RedTeamCSharpScripts](https://github.com/Mr-Un1k0d3r/RedTeamCSharpScripts) - C# Script used for Red Team
* [GhostPack/ForgeCert](https://github.com/GhostPack/ForgeCert) - "Golden" certificates
* [Mayyhem/SharpSCCM](https://github.com/Mayyhem/SharpSCCM) - A C# utility for interacting with SCCM
* [RCStep/CSSG](https://github.com/RCStep/CSSG) - Cobalt Strike Shellcode Generator
* [GhostPack/SharpDump](https://github.com/GhostPack/SharpDump) - SharpDump is a C# port of PowerSploit's Out-Minidump.ps1 functionality.
* [BloodHoundAD/SharpHound3](https://github.com/BloodHoundAD/SharpHound3) - C# Data Collector for the BloodHound Project, Version 3 *(archived)*
* [BloodHoundAD/SharpHound2](https://github.com/BloodHoundAD/SharpHound2) - The Old BloodHound C# Ingestor (Deprecated) *(archived)*
* [UnamSanctam/SilentCryptoMiner](https://github.com/UnamSanctam/SilentCryptoMiner) - A Silent (Hidden) Free Crypto Miner Builder - Supports ETC, RVN, XMR, RTM and much more.

### Authentication and Authorization

* [git-ecosystem/git-credential-manager](https://github.com/git-ecosystem/git-credential-manager) - Secure, cross-platform Git credential storage with authentication to GitHub, Azure Repos, and other popular Git hosting services.
* [openiddict/openiddict-core](https://github.com/openiddict/openiddict-core) - Flexible and versatile OAuth 2.0/OpenID Connect stack for .NET
* [stratumauth/app](https://github.com/stratumauth/app) - 📱 Two-Factor Authentication (2FA) client for Android + Wear OS
* [Jessecar96/SteamDesktopAuthenticator](https://github.com/Jessecar96/SteamDesktopAuthenticator) - Desktop implementation of Steam's mobile authenticator app
* [skoruba/IdentityServer4.Admin](https://github.com/skoruba/IdentityServer4.Admin) - The administration for the IdentityServer4 and Asp.Net Core Identity *(archived)*
* [microsoft/Git-Credential-Manager-for-Windows](https://github.com/microsoft/Git-Credential-Manager-for-Windows) - Secure Git credential storage for Windows with support for Visual Studio Team Services, GitHub, and Bitbucket multi-factor authentication. *(archived)*
* [aspnet-contrib/AspNet.Security.OAuth.Providers](https://github.com/aspnet-contrib/AspNet.Security.OAuth.Providers) - OAuth 2.0 social authentication providers for ASP.NET Core
* [jwt-dotnet/jwt](https://github.com/jwt-dotnet/jwt) - Jwt.Net, a JWT (JSON Web Token) implementation for .NET
* [aspnet/Identity](https://github.com/aspnet/Identity) - [Archived] ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data. Project moved to https://github.com/aspnet/AspNetCore *(archived)*
* [DotNetOpenAuth/DotNetOpenAuth](https://github.com/DotNetOpenAuth/DotNetOpenAuth) - A C# implementation of the OpenID, OAuth protocols *(archived)*
* [apache/casbin-Casbin.NET](https://github.com/apache/casbin-Casbin.NET) - An authorization library that supports access control models like ACL, RBAC, ABAC in .NET (C#)
* [JonPSmith/AuthPermissions.AspNetCore](https://github.com/JonPSmith/AuthPermissions.AspNetCore) - This library provides extra authorization and multi-tenant features to an ASP.NET Core application.
* [DuendeArchive/IdentityModel.OidcClient](https://github.com/DuendeArchive/IdentityModel.OidcClient) - Certified C#/NetStandard OpenID Connect Client Library for native mobile/desktop Applications (RFC 8252) *(archived)*
* [aspnet-contrib/AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - OpenID Connect/OAuth2 server framework for OWIN/Katana and ASP.NET Core *(archived)*

### Reverse Engineering

* [dnSpy/dnSpy](https://github.com/dnSpy/dnSpy) - .NET debugger and assembly editor *(archived)*
* [icsharpcode/ILSpy](https://github.com/icsharpcode/ILSpy) - .NET Decompiler with support for PDB generation, ReadyToRun, Metadata (&more) - cross-platform!
* [Perfare/Il2CppDumper](https://github.com/Perfare/Il2CppDumper) - Unity il2cpp reverse engineer
* [de4dot/de4dot](https://github.com/de4dot/de4dot) - .NET deobfuscator and unpacker. *(archived)*
* [atom0s/Steamless](https://github.com/atom0s/Steamless) - Steamless is a DRM remover of the SteamStub variants. The goal of Steamless is to make a single solution for unpacking all Steam DRM-packed files. Steamless aims to support as many games as possible.
* [notscuffed/repkg](https://github.com/notscuffed/repkg) - Wallpaper engine PKG extractor/TEX to image converter
* [morkt/GARbro](https://github.com/morkt/GARbro) - Visual Novels resource browser
* [4sval/FModel](https://github.com/4sval/FModel) - Unreal Engine Archives Explorer
* [mafaca/UtinyRipper](https://github.com/mafaca/UtinyRipper) - GUI and API library to work with Engine assets, serialized and bundle files
* [SamboyCoding/Cpp2IL](https://github.com/SamboyCoding/Cpp2IL) - Work-in-progress tool to reverse unity's IL2CPP toolchain.
* [uxmal/reko](https://github.com/uxmal/reko) - Reko is a binary decompiler.
* [0xd4d/dnlib](https://github.com/0xd4d/dnlib) - Reads and writes .NET assemblies and modules
* [ValveResourceFormat/ValveResourceFormat](https://github.com/ValveResourceFormat/ValveResourceFormat) - Source 2 Viewer is an all-in-one tool to browse VPK archives, view, extract, and decompile Source 2 assets, including maps, models, materials, textures, sounds, and more.
* [ReClassNET/ReClass.NET](https://github.com/ReClassNET/ReClass.NET) - More than a ReClass port to the .NET platform.
* [Squalr/Squalr-Sharp](https://github.com/Squalr/Squalr-Sharp) - Squalr Memory Editor - Game Hacking Tool Written in C#
* [Misaka-Mikoto-Tech/MonoHook](https://github.com/Misaka-Mikoto-Tech/MonoHook) - hook C# method at runtime without modify dll file (such as UnityEditor.dll), works on Windows, Mac, Android il2cpp(armv7a and armv8a)
* [MonoMod/MonoMod](https://github.com/MonoMod/MonoMod) - C# modding swiss army knife, powered by cecil.
* [erfg12/memory.dll](https://github.com/erfg12/memory.dll) - C# Hacking library for making PC game trainers.
* [abbaye/WpfHexEditorIDE](https://github.com/abbaye/WpfHexEditorIDE) - WpfHexEditor Studio is a IDE built on WPF and .NET 8, designed for advanced binary analysis and reverse engineering—combining a powerful hex editor, deep inspection tools, and native support for .NET projects and Visual Studio solutions in a single high-performance platform.
* [orlikoski/CyLR](https://github.com/orlikoski/CyLR) - CyLR - Live Response Collection Tool
* [JamesMenetrey/MemorySharp](https://github.com/JamesMenetrey/MemorySharp) - A C# based memory editing library targeting Windows applications, offering various functions to extract and inject data and codes into remote processes to allow interoperability.
* [Squalr/Squalr](https://github.com/Squalr/Squalr) - A generic game/software hacking tool written from the ground up in Rust.

## Concurrency and Performance

### Concurrency and Parallelism

* [Cysharp/UniTask](https://github.com/Cysharp/UniTask) - Provides an efficient allocation free async/await integration for Unity.
* [neuecc/UniRx](https://github.com/neuecc/UniRx) - Reactive Extensions for Unity *(archived)*
* [dotnet/reactive](https://github.com/dotnet/reactive) - The Reactive Extensions for .NET
* [akkadotnet/akka.net](https://github.com/akkadotnet/akka.net) - Canonical actor model implementation for .NET with local + distributed actors in C# and F#.
* [Cysharp/R3](https://github.com/Cysharp/R3) - The new future of dotnet/reactive and UniRx.
* [StephenCleary/AsyncEx](https://github.com/StephenCleary/AsyncEx) - A helper library for async/await.
* [asynkron/protoactor-dotnet](https://github.com/asynkron/protoactor-dotnet) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin
* [Real-Serious-Games/C-Sharp-Promise](https://github.com/Real-Serious-Games/C-Sharp-Promise) - Promises library for C# for management of asynchronous operations.
* [justinstenning/SharedMemory](https://github.com/justinstenning/SharedMemory) - C# shared memory classes for sharing data between processes (Array, Buffer and Circular Buffer)

### Performance and Optimization

* [dotnet/BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - Powerful .NET library for benchmarking
* [icsharpcode/SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
* [Sergio0694/ComputeSharp](https://github.com/Sergio0694/ComputeSharp) - A .NET library to run C# code in parallel on the GPU through DX12, D2D1, and dynamically generated HLSL compute and pixel shaders, with the goal of making GPU computing easy to use for all .NET developers! 🚀
* [PlummersSoftwareLLC/Primes](https://github.com/PlummersSoftwareLLC/Primes) - Prime number projects in 100+ programming languages, to compare their speed - and their programmer's cleverness
* [adamhathcock/sharpcompress](https://github.com/adamhathcock/sharpcompress) - SharpCompress is a fully managed C# library to deal with many compression types and formats.
* [microsoft/Microsoft.IO.RecyclableMemoryStream](https://github.com/microsoft/Microsoft.IO.RecyclableMemoryStream) - A library to provide pooling for .NET MemoryStream objects to improve application performance.
* [dadhi/FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) - Fast Compiler for C# Expression Trees and the lightweight LightExpression alternative. Diagnostic and code generation tools for the expressions.
* [dotnet/crank](https://github.com/dotnet/crank) - Benchmarking infrastructure for applications
* [MiloszKrajewski/K4os.Compression.LZ4](https://github.com/MiloszKrajewski/K4os.Compression.LZ4) - LZ4/LH4HC compression for .NET Standard 1.6/2.0 (formerly known as lz4net)

## Testing and Quality

### Testing

* [bchavez/Bogus](https://github.com/bchavez/Bogus) - :card_index: A simple fake data generator for C#, F#, and VB.NET. Based on and ported from the famed faker.js.
* [devlooped/moq](https://github.com/devlooped/moq) - The most popular and friendly mocking framework for .NET
* [xunit/xunit](https://github.com/xunit/xunit) - xUnit.net is a free, open source, community-focused unit testing tool for .NET.
* [testcontainers/testcontainers-dotnet](https://github.com/testcontainers/testcontainers-dotnet) - A library to support tests with throwaway instances of Docker containers for all compatible .NET Standard versions.
* [microsoft/WinAppDriver](https://github.com/microsoft/WinAppDriver) - Windows Application Driver
* [thomhurst/TUnit](https://github.com/thomhurst/TUnit) - A modern, fast and flexible .NET testing framework
* [fluentassertions/fluentassertions](https://github.com/fluentassertions/fluentassertions) - A very extensive set of extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style unit tests. Targets .NET Framework 4.7, as well as .NET Core 2.1, .NET Core 3.0, .NET 6, .NET Standard 2.0 and 2.1. Supports the unit test frameworks MSTest2, NUnit3, XUnit2, MSpec, and NSpec3.
* [AutoFixture/AutoFixture](https://github.com/AutoFixture/AutoFixture) - AutoFixture is an open source library for .NET designed to minimize the 'Arrange' phase of your unit tests in order to maximize maintainability. Its primary goal is to allow developers to focus on what is being tested rather than how to setup the test scenario, by making it easier to create object graphs containing test data.
* [VerifyTests/Verify](https://github.com/VerifyTests/Verify) - Verify is a snapshot testing tool that simplifies the assertion of complex data models and documents.
* [shouldly/shouldly](https://github.com/shouldly/shouldly) - Should testing for .NET—the way assertions should be!
* [coverlet-coverage/coverlet](https://github.com/coverlet-coverage/coverlet) - Cross platform code coverage for .NET
* [FlaUI/FlaUI](https://github.com/FlaUI/FlaUI) - UI automation library for .Net
* [danielpalme/ReportGenerator](https://github.com/danielpalme/ReportGenerator) - ReportGenerator converts coverage reports generated by coverlet, OpenCover, dotCover, Visual Studio, NCover, Cobertura, JaCoCo, Clover, gcov or lcov into human readable reports in various formats.
* [jbogard/Respawn](https://github.com/jbogard/Respawn) - Intelligent database cleaner for integration tests
* [nsubstitute/NSubstitute](https://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking libraries.
* [nunit/nunit](https://github.com/nunit/nunit) - NUnit Framework
* [stryker-mutator/stryker-net](https://github.com/stryker-mutator/stryker-net) - Mutation testing for .NET core and .NET framework!
* [ivaylokenov/MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - Fluent testing library for ASP.NET Core MVC.
* [microsoft/coyote](https://github.com/microsoft/coyote) - Coyote is a library and tool for testing concurrent C# code and deterministically reproducing bugs.
* [TNG/ArchUnitNET](https://github.com/TNG/ArchUnitNET) - A C# architecture test library to specify and assert architecture rules in C# for automated testing.
* [featurist/coypu](https://github.com/featurist/coypu) - Intuitive, robust browser automation for .Net

## Utilities

### Command Line Tools

* [PowerShell/PowerShell](https://github.com/PowerShell/PowerShell) - PowerShell for every system!
* [gerardog/gsudo](https://github.com/gerardog/gsudo) - Sudo for Windows
* [commandlineparser/commandline](https://github.com/commandlineparser/commandline) - The best C# command line parser that brings standardized *nix getopt style, for .NET. Includes F# support
* [PowerShell/PSReadLine](https://github.com/PowerShell/PSReadLine) - A bash inspired readline implementation for PowerShell
* [dotnet/command-line-api](https://github.com/dotnet/command-line-api) - Command line parsing, invocation, and rendering of terminal output.
* [mayuki/Cocona](https://github.com/mayuki/Cocona) - Micro-framework for .NET console application. Cocona makes it easy and fast to build console applications on .NET. *(archived)*
* [natemcmaster/CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) - Command line parsing and utilities for .NET
* [Cysharp/ConsoleAppFramework](https://github.com/Cysharp/ConsoleAppFramework) - Zero Dependency, Zero Overhead, Zero Reflection, Zero Allocation, AOT Safe CLI Framework powered by C# Source Generator.
* [Tyrrrz/CliFx](https://github.com/Tyrrrz/CliFx) - Class-first framework for building command-line interfaces
* [pdevito3/craftsman](https://github.com/pdevito3/craftsman) - A .NET scaffolding tool to help you stop worrying about boilerplate and focus on your business logic 🚀
* [frgnca/AudioDeviceCmdlets](https://github.com/frgnca/AudioDeviceCmdlets) - AudioDeviceCmdlets is a suite of PowerShell Cmdlets to control audio devices on Windows
* [MScholtes/VirtualDesktop](https://github.com/MScholtes/VirtualDesktop) - C# command line tool to manage virtual desktops in Windows 10
* [bilal-fazlani/commanddotnet](https://github.com/bilal-fazlani/commanddotnet) - A modern framework for building modern CLI apps
* [fclp/fluent-command-line-parser](https://github.com/fclp/fluent-command-line-parser) - A simple, strongly typed .NET C# command line parser library using a fluent easy to use interface

### Logging and Configuration

* [serilog/serilog](https://github.com/serilog/serilog) - Simple .NET logging with fully-structured events
* [NLog/NLog](https://github.com/NLog/NLog) - NLog - Flexible and Structured Logging for various .NET Platforms
* [thepirat000/Audit.NET](https://github.com/thepirat000/Audit.NET) - An extensible framework to audit executing operations in .NET
* [featbit/featbit](https://github.com/featbit/featbit) - Enterprise-grade feature flag platform that you can self-host. Get started - free.
* [dotnetcore/AgileConfig](https://github.com/dotnetcore/AgileConfig) - 基于.NET Core开发的轻量级分布式配置中心 / .NET Core lightweight configuration server
* [aloneguid/config](https://github.com/aloneguid/config) - ⚙ Config.Net - the easiest configuration framework for .NET developers. No BS.
* [net-commons/common-logging](https://github.com/net-commons/common-logging) - A portable logging abstraction for .NET
* [stevejgordon/CorrelationId](https://github.com/stevejgordon/CorrelationId) - An ASP.NET Core middleware component which synchronises a correlation ID for cross API request logging.

### Text Processing

* [QuestPDF/QuestPDF](https://github.com/QuestPDF/QuestPDF) - QuestPDF is a modern library for PDF document generation. Its fluent C# API lets you design complex layouts with clean, readable code. Create documents using a flexible, component-based approach.
* [Humanizr/Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities
* [xoofx/markdig](https://github.com/xoofx/markdig) - A fast, powerful, CommonMark compliant, extensible Markdown processor for .NET
* [dotnet/docfx](https://github.com/dotnet/docfx) - Static site generator for .NET API documentation.
* [scriban/scriban](https://github.com/scriban/scriban) - A fast, powerful, safe and lightweight scripting language and engine for .NET
* [ullmark/hashids.net](https://github.com/ullmark/hashids.net) - A small .NET package to generate YouTube-like hashes from one or many numbers. Use hashids when you do not want to expose your database ids to the user.
* [Cysharp/ZString](https://github.com/Cysharp/ZString) - Zero Allocation StringBuilder for .NET and Unity.
* [UglyToad/PdfPig](https://github.com/UglyToad/PdfPig) - Read and extract text and other content from PDFs in C# (port of PDFBox)
* [sprache/Sprache](https://github.com/sprache/Sprache) - A tiny, friendly, C# parser construction library
* [Antaris/RazorEngine](https://github.com/Antaris/RazorEngine) - Open source templating engine based on Microsoft's Razor parsing engine
* [datalust/superpower](https://github.com/datalust/superpower) - A C# parser construction toolkit with high-quality error reporting
* [mmanela/diffplex](https://github.com/mmanela/diffplex) - DiffPlex is Netstandard 2.0+ C# library to generate textual diffs.
* [axuno/SmartFormat](https://github.com/axuno/SmartFormat) - A lightweight text templating library written in C# which can be a drop-in replacement for string.Format
* [ststeiger/PdfSharpCore](https://github.com/ststeiger/PdfSharpCore) - Port of the PdfSharp library to .NET Core - largely removed GDI+ (only missing GetFontData - which can be replaced with freetype2)
* [rdvojmoc/DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) - C# .NET Core wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF.
* [benjamin-hodgson/Pidgin](https://github.com/benjamin-hodgson/Pidgin) - A lightweight and fast parsing library for C#.
* [Knagis/CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - Implementation of CommonMark specification in C# for converting Markdown documents to HTML. Optimized for maximum performance and portability.
* [twcclegg/libphonenumber-csharp](https://github.com/twcclegg/libphonenumber-csharp) - Offical C# port of https://github.com/googlei18n/libphonenumber
* [sblom/RegExtract](https://github.com/sblom/RegExtract) - Clean & simple idiomatic C# RegEx-based line parser that emits strongly typed results.
* [VahidN/iTextSharp.LGPLv2.Core](https://github.com/VahidN/iTextSharp.LGPLv2.Core) - iTextSharp.LGPLv2.Core is an unofficial port of the last LGPL version of the iTextSharp (V4.1.6) to .NET Core
* [adoconnection/RazorEngineCore](https://github.com/adoconnection/RazorEngineCore) - .NET10 Razor Template Engine

### Files and Operating System

* [winsw/winsw](https://github.com/winsw/winsw) - A wrapper executable that can run any executable as a Windows service, in a permissive license.
* [thebookisclosed/ViVe](https://github.com/thebookisclosed/ViVe) - C# library and console app for using new feature control APIs available in Windows 10 version 2004 and newer
* [Tyrrrz/CliWrap](https://github.com/Tyrrrz/CliWrap) - Library for interacting with command-line interfaces
* [Topshelf/Topshelf](https://github.com/Topshelf/Topshelf) - An easy service hosting framework for building Windows services using .NET *(archived)*
* [microsoft/CsWin32](https://github.com/microsoft/CsWin32) - A source generator to add a user-defined set of Win32 P/Invoke methods and supporting types to a C# project.
* [dotnet/pinvoke](https://github.com/dotnet/pinvoke) - A library containing all P/Invoke code so you don't have to import it every time. Maintained and updated to support the latest Windows OS. *(archived)*
* [dahall/Vanara](https://github.com/dahall/Vanara) - A set of .NET libraries for Windows implementing PInvoke calls to many native Windows APIs with supporting wrappers.
* [aelassas/servy](https://github.com/aelassas/servy) - Enterprise-Grade Windows Service Wrapper with Real-Time Monitoring
* [jcurl/RJCP.DLL.SerialPortStream](https://github.com/jcurl/RJCP.DLL.SerialPortStream) - SerialPortStream is an independent implementation of System.IO.Ports.SerialPort and SerialStream for better reliability and maintainability. Default branch is 2.x and now has support for Mono with help of a C library.
* [Grabacr07/VirtualDesktop](https://github.com/Grabacr07/VirtualDesktop) - C# wrapper for the Virtual Desktop API on Windows 11.
* [MelbourneDeveloper/Device.Net](https://github.com/MelbourneDeveloper/Device.Net) - A C# cross platform connected device framework
* [unosquare/raspberryio](https://github.com/unosquare/raspberryio) - The Raspberry Pi's IO Functionality in an easy-to-use API for Mono/.NET/C# *(archived)*
* [PeterKottas/DotNetCore.WindowsService](https://github.com/PeterKottas/DotNetCore.WindowsService) - Simple library that allows one to host dot net core application as windows services. Perfect solution to power micro-services architecture.

### Date and Time

* [quartznet/quartznet](https://github.com/quartznet/quartznet) - Quartz Enterprise Scheduler .NET
* [Arcenox-co/TickerQ](https://github.com/Arcenox-co/TickerQ) - TickerQ is a fast, reflection-free background task scheduler for .NET built with source generators, EF Core integration, cron + time-based execution, and a real-time dashboard.
* [nodatime/nodatime](https://github.com/nodatime/nodatime) - A better date and time API for .NET
* [fluentscheduler/FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface for the .NET platform.
* [HangfireIO/Cronos](https://github.com/HangfireIO/Cronos) - A fully-featured .NET library for working with Cron expressions. Built with time zones in mind and intuitively handles daylight saving time transitions
* [bradymholt/cron-expression-descriptor](https://github.com/bradymholt/cron-expression-descriptor) - A .NET library that converts cron expressions into human readable descriptions.
* [guryanovev/CrystalQuartz](https://github.com/guryanovev/CrystalQuartz) - pluggable UI for Quartz.NET
* [mattjohnsonpint/TimeZoneConverter](https://github.com/mattjohnsonpint/TimeZoneConverter) - Lightweight libraries to convert between IANA, Windows, Rails, and POSIX time zones.
* [hey-hoho/ScheduleMasterCore](https://github.com/hey-hoho/ScheduleMasterCore) - This is a distributed task management system base on .Net Core platform .

### Automation and Scripting

* [babalae/better-genshin-impact](https://github.com/babalae/better-genshin-impact) - 📦BetterGI · 更好的原神 - 自动拾取 | 自动剧情 | 全自动钓鱼(AI) | 全自动七圣召唤 | 自动伐木 | 自动刷本 | 自动采集/挖矿/锄地 | 一条龙 | 全连音游 | 自动烹饪 | 桌面分身 - UI Automation Testing Tools For Genshin Impact
* [RayWangQvQ/BiliBiliToolPro](https://github.com/RayWangQvQ/BiliBiliToolPro) - B 站（bilibili）自动任务工具，支持docker、青龙、k8s等多种部署方式。全面拥抱AI。敏感肌也能用。
* [elsa-workflows/elsa-core](https://github.com/elsa-workflows/elsa-core) - The Workflow Engine for .NET
* [danielgerlag/workflow-core](https://github.com/danielgerlag/workflow-core) - Lightweight workflow engine for .NET Standard
* [TelegramBots/Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) - .NET Client for Telegram Bot API
* [discord-net/Discord.Net](https://github.com/discord-net/Discord.Net) - An unofficial .Net wrapper for the Discord API (https://discord.com/)
* [open-rpa/openrpa](https://github.com/open-rpa/openrpa) - Free Open Source Enterprise Grade RPA
* [dotnet-script/dotnet-script](https://github.com/dotnet-script/dotnet-script) - Run C# scripts from the .NET CLI.
* [scriptcs/scriptcs](https://github.com/scriptcs/scriptcs) - Write C# apps with a text editor, nuget and the power of Roslyn!
* [PSAppDeployToolkit/PSAppDeployToolkit](https://github.com/PSAppDeployToolkit/PSAppDeployToolkit) - Project Homepage & Forums
* [cschneegans/unattend-generator](https://github.com/cschneegans/unattend-generator) - .NET Core library to create highly customized autounattend.xml files
* [MCCTeam/Minecraft-Console-Client](https://github.com/MCCTeam/Minecraft-Console-Client) - Lightweight console for Minecraft chat and automated scripts. Currently supports up to Minecraft 26.2
* [recyclarr/recyclarr](https://github.com/recyclarr/recyclarr) - Automatically sync TRaSH Guides to your Sonarr and Radarr instances
* [oleg-shilo/cs-script](https://github.com/oleg-shilo/cs-script) - C# scripting platform
* [Azure/durabletask](https://github.com/Azure/durabletask) - Durable Task Framework allows users to write long running persistent workflows in C# using the async/await capabilities.
* [saucepleez/taskt](https://github.com/saucepleez/taskt) - taskt (pronounced 'tasked' and formely sharpRPA) is free and open-source robotic process automation (rpa) built in C# powered by the .NET Framework
* [insoxin/China-Telecom-Helper](https://github.com/insoxin/China-Telecom-Helper) - 中国电信助手,白嫖年入保底256+话费 .每月金豆领取(lv6,1000金豆),每日签到(随机金豆),每日喂食宠物.每日登录奖励领取(5金豆),查看我的云盘(10金豆),翻牌 (10金豆),查看我的订单 (5金豆),打开消息 (100金豆),当日分享 (50金豆),浏览生活频道 (5金豆),查看我的金豆 (5金豆),关注直播 (5金豆),观看直播15s (5金豆),打开消息 (100金豆),答问卷 (100金豆),支付宝小程序
* [microsoft/PowerPlatformConnectors](https://github.com/microsoft/PowerPlatformConnectors) - This is a repository for Microsoft Power Automate, Power Apps, and Azure Logic Apps connectors
* [UiPath/CoreWF](https://github.com/UiPath/CoreWF) - WF runtime ported to work on .NET 6
* [michaelnoonan/inputsimulator](https://github.com/michaelnoonan/inputsimulator) - Windows Input Simulator (C# SendInput Wrapper - Simulate Keyboard and Mouse)
* [patriksvensson/cupboard](https://github.com/patriksvensson/cupboard) - A framework for provisioning local environments to a desired state, using the .NET SDK.
* [ALIILAPRO/warp-plus-cloudflare](https://github.com/ALIILAPRO/warp-plus-cloudflare) - Script for getting unlimited GB on Warp+ ( https://1.1.1.1/ )

### General Purpose Libraries

* [App-vNext/Polly](https://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner. From version 6.0.1, Polly targets .NET Standard 1.1 and 2.0+.
* [LuckyPennySoftware/MediatR](https://github.com/LuckyPennySoftware/MediatR) - Simple, unambitious mediator implementation in .NET
* [LuckyPennySoftware/AutoMapper](https://github.com/LuckyPennySoftware/AutoMapper) - A convention-based object-object mapper in .NET.
* [FluentValidation/FluentValidation](https://github.com/FluentValidation/FluentValidation) - A popular .NET validation library for building strongly-typed validation rules.
* [louthy/language-ext](https://github.com/louthy/language-ext) - C# pure functional programming framework - come and get declarative!
* [pardeike/Harmony](https://github.com/pardeike/Harmony) - A library for patching, replacing and decorating .NET and Mono methods during runtime
* [dotnet-state-machine/stateless](https://github.com/dotnet-state-machine/stateless) - A simple library for creating state machines in C# code
* [ldqk/Masuit.Tools](https://github.com/ldqk/Masuit.Tools) - 全龄段友好的C#万能工具库，码数吐司库，包含一些常用的操作类，大都是静态类，加密解密，反射操作，权重随机筛选算法，分布式短id，表达式树，linq扩展，文件压缩，多线程下载，硬件信息，字符串扩展方法，日期时间扩展操作，中国农历，大文件拷贝，图像裁剪，验证码，断点续传，集合扩展、Excel导出等常用封装。诸多功能集一身，代码量不到2MB！
* [laochiangx/Common.Utility](https://github.com/laochiangx/Common.Utility) - Various helper class
* [Cysharp/ZLinq](https://github.com/Cysharp/ZLinq) - Zero allocation LINQ with LINQ to Span, LINQ to SIMD, and LINQ to Tree (FileSystem, JSON, GameObject, etc.) for all .NET platforms and Unity, Godot.
* [MapsterMapper/Mapster](https://github.com/MapsterMapper/Mapster) - A fast, fun and stimulating object to object Mapper
* [autofac/Autofac](https://github.com/autofac/Autofac) - An addictive .NET IoC container
* [microsoft/RulesEngine](https://github.com/microsoft/RulesEngine) - A fast and reliable .NET Rules Engine with extensive Dynamic expression support
* [khellang/Scrutor](https://github.com/khellang/Scrutor) - Assembly scanning and decoration extensions for Microsoft.Extensions.DependencyInjection
* [jamesmh/coravel](https://github.com/jamesmh/coravel) - Near-zero config .NET library that makes advanced application features like Task Scheduling, Caching, Queuing, Event Broadcasting, and more a breeze!
* [riok/mapperly](https://github.com/riok/mapperly) - A .NET source generator for generating object mappings. No runtime reflection.
* [mcintyre321/OneOf](https://github.com/mcintyre321/OneOf) - Easy to use F#-like ~discriminated~ unions for C# with exhaustive compile time matching
* [morelinq/MoreLINQ](https://github.com/morelinq/MoreLINQ) - Extensions to LINQ to Objects
* [CommunityToolkit/dotnet](https://github.com/CommunityToolkit/dotnet) - .NET Community Toolkit is a collection of helpers and APIs that work for all .NET developers and are agnostic of any specific UI platform. The toolkit is maintained and published by Microsoft, and part of the .NET Foundation.
* [ardalis/GuardClauses](https://github.com/ardalis/GuardClauses) - A simple package with guard clause extensions.
* [dotnet/extensions](https://github.com/dotnet/extensions) - This repository contains a suite of libraries that provide facilities commonly needed when creating production-ready applications.
* [hadashiA/VContainer](https://github.com/hadashiA/VContainer) - The extra fast, minimum code size, GC-free DI (Dependency Injection) library running on Unity Game Engine.
* [vkhorikov/CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional extensions for C#
* [ninject/Ninject](https://github.com/ninject/Ninject) - the ninja of .net dependency injectors
* [altmann/FluentResults](https://github.com/altmann/FluentResults) - A generalised Result object implementation for .NET/C#
* [ardalis/SmartEnum](https://github.com/ardalis/SmartEnum) - A base class for quickly and easily creating strongly typed enum replacements in C#.
* [castleproject/Core](https://github.com/castleproject/Core) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter
* [Sergio0694/PolySharp](https://github.com/Sergio0694/PolySharp) - PolySharp provides generated, source-only polyfills for C# language features, to easily use all runtime-agnostic features downlevel. Add a reference, set your C# version to latest and have fun! 🚀
* [error-or/error-or](https://github.com/error-or/error-or) - A simple, fluent discriminated union of an error or a result.
* [Fody/PropertyChanged](https://github.com/Fody/PropertyChanged) - Injects INotifyPropertyChanged code into properties at compile time
* [dotnet/dotNext](https://github.com/dotnet/dotNext) - Next generation API for .NET
* [reactivemarbles/DynamicData](https://github.com/reactivemarbles/DynamicData) - Reactive collections based on Rx.Net
* [natemcmaster/DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) - .NET Core library for dynamically loading code
* [dotnetcore/AspectCore-Framework](https://github.com/dotnetcore/AspectCore-Framework) - AspectCore is an AOP-based cross platform framework for .NET Standard.
* [zzzprojects/Z.ExtensionMethods](https://github.com/zzzprojects/Z.ExtensionMethods) - C# Extension Methods | Over 1000 extension methods:
* [zzzprojects/System.Linq.Dynamic.Core](https://github.com/zzzprojects/System.Linq.Dynamic.Core) - The .NET Standard / .NET Core version from the System Linq Dynamic functionality.
* [Cysharp/Ulid](https://github.com/Cysharp/Ulid) - Fast .NET C# Implementation of ULID for .NET and Unity.
* [dotnet/corefxlab](https://github.com/dotnet/corefxlab) - This repo is for experimentation and exploring new ideas that may or may not make it into the main corefx repo. *(archived)*
* [justcoding121/advanced-algorithms](https://github.com/justcoding121/advanced-algorithms) - 100+ algorithms & data structures generically implemented in C#
* [pakrym/jab](https://github.com/pakrym/jab) - C# Source Generator based dependency injection container implementation.
* [BlueRaja/High-Speed-Priority-Queue-for-C-Sharp](https://github.com/BlueRaja/High-Speed-Priority-Queue-for-C-Sharp) - A C# priority queue optimized for pathfinding applications
* [GregFinzer/Compare-Net-Objects](https://github.com/GregFinzer/Compare-Net-Objects) - What you have been waiting for :+1: Perform a deep compare of any two .NET objects using reflection. Shows the differences between the two objects.
* [sestoft/C5](https://github.com/sestoft/C5) - C5 generic collection library for C#/.NET
* [Cysharp/ObservableCollections](https://github.com/Cysharp/ObservableCollections) - High performance observable collections and synchronized views, for WPF, Blazor, Unity.
* [yuzhengyang/Fork](https://github.com/yuzhengyang/Fork) - a c# utility library. C#工具包，C#工具类，常用方法，系统API，文件处理、加密解密、Winform美化（C# Tools）
* [mcintyre321/ValueOf](https://github.com/mcintyre321/ValueOf) - Deal with Primitive Obsession - define ValueObjects in a single line (of C#).
* [bing-framework/Bing.NetCore](https://github.com/bing-framework/Bing.NetCore) - Bing是基于 .net core 3.1 的框架，旨在提升团队的开发输出能力，由常用公共操作类（工具类、帮助类）、分层架构基类，第三方组件封装，第三方业务接口封装等组成。
* [nlkl/Optional](https://github.com/nlkl/Optional) - A robust option type for C#
* [domn1995/dunet](https://github.com/domn1995/dunet) - C# discriminated union source generator
* [grumpydev/TinyIoC](https://github.com/grumpydev/TinyIoC) - An easy to use, hassle free, Inversion of Control Container for small projects, libraries and beginners alike.
* [pamidur/aspect-injector](https://github.com/pamidur/aspect-injector) - AOP framework for .NET (c#, vb, etc)
* [abdonkov/DSA](https://github.com/abdonkov/DSA) - Data structures and algorithms in C#

## Systems and Hardware

### Embedded and Firmware

* [dorssel/usbipd-win](https://github.com/dorssel/usbipd-win) - Windows software for sharing locally connected USB devices to other machines, including Hyper-V guests and WSL 2.
* [nomi-san/parsec-vdd](https://github.com/nomi-san/parsec-vdd) - ✨ Perfect virtual display for game streaming
* [Davidobot/BetterJoy](https://github.com/Davidobot/BetterJoy) - Allows the Nintendo Switch Pro Controller, Joycons and SNES controller to be used with CEMU, Citra, Dolphin, Yuzu and as generic XInput
* [brandonlw/Psychson](https://github.com/brandonlw/Psychson) - Phison 2251-03 (2303) Custom Firmware & Existing Firmware Patches (BadUSB)
* [OpenTabletDriver/OpenTabletDriver](https://github.com/OpenTabletDriver/OpenTabletDriver) - Open source, cross-platform, user-mode tablet driver
* [nefarius/ScpToolkit](https://github.com/nefarius/ScpToolkit) - Windows Driver and XInput Wrapper for Sony DualShock 3/4 Controllers *(archived)*
* [qmk/qmk_toolbox](https://github.com/qmk/qmk_toolbox) - A Toolbox companion for QMK Firmware
* [Metabolix/HackBGRT](https://github.com/Metabolix/HackBGRT) - Windows boot logo changer for UEFI systems
* [RawAccelOfficial/rawaccel](https://github.com/RawAccelOfficial/rawaccel) - kernel mode mouse accel
* [dotnet/iot](https://github.com/dotnet/iot) - This repo includes .NET Core implementations for various IoT boards, chips, displays and PCBs.
* [koush/UniversalAdbDriver](https://github.com/koush/UniversalAdbDriver) - One size fits all Windows Drivers for Android Debug Bridge.

## Business and Domain

### Finance and Trading

* [StockSharp/StockSharp](https://github.com/StockSharp/StockSharp) - Algorithmic trading and quantitative trading open source platform to develop trading robots (stock markets, forex, crypto, bitcoins, and options).
* [btcpayserver/btcpayserver](https://github.com/btcpayserver/btcpayserver) - Accept Bitcoin payments. Free, open-source & self-hosted, Bitcoin payment processor.
* [smartstore/SmartStoreNET](https://github.com/smartstore/SmartStoreNET) - Open Source ASP.NET MVC Enterprise eCommerce Shopping Cart Solution
* [WalletWasabi/WalletWasabi](https://github.com/WalletWasabi/WalletWasabi) - Open-source, non-custodial, privacy preserving Bitcoin wallet for Windows, Linux, and Mac.
* [grandnode/grandnode](https://github.com/grandnode/grandnode) - Open source, headless, multi-tenant eCommerce platform built with .NET Core, MongoDB, AWS DocumentDB, Azure CosmosDB, Vue.js. *(archived)*
* [essensoft/paylinks](https://github.com/essensoft/paylinks) - 一套基于 现代 .NET 开发，支持跨平台、多商户的第三方支付SDK。

## Science and Math

### Mathematics

* [zalo/MathUtilities](https://github.com/zalo/MathUtilities) - A collection of some of the neat math and physics tricks that I've collected over the last few years.
* [mathnet/mathnet-numerics](https://github.com/mathnet/mathnet-numerics) - Math.NET Numerics
* [angularsen/UnitsNet](https://github.com/angularsen/UnitsNet) - Makes life working with units of measurement just a little bit better.
* [FreyaHolmer/Mathfs](https://github.com/FreyaHolmer/Mathfs) - Expanded Math Functionality for Unity
* [gradientspace/geometry3Sharp](https://github.com/gradientspace/geometry3Sharp) - C# library for 2D/3D geometric computation, mesh algorithms, and so on. Boost license.
* [Habrador/Computational-geometry](https://github.com/Habrador/Computational-geometry) - Computational Geometry Unity library with implementations of intersection algorithms, triangulations like delaunay, voronoi diagrams, polygon clipping, bezier curves, ear clipping, convex hulls, mesh simplification, etc
* [Unity-Technologies/Unity.Mathematics](https://github.com/Unity-Technologies/Unity.Mathematics) - The C# math library used in Unity providing vector types and math functions with a shader like syntax
* [asc-community/AngouriMath](https://github.com/asc-community/AngouriMath) - Open-source cross-platform symbolic algebra library for C# and F#. Can be used for both production and research purposes.
* [SciSharp/Numpy.NET](https://github.com/SciSharp/Numpy.NET) - C#/F# bindings for NumPy - a fundamental library for scientific computing, machine learning and AI
* [john-h-k/MathSharp](https://github.com/john-h-k/MathSharp) - A vector and matrix library written in C# using hardware intrinsics
* [asik/FixedMath.Net](https://github.com/asik/FixedMath.Net) - Fixed point math C# library *(archived)*

### Scientific Computing

* [SebLague/Digital-Logic-Sim](https://github.com/SebLague/Digital-Logic-Sim)
* [udacity/self-driving-car-sim](https://github.com/udacity/self-driving-car-sim) - A self-driving car simulator built with Unity *(archived)*
* [GavinYellow/SharpSCADA](https://github.com/GavinYellow/SharpSCADA) - C# SCADA
* [Unity-Technologies/Unity-Robotics-Hub](https://github.com/Unity-Technologies/Unity-Robotics-Hub) - Central repository for tools, tutorials, resources, and documentation for robotics simulation in Unity.
* [lgsvl/simulator](https://github.com/lgsvl/simulator) - A ROS/ROS2 Multi-robot Simulator for Autonomous Vehicles
* [siemens/ros-sharp](https://github.com/siemens/ros-sharp) - ROS# is a set of open source software libraries and tools in C# for communicating with ROS from .NET applications, in particular Unity3D
* [snape/RVO2-CS](https://github.com/snape/RVO2-CS) - Optimal Reciprocal Collision Avoidance (C#)

## Other

* [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) - Integrate cutting-edge LLM technology quickly and easily into your apps
* [thangchung/awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core) - :honeybee: A collection of awesome .NET core libraries, tools, frameworks and software
* [bitwarden/server](https://github.com/bitwarden/server) - Bitwarden infrastructure/backend (API, database, Docker, etc).
* [CoplayDev/unity-mcp](https://github.com/CoplayDev/unity-mcp) - Unity MCP acts as a bridge between AI assistants and your Unity Editor. Give your LLM tools to manage assets, control scenes, edit scripts, and automate tasks within Unity.
* [MiniMax-AI/skills](https://github.com/MiniMax-AI/skills)
* [dotnet/yarp](https://github.com/dotnet/yarp) - A toolkit for developing high-performance HTTP reverse proxy applications.
* [ThreeMammals/Ocelot](https://github.com/ThreeMammals/Ocelot) - .NET API Gateway
* [Uahh/ToastFish](https://github.com/Uahh/ToastFish) - 一个利用摸鱼时间背单词的软件。
* [Sylinko/Everywhere](https://github.com/Sylinko/Everywhere) - On-screen aware AI assistant for your desktop. Uses current app context, multiple LLMs, and MCP tools to help you act across apps.
* [PhilippC/keepass2android](https://github.com/PhilippC/keepass2android) - Password manager app for Android
* [win-acme/win-acme](https://github.com/win-acme/win-acme) - Automate SSL/TLS certificates on Windows with ease
* [Justsenger/ExHyperV](https://github.com/Justsenger/ExHyperV) - The Excalibur of Hyper-V / Hyper-V 神器
* [p-org/P](https://github.com/p-org/P) - The P programming language.
* [microsoft/mcp](https://github.com/microsoft/mcp) - Catalog of official Microsoft MCP (Model Context Protocol) server implementations for AI-powered data access and tool integration
* [dafny-lang/dafny](https://github.com/dafny-lang/dafny) - Dafny is a verification-aware programming language
* [wolfgarbe/SymSpell](https://github.com/wolfgarbe/SymSpell) - SymSpell: 1 million times faster spelling correction & fuzzy search through Symmetric Delete spelling correction algorithm
* [CosmosOS/Cosmos](https://github.com/CosmosOS/Cosmos) - Cosmos is an operating system "construction kit". Build your own OS using managed languages such as C#, VB.NET, and more!
* [FastReports/FastReport](https://github.com/FastReports/FastReport) - Free Open Source Reporting tool for .NET6/.NET Core/.NET Framework that helps your application generate document-like reports
* [aspnet/KestrelHttpServer](https://github.com/aspnet/KestrelHttpServer) - [Archived] A cross platform web server for ASP.NET Core. Project moved to https://github.com/aspnet/AspNetCore *(archived)*
* [apache/lucenenet](https://github.com/apache/lucenenet) - Apache Lucene.NET is an open-source full-text search library written in C#, ported from the Apache Lucene project.
* [microsoft/kernel-memory](https://github.com/microsoft/kernel-memory) - Research project. A Memory solution for users, teams, and applications.
* [Carlos487/awesome-wpf](https://github.com/Carlos487/awesome-wpf) - A collection of awesome WPF resources, libraries and UI controls.
* [openclaw/openclaw-windows-node](https://github.com/openclaw/openclaw-windows-node) - Windows companion suite for OpenClaw
* [jasonhua95/awesome-dotnet-core](https://github.com/jasonhua95/awesome-dotnet-core) - .NET Core库、工具、框架和软件的中文收录大全。 内容包括：库、工具、框架、模板引擎、身份认证、数据库、ORM框架、图片处理、文本处理、机器学习、日志、代码分析、教程等。
* [justcoding121/titanium-web-proxy](https://github.com/justcoding121/titanium-web-proxy) - A cross-platform high performing HTTP(S) proxy server in C#.
* [bcgit/bc-csharp](https://github.com/bcgit/bc-csharp) - BouncyCastle.NET Cryptography Library (Mirror)
* [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) - Model Context Protocol (MCP) plugin to connect with Unity Editor — designed for Cursor, Claude Code, Codex, Windsurf and other IDEs
* [microsoft/CodeXGLUE](https://github.com/microsoft/CodeXGLUE) - CodeXGLUE
* [webprofusion/certify](https://github.com/webprofusion/certify) - Professional ACME Client for Windows (and now cross-platform via Certify Management Hub). Certificate Management UI, powered by Let's Encrypt and compatible with all ACME v2 CAs. Used by over 150,000 organisations. Download from certifytheweb.com
* [NRules/NRules](https://github.com/NRules/NRules) - Rules engine for .NET, based on the Rete matching algorithm, with internal DSL in C#.
* [bianchenglequ/NetCodeTop](https://github.com/bianchenglequ/NetCodeTop) - 收集GitHub上有关C#/.Net、.NetCore有趣、有用、热门的开源项目。
* [MarimerLLC/csla](https://github.com/MarimerLLC/csla) - A home for your business logic in any .NET application.
* [amaneureka/AtomOS](https://github.com/amaneureka/AtomOS) - A multitasking monolithic Kernel based x86 targeting Operating System written in C# from scratch aiming for high-level implementation of drivers in managed environment.
* [nifanfa/MOOS](https://github.com/nifanfa/MOOS) - C# x64 operating system programming with the .NET native ahead-of-time compilation technology. *(archived)*
* [microsoft/CodeContracts](https://github.com/microsoft/CodeContracts) - Source code for the CodeContracts tools for .NET *(archived)*
* [curiosity-ai/catalyst](https://github.com/curiosity-ai/catalyst) - 🚀 Catalyst is a C# Natural Language Processing library built for speed. Inspired by spaCy's design, it brings pre-trained models, out-of-the box support for training word and document embeddings, and flexible entity recognition models.
* [JakeBayer/FuzzySharp](https://github.com/JakeBayer/FuzzySharp) - C# .NET fuzzy string matching implementation of Seat Geek's well known python FuzzyWuzzy algorithm.
* [yatt-ze/The-Collection](https://github.com/yatt-ze/The-Collection) - Collection of cracked malware, and ebooks
* [Lunat1q/Catchem-PoGo](https://github.com/Lunat1q/Catchem-PoGo) - Project is DEAD, Discord server: https://discord.me/Catchem *(archived)*
* [FlingOS/FlingOS](https://github.com/FlingOS/FlingOS) - An educational operating system written in C#. A great stepping stone from high to low level development. *(archived)*
* [bleroy/lunr-core](https://github.com/bleroy/lunr-core) - Lunr-core is a small, full text search library for use in small applications. It's a .NET port of LUNR.js.
