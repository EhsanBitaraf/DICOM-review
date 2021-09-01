#

<div align="center">
<p style="font-size:30px">DICOM Review</p>
This is a preliminary review of tools and codes related to the DICOM standard. It is an attempt to classify them.
<p>
 <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintained" > 
 <img src="https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg" alt="ask me anything" > 
 <img src="https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg" alt="made with Markdown" > 
 <img src="https://img.shields.io/github/last-commit/EhsanBitaraf/DICOM-review" alt="last commit" > 
 <img src="https://badges.aleen42.com/src/buymeacoffee.svg" alt="buy me a coffee" > 
<p>
 <img src="https://badges.frapsoft.com/os/v1/open-source.png?v=103" alt="open source" > 
</p>
</p>
</div>


# About [DICOM](https://www.dicomstandard.org/)


DICOM® — Digital Imaging and Communications in Medicine — is the international standard for medical images and related information. It defines the formats for medical images that can be exchanged with the data and quality necessary for clinical use.

DICOM® is implemented in almost every radiology, cardiology imaging, and radiotherapy device (X-ray, CT, MRI, ultrasound, etc.), and increasingly in devices in other medical domains such as ophthalmology and dentistry. With hundreds of thousands of medical imaging devices in use, DICOM® is one of the most widely deployed healthcare messaging Standards in the world. There are literally billions of DICOM® images currently in use for clinical care.

Since its first publication in 1993, DICOM® has revolutionized the practice of radiology, allowing the replacement of X-ray film with a fully digital workflow. Much as the Internet has become the platform for new consumer information applications, DICOM® has enabled advanced medical imaging applications that have “changed the face of clinical medicine”. From the emergency department, to cardiac stress testing, to breast cancer detection, DICOM® is the standard that makes medical imaging work — for doctors and for patients.

DICOM® is recognized by the International Organization for Standardization as the ISO 12052 standard.


