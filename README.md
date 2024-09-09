# Smart-Buoy 智慧浮标
## 项目介绍
我们小组的Capstone立足DMU的海洋基因，开发一款海洋智慧浮标。主要分为波浪动力学分析、发电装置设计、机械结构设计和传感四部分，分别由三位即将毕业的大四学牲负责。
## Buoy-wave interaction
为了使水上浮标在海面上有着稳定的姿态以保证可靠的工作效率和状态，团队需要对波浪动力模型进行详细的了解与分析。波浪动力模型是用来模拟水体在不同情况下流动的力学过程的一种数学模型。它可以帮助我们更好地理解波浪的运动规律和特性，进而为确定浮标的重心、浮心等关键参数提供科学依据。波浪动力模型的基本原理主要为流体运动的基本特性和动量方程等。基于此，我们需要经过确定研究对象，收集数据，建立模型模拟分析，结果解释五个主要步骤，完成项目中此部分对于波浪动力模型的建模分析。
## Power Take-off (PTO) design
鉴于海上天气复杂多变，飓风、暴风雨等恶劣天气频发，长时间的晴朗天气难以预料，使用太阳能电池板作为发电装置的光电转换效率低下，很难保证浮标能在海上长时间稳定工作。于是我们采用波浪能发电装置，灵感源于手摇发电手电筒，在浮标内部放置几个可自由移动的浮子，当有大浪来袭时浮子将上下剧烈运动，进而带动驱动发电机旋转运动而发电，最终这些电能将储存在蓄电池中。另外我们考虑到由于海面上非常光滑极易产生强大的气流，因此风力资源也非常丰富，我们期望配备合适的永磁同步发电机，并设计风向调节装置，使叶片始终正对风向，提高发电效率。
## Structure design
外部结构设计是确保其在海洋环境中稳定性和耐久性的关键。首先，材料选择至关重要，具体应选用了耐腐蚀、高强度的复合材料，能够抵御海水腐蚀和机械磨损。结构优化方面，通过有限元分析（FEM）和有限元网络（FEN）对浮标的应力分布进行详细分析，确保其在各种海况下的稳定性。浮标形状和尺寸的确定则通过流体动力学仿真（CFD）进行优化，以减少水阻并提高能源效率。此外，浮标外部还配备了防撞护栏和抗风浪装置，进一步增强其在恶劣海况中的生存能力。综合这些措施，旨在确保浮标在长期运行中表现出色，能够可靠地执行海洋监测任务。
## Sensing
