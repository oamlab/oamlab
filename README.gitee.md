<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">OAMLab · 运维实验室</h1>
<h4 align="center">公益的、免费的运维实验室！</h4>
<h4 align="center">始于2022</h4>
<p align="center">
  <a href="./LICENSE"><img alt="license" src="https://img.shields.io/github/license/oamlab/oamlab" /></a>
  <img alt="repo-size" src="https://img.shields.io/github/repo-size/oamlab/oamlab" />
</p>

<p align="center">
   <a href="https://github.com/oamlab">GitHub</a> | 
   <a href="https://gitee.com/oamlab/oamlab">Gitee</a> | 
   <a href="./README.English.md">English</a>
</p>

<p align="center"></p>

---
<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">传道 · 授业 · 解惑 · 躬行<br>奉献 · 友爱 · 互助 · 进步<br>言行一致 · 知行合一</h1>

## 🌏 前言：
- [在线文档：https://gitee.com/oamlab/oamlab](https://gitee.com/oamlab/oamlab)
- [Online Documentation：https://github.com/oamlab/oamlab](./README.English.md)
- 注：所有的历史实验文档，都在GitHub进行存档。
- 欢迎更多的运维技术人员参与实验，一起不断向前！

*[国际访问请使用国际资料仓GitHub入口，点击进入](https://github.com/oamlab)

## 🕒 预约实验设施:
- [预约申请表单：https://www.wenjuan.com/s/An2muew](https://www.wenjuan.com/s/An2muew)
- [OAMLab运维实验室管理制度](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/151_会议材料/20221030-运维实验室预约-11月暨首次使用宣讲/2、OAMLab.运维实验室.实验室管理制度.20221028.2151.pdf)

## 📃 OAMlab 介绍:

**OAMLab** 是公益免费的运维实验室，主要用于各位运维技术人员做运维技术实验使用，模块包括：

``` java
1,云计算-KVM: virsh,Openstack
服务器数量: 3

2,云计算-Container: docker,Kubernetes
服务器数量: 3

3,分布式存储: Hadoop,Hbase,Ceph
服务器数量: 3

4,数据
数据库: Mysql,MariaDB
缓存: Redis
对象存储: Mongodb,Minio
服务器数量: 3

5,日志分析: Elasticsearch,Logstash,Kibana
服务器数量: 3

6,负载均衡: Nginx-quic,HTTP/3,LVS,Keepalived,CDN
服务器数量: 3

7,DevSecOps工具集(CI-CT-CD):
服务器数量: 3
CI: Git,GitLab,Jenkins
CT-白盒-静态测试
CT-黑盒-动态测试
CT-API接口测试
CD-Ansible,IaC

8,安全:安全威胁建模,防火墙,WAF,自动防御,用户权限与文件权限,蜜罐,混沌工程与DRP
服务器数量: 2

9,监控: Nagios,Cacti,Zabbix,Prometheus等
服务器数量: 2

10,消息队列:
关键词: RabbitMQ,kafka等
服务器数量: 3
```

## 🧰 实验环境的基础设施：

目前提供的基础设施版本如下：
- 当前版本：[CentOS-Stream-9-x86_64](https://www.centos.org/download)，Kernel 5.14，版本终止时间：20270531
- 备用版本：[CentOS-Stream-10-x86_64](https://www.centos.org/download)，Kernel 6.12，版本终止时间：2030
- 系统演进：[Fedora >> Centos Stream >> Red Hat Enterprise Linux (RHEL)](https://blog.centos.org/2021/12/introducing-centos-stream-9/)

操作系统软件生命周期管理：
- 操作系统更新：每天，yum update
- 操作系统重启：每周六，reboot

运维工程实验的组件、软件来源：
- GitHub
  - https://github.com/search
- 清华大学开源软件镜像站
  - https://mirrors.tuna.tsinghua.edu.cn
- Apache软件基金会
  - https://projects.apache.org/projects.html
- SourceForge
  - https://sourceforge.net/directory

## 📚 OAMLab 分享内容：

- [仓库列表](https://gitee.com/oamlab/projects)

- [主仓目录](./OAMLab)

- [运维观点](https://gitee.com/OAMLab/oamlab/tree/main/OAMLab/161_运维观点)

- [运维工程](https://gitee.com/OAMLab/oamlab/raw/main/OAMLab/161_运维观点/202_运维.运维工程.20230319.0927.pdf) . [运维基本技能](https://gitee.com/OAMLab/oamlab/raw/main/OAMLab/161_运维观点/206_运维.基本技能.20230324.2009.pdf) . [运维职业发展](https://gitee.com/OAMLab/oamlab/raw/main/OAMLab/161_运维观点/212_运维.职业发展.20230322.1911.pdf) . [运维圈内语](https://gitee.com/OAMLab/oamlab/blob/main/OAMLab/161_运维观点/311_运维.圈内语.md)

- [运维工程服务质量策划(SLA)](./OAMLab/161_运维观点/6101_Service_Quality_Planning_for_OAM_Engineering.20240426.2001.md)

- [企业私有云建设参考](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/161_运维观点/5102_运维.私有云.企业私有云建设参考.20230406.1959.pdf)

- [企业软件研发效能DevSecOps工具集](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/161_运维观点/5202_运维.DecSecOps.企业软件研发效能DecSecOps工具集在企业应用中的参考.20230415.2101.pdf) . [企业软件研发效能DevSecOps工具集.流水线.示意图](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/161_运维观点/5206_运维.敏捷项目管理.企业软件研发效能DevSecOps工具集.流水线.示意图.20240701.2045.pdf)

- [企业开始注重信息安全的几个征兆](https://gitee.com/OAMLab/oamlab/raw/main/OAMLab/161_运维观点/5302_运维.安全.信息安全.企业开始注重信息安全的几个征兆.20230328.2002.pdf)

- [企业商业隐私数据的几个关键词](https://gitee.com/OAMLab/oamlab/raw/main/OAMLab/161_运维观点/5312_运维.安全.信息安全.企业商业隐私数据的几个关键词.20240808.2201.pdf) . [企业商业隐私数据泄露的几个途径](https://gitee.com/OAMLab/oamlab/raw/main/OAMLab/161_运维观点/5304_运维.安全.信息安全.企业商业隐私数据泄露的几个途径.20230424.2225.pdf)


- OAMLab.运维实验室.202211期.课题分享会 . [视频](./OAMLab/401_运维实验/2022-11)
  - [李渊荣老师：夜莺v4监控系统安装使用介绍](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2022-11/1009_01_OAMLab.运维实验室.运维实验.夜莺v4监控系统安装使用介绍.20221115.2044.docx)
  - [张楷熊老师：关于nginx的介绍和应急故障处理](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2022-11/1006_01_OAMLab.运维实验室.运维实验.关于nginx的介绍和应急故障处理.20221115.1659.pptx)


- OAMLab.运维实验室.202302期.课题分享会 . [视频](./OAMLab/401_运维实验/2023-02)
  - [况波老师：夜莺V5监控告警](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-02/1009_01_OAMLab.运维实验室.运维实验.夜莺V5监控告警.20221217.1955.docx)
  - [刘军老师：关于消息搜索在ES上使用的实践](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-02/1005_01_OAMLab.运维实验室.运维实验.关于消息搜索在ES上使用的实践.20221115.1659.pptx)


- OAMLab.运维实验室.202304期.课题分享会 . [视频](./OAMLab/401_运维实验/2023-04)
  - [邱科老师：关于jenkins的pipeline用法](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-04/1007_01_OAMLab.运维实验室.运维分享.关于jenkins的pipeline用法.20230404.1615.pptx)
  - [孙焱楚老师：关于金融行业的智能运维建设](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-04/1001_01_OAMLab.运维实验室.运维分享.关于金融行业的智能运维建设.20230410.1415.pptx)


- OAMLab.运维实验室.202306期.课题分享会 . [视频](./OAMLab/401_运维实验/2023-06)
  - [田夜明老师：基于安全基线的安全运维建设](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-06/1008_01_OAMLab.运维实验室.运维分享.基于安全基线的安全运维建设.20230616.2135.pptx)
  - [况波老师：Jenkins的Pipeline](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-06/1007_01_OAMLab.运维实验室.运维分享.jenkins的pipeline.20230616.0930.md)


- OAMLab.运维实验室.202308期.课题分享会 . [视频](./OAMLab/401_运维实验/2023-08)
  - [曾祥林老师：k8s的api的简单调用](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-08/1002_01_OAMLab.运维实验室.运维实验.k8s的api的简单调用.20230412.2053.docx)
  - [段世华老师：数据库发展趋势](https://gitee.com/oamlab/oamlab/raw/main/OAMLab/401_运维实验/2023-08/1004_01_OAMLab.运维实验室.运维分享.数据库发展趋势.20230410.1035.pptx)


- OAMLab.运维实验室.202404期.课题分享会 . [视频](./OAMLab/401_运维实验/2024-04)
  - [刘思雨老师：关于VictorMetrics的使用](https://gitee.com/oamlab/victoriametrics/blob/main/victoriametrics/3181_Others/README.md)


- OAMLab.运维实验室.202406期.课题分享会 . [视频](./OAMLab/401_运维实验/2024-06)
  - [周伟老师：关于DevSecOps演示环境的部署方法和测试](https://gitee.com/oamlab/devsecops/blob/main/devsecops/3181_Others/README.md)
  - [张兵老师：关于Loki的部署和使用方法](https://gitee.com/oamlab/loki/blob/main/loki/3181_Others/README.md)


- OAMLab.运维实验室.202412期.课题分享会 . [视频](./OAMLab/401_运维实验/2024-12)
  - [杨启涌老师：基于Nginx的灰度发布方法](https://gitee.com/oamlab/nginx/blob/develop/nginx/3181_Others/README.md)


- OAMLab.运维实验室.202508期.课题分享会 . [视频](./OAMLab/401_运维实验/2025-08)
  - [兰正旺老师：关于部署Jenkins Pipeline演示环境](https://gitee.com/oamlab/jenkins/blob/main/jenkins/3181_Others/Jenkins_Pipeline_20250731_2201.md)


- [传送门](https://gitee.com/oamlab/projects)
  - [OAMLab](https://gitee.com/oamlab)
  - [DevSecOps](https://gitee.com/oamlab/devsecops)
  - [Kubernetes](https://gitee.com/oamlab/kubernetes)
  - [STS](https://gitee.com/oamlab/STS)
  - [Nightingale](https://gitee.com/oamlab/nightingale)
  - [VictoriaMetrics](https://gitee.com/oamlab/victoriametrics)
  - [Jenkins](https://gitee.com/oamlab/jenkins)
  - [Loki](https://gitee.com/oamlab/loki)
  - [使用HTTP/3，Nginx-QUIC](https://gitee.com/oamlab/nginx-quic)
  - [攻击者清单](https://gitee.com/oamlab/attacker)
  - [IP属地分析，nali](https://gitee.com/oamlab/nali)

*[国际访问请使用国际资料仓GitHub入口，点击进入](https://github.com/oamlab)

## 🤝 联合发起人

倡导勤于技术，不断学习的联合发起人如下：

- **姚国贵** 77810419@qq.com
- **张楷熊** 759869080@qq.com
- **丁丹** 20580822@qq.com
- **吕银兴** 591244761@qq.com
- **段世华** 275142133@qq.com
- **赵丹伟** 491446839@qq.com
- **孙焱楚** 951803764@qq.com
- **刘建淮** 496707275@qq.com
- **刘军** 1186158664@qq.com
- **李渊荣** 584194788@qq.com
- **曾祥林** 839225516@qq.com

*排名根据填写问卷的时间顺序

## 💖 大爱捐赠人

关注实验室建设，积极捐增的爱心人士如下：

| 姓名						 | 捐赠比例	 |联系方式|
|----------|------:|-----------------|
| **姚国贵** | 11.0% |   77810419@qq.com |
| **张楷雄** |  2.8% |  759869080@qq.com |
| **丁丹**  |  5.5% |   20580822@qq.com |
| **吕银兴** |  1.7% |  591244761@qq.com |
| **段世华** |  0.6% |  275142133@qq.com |
| **赵丹伟** |  5.5% |  491446839@qq.com |
| **孙焱楚** |  1.1% |  951803764@qq.com |
| **刘建淮** |  0.6% |  496707275@qq.com |
| **刘军**  |  1.1% | 1186158664@qq.com |
| **李渊荣** |  0.6% |  584194788@qq.com |
| **曾祥林** |  1.7% |  839225516@qq.com |
| **邱科**  |  2.2% |  23198985@qq.com |
| **刘思雨** |  0.6% |  2176804187@qq.com |
| **周伟**  |  0.6% |  243120635@qq.com |
| **兰正旺**  |  1.1% |  1223790502@qq.com |
| **陶武杰**  |  1.1% |  1070587554@qq.com |
| **王论**  |  0.6% |  371186235@qq.com |

*排名根据填写问卷的时间顺序；当前整体捐赠进度约49%；捐赠比例跟随总成本。

## 🥇 积极传道者
- [传道、授业、解惑的积极实践者。(点击查看)](./OAMLab/131_传道者)


- 《传道者奖章》获得者：

| 姓名						 | 星级	                            |联系方式|
|----------|:-------------------------------|-----------------|
| **李渊荣**  | <font color="#FFD700">⭐</font> |   584194788@qq.com |
| **张楷雄**  | <font color="#FFD700">⭐</font> |  759869080@qq.com |
| **况波**   | <font color="#FFD700">⭐</font> |   1214966109@qq.com |
| **刘军**   | <font color="#FFD700">⭐</font> |  1186158664@qq.com |
| **邱科**   | <font color="#FFD700">⭐</font> |  23198985@qq.com |

## 📶 技术交流群
深圳运维圈 QQ交流群：216589280 [点击加入](https://jq.qq.com/?_wv=1027&k=tdDtDoUp)

## 🔃 提交代码
- 提交代码路径：个人分支 >> develop >> main
- 譬如：develop_AndyYao_202301 >> develop >> main
- 为了方便做代码评审，每次最多提交5个代码文件，每次最多提交200行代码。
- [使用SSH的方式连接GitHub](./OAMLab/171_运维工具/301_开发工具/211_GitHub_SSH_Key.md)

## 🆓 版权说明
- 原软件或依赖软件仍保持其原有授权。
- 独立于原软件或依赖软件之外编写的代码、辅助软件、使用方法、文档等，是GNU General Public License v3.0授权。
- 譬如：XXX Community Server 1.0.1是基于GPL v2.0授权，我们编写的辅助软件start_XXX.sh和文档是基于GPL v3.0。

<p align="center">
	<img alt="OAMLab_gitee_img" src="https://www.wegoodgoodstudydaydayup.com/oamlab_gitee.webp?v=202308012358">
</p>

<br>