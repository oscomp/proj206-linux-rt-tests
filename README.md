# proj-linux-rt-tests

## linux-rt-tests
Linux实时化测试性能提升

### 【项目描述】
rt-tests是Linux下的一个测试工具，一般主要用来测试使用内核的延迟，从而判断内核的实时性。rt-tests下有signaltest（测试信号发送接收之间的延迟）、cyclictest（测试进程切换延迟）等多个实时测试程序。本项目要求调试Linux内核，或在Linux内核中加入采样代码，确定导致rt-tests延迟发生的原因，并且依据总结的原因对内核进行改进。


### 【所属赛道】
2025全国大学生操作系统比赛的“OS内核设计”赛道

### 【参赛要求】
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

### 【项目导师】
刘志立
- github https://github.com/liuzhili-ya
- email zhili.liu@ucas.com.cn

### 【难度】
中等

### 【License】
MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)  

## 【预期目标】
- 结合实时性测试目标，通过调试内核中导致延迟的原因
- 在内核中加入采样代码，进一步采样延迟的原因
- 对内核进行改进，提高实时性

### 【参考资源】
- Linux内核实时化项目：https://wiki.linuxfoundation.org/realtime/start
- Linux RT-Tests: https://git.kernel.org/pub/scm/utils/rt-tests/rt-tests.git 
