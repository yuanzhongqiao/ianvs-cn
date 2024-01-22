# Ianvs

[![CI](https://github.com/kubeedge/ianvs/workflows/CI/badge.svg?branch=main)](https://github.com/sedna/ianvs/actions)
[![LICENSE SCAN](https://app.fossa.com/api/projects/custom%2B32178%2Fgithub.com%2Fkubeedge%2Fianvs.svg?type=shield)](https://app.fossa.com/projects/custom%2B32178%2Fgithub.com%2Fkubeedge%2Fianvs?ref=badge_shield)
[![LICENSE](https://img.shields.io/github/license/kubeedge-sedna/ianvs.svg)](/LICENSE)

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-ianvs" class="anchor" aria-hidden="true" tabindex="-1" href="#ianvs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扬夫斯</font></font></h1>
<p dir="auto"><a href="https://github.com/sedna/ianvs/actions"><img src="https://github.com/kubeedge/ianvs/workflows/CI/badge.svg?branch=main" alt="CI" style="max-width: 100%;"></a>
<a href="https://app.fossa.com/projects/custom%2B32178%2Fgithub.com%2Fkubeedge%2Fianvs?ref=badge_shield" rel="nofollow"><img src="https://camo.githubusercontent.com/95a4113f9a4bc274327e5f541b6cc88ec4ad14d63ef322ef137b3925a61ff4d4/68747470733a2f2f6170702e666f7373612e636f6d2f6170692f70726f6a656374732f637573746f6d25324233323137382532466769746875622e636f6d2532466b7562656564676525324669616e76732e7376673f747970653d736869656c64" alt="许可证扫描" data-canonical-src="https://app.fossa.com/api/projects/custom%2B32178%2Fgithub.com%2Fkubeedge%2Fianvs.svg?type=shield" style="max-width: 100%;"></a>
<a href="/kubeedge/ianvs/blob/main/LICENSE"><img src="https://camo.githubusercontent.com/ecb340fc4d881f492ac79daf25abd0deff858a1bae1fc3aad80c84cb7a4a387f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f6b756265656467652d7365646e612f69616e76732e737667" alt="执照" data-canonical-src="https://img.shields.io/github/license/kubeedge-sedna/ianvs.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ianvs是KubeEdge SIG AI孵化的分布式协同AI基准测试项目。</font><font style="vertical-align: inherit;">Ianvs旨在按照公认的标准测试分布式协同AI解决方案的性能，以促进更高效和有效的开发。</font><font style="vertical-align: inherit;">更详细地说，Ianvs不仅准备了带有数据集和相应算法的测试用例，还准备了包括模拟和超参数搜索在内的基准测试工具。</font><font style="vertical-align: inherit;">Ianvs 还通过排行榜和测试报告等演示工具为开发人员和最终用户揭示了最佳实践。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-scope" class="anchor" aria-hidden="true" tabindex="-1" href="#scope"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分布式协同人工智能基准测试Ianvs旨在按照公认的标准测试分布式协同人工智能解决方案的性能，以促进更高效和有效的开发。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ianvs 的范围包括</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于典型的分布式协同人工智能范式和应用，提供跨设备、边缘节点和云节点的端到端基准测试工具包。
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理测试环境的工具。</font><font style="vertical-align: inherit;">例如，需要在测试环境中支持 CRUD（创建、读取、更新和删除）操作。</font><font style="vertical-align: inherit;">此类测试环境的元素包括算法方面和系统方面的配置。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">控制测试用例的工具。</font><font style="vertical-align: inherit;">典型的例子包括范式模板、仿真工具和基于超参数的辅助工具。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于管理基准演示的工具，例如排行榜和测试报告生成。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与其他组织或社区合作，例如在 KubeEdge SIG AI 中，建立全面的基准并开发相关应用程序，包括但不限于
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集收集、重组和发布</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正式规范，例如标准</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">举办竞赛或编码活动，例如开源推广计划</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护解决方案排行榜或商业用途认证</font></font></li>
</ul>
</li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-architecture" class="anchor" aria-hidden="true" tabindex="-1" href="#architecture"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建筑学</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">架构及相关概念如下图所示。</font><font style="vertical-align: inherit;">ianvs 设计为</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在单个节点内</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行。</font><font style="vertical-align: inherit;">关键组件包括</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试环境管理器：供全球使用的测试环境的 CRUD</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试用例控制器：控制测试用例的运行时行为，例如实例生成和消失
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成助手：帮助用户根据一定的规则或约束（例如参数的范围）生成测试用例</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仿真控制器：控制边云协同AI的仿真过程，包括仿真容器的实例生成和消失</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">故事管理器：测试用例的输出管理和呈现，例如排行榜</font></font></li>
</ul>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/kubeedge/ianvs/blob/main/docs/guides/images/ianvs_arch.png"><img src="/kubeedge/ianvs/raw/main/docs/guides/images/ianvs_arch.png" alt="" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 Ianvs 组件的更多详细信息：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试环境管理器支持测试环境的CRUD，主要包括
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">算法配置
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预处理算法</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征工程算法</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后处理算法，如度量计算</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统级配置
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整体架构</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统限制或预算
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端到端跨节点</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个节点</font></font></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试用例控制器，包括但不限于以下组件
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见的分布式协同人工智能范式的模板，可以帮助开发人员轻松准备测试用例。</font><font style="vertical-align: inherit;">这些范式包括边云协同联合推理、增量学习、联邦学习和终身学习。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模拟工具。</font><font style="vertical-align: inherit;">为测试用例开发模拟测试环境</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">协助测试用例生成的其他工具。</font><font style="vertical-align: inherit;">例如，根据给定的超参数范围准备测试用例。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Story Manager，包括但不限于以下组件
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">排行榜生成</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试报告生成</font></font></li>
</ul>
</li>
</ol>
<h2 tabindex="-1" dir="auto"><a id="user-content-guides" class="anchor" aria-hidden="true" tabindex="-1" href="#guides"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指南</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-documents" class="anchor" aria-hidden="true" tabindex="-1" href="#documents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档位于</font></font><a href="https://ianvs.readthedocs.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">readthedoc.io</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">这些文档包括快速入门、指南、数据集描述、算法、用户界面、故事和路线图。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照</font></font><a href="/kubeedge/ianvs/blob/main/docs/guides/how-to-install-ianvs.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ianvs 安装文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 Ianvs。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-examples" class="anchor" aria-hidden="true" tabindex="-1" href="#examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">场景PCB-AoI：</font></font><a href="/kubeedge/ianvs/blob/main/docs/proposals/scenarios/industrial-defect-detection/pcb-aoi.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PCB-AoI数据集上的工业缺陷检测</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
示例 PCB-AoI-1：</font></font><a href="/kubeedge/ianvs/blob/main/docs/proposals/test-reports/testing-single-task-learning-in-industrial-defect-detection-with-pcb-aoi.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试工业缺陷检测中的单任务学习</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
示例 PCB-AoI-2：</font></font><a href="/kubeedge/ianvs/blob/main/docs/proposals/test-reports/testing-incremental-learning-in-industrial-defect-detection-with-pcb-aoi.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试工业缺陷检测中的增量学习</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-roadmap" class="anchor" aria-hidden="true" tabindex="-1" href="#roadmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图</font></font></h2>
<ul dir="auto">
<li><a href="/kubeedge/ianvs/blob/main/docs/roadmap.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2022 年下半年路线图</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-meeting" class="anchor" aria-hidden="true" tabindex="-1" href="#meeting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">会议</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KubeEdge SIG AI 例行社区会议每周举行：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欧洲时间：</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">北京时间周四16:30-17:30</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">（</font></font><a href="https://www.thetimezoneconverter.com/?t=16%3A30&amp;tz=GMT%2B8&amp;" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转换为您的时区。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资源：</font></font></p>
<ul dir="auto">
<li><a href="https://docs.google.com/document/d/12n3kGUWTkAH4q2Wv5iCVGPTA_KRWav_eakbFrF9iAww/edit" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">会议记录和议程</font></font></a></li>
<li><a href="https://www.youtube.com/playlist?list=PLQtlO1kVWGXkRGkjSrLGEPJODoPb8s5FM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">会议录音</font></font></a></li>
<li><a href="https://zoom.us/j/4167237304" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">会议链接</font></font></a></li>
<li><a href="https://calendar.google.com/calendar/u/0/r?cid=Y19nODluOXAwOG05MzFiYWM3NmZsajgwZzEwOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">会议日历</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://calendar.google.com/calendar/u/0/r?cid=OHJqazhvNTE2dmZ0ZTIxcWlidmxhZTNsajRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">订阅</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-contact" class="anchor" aria-hidden="true" tabindex="-1" href="#contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接触</font></font></h2>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有疑问，请随时通过以下方式与我们联系：</font></font></p>
<ul dir="auto">
<li><a href="https://app.slack.com/client/TDZ5TGXQW/C01EG84REVB/details" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">松弛通道</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有兴趣成为贡献者并希望参与 Ianvs 代码的开发，请参阅</font></font><a href="/kubeedge/ianvs/blob/main/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取有关提交补丁和贡献工作流程的详细信息。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ianvs 遵循 Apache 2.0 许可证。</font><font style="vertical-align: inherit;">有关详细信息，请参阅</font></font><a href="/kubeedge/ianvs/blob/main/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font></font></p>
</article></div>
