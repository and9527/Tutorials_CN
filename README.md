## DolphinDB 教程

- 安装和部署
    - [安装使用指南](dolphindb_user_guide.md)
    - [单节点部署](standalone_server.md)
    - [单节点部署(嵌入式ARM版本)](ARM_standalone_deploy.md)
    - [单服务器集群部署](single_machine_cluster_deploy.md)
    - [多服务器集群部署](multi_machine_cluster_deployment.md)
    - [高可用集群部署教程](ha_cluster_deployment.md)
    - [如何扩展集群节点和存储](scale_out_cluster.md)
    - [DolphinDB客户端软件教程](client_tool_tutorial.md)
    - [DolphinDB技术支持攻略](dolphindb_support.md)
    - [用新服务器从零开始部署 DolphinDB](deploy_dolphindb_on_new_server.md)
- 云上部署 DolphinDB
    - [DolphinDB Docker单机部署方案](../../../dolphindb-k8s/blob/master/docker_single_deployment.md)
    - [基于Docker-Compose的DolphinDB多容器集群部署](../../../dolphindb-k8s/blob/master/docker-compose_high_cluster.md)
    - [快速上手 DolphinDB-Mgr](../../../dolphindb-k8s/blob/master/deploy_k8s_quickly.md)
    - [自托管的 Kubernetes 部署 DolphinDB 集群](../../../dolphindb-k8s/blob/master/k8s_deployment.md)
    - [AWS Markeplace上的DolphinDB MGR快速上手](../../../dolphindb-k8s/blob/master/k8s_deployment_in_AWS.md)
    - [基于阿里云K8S的DolphinDB套件部署教程](../../../dolphindb-k8s/blob/master/k8s_deployment_in_Aliyun.md)
- 数据库
    - [分区数据库设计和操作](database.md)
    - [数据导入教程](import_data.md)
    - [数据备份恢复教程](restore-backup.md)
    - [动态增加字段和计算指标](add_column.md)
    - [内存表数据加载与操作](partitioned_in_memory_table.md)
    - [文本数据加载教程](import_csv.md)
    - [集群间数据库同步](data_synchronization_between_clusters.md)
    - [CacheEngine与数据库日志教程](redoLog_cacheEngine.md)
    - [内存表详解](in_memory_table.md)
    - [DolphinDB 分布式表数据更新原理和性能介绍](dolphindb_update.md)
    - [DolphinDB TSDB 存储引擎介绍](tsdb_engine.md)
- 编程语言
    - [脚本语言的混合范式编程](hybrid_programming_paradigms.md)
    - [函数化编程案例](functional_programming_cases.md)
    - [模块复用教程](module_tutorial.md)
    - [通用计算教程](general_computing.md)
    - [即时编译(JIT)教程](jit.md)
    - [元编程教程](meta_programming.md)
    - [自定义聚合函数](udaf.md)
    - [矩阵计算](matrix.md)
    - [日期/时间类型](date_time.md)
    - [DolphinDB窗口计算综述](window_cal.md)    
    - [DolphinDB SQL案例教程](DolphinDB_SQL_Case_Tutorial.md)
    - [DolphinDB SQL执行计划教程](DolphinDB_Explain.md)
- 流计算
    - [流数据教程](streaming_tutorial.md)
    - [流数据时序聚合引擎](stream_aggregator.md)
    - [流数据横截面引擎](streaming_crossSectionalAggregator.md)
    - [流数据异常检测引擎](Anomaly_Detection_Engine.md)
    - [历史数据回放教程](historical_data_replay.md)
    - [流数据高可用](haStreamingTutorial.md)
- 系统管理
    - [权限管理和安全](ACL_and_Security.md)
    - [作业管理](job_management_tutorial.md)
    - [内存管理](memory_management.md)
    - [启动脚本教程](Startup.md)
    - [定时作业](scheduledJob.md)
    - [使用Prometheus监控告警](DolphinDB_monitor.md)
    - [如何正确定位节点宕机的原因](how_to_handle_crash.md)
    - [线程简介](thread_intro.md)
    - [从一次SQL查询的全过程看DolphinDB 的线程模型](thread_model_SQL.md)
    - [DolphinDB 集群运维监控教程](cluster_monitor.md)
