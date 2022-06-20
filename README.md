# Newspiral

## 介绍
NewSpiral是在工信部及江苏省委网信办、江苏省工信厅、江苏省通信管理局等有关部门指导下发布的适用于生产环境国产联盟区块链底层平台，由南京金宁汇科技有限公司联合头部企业和高校共同研发，具备高完整性、高性能、高广义效率等显著技术优势。NewSpiral底层区块链平台自2020年发布以来，获得了行业和社会各界的广泛关注，在区块链产业发展加速、开源技术层出不穷的当下，为国内区块链技术的自主创新提供新动能。


## 主要特性
### 公网环境下过万TPS
Newspiral单链4节点公网环境下（南京、广州、上海、合肥）下性能TPS可达万级

### 业务透明并行计算
Newspiral支持并行计算，并且完全由底层平台智能判断各个交易的关联关系，不需要业务应用提供任何额外信息

### 在线组链
Newspiral支持在线通过图形化管理界面构建业务链，节点可根据业务需要加入和退出任意业务链

### 各业务链管理配置独立且可在线更新
Newspiral支持不同中心化程度的业务链管理模式，既支持由一个链主对链中节点、合约等进行统一管理，也支持由链中多个参与方共同管理，并且支持在线变更管理模式，可适配联盟区块链落地的各种场景

### 分布式存储
Newspiral在单节点支持分布式存储，支持百亿级别结构化数据存储，并提供数据归档等操作以节省链上空间

### 一流BFT共识算法
Newspiral采用NweBFT算法，基于HotStuff算法进行系统的工程化改进，具有O(n)的通信复杂度，可支持大规模节点组网

### 隐私保护算法
Newspiral融合同态加密、零知识证明的隐私计算算法至平台，为数据隐私保护提供有力支撑

### 支持全链路国密算法
Newspiral支持通信链路层、业务交互层等全方位的国密算法支持

### 信创完全兼容
Newspiral作为工信部信创区块链首批测评通过的联盟链平台，与各类信创硬件、操作系统等具有极佳的兼容性

## 软件架构
与Hyperleger Fabric不同，Newspiral并不区分背书、排序、确认节点，所有参与共识的节点地位完全平等，任意一时刻，均有一个当前视图的主节点负责对一批交易进行排序和执行，然后使用共识算法在多个节点间针对区块达成共识，彻底解决了交易背书成功但共识失败、单区块内不允许存在关联交易等问题。
具体架构说明，可参考[在线开发者文档](http://docs.jinninghui.com){:target="_blank"}
markdown: [[kramdown ](http://docs.jinninghui.com)](http://docs.jinninghui.com)


## 安装教程
Newspiral提供图形化界面安装以及节点一键部署脚本，详情见[在线开发者文档](http://docs.jinninghui.com){:target="_blank"}
<a href="http://docs.jinninghui.com" target="_blank">Go</a>

[go](http://stackoverflow.com){:target="_blank" rel="noopener"}


## 使用说明
Newspiral提供完整的接入文档和示例工程，详情见[在线开发者文档](http://docs.jinninghui.com){:target="_blank" rel="noopener"}

## 参与贡献
1.  Fork 本仓库
2.  新建 Feature_xxx 分支
3.  提交代码
4.  新建 Pull Request
