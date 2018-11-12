# PVD Project Wiki

## Table of contents
* [Abstract](#abstract)
* [Components](#components)
	* [Android App](#android-application)
	* [Web Server](#web-server)
	* [Data Processor](#data-processor)

> A project by Ori Cohen & Samyon Shahnovitch  
> Supervised by Ofer Danino & Erez Fridman  
> Technion EE, SIPL Lab, 2018.
<br />


## Abstract
Project description, as quoted from the project report:
> PVD is a highly common blood vessel disease in modern society, which can be treated in a variety of ways.
> Treatment of the disease ranges from non-invasive treatments such as taking drugs to especially invasive
> treatments such as surgery under anesthesia. However, the problem we wish to solve relates to the
> accessibility of diagnosing the disease to the general population, with an emphasis on simple diagnosis.
> Today, diagnosis of the disease requires expensive resources because the existing tests require hospital
> equipment and the interpretation of a specialist.
> In this project we are trying to implement a smart and accessible system for identifying a symptom of PVD.
> Prof. Aharon Hoffman suggested using a free smartphone application that measures the patient's
> acceleration during walking. The phone is placed in the user's pocket and by command is measuring his
> acceleration for a few minutes.
> This project is a follow-up project. However, we needed to do all the work again due to significant failures in
> the previous results that led to the selection of a new solution. In Part I of the project, we will focus primarily
> on the initial processing phase, building the application, using a server for the data storage and the system
> used by the doctor, and processing the initial information that the application measures in order to extract a
> number of features that we can use more easily to diagnose the disease.
> Eventually, a learning system will be used to examine these characteristics and classify whether the person is
> ill and the degree of his illness.
<br />

## Components

Our project is divided into components, where each component is responsible for some part of the project.
<br />

* ### Android Application
	The Android app is responsible for the data acquisition part of our project.  
	The app is connecting to the smartphone sensors, records their data and uploads it to our server,  
	While providing a very simple user interface

	> **Development environment:**	Android Studio 3.2.1  
	> **Programming language:**		Java  
	> **Wiki page:**				[Android application](www.mywiki.com)  
	> **GitHub repository:**		[samyon196/pvd_app](https://github.com/samyon196/pvd_app/)  	
<br />

* ### Web Server
	Our web server is responsible for data exchange between the app and the processor,  
	And also serves as a user interface for the doctors to view the data uploaded from the app and label it with sickness classes.

	> **Development environment:** PhpStorm  
	> **Programming language:** HTML+CSS For display, PHP For logic  
	> **GitHub repository:** [samyon196/pvd_server](https://github.com/samyon196/pvd_server/)  
	> **Wiki page:** [Web Server](www.mywiki.com)  
<br />

* ### Data Processor
	Our data processor downloads the smaples from the srever..  
	Edit..
	Edit..  
	Edit..  
	And uploads it back as a folder

	> **Development environment:** PyCharm  
	> **Programming language:** Python  
	> **GitHub repository:** [samyon196/pvd_processor](https://github.com/samyon196/pvd_processor/)  
	> **Wiki page:** [Data Processor](www.mywiki.com)
<br />
