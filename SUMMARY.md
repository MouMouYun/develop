# Summary

* [猛犸新版介绍](intro/1.md)
* 模块指南
    * 项目中心
        * [新建项目](proj/1.md)
        * [资源申请与管理](proj/2.md)
        * [加入成员与角色管理](proj/3.md)
        * 权限管理
            * Hive权限
                * [项目内数据授权与查看](proj/data/1.md)
                * 项目外数据授权与查看
                    * [项目内表设为公开](proj/data/2.md)
                    * [项目外表申请读权限](proj/data/3.md)
                    * [项目内表收回读权限、设置私有](proj/data/4.md)
            * HDFS权限
                * [项目内目录授权](proj/data/5.md)
                * [项目外目录授权](proj/data/6.md)
            * 队列权限
            * [功能权限设计与查看](proj/func/1.md)
        * [活动跟踪](proj/5.md)
        * [项目keytab](proj/6.md)
        * [个人keytab](proj/7.md)
        * [资源监控](proj/8.md)
    * 数据开发
        * 说明
            * [节点、作业流与项目的区别](desc/job/1.md)
            * [开发模式与线上模式的区别](desc/de/1.md)
            * [调度系统参数清单](desc/azkaban.md)
            * [作业流终节点](desc/job/noop.md)
        * 任务列表
            * [文件夹树状列表](dev/dirmgr/joblist.md)
            * [新建文件夹](dev/dirmgr/createfile.md)
            * [重命名](dev/dirmgr/rename.md)
            * [删除](dev/dirmgr/delete.md)
            * [上传资源包](dev/dirmgr/uploadSourceZip.md)
            * [显示/隐藏文件夹](dev/dirmgr/hide.md)
            * [默认文件夹](dev/dirmgr/default.md)
        * 数据列表
            * [数据树状列表](dev/dirmgr/datalist.md)
            * [表详情](dev/dirmgr/tabledetail.md)
            * [新建离线表](dev/dirmgr/createtable2.md)
            * [新建流表](dev/dirmgr/createtable.md)
        * 数据应用开发与调试
            * [新建节点任务](dev/job/new.md)
                * [数据传输任务](dev/job/sqoop.md)
                * [HiveQL任务](dev/job/hiveql.md)
                * [SparkSQL任务](dev/job/sparksql.md)
                * [Spark任务](dev/job/spark.md)
                * [MR任务](dev/job/mapreduce.md)
                * [Script任务](dev/job/script.md)
                * [kafka入库](dev/job/kafka/1.md)
                * [kafka归档](dev/job/kafka/2.md)
                * [选择节点](dev/job/choose.md)
                * [嵌套流任务](dev/job/nest.md)
                * [虚拟节点](dev/job/null.md)
                * [小文件合并](dev/filemerge/xiao-wen-jian-he-bing.md)
            * 新建作业流任务
                * [新建节点](dev/flow/graph/create.md)
                * [设置依赖](dev/flow/graph/dependencies.md)
                * [编辑节点](dev/flow/graph/edit.md)
                * [画布其他功能](dev/flow/graph/other.md)
            * [新建项目](dev/jobmgr/4.md)
            * [上传ZIP包](dev/jobmgr/5.md)
            * [运行设置/运行](dev/jobexec/execute.md)
                * [运行结果](dev/jobexec/histories/result.md)
                * [运行状态](dev/jobexec/histories/status.md)
                * [工作流日志](dev/jobexec/histories/flow.md)
                * [作业日志](dev/jobexec/histories/node.md)
                * [SQL节点运行结果](dev/jobexec/histories/sql.md)
            * 提交上线并调度
                * [提交上线](dev/schedule/submit.md)
                * [设置并提交调度](dev/schedule/schedule.md)
                * [取消调度](dev/schedule/cancel.md)
            * [跨流依赖](dev/schedule/flowdepend.md)
                * [设置依赖](dev/schedule/flowdepend-1.md)
                * [查看依赖、依赖约束](dev/schedule/flowdepend-2.md)
                * [项目间依赖授权](dev/schedule/flowdepend-3.md)
                * [跨流依赖详情](dev/schedule/flowdepend-4.md)
    * 任务运维
        * [运维概览]()
        * [实例运维](ops/1.md)
            * [实例详情](ops/detail/detail.md)
            * [重跑](ops/job/1.md)
        * 任务管理
            * [任务列表](ops/2.md)
            * [补数据](ops/job/2.md)
            * [任务血缘]
    * 自助分析
        * [Notebook](query/notebook.md)
        * [HQL查询](query/query.md)
    * 实时流计算
        * [任务管理](sloth/job.md)
        * [任务运维](sloth/online.md)
        * [UDF管理](sloth/udf.md)
    * 数据管理
        * Hive元数据
            * [物理视图](data/hivemeta.md)
            * [主题视图](data/subject.md)
            * [修改表](data/modifytbl.md)
            * [数据血缘](data/lingage.md)
        * [数仓管理](data/subject.md)
        * [文件管理](data/hdfsys.md)
        * [数据源](data/2.md)
* [技术文档](tech.md)
    * [Hive](tech/hive.md)
    * [MR](tech/mr.md)
    * [Spark](tech/spark.md)
    * [Impala](tech/impala.md)
    * [SparkSQL](tech/sparksql.md)
    * [HDFS](tech/hdfs.md)
* FAQ
    * [数据开发](FAQ/dev.md)
    * [Hive](FAQ/hive.md)
    * [Spark](FAQ/spark.md)
    * [数据传输](FAQ/sqoop.md)
    * [自助分析](FAQ/query.md)
* [开源组件版本](version.md)
