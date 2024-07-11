# GUI-Agent-Survey

This is the official repository for the paper "Empowering GUI Agent with Large Language Model: A Comprehensive Survey".

## Abstract

The Graphical User Interface (GUI) is a visual method that allows users to interact with computers and mobile electronic devices. Nowadays users rely on GUI for completing some tasks such as browsing web or using mobile applications. Users often face the challenge to handle tedious tasks within GUI, such as replying to a specific type mass emails in Gmail application. GUI Agent are designed to help users by automating tasks in the GUI environment. Traditional automation agents lack flexibility, are often limited to specific applications, and require significant manual intervention. Benefiting from the powerful planning and reasoning capabilities of Large Language Model (LLM), LLM-based Agent achieved significant success in some fields (healthcare and autonomous driving). Researchers have also begun to explore the potential of LLM-based GUI Agent to automate task. Fortunately, these GUI agents have overcome the limitations of traditional agents and demonstrated remarkable performance.  Our survey reviews recent relevant LLM-based GUI Agent research and defines GUI task automation flow,  we focus on three key issues : (1) GUI Environment Understanding;  (2) User Interaction Experience;  (3) Efficient automation task Key step.  We finally outline the challenge and future opportunity in this field. This paper aims to provide valuable insights for researchers and engineers. A comprehensive list of studies in this survey is available at [https://github.com/longzhaohuang/GUI-Agent-Survey](https://github.com/longzhaohuang/GUI-Agent-Survey).

## News

😊 This project is under development. You can hit the **STAR** and **WATCH** to follow the updates.

## Table of Contents

- [GUI-Agent-Survey](#GUI-Agent-Survey)
  - [Abstract](#abstract)
  - [News](#news)
  - [Table of Contents](#table-of-contents)
  - [GUI Environment Understanding](#GUI-Environment-Understanding)
    - [Text-Based Understanding Method](#Text-Based-Understanding-Method)
    - [Vision-Based Understanding Method](#Vision-Based-Understanding-Method)
    - [Hybrid Text-Vision Understanding Method](#Hybrid-Text-Vision-Understanding-Method)
  - [Device Control](#Device-Control)
    - [Code-Based Method](#Code-Based-Method)
    - [Ui-Based Method](#Ui-Based Method)
  - [Dataset](#Dataset)
  - [Acknowledgement](#acknowledgement)

## GUI Environment Understanding
### Text-Based Understanding Method
[67][84][74][75]

### Vision-Based Understanding Method
[23][24][62][64][66][69][72][78][98]

### Hybrid Text-Vision Understanding Method
[73][80][79][99]

## Device Control
### Code-Based Method
[24][75][77][81][82][83]

### Ui-Based Method
[62]-[70],[71]-[74],[78]-[80],[83]

## Dataset
| Dataset                              | Platform | Observe         | Chat | High-Level | Domain | Instance   |
|--------------------------------------|----------|-----------------|------|-----------|--------|------------|
| Meta-GUI~\cite{sun2022meta}         | Mobile   | ScreenShot, VH  | ✗    | ✓         | 11     | 1125       |
| MobileGPT~\cite{lee2023explore}     | Mobile   | ScreenShot, VH  | ✗    | ✓         | 8      | 80         |
| PixelHelp~\cite{li2020mapping}       | Mobile   | ScreenShot, VH  | ✗    | ✓         | -      | 187        |
| RICOSCA~\cite{li2020mapping}         | Mobile   | ScreenShot, VH  | ✗    | ✗         | -      | 25,677     |
| MoTiF~\cite{burns2022dataset}       | Mobile   | ScreenShot, VH  | ✗    | ✓         | 125    | 61K        |
| UGIF~\cite{venkatesh2022ugif}       | Mobile   | ScreenShot, VH  | ✗    | ✓         | -      | 523        |
| MobileAgentBench~\cite{wang2024mobileagentbench} | Mobile | ScreenShot, VH  | ✗    | ✓         | 10     | 100        |
| DroidTask~\cite{wen2023empowering}   | Mobile   | ScreenShot, VH  | ✗    | ✓         | 13     | 158        |
| AndroidEnv~\cite{toyama2021androidenv}| Mobile   | ScreenShot       | ✗    | ✓         | 30     | 100        |
| MobileEnv~\cite{zhang2023mobile}     | Mobile   | ScreenShot, VH  | ✗    | ✓         | -      | 856,045    |
| WebArena~\cite{zhou2023webarena}     | Computer | ScreenShot, DOM | ✗    | ✓         | 6      | 812        |
| VWA~\cite{koh2024visualwebarena}     | Computer | ScreenShot, DOM | ✗    | ✓         | 3      | 910        |
| WebVoyager~\cite{he2024webvoyager}   | Computer | ScreenShot, DOM | ✗    | ✓         | 15     | 300        |
| WebShop~\cite{yao2022webshop}        | Computer | ScreenShot, DOM | ✗    | ✓         | 1      | 12,087     |
| MninWoB++~\cite{shi2017world}        | Computer | ScreenShot, DOM | ✗    | ✗         | 100    | 17,971     |
| WebLINX~\cite{lu2024weblinx}         | Computer | ScreenShot, DOM | ✓    | ✓         | 155    | 2337       |
| RUSS~\cite{xu2021grounding}          | Computer | ScreenShot, DOM | ✓    | ✓         | 22     | 80         |
| PharseNode~\cite{pasupat2018mapping} | Computer | ScreenShot, DOM | ✗    | ✗         | -      | 51,663     |
| UIBert~\cite{bai2021uibert}          | Computer | ScreenShot, DOM | ✗    | ✗         | -      | 16,660     |
| Mind2Web~\cite{deng2024mind2web}     | Computer | ScreenShot, DOM | ✗    | ✓         | 137    | 2,350      |
| AssistGUI~\cite{gao2023assistgui}     | Computer | ScreenShot, Metadata | ✗    | ✓         | 9      | 100        |
| AITW~\cite{rawles2023android}        | Mobile, Computer | ScreenShot | ✗    | ✓         | 357    | 30K        |
| ScreenSpot~\cite{cheng2024seeclick}  | Mobile, Computer | ScreenShot | ✗    | ✗         | -      | 600        |

| Caption: Overview of Datasets for GUI Task Automation. The columns indicate: the platform used (Platform), the method of environment observation (Observe), support for multi-turn dialogue (Chat), whether tasks need multi-step to complete (High-Level), the number of different domains included in the dataset (Domain), and the number of instances in the dataset (Instance). |

[11],[13],[79],[63,65],[113-124],[107,108],[69,74]

* Densegap: graph-structured dense correspondence learning with anchor points (ICPR, 2022) [[paper]](https://arxiv.org/pdf/2112.06910)

## Acknowledgement

This work is supported by Beijing Natural Science Foundation No. JQ23014, in part by the National Natural Science Foundation of China (No. 62271074).
