# 平台介绍

## 🏠【关于我们】

![天天开源](https://open.tntlinking.com/assets/logo-b-BzFUYaRU.png) 

天天开源致力于构建开放共赢的平台，推动安全高效的开源应用普及。我们始终秉持“开源、众包、共享”的理念，致力于为医疗、教育、中小企业等行业提供优质的开源解决方案。

天天开源聚焦医疗、企业、教育三大行业信息化市场，现已发布OpenHIS、OpenCOM、OpenEDU系列开源软件产品。我们通过建立开源生态，联合生态伙伴共同打造创新行业协作模式，让数字化普惠、可信、安全。

天天开源的前身是新致开源，最早于2022年6月发布OpenHIS开源医疗，于2023年6月发布OpenCOM开源企业。2025年7月，新致开源品牌升级为天天开源。我们将持续践行开源精神，期待成为全球开源生态的引领者。

了解我们：https://open.tntlinking.com/about?site=github

## 💾【部署包下载】

请访问官网产品中心下载部署包：https://open.tntlinking.com/resource/productCenter?site=github

## 📚【支持文档】

技术文档：https://open.tntlinking.com/resource/openProductDoc?site=github
（含演示环境、操作手册、部署手册、开发手册、常见问题等）

产品介绍：https://open.tntlinking.com/resource/industryKnowledge?site=github

操作教程：https://open.tntlinking.com/resource/operationTutorial?site=github

沙龙回顾：https://open.tntlinking.com/resource/openSourceSalon#23?site=github

## 🤝【合作方式】

产品服务价格：https://open.tntlinking.com/cost?site=github

加入生态伙伴：https://open.tntlinking.com/ecology/becomePartner?site=github

## 🤗【技术社区】

请访问官网扫码加入技术社区交流：https://open.tntlinking.com/ecology/joinCommunity?site=github

请关注公众号【天天开源软件】以便获得最新产品更新信息。



# 项目介绍

OpenHIS医院系统（信创版）集十大核心模块于一体，涵盖目录管理、基础数据配置、个性化设置、门诊/住院全流程管理、药房药库智能管控、精细化耗材管理、财务核算体系、医保合规对接及多维报表分析等功能模块，共计372项标准化功能。

系统深度适配民营及公立一二级医院业务场景，支持单体医院、集团化运营及区域医疗协同等多种部署模式，并通过国家信创认证体系，确保全栈技术自主可控。如有项目需求，可联系官方平台合作。


## 运行环境

    jdk17 (必须)
    node.js-v16.15 (推荐)
    PostgreSQL-v16.2 (必须)
    redis (常用稳定版本即可)

## 开发提示

    需要修改数据库和redis的连接信息,详见:
        application.yml
        application-druid.yml

## 目录解释
	
    前端: openhis-ui-vue3
    后端: openhis-server
        启动类: OpenHisApplication
		
