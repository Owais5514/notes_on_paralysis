---
paper_id: 691e8c8db925760d9c07743c
title: Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors
authors: Aswin Sujith Varghese, Hudaif Abdul Hameed Neroth, Adarsh A, Poojashree Murali, Deepa Natesan
publication_date: 2025
abstract: This system is programmed to offer holistic care to paralysis patients through the integration of symptom monitoring, medical treatment support, and rehabilitation support utilizing IoT technology. The proposed system consists of networked devices like sensors, wearables, and a web application that communicate with each other and healthcare providers. The flex sensors monitor patient movements, the AD8232 ECG sensor monitors cardiac activity, the MPU6050 monitors falls, and a temperature sensor offers body temperature monitoring. Information is transmitted wirelessly via an ESP8266 Wi-Fi module to a Node-RED dashboard, enabling real-time visualization and instant notifications. The system offers rehabilitation exercises, medication and activity reminders, and health data collection for analytics. Smart algorithms allow healthcare providers to detect behavioral patterns, enabling customized interventions and treatment plans. This IoT-based system offers customized, realtime healthcare, enhancing treatment outcomes and quality of life for paralysis patients.
comments: Good paper, threshold based monitoring. no system for redundancy
pdf: "[[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf]]"
url: https://doi.org/10.1109/ICICV64824.2025.11085798
tags:
  - health
  - monotoring
  - paralysis
  - conference
---
> [!PDF|red] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=78,34,80,25&color=red|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > integration of symptom monitoring, medical treatment support, and rehabilitation support utilizing IoT technology.

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=81,20,81,61&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > sensors, wearables, and a web application

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=82,54,85,53&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > The flex sensors monitor patient movements, the AD8232 ECG sensor monitors cardiac activity, the MPU6050 monitors falls, and a temperature sensor offers body temperature monitoring

> [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=92,15,94,15&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > Smart algorithms allow healthcare providers to detect behavioral patterns, enabling customized interventions and treatment plans

## Problems the paper wants to tackle

> [!PDF|red] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=125,0,166,15&color=red|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > Manual supervision, irregular clinical assessments, and crude assistive technology like button remotes have been the main- stays of traditional paralysis patient care techniques. Although these button remotes give patients a certain amount of autonomy, they only alert caregivers without identifying the patient’s true needs and require adequate hand or finger mobility. As a result, communication gaps continue to exist, leading to unmet critical needs and delayed responses. Fur- thermore, routine vital sign checks are frequently restricted to planned hospital or home visits, which leaves a patient’s condition unmonitored for extended periods of time

> [!PDF|red] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=173,35,188,11&color=red|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > incapacity to express needs like hunger, thirst, discomfort, or emergencies

> [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=260,0,289,37&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > The system overcomes the binary limita- tions of button remotes by using flex sensors to interpret a variety of hand and finger movements, allowing patients to effectively communicate specific need

## Things they are measuring

- Fall Detection
- ECG
- temperature (hypothermia and fever)

> [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=1&selection=393,13,406,12&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.1]]
> > 24-hour surveillance, reducing manual inter- vention, and providing actionable insights through intelligent

![[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=2&rect=43,507,303,676&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.2]]

> [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=2&selection=54,0,54,32&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.2]]
> > S. P. Preejith et al. (2016) [1]
> 
> > [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=2&selection=63,12,73,8&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.2]]
> >  ultra-low power, wearable ECG system capable of monitoring beat- to-beat heart rate and respiratory trends continuously. The device operates for extended periods on a single charge and provides both raw ECG data storage and real-time abnormality detection through visualization modes, offering an effective solution for long-term cardiac health tracking

> [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=2&selection=75,0,75,27&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.2]]
> > S. Ananth et al. (2019) [2]
> 
> > [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=2&selection=81,11,107,21&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.2]]
> >  IoT-enabled health monitoring framework where wearable devices capture physi- ological parameters such as heart rate and temperature. These data are transmitted wirelessly to healthcare providers, allow- ing remote and real-time patient status update

> [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=2&selection=81,11,107,21&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.2]]
> >  IoT-enabled health monitoring framework where wearable devices capture physi- ological parameters such as heart rate and temperature. These data are transmitted wirelessly to healthcare providers, allow- ing remote and real-time patient status update

> [!PDF|red] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=3&selection=11,13,21,15&color=red|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.3]]
> > system aims to provide real-time health moni- toring and emergency alerting for paralyzed patients by inte- grating gesture-based communication, continuous vital sign monitoring, fall detection, and cloud-based data visualization. Using IoT-enabled wearable sensors and Arduino Mega, the system ensures seamless, non-invasive monitoring of patient health parameters and their immediate needs

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=3&selection=27,1,27,51&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.3]]
> > lex sensors to identify hand and finger movements,

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=3&selection=29,49,31,47&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.3]]
> > ECG signals and identifying early indicators of irregular heart rhythms, the AD8232 ECG sensor offers continuous cardiac monitoring

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=3&selection=34,4,43,48&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.3]]
> > LM35 temperature sensor aids in the diagnosis of illnesses like fever or hypothermia

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=3&selection=43,50,45,9&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.3]]
> > Reliable fall detection is made possible by the MPU6050 accelerometer and gyroscope

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=3&selection=45,55,48,47&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.3]]
> > An Arduino Mega microcontroller serves as the central processing unit and is connected to all of these sensors. Before sending the raw data over the ESP8266 Wi-Fi, it stabilizes and filters it

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=3&selection=78,0,86,13&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.3]]
> > system incorporates threshold-based decision-making algorithms that monitor real-time inputs for critical health and safety events

> [!PDF|yellow] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=5&selection=86,10,87,33&color=yellow|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.5]]
> > email alert mechanisms are integrated into the NodeRED environment using SMTP nodes.

> [!PDF|important] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=6&selection=7,37,14,1&color=important|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.6]]
> > lex sensors accu- rately detected patient gestures for water, food, and emergency needs with over 95% recognition accuracy

> [!PDF|note] [[Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors.pdf#page=6&selection=17,0,28,7&color=note|Real-Time Health Surveillance System for Paralyzed Patients using IoT and Smart Sensors, p.6]]
> > minimal latency of around 3–4 seconds

