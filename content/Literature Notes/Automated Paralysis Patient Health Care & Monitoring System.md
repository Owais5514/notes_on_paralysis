---
paper_id: 691e9da0b925760d9c07743d
title: Automated Paralysis Patient Health Care & Monitoring System
authors: Hasin Eshrak, Mohammad Rejwan Uddin, Asif Mahmood, Mahady Hasan
publication_date: 2023
abstract: The majority of paralysis sufferers have difficulty communicating as well as moving certain body parts. An automated paralysis patient healthcare system can be incredibly valuable to these individuals. It's a computerized healthcare system. By moving any part of their body that can move, a disabled person can utilize this technology to display a message on an LCD panel. This strategy is also useful when the patient is left alone, and no one is available to provide care. A GPRS modem (SIM) is used to send an SMS, allowing whoever is caring for the patient to monitor the patient's condition from a distance. The system functions by understanding the user's tilt direction and monitoring real-time vitals. The device is used to demonstrate how it works by holding the thing in the fingers of the moving hand. The user only needs to tilt the device at a specific angle to send a message. This approach was designed to safeguard the safety and health of paralysis patients by giving immediate assistance.
comments:
pdf: "[[Automated Paralysis Patient Health Care & Monitoring System.pdf]]"
url:
tags:
  - paralysis
  - monitoring
  - patient
---

> [!PDF|red] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=40,7,42,15&color=red|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> >  By moving any part of their body that can move, a disabled person can utilize this technology to display a message on an LCD panel
> 
> Having atleast one moving part of their body

> [!PDF|yellow] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=43,54,44,34&color=yellow|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> >  GPRS modem (SIM) is used to send an SMS

> [!PDF|yellow] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=46,10,47,42&color=yellow|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> > The system functions by understanding the user's tilt direction and monitoring real-time vitals.
> 
> Is the tilt related to head or other part of the body? Later it described their demo using finder of a moving hand.

> [!PDF|yellow] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=79,0,82,14&color=yellow|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> > combining hand motion control

> [!PDF|yellow] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=82,42,84,1&color=yellow|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> > circuitry based on microcontrollers
> 
> 

## What are they measuring

- motion of a limb (using accelerometer)
- [[ECG]]
- [[BPM]]
- Temperature (has a temperature sensor)
- Fall Detection (fall detection sensor)

> [!PDF|red] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=134,57,140,54&color=red|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> > he patient can interact with the caregiver and request assistance if necessary, and the caregiver will receive a message in the event of an emergency. The ECG is the second figure from the left. The BPM of the patients will be measured. It will continuously provide reliable data, allowing the caregiver to have a detailed picture of the patient's current state

> [!PDF|red] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=183,36,184,29&color=red|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> > A message and a siren can also be broadcast as aler

> [!PDF|yellow] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=200,19,202,12&color=yellow|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> > pproach focuses on a glove that has an accelerometer built into it so that users may tilt their hands to send message

> [!PDF|yellow] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=1&selection=211,13,212,19&color=yellow|Automated Paralysis Patient Health Care & Monitoring System, p.1]]
> > consists of a transmitter module, a reception unit, and a compute
> 
> Their device is like a glove and those three units are necessary

## Modes of the System

- Monitoring
> [!PDF|important] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=2&selection=76,17,77,61&color=important|Automated Paralysis Patient Health Care & Monitoring System, p.2]]
> > ather information from the patient's sensors and continuously track their vital signs and mobility
> 

- Alert
> [!PDF|important] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=2&selection=83,15,84,13&color=important|Automated Paralysis Patient Health Care & Monitoring System, p.2]]
> >  detects critical changes in the patient's health status
> 

> [!PDF|important] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=4&selection=190,42,192,17&color=important|Automated Paralysis Patient Health Care & Monitoring System, p.4]]
> > ystem monitors the patient continuously, the caregiver can get a full health condition summary

## What sensors they used

> [!PDF|] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=4&selection=194,0,203,32|Automated Paralysis Patient Health Care & Monitoring System, p.4]]
> > Using a combination of the LM35 temperature sensor, ADXL335 accelerometer, flex sensor, AD8232 ECG module kit, SIM800L SIM module, Arduino Mega 2560, and an I2C LCD screen

> [!PDF|important] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=5&selection=23,21,24,35&color=important|Automated Paralysis Patient Health Care & Monitoring System, p.5]]
> >  integration of remote monitoring, the system aims to improve patient care

> [!PDF|note] [[Automated Paralysis Patient Health Care & Monitoring System.pdf#page=5&selection=25,0,26,26&color=note|Automated Paralysis Patient Health Care & Monitoring System, p.5]]
> > lacks a module that can be added to this project to act as an automated injection pusher
> 
> for insulin supply at predefined time

