---
title: "Practicum Report: Magnetic Capsule Endoscopy Robot"
summary: A practicum report from Principle and Design of Medical Devices
tags:
  - Practicum
  - Medical Devices
  - Capsule Endoscopy Robot
date: '2022-08-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 'Image credit: [**Reference**](https://link.springer.com/article/10.1007/s12213-016-0087-x)'
  focal_point: Smart

links:
  - icon: square-rss
    icon_pack: fas
    name: Supervisor
    url: https://sz.ustc.edu.cn/rcdw_show/44.html
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---
# Notice
Welcome to visit this practicum project!🤝

In view of my limited knowledge, there are still many deficiencies in this report. Please forgive and point out my mistakes.
 
# Report
## 需求分析
  消化道系统疾病是人类社会中最常见的疾病之一，无论年龄、性别还是地域，几乎所有人都经历过消化道系统疾病的困扰。随着年龄的增长，罹患消化道系统的概率与频率将不断增长，而在当今21世纪的全球人口达到人类历史顶峰和社会老龄化现象逐渐蔓延的情况下，消化道系统疾病将会给各国的社会保障体系和医疗保健系统造成前所未有的压力[1-7]。据相关数据统计[1, 7]，胃溃疡或十二指肠消化性溃疡在欧洲人群中的总患病率为4.1%，在中国人群中总患病率则为17.2%，而胃病的全球人群中的总患病率更是高达50%，胃癌不仅是四大常见癌症之一，还是常见癌症中第二大死亡诱因。
尽管消化道系统疾病种类繁多、疗法复杂，但是定期的筛查与发生异常时的诊断肯定是治疗消化道系统疾病必不可少的一环。内窥镜不仅是临床上进行疾病诊断的常见手段，也是检查消化道系统疾病的金标准[5-10]。具体而言，胃肠道约有9米，其中，小肠约占三分之二，易患有出血、溃疡、吸收不良、炎症、狭窄、息肉和癌症等疾病。然而，传统的光导纤维内窥镜存在结构上粗硬、成像质量较差等问题，进一步来说，基于有线信号传输与机械传动的侵入性有线内窥镜难以深入消化道进行观察，特别是实现全小肠的检查[5-8]。于是，本文基于内窥镜在消化道系统疾病的诊疗过程的重要地位，总结了三类新型内窥镜以进行创新医疗器械的需求筛选，并最终确定磁控胶囊式内窥镜系统为当前国内该领域的医疗器械创新方案首选。
| Syntax      | Description | Syntax      | Description | Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Fireproof Microcapsules
  The use of fire-extinguishing agents to suppress the lithium battery deflagration is a good choice. However, the existing fire-extinguishing agents halogenated alkane 1301, carbon dioxide, heptafluoropropane, can only extinguish the open fire, but can not fundamentally inhibit the fire, which leads to the re-ignition of the battery, and does not have the dual function of cooling and fire-extinguishing.

  **Moreover, complex fire fighting facilities will increase the weight or volume of the energy storage system, which is not absolutely reliable in the case of thermal runaway.** Therefore, the selection of suitable fire-extinguishing agents and the design of new fire-extinguishing devices are important research areas for the large-scale application of lithium-ion batteries.

  Therefore, considering the shortcomings of most halogenated hydrocarbon extinguishing agents such as high cost, low boiling point, difficult storage, use of complex equipment fittings, and high pressure required for injection, microencapsulation of halogenated hydrocarbon extinguishing agents is a good and feasible solution. So, what can be used as the core material of microcapsules to effectively achieve fire-extinguishing and flame retardant function?

  It was found that fluorinated derivatives can stop the chain reaction that occurs during lithium-ion battery combustion and have no other negative effects on electrical equipment, such as perfluorocaproone (NOVEC 1230), a green fire-extinguishing agent that contains no bromine or chlorine, has an almost zero ozone depletion value, and degrades completely in the atmosphere within 1 to 2 weeks.
  
  Noteworthy, at low concentrations, perflourohexanone can instead enhance combustion. Therefore, according to the actual lithium-ion battery ignition conditions, it is necessary to select a suitable high boiling point, high heat of vaporization and high specific heat composite fire-extinguishing agent (fire-extinguishing agent + coolant) in order to ensure the fire-extinguishing performance while taking into account the cooling capacity.

  **However, perfluorhexanone is difficult to microencapsulate because its inactive nature makes it difficult to dissolve or be dissolved into other substances, making it difficult to synthesize microcapsules by chemical methods. In addition, the high density and volatility of perflourohexanone make it difficult to be microencapsulated by other general techniques.**

  To address these issues, our team encapsulated perflourohexanone through **actively excited microfluidic technology**, which not only isolates it from the external environment to protect and store the extinguishing agent, but when the ambient temperature rises (~80°C), perflourohexanone, the core material, absorbs heat and evaporates, rising through the outer walls of the microcapsules, thereby releasing and inhibiting further chain reactions and eliminating the fire before it is too late.

  In the pre-exploration, we have not only verified that the fireproof microcapsules developed by our team can remain stable in the electrolyte (30 days), but have also conducted experiments on small batteries (aluminum-plastic film batteries, 3.2V-40Ah) and achieved good fire-extinguishing results.

