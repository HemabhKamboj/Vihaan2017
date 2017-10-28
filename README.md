# SIGN2SPEECH

Team Name : F.Society

Theme : Fighting Disabilities

## Description:
A *flex* sensor powered glove to convert sign language into audio format. The glove will be connected to any mobile device through which the gesture are converted into text and hence that will be converted into audio using text to speech API. This is a gadget that gives voice to the mute people.

Almost every human nowadays owns a mobile phone. Hence we can trasmit our glove's data to their phones to convert the data into human understandable signals.

## Problem Statement:
360 million people are deaf, 240 million people are mute and among all these people only a 70 million people know sign language. Even if these 70 million people know sign language they can't convey their message properly as most of the normal people can not understand sign language. So to overcome this barrier of communication our gadget is highly scalable.

## Concept and Tech Stack:
We are currently using Fritzing (Arduino and Circuit Stimulator) for the testing purposes and POC (Proof Of Concept). The same will give the mobile interface a response via bluetooth module and hence the signals will be converted into text and finally will be audible using a text to speech API.
For the mobile interface, we are building a simple application in ionic (hybrid mobile app framework) hence application production cost will also be less.
The app interface as a part of this hack, has a simple bluetooth data streaming and the conversion part.

<h6>Languages:</h6>
* C (for arduino programming)
* Javascript (TypeScript) for mobile interface
* Ionic framework (Angular framework) for mobile frontend

## Costing:
Flex sensors: 485 per piece -> each product will have 5 of these therefore, 2000 INR
HC05 Wireless bluetoothRF: 250 INR
PCB: 50 INR
Other electrical material: 150 INR

Total cost: 2450 INR (cost will actually go down when produced in large quantities)

## Progress:
We are finished with designing the ciruit board and getting result data on our virtual arduino device. Now, we'll be starting the bluetooth module working on our device and then the mobile app interface. So yet, most of the major work is finished.