# DICOM Standard Parts
[DICOM **Part 1**](http://dicom.nema.org/medical/dicom/current/output/html/part01.html): Introduction and Overview	

[DICOM **Part 2**](http://dicom.nema.org/medical/dicom/current/output/html/part02.html): Conformance 
	
[DICOM **Part 3**](http://dicom.nema.org/medical/dicom/current/output/html/part03.html): Information Object Definitions
 	
[DICOM **Part 4**](http://dicom.nema.org/medical/dicom/current/output/html/part04.html): Service Class Specifications
 	
[DICOM **Part 5**](http://dicom.nema.org/medical/dicom/current/output/html/part05.html): Data Structures and Encoding
 	
[DICOM **Part 6**](http://dicom.nema.org/medical/dicom/current/output/html/part06.html): Data Dictionary
 	
[DICOM **Part 7**](http://dicom.nema.org/medical/dicom/current/output/html/part07.html): Message Exchange
 	
[DICOM **Part 8**](http://dicom.nema.org/medical/dicom/current/output/html/part08.html): Network Communication Support for Message Exchange
 	
[DICOM **Part 10**](http://dicom.nema.org/medical/dicom/current/output/html/part10.html): Media Storage and File Format for Media Interchange
 	
[DICOM **Part 11**](http://dicom.nema.org/medical/dicom/current/output/html/part11.html): Media Storage Application Profiles
 	
[DICOM **Part 12**](http://dicom.nema.org/medical/dicom/current/output/html/part12.html): Media Formats and Physical Media for Media Interchange
 	
[DICOM **Part 14**](http://dicom.nema.org/medical/dicom/current/output/html/part14.html): Grayscale Standard Display Function
 	
[DICOM **Part 15**](http://dicom.nema.org/medical/dicom/current/output/html/part15.html): Security and System Management Profiles
 	
[DICOM **Part 16**](http://dicom.nema.org/medical/dicom/current/output/html/part16.html): Content Mapping Resource
 	
[DICOM **Part 17**](http://dicom.nema.org/medical/dicom/current/output/html/part17.html): Explanatory Information
 	
[DICOM **Part 18**](http://dicom.nema.org/medical/dicom/current/output/html/part18.html): Web Services
 	
[DICOM **Part 19**](http://dicom.nema.org/medical/dicom/current/output/html/part19.html): Application Hosting
 	
[DICOM **Part 20**](http://dicom.nema.org/medical/dicom/current/output/html/part20.html): Imaging Reports using HL7 Clinical Document Architecture 
	
[DICOM **Part 21**](http://dicom.nema.org/medical/dicom/current/output/html/part21.html): Transformations between DICOM and other Representations
 	
[DICOM **Part 22**](http://dicom.nema.org/medical/dicom/current/output/html/part22.html): Real-Time Communication

# DICOMweb™

>DICOMweb™ is the DICOM Standard for web-based medical imaging. It is a set of RESTful services, enabling web developers to unlock the power of healthcare images using industry-standard toolsets. DICOMweb can be implemented directly or as a proxy to the DIMSE services to offer modern web-based access to DICOM-enabled systems. Image-producing modalities don’t all need to be retrofitted to support DICOMweb.

**DICOMweb Services**

|Service     |Description                               |Standard         |
|------------|------------------------------------------|-----------------|
|Query       |Search for DICOM objects (QIDO-RS)        |[DICOM PS3.18 10.6](http://dicom.nema.org/medical/dicom/current/output/chtml/part18/sect_10.6.html)|
|Retrieve    |Retrieve DICOM objects (WADO-RS)          |[DICOM PS3.18 10.4](http://dicom.nema.org/medical/dicom/current/output/chtml/part18/sect_10.4.html)|
|  	     |Retrieve single DICOM instances (WADO-URI)|[DICOM PS3.18 9](http://dicom.nema.org/medical/dicom/current/output/chtml/part18/chapter_9.html)   |
|Store 	     |Store DICOM objects (STOW-RS) 	        |[DICOM PS3.18 10.5](http://dicom.nema.org/medical/dicom/current/output/chtml/part18/sect_10.5.html)|
|Worklist    |Manage worklist items (UPS-RS)            |[DICOM PS3.18 11](http://dicom.nema.org/medical/dicom/current/output/chtml/part18/chapter_11.html)  |
|Capabilities|Discover services                         |[DICOM PS3.18 8.9](http://dicom.nema.org/medical/dicom/current/output/chtml/part18/sect_8.9.html) |


#
------
# Table of Content

- [DICOM Viewer](#dicom-viewer)
	- [osirix](#osirix)
	- [dicomweb-client](#dicomweb-client)
	- [DICOMweb-js](#dicomweb-js)
	- [dicomweb-client](#dicomweb-client-1)
	- [u-dicom-viewer](#u-dicom-viewer)
	- [dwv-vue](#dwv-vue)
	- [react-cornerstone-viewport](#react-cornerstone-viewport)
	- [react-cornerstone-example](#react-cornerstone-example)
	- [dicom-microscopy-viewer](#dicom-microscopy-viewer)
	- [dicomViewerLib](#dicomviewerlib)
	- [bluelight](#bluelight)
	- [Dicom-Viewer](#dicom-viewer-1)
	- [Visualization-DMIM](#visualization-dmim)
	- [dwv-jqmobile](#dwv-jqmobile)
	- [dicom-viewer](#dicom-viewer-2)
	- [DicomBrowser](#dicombrowser)
	- [simply-dicom](#simply-dicom)
	- [embedded-pydicom-react-viewer](#embedded-pydicom-react-viewer)
	- [GDP](#gdp)
	- [DicomVis](#dicomvis)
	- [DICOM\_viewer](#dicom_viewer)
	- [cornerstone](#cornerstone)
- [DICOM Parser](#dicom-parser)
	- [pynetdicom](#pynetdicom)
	- [Daikon](#daikon)
	- [Evil-DICOM](#evil-dicom)
	- [dicomutils](#dicomutils)
	- [dicom\_parser](#dicom_parser)
	- [pydicom](#pydicom)
	- [fo-dicom](#fo-dicom)
	- [fo-dicom-samples](#fo-dicom-samples)
- [DICOM Server](#dicom-server)
	- [cornerstoneWADOImageLoader](#cornerstonewadoimageloader)
	- [dicom-server *](#dicom-server-)
	- [DICOMcloud *](#dicomcloud-)
	- [dicomweb-server](#dicomweb-server)
	- [Conquest-DICOM-Server](#conquest-dicom-server)
	- [clara-dicom-adapter](#clara-dicom-adapter)
	- [hermes **\***](#hermes-)
	- [Orthanc](#orthanc)
	- [dcm4chee-arc-cdi](#dcm4chee-arc-cdi)
- [DICOM Convertor](#dicom-convertor)
	- [mritopng](#mritopng)
	- [dicom2stl](#dicom2stl)
	- [dicom-ecg-plot](#dicom-ecg-plot)
	- [dcmstack](#dcmstack)
	- [Dicom\_RT\_and\_Images\_to\_Mask](#dicom_rt_and_images_to_mask)
	- [dicomweb-proxy](#dicomweb-proxy)
	- [DICOM-to-JPG](#dicom-to-jpg)
	- [wsi-to-dicom-converter](#wsi-to-dicom-converter)
	- [dicomifier](#dicomifier)
	- [imageformats](#imageformats)
	- [pylibjpeg](#pylibjpeg)
- [DICOM Miscellaneous](#dicom-miscellaneous)
	- [DVTk](#dvtk)
	- [ECGToolkit](#ecgtoolkit)
	- [DVH-Analytics](#dvh-analytics)
	- [DICOM-CNN](#dicom-cnn)
	- [dicomWeb](#dicomweb)
	- [Niffler](#niffler)
	- [OnkoDICOM](#onkodicom)
	- [dovo](#dovo)
	- [healthcare-api-dicomweb-cli](#healthcare-api-dicomweb-cli)
	- [dcmgw](#dcmgw)
	- [virtual-dicom-printer](#virtual-dicom-printer)
	- [dicom-character-set](#dicom-character-set)
	- [DICOMToFHIRImagingStudy](#dicomtofhirimagingstudy)
	- [Pinnacle-tar-DICOM](#pinnacle-tar-dicom)
	- [dicom-data-dictionary](#dicom-data-dictionary)
	- [cornerstoneTools](#cornerstonetools)
	- [medpy](#medpy)
- [Image Processing](#image-processing)
- [PACS](#pacs)
	- [Dicoogle](#dicoogle)
	- [EasyPACS **\***](#easypacs-)
	- [neurdicom **\***](#neurdicom-)
	- [RadiologyInformationSystem](#radiologyinformationsystem)
	- [dicomweb-pacs](#dicomweb-pacs)
- [Keyword](#keyword)



# DICOM Viewer

## [osirix](https://github.com/pixmeo/osirix)

OsiriX is the most widely used DICOM viewer in the world. OsiriX MD, the commercial version, is certified for medical use (FDA cleared and CE II labeled).

![GitHub license](https://img.shields.io/github/license/pixmeo/osirix.svg)

![Total line](https://img.shields.io/tokei/lines/github/pixmeo/osirix)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pixmeo/osirix?style=plastic)

![Star](https://img.shields.io/github/stars/pixmeo/osirix?style=social)

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Links** : 

[https://www.osirix-viewer.com/](https://www.osirix-viewer.com/)

## [dicomweb-client](https://github.com/dcmjs-org/dicomweb-client)

JavaScript client implementation of [DICOMweb](https://www.dicomstandard.org/dicomweb/). For further details please refer to [PS3.18 of the DICOM standard](http://dicom.nema.org/medical/dicom/current/output/chtml/part18/PS3.18.html). JavaScript client for DICOMweb RESTful services

![GitHub license](https://img.shields.io/github/license/dcmjs-org/dicomweb-client.svg)

![Total line](https://img.shields.io/tokei/lines/github/dcmjs-org/dicomweb-client)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dcmjs-org/dicomweb-client?style=plastic)

![Star](https://img.shields.io/github/stars/dcmjs-org/dicomweb-client?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

**Package** : 


## [DICOMweb-js](https://github.com/DICOMcloud/DICOMweb-js)

DICOMweb-JS is an open source JS client for consuming DICOM Web Services - part 13 with a ASP.NET MVC demo that uses the [Cornerstone viewer](https://github.com/chafey/cornerstone) and [cornerstoneWADOImageLoader](https://github.com/chafey/cornerstoneWADOImageLoader)

The code provide a basic library for sending DICOM Web requests and parsing JSON and multipart reposnses in (DIOCM, XML, Buld data...) .

![GitHub license](https://img.shields.io/github/license/DICOMcloud/DICOMweb-js.svg)

![Total line](https://img.shields.io/tokei/lines/github/DICOMcloud/DICOMweb-js)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/DICOMcloud/DICOMweb-js?style=plastic)

![Star](https://img.shields.io/github/stars/DICOMcloud/DICOMweb-js?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

**Package** : 

## [dicomweb-client](https://github.com/MGHComputationalPathology/dicomweb-client)

Please refer to the online documentation at [dicomweb-client.readthedocs.io](https://dicomweb-client.readthedocs.io/), which includes a user guide with examples, a developer guide, and complete documentation of the application programming interface of the dicomweb\_client Python package as well as the command line interface of the dicomweb\_client program.

![GitHub license](https://img.shields.io/github/license/MGHComputationalPathology/dicomweb-client.svg)

![Total line](https://img.shields.io/tokei/lines/github/MGHComputationalPathology/dicomweb-client)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/MGHComputationalPathology/dicomweb-client?style=plastic)

![Star](https://img.shields.io/github/stars/MGHComputationalPathology/dicomweb-client?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Package** : 
pydicom

## [u-dicom-viewer](https://github.com/webnamics/u-dicom-viewer)

**U Dicom Viewer** or **UDV** is a simple but functional DICOM viewer for any device with a web browser, it allows to open and view 2D medical images in a wide variety of DICOM formats.

![GitHub license](https://img.shields.io/github/license/webnamics/u-dicom-viewer.svg)

![Total line](https://img.shields.io/tokei/lines/github/webnamics/u-dicom-viewer)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/webnamics/u-dicom-viewer?style=plastic)

![Star](https://img.shields.io/github/stars/webnamics/u-dicom-viewer?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://webnamics.github.io/u-dicom-viewer/](https://webnamics.github.io/u-dicom-viewer/)

**Package** : 
cornerstone-core

## [dwv-vue](https://github.com/ivmartel/dwv-vue)

Medical viewer using [DWV](https://github.com/ivmartel/dwv) (DICOM Web Viewer) and [Vue.js](https://vuejs.org/).

![GitHub license](https://img.shields.io/github/license/ivmartel/dwv-vue.svg)

![Total line](https://img.shields.io/tokei/lines/github/ivmartel/dwv-vue)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ivmartel/dwv-vue?style=plastic)

![Star](https://img.shields.io/github/stars/ivmartel/dwv-vue?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black), Vue

**Links** : 

[https://ivmartel.github.io/dwv-vue/](https://ivmartel.github.io/dwv-vue/)

**Package** : 

## [react-cornerstone-viewport](https://github.com/cornerstonejs/react-cornerstone-viewport)

Cornerstone medical image viewport component for React

![GitHub license](https://img.shields.io/github/license/cornerstonejs/react-cornerstone-viewport.svg)

![Total line](https://img.shields.io/tokei/lines/github/cornerstonejs/react-cornerstone-viewport)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cornerstonejs/react-cornerstone-viewport?style=plastic)

![Star](https://img.shields.io/github/stars/cornerstonejs/react-cornerstone-viewport?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://react.cornerstonejs.org/](https://react.cornerstonejs.org/)

**Package** : 
cornerstone-core

## [react-cornerstone-example](https://github.com/shalkam/react-cornerstone-example)

This is a basic example showing how to use [cornerstrone.js](https://github.com/cornerstonejs/cornerstone) library along with React.js to show DICOM images.

![GitHub license](https://img.shields.io/github/license/shalkam/react-cornerstone-example.svg)

![Total line](https://img.shields.io/tokei/lines/github/shalkam/react-cornerstone-example)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/shalkam/react-cornerstone-example?style=plastic)

![Star](https://img.shields.io/github/stars/shalkam/react-cornerstone-example?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://shalkam.github.io/react-cornerstone-example/](https://shalkam.github.io/react-cornerstone-example/)

**Package** : 
cornerstone-core

## [dicom-microscopy-viewer](https://github.com/MGHComputationalPathology/dicom-microscopy-viewer)

**DICOM Microscopy Viewer**

Vanilla JS library for web-based visualization of [DICOM VL Whole Slide Microscopy Image](http://dicom.nema.org/medical/dicom/current/output/chtml/part03/sect_A.32.8.html) datasets.

The viewer allows visualization of slide microscopy images stored in a [DICOMweb](https://www.dicomstandard.org/dicomweb/) compatible archive. It leverages the [dicomweb-client](https://github.com/dcmjs-org/dicomweb-client) JavaScript library to retrieve data from the archive.

![GitHub license](https://img.shields.io/github/license/MGHComputationalPathology/dicom-microscopy-viewer.svg)

![Total line](https://img.shields.io/tokei/lines/github/MGHComputationalPathology/dicom-microscopy-viewer)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/MGHComputationalPathology/dicom-microscopy-viewer?style=plastic)

![Star](https://img.shields.io/github/stars/MGHComputationalPathology/dicom-microscopy-viewer?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://microscopy.dcmjs.org/](https://microscopy.dcmjs.org/)

[https://mghcomputationalpathology.github.io/dicom-microscopy-viewer/](https://mghcomputationalpathology.github.io/dicom-microscopy-viewer/)

**Package** :
cornerstone-core 

## [dicomViewerLib](https://github.com/fourctv/dicomViewerLib)

Dicom Viewer Component

This is an Angular 9+ DICOM Web Viewer Component, based on [CornerstoneJS](https://github.com/cornerstonejs) Project.

It includes a demo app that can be tried [here](https://fourctv.github.io/dicomViewerDemo/). Demo app source is included in the project.

![GitHub license](https://img.shields.io/github/license/fourctv/dicomViewerLib.svg)

![Total line](https://img.shields.io/tokei/lines/github/fourctv/dicomViewerLib)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/fourctv/dicomViewerLib?style=plastic)

![Star](https://img.shields.io/github/stars/fourctv/dicomViewerLib?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

**Package** :
cornerstone-core 

## [bluelight](https://github.com/cylab-tw/bluelight)

**Blue Light** is a browser-based medical image viewer is primarily maintained by the [Imaging Informatics Labs](https://cylab.dicom.tw/). It is a pure single-page application (SPA), lightweight, and using only JavaScript and HTML5 technologies so as to deploy it on any HTTP server easily (just put it in HTTP server). It supports not only opening local data, but also connecting to medical image archives which support [DICOMweb](https://www.dicomstandard.org/dicomweb/). It can display the various image markups and annotations such as Annotation and Image Markup (AIM), DICOM-RT structure set (RTSS), DICOM Overlay, and DICOM Presentation State. It provides tools for medical image interpretation and 3D image reconstruction, e.g., Multiplanar Rreformation or Reconstruction (MPR) and Volume Rendering (VR).

![GitHub license](https://img.shields.io/github/license/cylab-tw/bluelight.svg)

![Total line](https://img.shields.io/tokei/lines/github/cylab-tw/bluelight)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cylab-tw/bluelight?style=plastic)

![Star](https://img.shields.io/github/stars/cylab-tw/bluelight?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://cylab-tw.github.io/bluelight/bluelight/html/start.html](https://cylab-tw.github.io/bluelight/bluelight/html/start.html)

**Package** :
cornerstone, dicomParser, cornerstoneWADOImageLoader 

## [Dicom-Viewer](https://github.com/wenyalintw/Dicom-Viewer)

An application displaying 2D/3D Dicom

![GitHub license](https://img.shields.io/github/license/wenyalintw/Dicom-Viewer.svg)

![Total line](https://img.shields.io/tokei/lines/github/wenyalintw/Dicom-Viewer)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/wenyalintw/Dicom-Viewer?style=plastic)

![Star](https://img.shields.io/github/stars/wenyalintw/Dicom-Viewer?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** : 

**Package** :
pydicom
, PyQt5

## [Visualization-DMIM](https://github.com/nis1/Visualization-DMIM)

DICOM 3D Medical Image Modeling (DMIM)

Nowadays, patients are sent to MRI, PET, and CT scans more than before. Each scan produces a large amount of information of a patient, normally as a set of 2D slices, that will be inspected by a doctor or a technician. The project aims to visualize any DICOM images by creating a 3D model in addition to the classic slice-by-slice inspection.

![GitHub license](https://img.shields.io/github/license/nis1/Visualization-DMIM.svg)

![Total line](https://img.shields.io/tokei/lines/github/nis1/Visualization-DMIM)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/nis1/Visualization-DMIM?style=plastic)

![Star](https://img.shields.io/github/stars/nis1/Visualization-DMIM?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://www.youtube.com/watch?v=Xz3xwpmoMHg](https://www.youtube.com/watch?v=Xz3xwpmoMHg)

**Package** :

Be checked

## [dwv-jqmobile](https://github.com/ivmartel/dwv-jqmobile)

Medical viewer using [DWV](https://github.com/ivmartel/dwv) (DICOM Web Viewer) and [jQuery mobile](https://jquerymobile.com/).

![GitHub license](https://img.shields.io/github/license/ivmartel/dwv-jqmobile.svg)

![Total line](https://img.shields.io/tokei/lines/github/ivmartel/dwv-jqmobile)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ivmartel/dwv-jqmobile?style=plastic)

![Star](https://img.shields.io/github/stars/ivmartel/dwv-jqmobile?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://ivmartel.github.io/dwv-jqmobile/](https://ivmartel.github.io/dwv-jqmobile/)

**Package** :

Be checked

## [dicom-viewer](https://github.com/termijn/dicom-viewer)

Views medical datasets in 3D

![GitHub license](https://img.shields.io/github/license/termijn/dicom-viewer.svg)

![Total line](https://img.shields.io/tokei/lines/github/termijn/dicom-viewer)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/termijn/dicom-viewer?style=plastic)

![Star](https://img.shields.io/github/stars/termijn/dicom-viewer?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white), ![](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Links** : 

**Package** :
fo-dicom

## [DicomBrowser](https://github.com/ericspod/DicomBrowser)

This is a lightweight portable Dicom browser application written in Python. It allows Dicom directories to be loaded, images and tag data viewed, and not much else aside. This is intended to be a cross-platform utility suitable for previewing Dicom data rather than doing any sort of processing.

![GitHub license](https://img.shields.io/github/license/ericspod/DicomBrowser.svg)

![Total line](https://img.shields.io/tokei/lines/github/ericspod/DicomBrowser)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ericspod/DicomBrowser?style=plastic)

![Star](https://img.shields.io/github/stars/ericspod/DicomBrowser?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** : 

[https://ericspod.github.io/Eidolon/](https://ericspod.github.io/Eidolon/)

**Package** : 
pydicom

## [simply-dicom](https://github.com/cpboyd/simply-dicom)

simplyDICOM for Android

![GitHub license](https://img.shields.io/github/license/cpboyd/simply-dicom.svg)

![Total line](https://img.shields.io/tokei/lines/github/cpboyd/simply-dicom)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cpboyd/simply-dicom?style=plastic)

![Star](https://img.shields.io/github/stars/cpboyd/simply-dicom?style=social)

![](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white), ![](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)

**Links** : 

**Package** : 
pydicom

## [embedded-pydicom-react-viewer](https://github.com/grimmer0125/embedded-pydicom-react-viewer)

Medical DICOM file P10 Viewer + Python Code In Browser (-Pyodide-\&gt; WebAssembly) + Pydicom parser + TypeScript React App (CRA) + Python FastAPI Server Deployment + Mac M1 Docker support

![GitHub license](https://img.shields.io/github/license/grimmer0125/embedded-pydicom-react-viewer.svg)

![Total line](https://img.shields.io/tokei/lines/github/grimmer0125/embedded-pydicom-react-viewer)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/grimmer0125/embedded-pydicom-react-viewer?style=plastic)

![Star](https://img.shields.io/github/stars/grimmer0125/embedded-pydicom-react-viewer?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white), ![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

**Package** : 

Be checked

## [GDP](https://github.com/hh-mk/GDP)

DICOM VIEWER FOR iOS

![GitHub license](https://img.shields.io/github/license/hh-mk/GDP.svg)

![Total line](https://img.shields.io/tokei/lines/github/hh-mk/GDP)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/hh-mk/GDP?style=plastic)

![Star](https://img.shields.io/github/stars/hh-mk/GDP?style=social)

![](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [DicomVis](https://github.com/MKozuch/DicomVis)

Simple 4-pane viewer for visualising series of DICOM images. Written in Python using VTK. Requires VTK and PyQt4

![GitHub license](https://img.shields.io/github/license/MKozuch/DicomVis.svg)

![Total line](https://img.shields.io/tokei/lines/github/MKozuch/DicomVis)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/MKozuch/DicomVis?style=plastic)

![Star](https://img.shields.io/github/stars/MKozuch/DicomVis?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** : 

**Package** : 
vtk
, PyQt4
, DicomVis\_ui

## [DICOM\_viewer](https://github.com/UoA-eResearch/DICOM_viewer)

A Unity hololens viewer for DICOM images

![GitHub license](https://img.shields.io/github/license/UoA-eResearch/DICOM_viewer.svg)

![Total line](https://img.shields.io/tokei/lines/github/UoA-eResearch/DICOM_viewer)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/UoA-eResearch/DICOM_viewer?style=plastic)

![Star](https://img.shields.io/github/stars/UoA-eResearch/DICOM_viewer?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [cornerstone](https://github.com/cornerstonejs/cornerstone)

Cornerstone.js delivers a complete web based medical imaging platform. This repository contains the Cornerstone.js &quot;Core&quot; component which is a lightweight JavaScript library for displaying medical images in modern web browsers that support the HTML5 canvas element.

![GitHub license](https://img.shields.io/github/license/cornerstonejs/cornerstone.svg)

![Total line](https://img.shields.io/tokei/lines/github/cornerstonejs/cornerstone)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cornerstonejs/cornerstone?style=plastic)

![Star](https://img.shields.io/github/stars/cornerstonejs/cornerstone?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://docs.cornerstonejs.org/](https://docs.cornerstonejs.org/)

**Package** : 

Be checked

# DICOM Parser

## [pynetdicom](https://github.com/pydicom/pynetdicom)

A Python implementation of the [DICOM](http://dicom.nema.org/) networking protocol, originally based on (legacy) [pynetdicom](https://github.com/patmun/pynetdicom_legacy).

![GitHub license](https://img.shields.io/github/license/pydicom/pynetdicom.svg)

![Total line](https://img.shields.io/tokei/lines/github/pydicom/pynetdicom)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pydicom/pynetdicom?style=plastic)

![Star](https://img.shields.io/github/stars/pydicom/pynetdicom?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [Daikon](https://github.com/rii-mango/Daikon)

Daikon is a pure JavaScript DICOM reader.

![GitHub license](https://img.shields.io/github/license/pydicom/pynetdicom.svg)

![Total line](https://img.shields.io/tokei/lines/github/pydicom/pynetdicom)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pydicom/pynetdicom?style=plastic)

![Star](https://img.shields.io/github/stars/pydicom/pynetdicom?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

**Package** : 

Be checked

## [Evil-DICOM](https://github.com/rexcardan/Evil-DICOM)

A simple to use C# library for reading and manipulating DICOM files.

![GitHub license](https://img.shields.io/github/license/rexcardan/Evil-DICOM.svg)

![Total line](https://img.shields.io/tokei/lines/github/rexcardan/Evil-DICOM)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rexcardan/Evil-DICOM?style=plastic)

![Star](https://img.shields.io/github/stars/rexcardan/Evil-DICOM?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** : 

**Package** : 

Be checked


## [dicomutils](https://github.com/raysearchlabs/dicomutils)

A set of utilities for working with DICOM files. The main utility is currently build\_dicom, which can generate simple synthetic CT data, MR data, PET data, RT Structure sets, RT Doses and RT Plans.

![GitHub license](https://img.shields.io/github/license/raysearchlabs/dicomutils.svg)

![Total line](https://img.shields.io/tokei/lines/github/raysearchlabs/dicomutils)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/raysearchlabs/dicomutils?style=plastic)

![Star](https://img.shields.io/github/stars/raysearchlabs/dicomutils?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [dicom\_parser](https://github.com/open-dicom/dicom_parser)

_dicom\_parser_ is a utility python package meant to facilitate access to [DICOM](https://www.dicomstandard.org/) header information by extending the functionality of [_pydicom_](https://pydicom.github.io/).

![GitHub license](https://img.shields.io/github/license/open-dicom/dicom_parser.svg)

![Total line](https://img.shields.io/tokei/lines/github/open-dicom/dicom_parser)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/open-dicom/dicom_parser?style=plastic)

![Star](https://img.shields.io/github/stars/open-dicom/dicom_parser?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [pydicom](https://github.com/pydicom/pydicom)

_pydicom_ is a pure Python package for working with [DICOM](https://www.dicomstandard.org/) files. It lets you read, modify and write DICOM data in an easy &quot;pythonic&quot; way.

As a pure Python package, _pydicom_ can run anywhere Python runs without any other requirements, although if you&#39;re working with _Pixel Data_ then we recommend you also install [NumPy](http://www.numpy.org/).

If you&#39;re looking for a Python library for DICOM networking then you might be interested in another of our projects: [pynetdicom](https://github.com/pydicom/pynetdicom).

![GitHub license](https://img.shields.io/github/license/pydicom/pydicom.svg)

![Total line](https://img.shields.io/tokei/lines/github/pydicom/pydicom)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pydicom/pydicom?style=plastic)

![Star](https://img.shields.io/github/stars/pydicom/pydicom?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** : 

[https://pydicom.github.io/pydicom/dev/](https://pydicom.github.io/pydicom/dev/)

## [fo-dicom](https://github.com/fo-dicom/fo-dicom)

Fellow Oak DICOM for .NET, .NET Core, Universal Windows, Android, iOS, Mono and Unity

![GitHub license](https://img.shields.io/github/license/fo-dicom/fo-dicom.svg)

![Total line](https://img.shields.io/tokei/lines/github/fo-dicom/fo-dicom)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/fo-dicom/fo-dicom?style=plastic)

![Star](https://img.shields.io/github/stars/fo-dicom/fo-dicom?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white), ![](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [fo-dicom-samples](https://github.com/fo-dicom/fo-dicom-samples)

**Sample applications associated with the** [**fo-dicom**](https://github.com/fo-dicom/fo-dicom) **framework, version 4.0.5**

![GitHub license](https://img.shields.io/github/license/fo-dicom/fo-dicom-samples.svg)

![Total line](https://img.shields.io/tokei/lines/github/fo-dicom/fo-dicom-samples)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/fo-dicom/fo-dicom-samples?style=plastic)

![Star](https://img.shields.io/github/stars/fo-dicom/fo-dicom-samples?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** : 

**Package** : 

Be checked

# DICOM Server

## [cornerstoneWADOImageLoader](https://github.com/cornerstonejs/cornerstoneWADOImageLoader)

cornerstone WADO Image Loader

A [cornerstone](https://github.com/cornerstonejs/cornerstone) Image Loader for DICOM P10 instances over HTTP (WADO-URI) or DICOMWeb (WADO-RS). This can be used to integrate cornerstone with WADO-URI servers, DICOMWeb servers or any other HTTP based server that returns DICOM P10 instances (e.g. [Orthanc](http://www.orthanc-server.com/) or custom servers)

![GitHub license](https://img.shields.io/github/license/cornerstonejs/cornerstoneWADOImageLoader.svg)

![Total line](https://img.shields.io/tokei/lines/github/cornerstonejs/cornerstoneWADOImageLoader)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cornerstonejs/cornerstoneWADOImageLoader?style=plastic)

![Star](https://img.shields.io/github/stars/cornerstonejs/cornerstoneWADOImageLoader?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

**Package** : 

Be checked

## [dicom-server](https://github.com/microsoft/dicom-server) *

The Medical Imaging Server for DICOM is an open source DICOM server that is easily deployed on Azure. It allows standards-based communication with any DICOMweb™ enabled systems, and injects DICOM metadata into a FHIR server to create a holistic view of patient data. The Medical Imaging Server for DICOM integrates tightly with the [FHIR Server for Azure](https://github.com/microsoft/fhir-server) enabling healthcare professionals, ISVs, and medical device vendors to create new and innovative solutions. FHIR is becoming an important standard for clinical data and provides extensibility to support integration of other types of data directly, or through references. By using the Medical Imaging Server for DICOM, organizations can store references to imaging data in FHIR and enable queries across clinical and imaging datasets.

![GitHub license](https://img.shields.io/github/license/microsoft/dicom-server.svg)

![Total line](https://img.shields.io/tokei/lines/github/microsoft/dicom-server)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/microsoft/dicom-server?style=plastic)

![Star](https://img.shields.io/github/stars/microsoft/dicom-server?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [DICOMcloud](https://github.com/DICOMcloud/DICOMcloud) *

The DICOMcloud is a standalone DICOMweb server with RESTful implementation of the DICOMweb/WADO services:

- **QIDO-RS:** Look up studies, series, images. Results will be limited to a maximum results. [more info](https://dicomcloud.github.io/docs/dicomcloud/pagination/)
- **WADO-RS:** Retrieve studies, series, images, frames and metadata
- **STOW-RS:** Store DICOM instances/images
- **WADO-URI:** Web Access to DICOM objects

![GitHub license](https://img.shields.io/github/license/DICOMcloud/DICOMcloud.svg)

![Total line](https://img.shields.io/tokei/lines/github/DICOMcloud/DICOMcloud)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/DICOMcloud/DICOMcloud?style=plastic)

![Star](https://img.shields.io/github/stars/DICOMcloud/DICOMcloud?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [dicomweb-server](https://github.com/dcmjs-org/dicomweb-server)

Lightweight DICOMweb Server with CouchDB

![GitHub license](https://img.shields.io/github/license/dcmjs-org/dicomweb-server.svg)

![Total line](https://img.shields.io/tokei/lines/github/dcmjs-org/dicomweb-server)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dcmjs-org/dicomweb-server?style=plastic)

![Star](https://img.shields.io/github/stars/dcmjs-org/dicomweb-server?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** : 

[https://projectweek.na-mic.org/PW30\_2019\_GranCanaria/Projects/DICOMweb-CouchDB/](https://projectweek.na-mic.org/PW30_2019_GranCanaria/Projects/DICOMweb-CouchDB/)

**Package** : 

Be checked

## [Conquest-DICOM-Server](https://github.com/marcelvanherk/Conquest-DICOM-Server)

This is the new **conquest DICOM server** source code repository, it is the first ever release of the full source code of Conquest Dicom server with full source code, including the windows GUI.

![GitHub license](https://img.shields.io/github/license/marcelvanherk/Conquest-DICOM-Server.svg)

![Total line](https://img.shields.io/tokei/lines/github/marcelvanherk/Conquest-DICOM-Server)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/marcelvanherk/Conquest-DICOM-Server?style=plastic)

![Star](https://img.shields.io/github/stars/marcelvanherk/Conquest-DICOM-Server?style=social)

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
, ![](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Links** : 

[https://ingenium.home.xs4all.nl/dicom.html](https://ingenium.home.xs4all.nl/dicom.html)

**Package** : 

Be checked

## [clara-dicom-adapter](https://github.com/NVIDIA/clara-dicom-adapter)

Clara DICOM Adapter

Designed for the Clara Deploy SDK, the Clara DICOM Adapter implements the necessary DICOM services for interoperability between Clara and other medical devices. The Clara DICOM Adapter allows you to send/receive DICOM objects using standard DICOM protocols and interpret standard DICOM part-10 formats.

![GitHub license](https://img.shields.io/github/license/NVIDIA/clara-dicom-adapter.svg)

![Total line](https://img.shields.io/tokei/lines/github/NVIDIA/clara-dicom-adapter)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/NVIDIA/clara-dicom-adapter?style=plastic)

![Star](https://img.shields.io/github/stars/NVIDIA/clara-dicom-adapter?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** : 

**Package** : 

Be checked

## [hermes](https://github.com/hermes-router/hermes) **\***

**Hermes DICOM Router**

**Important:** The project has been renamed to mercure and is currently undergoing significant development work towards version 0.2. Make sure to checkout only the branch _stable-v0.1_ for a working version. All ongoing development work has been moved to [https://github.com/mercure-imaging/mercure](https://github.com/mercure-imaging/mercure)

![GitHub license](https://img.shields.io/github/license/hermes-router/hermes.svg)

![Total line](https://img.shields.io/tokei/lines/github/hermes-router/hermes)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/hermes-router/hermes?style=plastic)

![Star](https://img.shields.io/github/stars/hermes-router/hermes?style=social)

…

**Links** : 

[https://hermes-router.github.io/](https://hermes-router.github.io/)

**Package** : 

Be checked

## [Orthanc](https://github.com/jodogne/Orthanc)

[Orthanc](https://www.orthanc-server.com/) is a lightweight DICOM server for medical imaging.

Here is the [new location of the official source code](https://hg.orthanc-server.com/).

![Star](https://img.shields.io/github/stars/jodogne/Orthanc?style=social)

…

**Links** :

[https://www.orthanc-server.com/](https://www.orthanc-server.com/)

**Package** : 

Be checked

## [dcm4chee-arc-cdi](https://github.com/dcm4che/dcm4chee-arc-cdi)

Full-featured DICOM Archive based on Java Enterprise

![GitHub license](https://img.shields.io/github/license/dcm4che/dcm4chee-arc-cdi.svg)

![Total line](https://img.shields.io/tokei/lines/github/dcm4che/dcm4chee-arc-cdi)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dcm4che/dcm4chee-arc-cdi?style=plastic)

![Star](https://img.shields.io/github/stars/dcm4che/dcm4chee-arc-cdi?style=social)

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)

**Links** :

**Package** : 

Be checked

[https://github.com/dcm4che/dcm4chee-arc-cdi](https://github.com/dcm4che/dcm4chee-arc-cdi)

# DICOM Convertor

## [mritopng](https://github.com/danishm/mritopng)

A simple python module to make it easy to batch convert a binary DICOM file, which is usually an output from an MRI scan to a PNG image.

![GitHub license](https://img.shields.io/github/license/danishm/mritopng.svg)

![Total line](https://img.shields.io/tokei/lines/github/danishm/mritopng)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/danishm/mritopng?style=plastic)

![Star](https://img.shields.io/github/stars/danishm/mritopng?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 

Be checked

## [dicom2stl](https://github.com/dave3d/dicom2stl)

dicom2stl.py is a script that takes a [Dicom](https://www.dicomstandard.org/about/) series and generates a STL surface mesh.

![GitHub license](https://img.shields.io/github/license/dave3d/dicom2stl.svg)

![Total line](https://img.shields.io/tokei/lines/github/dave3d/dicom2stl)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dave3d/dicom2stl?style=plastic)

![Star](https://img.shields.io/github/stars/dave3d/dicom2stl?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 

Be checked

## [dicom-ecg-plot](https://github.com/marcodebe/dicom-ecg-plot)

A python tool to plot Dicom ECG. The DICOM file can also be specified as studyUID seriesUID objectUID and retrieved from your WADO server.

![GitHub license](https://img.shields.io/github/license/marcodebe/dicom-ecg-plot.svg)

![Total line](https://img.shields.io/tokei/lines/github/marcodebe/dicom-ecg-plot)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/marcodebe/dicom-ecg-plot?style=plastic)

![Star](https://img.shields.io/github/stars/marcodebe/dicom-ecg-plot?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

[https://ecg.galliera.it/](https://ecg.galliera.it/)

**Package** : 
pydicom

## [dcmstack](https://github.com/moloney/dcmstack)

This package provides DICOM to Nifti conversion with the added ability to extract and summarize meta data from the source DICOMs. The meta data can be injected it into a Nifti header extension or written out as a JSON formatted text file.

![GitHub license](https://img.shields.io/github/license/moloney/dcmstack.svg)

![Total line](https://img.shields.io/tokei/lines/github/moloney/dcmstack)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/moloney/dcmstack?style=plastic)

![Star](https://img.shields.io/github/stars/moloney/dcmstack?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 
pydicom 
, nibabel 

## [Dicom\_RT\_and\_Images\_to\_Mask](https://github.com/brianmanderson/Dicom_RT_and_Images_to_Mask)

This code provides functionality for turning dicom images and RT structures into nifti files as well as turning prediction masks back into RT structures.

![GitHub license](https://img.shields.io/github/license/brianmanderson/Dicom_RT_and_Images_to_Mask.svg)

![Total line](https://img.shields.io/tokei/lines/github/brianmanderson/Dicom_RT_and_Images_to_Mask)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/brianmanderson/Dicom_RT_and_Images_to_Mask?style=plastic)

![Star](https://img.shields.io/github/stars/brianmanderson/Dicom_RT_and_Images_to_Mask?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 
pydicom 

## [dicomweb-proxy](https://github.com/knopkem/dicomweb-proxy)

A proxy to translate between dicomweb and traditional dicom dimse services

![GitHub license](https://img.shields.io/github/license/knopkem/dicomweb-proxy.svg)

![Total line](https://img.shields.io/tokei/lines/github/knopkem/dicomweb-proxy)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/knopkem/dicomweb-proxy?style=plastic)

![Star](https://img.shields.io/github/stars/knopkem/dicomweb-proxy?style=social)

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Links** :

**Package** : 

## [DICOM-to-JPG](https://github.com/vivek8981/DICOM-to-JPG)

Convert all DICOM (.dcm) images in a folder to JPG/PNG and extract all patients information in a &#39;.csv&#39; format in a go using python.

![GitHub license](https://img.shields.io/github/license/vivek8981/DICOM-to-JPG.svg)

![Total line](https://img.shields.io/tokei/lines/github/vivek8981/DICOM-to-JPG)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/vivek8981/DICOM-to-JPG?style=plastic)

![Star](https://img.shields.io/github/stars/vivek8981/DICOM-to-JPG?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 

## [wsi-to-dicom-converter](https://github.com/GoogleCloudPlatform/wsi-to-dicom-converter)

This repository contains a tool that converts whole slide images (WSIs) to DICOM. To read the underlying whole slide images (WSIs), this tool relies on [OpenSlide](https://openslide.org/), which supports a variety of file formats.

![GitHub license](https://img.shields.io/github/license/GoogleCloudPlatform/wsi-to-dicom-converter.svg)

![Total line](https://img.shields.io/tokei/lines/github/GoogleCloudPlatform/wsi-to-dicom-converter)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/GoogleCloudPlatform/wsi-to-dicom-converter?style=plastic)

![Star](https://img.shields.io/github/stars/GoogleCloudPlatform/wsi-to-dicom-converter?style=social)

...

**Links** :

**Package** : 

## [dicomifier](https://github.com/lamyj/dicomifier)

Dicomifier is a set of tools to convert Bruker data to DICOM files, and DICOM files to NIfTI. It retains meta-data (e.g. MR parameters such as echo time or subject parameters such as weight or height) throughout the conversion process, and aligns the meta-data from Bruker on the DICOM dictionary for unified processing pipelines.

![GitHub license](https://img.shields.io/github/license/lamyj/dicomifier.svg)

![Total line](https://img.shields.io/tokei/lines/github/lamyj/dicomifier)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/lamyj/dicomifier?style=plastic)

![Star](https://img.shields.io/github/stars/lamyj/dicomifier?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 

## [imageformats](https://github.com/dbrant/imageformats)

Library for decoding obscure graphics formats, such as Targa (.TGA), Sun raster (.RAS, .SUN), ZSoft (.PCX), Netpbm (.PPM, .PGM, .PBM, .PNM), Amiga (LBM, PIC), SGI, MacPaint, and DICOM.

![GitHub license](https://img.shields.io/github/license/dbrant/imageformats.svg)

![Total line](https://img.shields.io/tokei/lines/github/dbrant/imageformats)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dbrant/imageformats?style=plastic)

![Star](https://img.shields.io/github/stars/dbrant/imageformats?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** :

**Package** : 

## [pylibjpeg](https://github.com/pydicom/pylibjpeg)

A Python 3.6+ framework for decoding JPEG images and decoding/encoding RLE datasets, with a focus on providing support for [pydicom](https://github.com/pydicom/pydicom).

![GitHub license](https://img.shields.io/github/license/pydicom/pylibjpeg.svg)

![Total line](https://img.shields.io/tokei/lines/github/pydicom/pylibjpeg)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pydicom/pylibjpeg?style=plastic)

![Star](https://img.shields.io/github/stars/pydicom/pylibjpeg?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 
pydicom

# DICOM Miscellaneous

## [DVTk](https://github.com/dvtk-org/DVTk)

DICOM Validation Toolkit

This GitHub project contains the complete and latest source code of the DVTk (DICOM Validation Toolkit) Open Source project. The Windows installers and forum are located on [https://www.dvtk.org/](https://www.dvtk.org/).

![GitHub license](https://img.shields.io/github/license/dvtk-org/DVTk.svg)

![Total line](https://img.shields.io/tokei/lines/github/dvtk-org/DVTk)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dvtk-org/DVTk?style=plastic)

![Star](https://img.shields.io/github/stars/dvtk-org/DVTk?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white), ![](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Links** :

**Package** : 

## [ECGToolkit](https://github.com/Refactoring/ECGToolkit)

C# ECG Toolkit 2.5

C# ECG Toolkit is an open source software toolkit to convert, view and print electrocardiograms. The toolkit is developed using C# .NET 2.0 (code also supports 1.1, 3.5 and 4.0). Support for ECG formats: SCP-ECG, DICOM, HL7 aECG, ISHNE and MUSE-XML.

![GitHub license](https://img.shields.io/github/license/Refactoring/ECGToolkit.svg)

![Total line](https://img.shields.io/tokei/lines/github/Refactoring/ECGToolkit)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Refactoring/ECGToolkit?style=plastic)

![Star](https://img.shields.io/github/stars/Refactoring/ECGToolkit?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Links** :

**Package** : 

## [DVH-Analytics](https://github.com/cutright/DVH-Analytics)

DVH Analytics (DVHA) is a software application for building a local database of radiation oncology treatment planning data. It imports data from DICOM-RT files (_i.e._, plan, dose, and structure), creates a SQL database, provides customizable plots, and provides tools for generating linear, multi-variable, and machine learning regressions.

![GitHub license](https://img.shields.io/github/license/cutright/DVH-Analytics.svg)

![Total line](https://img.shields.io/tokei/lines/github/cutright/DVH-Analytics)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cutright/DVH-Analytics?style=plastic)

![Star](https://img.shields.io/github/stars/cutright/DVH-Analytics?style=social)

![](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 

## [DICOM-CNN](https://github.com/ben-heil/DICOM-CNN)

Scripts useful for doing deep learning on DICOM images. Used to differentiate between images with and without lung nodules for my semester project in machine learning.

![GitHub license](https://img.shields.io/github/license/ben-heil/DICOM-CNN.svg)

![Total line](https://img.shields.io/tokei/lines/github/ben-heil/DICOM-CNN)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ben-heil/DICOM-CNN?style=plastic)

![Star](https://img.shields.io/github/stars/ben-heil/DICOM-CNN?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

**Package** : 

## [dicomWeb](https://github.com/chafey/dicomWeb)

Information about DICOMWeb - API&#39;s, implementations, etc. Pull requests are welcome!!

![GitHub license](https://img.shields.io/github/license/chafey/dicomWeb.svg)

![Total line](https://img.shields.io/tokei/lines/github/chafey/dicomWeb)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/chafey/dicomWeb?style=plastic)

![Star](https://img.shields.io/github/stars/chafey/dicomWeb?style=social)

**Links** :

**Package** : 

## [Niffler](https://github.com/Emory-HITI/Niffler)

Niffler is an efficient DICOM Framework for machine learning pipelines and processing workflows on metadata. It facilitates efficient transfer of DICOM images on-demand and real-time from PACS to the research environments, to run processing workflows and machine learning pipelines.

![GitHub license](https://img.shields.io/github/license/Emory-HITI/Niffler.svg)

![Total line](https://img.shields.io/tokei/lines/github/Emory-HITI/Niffler)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Emory-HITI/Niffler?style=plastic)

![Star](https://img.shields.io/github/stars/Emory-HITI/Niffler?style=social)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Links** :

[https://emory-hiti.github.io/Niffler/](https://emory-hiti.github.io/Niffler/)

**Package** : 

## [OnkoDICOM](https://github.com/didymo/OnkoDICOM)

OnkoDICOM is an Open Source DICOM-RT viewer with enhanced capabilities that make it useful for research in the field of Radiation Oncology. It was created with Radiation Oncologists to allow Radiation Oncologists to do research on DICOM standard image, but Radiation Therapists and Radiation Physicists will find tools included that are useful when manipulating image sets like DICOM-RT, CT, MRI, and PET.

Star : 24

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

[https://github.com/didymo/OnkoDICOM](https://github.com/didymo/OnkoDICOM)

[https://onkodicom.com.au/](https://onkodicom.com.au/)

## [dovo](https://github.com/DraconPern/dovo)

Point of care, cross-platform software for importing DICOM CD and files then sending it to PACS. Usage scenario is front desk staff getting handed a CD with patient&#39;s images. This tool allows the front desk to preview the images, and send to PACS. Tested on Windows and OS X.

Star : 24

![](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Links** :

[https://www.draconpern.com/software/dovo/](https://www.draconpern.com/software/dovo/)

**Package** : 

## [healthcare-api-dicomweb-cli](https://github.com/GoogleCloudPlatform/healthcare-api-dicomweb-cli)

DICOMweb command line tool is a command line utility for interacting with DICOMweb servers.

Star : 22

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

[https://github.com/GoogleCloudPlatform/healthcare-api-dicomweb-cli](https://github.com/GoogleCloudPlatform/healthcare-api-dicomweb-cli)

## [dcmgw](https://github.com/jap1968/dcmgw)

Dicom gateway. The script acts like a web service allowing to perform c-find queries to a Dicom Query / Retrieve SCP. dcmgw relies upon dcmqr, from the [dcm4che2 toolkit](http://www.dcm4che.org/confluence/display/d2/dcm4che2+DICOM+Toolkit).

Star : 22

PHP

[https://github.com/jap1968/dcmgw](https://github.com/jap1968/dcmgw)

## [virtual-dicom-printer](https://github.com/Softus/virtual-dicom-printer)

Virtual printer for DICOM. Works as a proxy and spooler for a real printer(s). Also, all prints may be archived in a DICOM storage server.

Star : 22

![](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

[https://github.com/Softus/virtual-dicom-printer](https://github.com/Softus/virtual-dicom-printer)

## [dicom-character-set](https://github.com/radialogica/dicom-character-set)

Converts bytes of encoded DICOM text to Javascript DOMString

Converts DICOM text (as bytes) to a JavaScript string. Handles multiple character sets (single-byte and multi-byte, with and without extensions) within a single block of text according to the DICOM standard. All encodings specified in the standard are currently supported. For a complete list of all encodings, see [here](http://dicom.nema.org/medical/dicom/current/output/chtml/part03/sect_C.12.html#sect_C.12.1.1.2).

Star : 22

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[https://github.com/radialogica/dicom-character-set](https://github.com/radialogica/dicom-character-set)

## [DICOMToFHIRImagingStudy](https://github.com/chafey/DICOMToFHIRImagingStudy)

HTML5 App to create a [FHIR Imaging Study](http://www.hl7.org/implement/standards/fhir/imagingstudy.html) resource from a DICOMweb Study (via WADO-RS Retrieve Metadata)

Star : 16

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[https://github.com/chafey/DICOMToFHIRImagingStudy](https://github.com/chafey/DICOMToFHIRImagingStudy)

[http://chafey.github.io/DICOMToFHIRImagingStudy/](http://chafey.github.io/DICOMToFHIRImagingStudy/)

## [Pinnacle-tar-DICOM](https://github.com/AndrewWAlexander/Pinnacle-tar-DICOM)

Converting Pinnacle tar files to DICOM files

Star : 16

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Package : pydicom

[https://github.com/AndrewWAlexander/Pinnacle-tar-DICOM](https://github.com/AndrewWAlexander/Pinnacle-tar-DICOM)

## [dicom-data-dictionary](https://github.com/OHIF/dicom-data-dictionary)

DICOM Data Dictionary JavaScript Library

The purpose of this library is to provide DICOM data dictionary functionality. Currently it just provides a set of standard tags from an unknown version of the DICOM standard. See backlog for some ideas of things to add in the future - pull requests are welcome!

Star : 13

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[https://github.com/OHIF/dicom-data-dictionary](https://github.com/OHIF/dicom-data-dictionary)

## [cornerstoneTools](https://github.com/cornerstonejs/cornerstoneTools)

Provides a simple, extensible framework for creating tools on top of [Cornerstone.js](https://github.com/cornerstonejs/cornerstone/). Includes common tool implementations, and leverages DICOM metadata (when available) for advanced functionality.

Star : 442

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[https://github.com/cornerstonejs/cornerstoneTools](https://github.com/cornerstonejs/cornerstoneTools)

[https://tools.cornerstonejs.org/examples/](https://tools.cornerstonejs.org/examples/)

## [medpy](https://github.com/loli/medpy)

MedPy is an image processing library and collection of scripts targeted towards medical (i.e. high dimensional) image processing.

Star : 359

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white), ![](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

[https://github.com/loli/medpy](https://github.com/loli/medpy)

[http://loli.github.io/medpy/](http://loli.github.io/medpy/)

# Image Processing

# PACS

## Dicoogle

Dicoogle is an extensible, platform-independent and open-source PACS archive software that replaces the traditional centralized database with a more agile indexing and retrieval mechanism. It was designed to support automatic extraction, indexing and storage of all meta-data detected in medical images, including private DICOM attribute tags, without re-engineering or reconfiguration requirements.

Star : 264

Java

[https://github.com/bioinformatics-ua/dicoogle](https://github.com/bioinformatics-ua/dicoogle)

[https://www.dicoogle.com/](https://www.dicoogle.com/)

[https://demo.dicoogle.com/#/search](https://demo.dicoogle.com/#/search)

## [EasyPACS](https://github.com/mehmetsen80/EasyPACS) **\***

EasyPACS is the simpliest PACS server for your dicom files. It uses DCM4CHEE listener and converts dicom files into jpegs. It is the easiest way to store dicom files.

Star : 104

Java, ![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[https://github.com/mehmetsen80/EasyPACS](https://github.com/mehmetsen80/EasyPACS)

[http://mehmetsen80.github.io/EasyPACS/](http://mehmetsen80.github.io/EasyPACS/) (Database info)

## [neurdicom](https://github.com/reactmed/neurdicom) **\***

NeurDICOM

NeurDICOM is portable and easy-to-deploy RESTful DICOM and PACS server that allows physicians to use state-of-the-art methods of machine learning and neural networks to make a diagnosis based on medical images processing and interpetating.

Star : 84

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

[https://github.com/reactmed/neurdicom](https://github.com/reactmed/neurdicom)

## [RadiologyInformationSystem](https://github.com/AlecCromer/RadiologyInformationSystem)

Radiology information System, holds radiology specific text data. This system is use to Select a patient from the worklist that is automatically updated which appears on the modality monitor. Patient tracking and fetching previous patient images from PACS. RIS is also used for Creating radiologist reports, transcriptions, communicating with PACS to find images and film archiving. Each component talks to one another through Digital imaging and communication in medicine (DICOM) and Health Level-7 (HL7).

Star : 17

Java

[https://github.com/AlecCromer/RadiologyInformationSystem](https://github.com/AlecCromer/RadiologyInformationSystem)

## [dicomweb-pacs](https://github.com/knopkem/dicomweb-pacs)

Easy to use DICOMWEB enabled PACS with DIMSE services based on sqlite database

Star : 17

![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Package : dicom-data-dictionary, dicom-dimse-native, dicom-parser

[https://github.com/knopkem/dicomweb-pacs](https://github.com/knopkem/dicomweb-pacs)


# Keyword

DICOM _Service Class Users_ (SCUs) and _Service Class Providers_ (SCPs).

DIMSE service

(Patient-\&gt;Study-\&gt;Series-\&gt;Image) into a directory tree in the file system.

qido-rs, wado-rs, stow-rs, wado-uri

- Open Health Imaging Foundation ([OHIF](http://ohif.org/))
- Quantitative Image Informatics for Cancer Research ([QIICR](http://qiicr.org/))
- [Radiomics](http://radiomics.io/)
- The [Neuroimage Analysis Center](http://nac.spl.harvard.edu/)
- The [National Center for Image Guided Therapy](http://ncigt.org/)
- The [MGH &amp; BWH Center for Clinical Data Science](https://www.ccds.io/)

[https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI)

Nifti format

Stored in IndexedDB, the client-side database of web browser.

UDV uses:

- [Cornerstone Core](https://github.com/cornerstonejs/cornerstone), complete web based medical imaging platform.
- [CornerstoneTools](https://github.com/cornerstonejs/cornerstoneTools), library of common tools that can be used with Cornerstone.
- [webnamics/CornerstoneWADOImageLoader](https://github.com/webnamics/cornerstoneWADOImageLoader), Cornerstone Image Loader that works with WADO-URI, WADO-RS and DICOM P10 files. A fork that allow to load image from ArrayBuffer.
- [CornerstoneWebImageLoader](https://github.com/cornerstonejs/cornerstoneWebImageLoader), Cornerstone Image Loader that works with PNG and JPEG files.
- [CornerstoneFileImageLoader](https://github.com/webnamics/cornerstoneFileImageLoader), Cornerstone Image Loader for images (JPG, PNG) using the HTML5 File API.
- [dicomParser](https://github.com/cornerstonejs/dicomParser), JavaScript library designed to parse DICOM for web browsers.
- [Daikon](https://github.com/rii-mango/Daikon), pure JavaScript DICOM reader.

As well as the following third-party libraries:

- [Dexie.js](https://github.com/dfahlander/Dexie.js/), wrapper library for indexedDB - the standard database in the browser.
- [react-device-detect](https://github.com/duskload/react-device-detect), detect device, and render view according to detected device type.
- [Material-UI](https://material-ui.com/), React components for faster and easier web development. Build your own design system, or start with Material Design.
- [hammer.js](https://github.com/hammerjs/hammer.js/tree/master), JavaScript library for detecting touch gestures.
- [axios](https://github.com/axios/axios), Promise based HTTP client for the browser and node.js.
- [JSZip](https://github.com/Stuk/jszip), Create, read and edit .zip files with Javascript.
- [React-Perfect-Scrollbar](https://github.com/goldenyz/react-perfect-scrollbar), Wrapper to allow use perfect-scrollbar in React.

[https://www.dicomstandard.org/dicomweb](https://www.dicomstandard.org/dicomweb)

[https://github.com/cylab-tw/raccoon](https://github.com/cylab-tw/raccoon)

[https://github.com/rordenlab/MRIcroGL](https://github.com/rordenlab/MRIcroGL)

[https://github.com/dvisionlab/Larvitar](https://github.com/dvisionlab/Larvitar)


