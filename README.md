# agent_csv
##  1 首先选用gpt-4o-mini作为llm  
##  2 定义工具(tools)  
>  - 定义每一个工具时，首先定义输入参数input类，用于描述输入参数类型，继承自BaseModel  
>  - 具体的tool function , 用于agent的工具调用
>  - 利用StructureTool.from_function对function描述
###  2.1 load_csv_tool     
###  2.2 data_summary_tool  
###  2.3 impute_mean_tool  
###  2.4 plot_distribution_tool  
###  2.5 train_model_tool  
###  2.6 predict_tool  
##  3 构建Agent  
> 结构化聊天 + 零样本 + ReAct 描述型 

