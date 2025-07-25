# 统计分析接口

本模块提供了滴答清单的各种统计分析功能，帮助用户了解自己的任务完成情况和使用习惯。

## 接口列表

### 用户排名统计
- [获取用户排名统计](../statistics.md) - 获取用户在滴答清单中的排名和基本统计信息

### 通用统计
- [获取通用统计信息](./general-statistics.md) - 获取概览、成就值、趋势等通用统计信息

### 任务统计
- [获取任务统计信息](./task-statistics.md) - 获取指定日期范围内的任务统计信息

## 使用说明

1. **认证要求**: 所有统计接口都需要先完成微信登录获取认证会话
2. **数据实时性**: 统计数据实时更新，反映最新的用户活动
3. **时间范围**: 部分接口支持自定义时间范围查询
4. **多维度统计**: 提供任务、项目、标签等多维度的统计分析

## 相关模块

- [任务管理](../tasks/get-all-tasks.md) - 任务相关操作
- [习惯管理](../habits.md) - 习惯打卡统计
- [番茄专注](../pomodoros.md) - 专注时间统计
- [认证相关](../auth/) - 登录认证流程
