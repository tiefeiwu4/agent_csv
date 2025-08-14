# agent_csv
##  1 首先选用gpt-4o-mini作为llm  
##  2 定义工具(tools)  
>  定义每一个工具时，首先定义输入参数input类，用于描述输入参数类型，继承自BaseModel  
>  具体的tool function , 用于agent的工具调用
>  利用StructureTool.from_function对function描述
###  1.1 load_csv_tool     
###  1.2 data_summary_tool  
###  1.3 impute_mean_tool  
###  1.4 plot_distribution_tool  
###  1.5 train_model_tool  
###  1.6 predict_tool  
##  3 构建Agent  
> 结构化聊天 + 零样本 + ReAct 描述型 