- API
    - [Python API使用教程](../../../api_python3/blob/master/README_CN.md)
    - [Java API使用教程](../../../api-java/blob/master/README_CN.md)
    <!--先隐藏，等教程更新完毕再暴露 - [Java API使用实例](../../../api-java/blob/master/example/README_CN.md) -->
    - [JDBC](../../../jdbc/blob/master/README_CN.md)
    - [C# API使用教程](../../../api-csharp/blob/master/README_CN.md)
    - [C++ API使用教程](../../../api-cplusplus/blob/master/README_CN.md)
    - [用VS2017编译DolphinDB C++ API动态库](cpp_api_vs2017_tutorial.md)
    - [C++ API 数据读写指南](c%2B%2Bapi.md)
    - [Go API使用教程](../../../api-go/blob/master/README.md)
    - [Go API使用实例](../../../api-go/blob/master/example/README_CN.md)
    - [R API使用教程](../../../api-r/blob/master/README_CN.md)
    - [Json API使用教程](../../../api-json/blob/master/README_CN.md)
    - [NodeJS API使用教程](../../../api-nodejs/blob/master/README.md)
    - [JavaScript API使用教程](../../../api-javascript/blob/master/README.zh.md)
    - [redash连接DolphinDB数据源的教程](data_interface_for_redash.md)
    - [DolphinDB整合前端chart组件展示数据教程](web_chart_integration.md)
    - [Grafana连接DolphinDB数据源](../../../grafana-datasource/blob/master/README.zh.md)
    - [帆软报表软件连接DolphinDB数据源](FineReport_to_dolphindb.md)
    - [API交互协议](api_protocol.md)
- 插件
    - [插件开发教程](plugin_development_tutorial.md) 
    - [插件开发深度解析](plugin_advance.md)
    - [amdQuote](../../../DolphinDBPlugin/blob/release200/amdQuote/README.md)
    - [AWS S3](../../../DolphinDBPlugin/blob/release200/aws/README.md)
    - [DolphinDB VSCode 插件](vscode_extension.md)
    - [Excel](../../../excel-add-in)
    - [Feather](../../../DolphinDBPlugin/blob/release200/feather/README.md)
    - [HBase](../../../DolphinDBPlugin/blob/release200/hbase/README.md)
    - [HDF5](../../../DolphinDBPlugin/blob/release200/hdf5/README_CN.md)
    - [HDFS](../../../DolphinDBPlugin/blob/release200/hdfs/README.md)
    - [HttpClient](send_messages_external_systems.md)
    - [Insight](../../../DolphinDBPlugin/blob/release200/insight/README.md)
    - [Kafka](../../../DolphinDBPlugin/blob/release200/kafka/README_CN.md)
    - [kdb](../../../DolphinDBPlugin/blob/release200/kdb/README_CN.md)
    - [Matching Engine](../../../DolphinDBPlugin/blob/release200/MatchingEngine/README.md)
    - [Matlab](../../../DolphinDBPlugin/blob/release200/mat/README.md)
    - [MongoDB](../../../DolphinDBPlugin/blob/release200/mongodb/README_CN.md)
    - [MQTT](../../../DolphinDBPlugin/blob/release200/mqtt/README_CN.md)
    - [MSeed](../../../DolphinDBPlugin/blob/release200/mseed/README.md)
    - [MySQL](../../../DolphinDBPlugin/blob/release200/mysql/README_CN.md)
    - [NSQ](../../../DolphinDBPlugin/blob/release200/nsq/README.md)
    - [ODBC](../../../DolphinDBPlugin/blob/release200/odbc/README_CN.md)
    - [OPC](../../../DolphinDBPlugin/blob/release200/opc/README_CN.md)
    - [OPCUA](../../../DolphinDBPlugin/blob/release200/opcua/README_CN.md)
    - [Parquet](../../../DolphinDBPlugin/blob/release200/parquet/README_CN.md)
    - [Py](../../../DolphinDBPlugin/blob/release200/py/README_CN.md)
    - [Signal](../../../DolphinDBPlugin/blob/release200/signal/README_CN.md)
    - [SVM](../../../DolphinDBPlugin/blob/release200/svm/README_CN.md)
    - [XGBoost](../../../DolphinDBPlugin/blob/release200/xgboost/README_CN.md)
    - [ZLib](../../../DolphinDBPlugin/blob/release200/zlib/README_CN.md)
    - [zmq](../../../DolphinDBPlugin/blob/release200/zmq/README.md)
- 模块
    - [技术分析(Technical Analysis)指标库](../../../DolphinDBModules/blob/master/ta/README_CN.md) 
    - [mytt (My麦语言T通达信T同花顺)指标库](../../../DolphinDBModules/blob/master/mytt/README.md)
    - [WorldQuant 101 Alpha因子指标库](../../../DolphinDBModules/blob/master/wq101alpha/README_CN.md)
    - [ops运维函数库](../../../DolphinDBModules/blob/master/ops/README.md)
    - [国泰君安191 Alpha因子库](../../../DolphinDBModules/blob/master/gtja191Alpha/README_CN.md)
- 应用场景示例
    - [使用DolphinDB进行机器学习](machine_learning.md)
    - [DolphinDB缓存表（CachedTable）快速实现MySQL跨数据库基础信息同步功能](cachedtable.md)
    - [DolphinDB中有关时间信息的最佳实践指南](timezone.md)
    - [DolphinDB Python API离线安装](python_api_install_offline.md)
  - 金融：
    - [在DolphinDB中计算K线](OHLC.md) 
    - [实时计算高频因子](hf_factor_streaming.md)
    - [DolphinDB教程：面板数据的处理](panel_data.md)
    - [金融高频因子的流批统一计算：DolphinDB响应式状态引擎](reactive_state_engine.md)
    - [股票行情数据导入实例](stockdata_csv_import_demo.md)
    - [快照引擎](snapshot_engine.md)
    - [节点启动时的流计算自动订阅教程](streaming_auto_sub.md)
    - [DolphinDB机器学习在金融行业的应用：实时实际波动率预测](machine_learning_volatility.md)
    - [DolphinDB流计算在金融行业的应用：实时计算分钟资金流](streaming_capital_flow_order_by_order.md)
    - [基于DolphinDB的因子计算最佳实践](best_practice_for_factor_calculation.md)
    - [SQL优化案例：深度不平衡、买卖压力指标、波动率计算](sql_performance_optimization_wap_di_rv.md)
    - [SQL优化案例：外汇掉期估值计算](FxSwapValuation.md)
    - [DolphinDB流计算在金融行业的应用：实时计算日累计逐单资金流](streaming_capital_flow_daily.md)
    - [DolphinDB历史数据回放功能应用：股票行情回放](stock_market_replay.md)
    - [DolphinDB流计算应用：基金份额参考价值IOPV计算](streaming_IOPV.md)
    - [DolphinDB元编程：开发股票波动率预测模型的676个输入特征](metacode_derived_features.md)
    - [从4.5小时到3.5分钟，如何利用DolphinDB高效清洗数据](data_ETL.md)
    - [DolphinDB流式计算中证1000指数主买/主卖交易量](CSI_1000.md)
    - [公募基金历史数据基础分析教程](public_fund_basic_analysis.md)
    - [平均性能超Python10倍: 如何使用DolphinDB计算基金日频因子](fund_factor_contrasted_by_py.md)
    - [DolphinDB Kafka插件最佳实践指南](kafka_plugin_guide.md)
    - [中高频多因子库存储最佳实践](best_practices_for_multi_factor.md)
    - [金融 PoC 用户历史数据导入指导手册之股票 level2 逐笔篇](LoadDataForPoc.md)
    - [DolphinDB NSQ 插件最佳实践指南](best_implementation_for_NSQ_Plugin.md)
    - [通过 DolphinDB JIT 功能加速计算 ETF 期权隐含波动率和希腊值](IV_Greeks_Calculation_for_ETF_Options_Using_JIT.md)
    - [DolphinDB 流数据连接引擎应用：多数据源流式实时关联处理](streaming-real-time-correlation-processing.md)
  - 物联网：
    - [DolphinDB在工业物联网的应用](iot_demo.md)
    - [物联网时序数据查询案例](iot_query_case.md)
    - [DolphinDB流计算引擎实现传感器数据异常检测](iot_anomaly_detection.md)
    - [DolphinDB流计算在物联网的应用：实时检测传感器状态变化](DolphinDB_streaming_application_in_IOT.md)
    - [随机振动信号分析解决方案](Random_Vibration_Signal_Analysis_Solution.md)
- 入门和测试
    - [DolphinDB入门：量化金融范例](quant_finance_examples.md)
    - [DolphinDB入门：物联网范例](iot_examples.md)
- 测试报告
    - [DolphinDB API性能基准测试报告](api_performance.md)
    - [金融市场高频数据应当如何管理 - DolphinDB与pickle的性能对比测试和分析](DolphinDB_pickle_comparison.md)
    - [DolphinDB集群水平扩展性能测试](Cluster_scale_out_performance_test.md)
- 迁移
    - [Python 函数到 DolphinDB 函数的映射](function_mapping_py.md)
    - [从 Kdb+ 到 DolphinDB](kdb_to_dolphindb.md)
    - [从 SQL Server 迁移数据到 DolphinDB](SQLServer_to_DolphinDB.md)
    - [从 InfluxDB 迁移数据到 DolphinDB](Migrate_data_from_InfluxDB_to_DolphinDB.md)
    - [从 Redshift 迁移数据到 DolphinDB](Migrate_data_from_Redshift_to_DolphinDB.md)

