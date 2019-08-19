# 几个概念
+ vugen:虚拟用户生成器。（捕获业务操作流程，创建自动测试脚本）用于录制脚本
+ controller: 用于创建、管理和监控场景的中央控制台。
+ 负载生成器：用于运行虚拟用户生成负载
+ analysis: 用于分析性能测试结果
# 测试流程
+ 1.创建脚本：通过录制在程序中的业务操作步骤生成自动化测试脚本（录制-回放-增强：添加事务、内容检查）
+ 2.设计场景：设置负载测试环境（如定义模拟用户数、加压的系统、执行的操作）
+ 3.运行场景：运行、管理并监控负载测试
+ 4.分析结果