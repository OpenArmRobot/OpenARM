OpenARM is an open-source remake version 7DOF humanoid arm hardware designed for physical AI research and deployment in many environments.
	With high backdrivability and compliance with High cost-effective standard for robot joint motors in China's supply chain, it excels at safe human-robot.

 ##Hardware Model: 
	OpenARM_01_DM :  OpenARM 01 with Damiao Motors   
		供应链说明：  达妙科技        供货状态稳定不稳定
	      CAD :构设计文件 for  OpenARM_01_DM 
	         Compatiable with OpenArm.dev 's  OpenArm01 
	        -----   Driver  硬件驱动       for  OpenARM_01_DM 
	        -----   PCB    PCBA主板设计  for  OpenARM_01_DM 
	        -----   Wiring  接线设计和教程  for  OpenARM_01_DM 
    OpenARM_01_RS   :  OpenARM 01 with Robstride Motors
			供应链：灵足电机   已验证小米系供应链 供货状态稳定
	        -----    CAD    结构设计文件  for OpenARM_01_RS
	        -----   Driver  硬件驱动         for OpenARM_01_RS
	        -----   PCB    PCBA主板设计   for OpenARM_01_RS
	        -----   Wiring  接线设计和教程   for OpenARM_01_RS
    OpenARM_01_HC   :  OpenARM 01 with HCFA Motors  
		供应链：禾川电机 上市公司 股票代码  688320.sh ，供货状态稳定
    OpenARM_G1_Strench : OpenARM Strench Gen1(Based on OpenARM_01_RS，OpenARM_01_HC)
	        -----    CAD    结构设计文件    for OpenARM_G1_Strench
	        -----   Driver  硬件驱动    for OpenARM_G1_Strench
	        -----   PCB    PCBA主板设计   for OpenARM_G1_Strench
	        -----   Wiring  接线设计和教程    for OpenARM_G1_Strench
    OpenARM_G1_Station : OpenARM Station Gen1(Based on OpenARM_01_RS，OpenARM_01_HC)
	        -----    CAD    结构设计文件 for  OpenARM_G1_Station
	        -----   Driver  硬件驱动   for  OpenARM_G1_Station
	        -----   PCB    PCBA主板设计 for  OpenARM_G1_Station
	        -----   Wiring  接线设计和教程  for  OpenARM_G1_Station
    OpenARM_G1_Heavy : OpenARM Heavy Gen1(Based on OpenARM_01_RS，OpenARM_01_HC)
	        -----    CAD    结构设计文件
	        -----   Driver  硬件驱动
	        -----   PCB    PCBA主板设计
	        -----   Wiring  接线设计和教程

 SubDirectory:
	CAD (本体硬件工程)
		 STEP / STL/:Assembly files for other CAD platforms (SolidWorks, OnShape, FreeCAD, etc.) 
 		提供兼容国际版仿真构型完整一致的的机械加工 3D 模型，用于 3D 打印或 CNC 制造
	 Driver/:
  		 CAN_BUS 电机驱动
	   EtherCat   总线驱动
	   Canable   开源CAN驱动
	PCBA/:
	   PCB_MainBoard  PCBA主板设计
	Wiring/:  
		  communication.pdf:  线束工程线路连接图。
		  J1_J2.pdf: 各关节电机的接口定义图纸。
