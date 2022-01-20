# rfsignalsml_spectrumsensdisasters_jgc
RF Signals ML demo with SpectrumSens system for hackathon AWS Disaster Response.

## Summary

Communications in disaster situations are vital. Anticipating the disaster to prepare the population and being able to communicate when the disaster has already occurred is essential.

This machine learning algorithm aims to be able to anticipate the disaster, and also know the global status of all communications when the disaster has occurred.

The basis of its operation is through the analysis of the radioelectric spectrum and the detection of anomalies in it to detect (for example through signal disturbances) that a disaster may occur, or to detect that communications have been interrupted in certain areas, among other functions.

It can work without telephone coverage, analyzes all frequencies (also those used by emergencies, military, police,...) and can be designed to work without electricity in the event of a disaster.

It can be implemented at a very low cost, is very easy to use, and is highly scalable and replicable.

## Basic technical characteristics (DEMO)

Development of a spectrum analyser thought especially for potencial disaster area whose objective is to perform the permanent monitoring of the RF spectrum environment.

The device will carry out a constant modular monitoring (usually within a range that will be between 30 kHz and 30 GHz, range and bands which could be defined according to the geographical environment where the device is used).

The objective of the development of the base is to establish it on open systems such as the microcontrollers / microprocessors as ARDUINO or RASPBERRY to mention two examples.

Although there are different possible options (in the same way that there are different possibilities of subsequent connectivity to the display or warning platforms, as well as the networks: SIGFOX, LORA, etc.), in this case, it is specifically chosen Raspberry Pi, not only due to its low cost of development but also due to its capacity to work with a SDR system with an RTL-SDR receptor, and the ability to integrate the machine learning model.

The base system (in general applied to the whole “IoT environment” and “classic ISM”) allows to obtain an autonomous system which is capable of detecting malfunctions or disturbances in the communications frequency bands which are in the IEEE 802.11g/b/n/ac standard. In this case, due to the own restrictions of the used system, the frequency band that can be used will be those which are between 26 and 1766 MHz, but this base allows that you can work can by setting slight variations on any other band/s spectrum.

## Conclusions and credits

Exploratory analysis by Jordi Garcia Castillon with SageMaker Studio Lab and with GPL-3.0 license, for the AWS Disaster Response hackathon. Data obtained from Kaggle (user: jiahuali). Hosted on Github: https://github.com/gcjordi/rfsignalsml_spectrumsensdisasters_jgc

PITCH IN YOUTUBE: https://youtu.be/QnlGWT9OTFk

INDEX DOCUMENT IN MY WEB: https://spectrumsensawsdisasterresponse.jordigarcia.eu/
