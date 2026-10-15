<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:0284c7&height=190&section=header&text=LUO-ROOT&fontSize=44&fontColor=f8fafc&desc=WORKFLOWS%20%2F%20BACKEND%20%2F%20AGENT%20INFRASTRUCTURE&descSize=16&descAlignY=72&animation=fadeIn" width="100%" alt="Luo-root — Workflows, Backend, Agent Infrastructure" />
</div>

<h3 align="center">用 Go，把复杂流程做成可靠系统。</h3>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=24&pause=1800&color=0284C7&center=true&vCenter=true&width=720&height=60&lines=Go+%C2%B7+Workflows+%C2%B7+Agent+Infrastructure;Readable+APIs.+Observable+execution." alt="Go · Workflows · Agent Infrastructure / Readable APIs. Observable execution." />
</div>

<p align="center">
  <a href="https://jiangnanstudio.cloud">博客</a> ·
  <a href="https://github.com/Luo-root?tab=repositories">开源项目</a> ·
  <a href="https://luo-root.github.io/pulse/">Pulse 文档</a>
</p>

<br/>

## 关于

我是 **Luo-root / 江南**，围绕 **Go、工作流与 Agent 基础设施** 构建开源软件。

我关心流程如何组合、执行如何被观察、程序中断后如何继续，也关心开发者能否用清楚的 API 把这些能力用起来。现在的工作主要落在 **工作流执行与检查点恢复**，并持续探索它们在 Agent 系统中的应用。

## 代表作品

### [Pulse](https://github.com/Luo-root/pulse) · 数据驱动的工作流执行库

把一组 Go 函数组合成可复用的工作流：节点声明需要和产生的数据，执行依赖由声明推导，输入到达后开始工作。

支持并行、分支与汇聚、子图组合、流式处理和执行观测。流程定义与单次执行分离，核心包仅依赖 Go 标准库，可以嵌入已有服务、命令行程序或 Agent 应用。

[源码](https://github.com/Luo-root/pulse) · [文档](https://luo-root.github.io/pulse/)

### [Pulse Durable](https://github.com/Luo-root/pulse-durable) · 检查点存储与恢复

为 Pulse 工作流提供检查点存储与恢复，让流程在中断后继续：复用已确认的节点成果，重新执行未确认的步骤。

项目当前处于开发阶段。

[源码](https://github.com/Luo-root/pulse-durable) · [文档](https://luo-root.github.io/pulse-durable/)

## 工程取向

- **API 要让人少写错。** 从真实使用场景出发，减少重复声明与隐式约定。
- **运行过程要看得清。** 让等待、执行、失败与取消都有明确的状态和原因。
- **承诺要有证据。** 用可复现的用例说明行为，用清晰的边界说明能力。

## 常用技术

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,ts,github,docker,kubernetes&theme=dark" alt="Go, TypeScript, GitHub, Docker, Kubernetes" />
</p>

## 开源足迹

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Luo-root&show_icons=true&hide_border=true&include_all_commits=true&bg_color=0f172a&title_color=38bdf8&icon_color=22d3ee&text_color=cbd5e1" />
        <img src="https://github-readme-stats.vercel.app/api?username=Luo-root&show_icons=true&hide_border=true&include_all_commits=true&bg_color=f8fafc&title_color=0369a1&icon_color=0891b2&text_color=0f172a" width="100%" alt="GitHub statistics for Luo-root" />
      </picture>
    </td>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Luo-root&hide_border=true&background=0f172a&stroke=1e293b&ring=38bdf8&fire=22d3ee&currStreakLabel=38bdf8&currStreakNum=f1f5f9&sideLabels=cbd5e1&dates=94a3b8" />
        <img src="https://streak-stats.demolab.com?user=Luo-root&hide_border=true&background=f8fafc&stroke=e2e8f0&ring=0284c7&fire=0891b2&currStreakLabel=0369a1&currStreakNum=0f172a&sideLabels=475569&dates=64748b" width="100%" alt="GitHub contribution streak for Luo-root" />
      </picture>
    </td>
  </tr>
</table>

<br/>

<div align="center">
  <a href="https://jiangnanstudio.cloud"><img src="https://img.shields.io/badge/BLOG-jiangnanstudio.cloud-0f172a?style=flat-square&logo=safari&logoColor=38bdf8" alt="personal blog" /></a>
  <a href="https://github.com/Luo-root"><img src="https://img.shields.io/badge/GITHUB-Luo--root-0f172a?style=flat-square&logo=github&logoColor=38bdf8" alt="Luo-root on GitHub" /></a>
  <a href="https://luo-root.github.io/pulse/"><img src="https://img.shields.io/badge/PULSE-DOCUMENTATION-0f172a?style=flat-square&logo=go&logoColor=38bdf8" alt="Pulse documentation" /></a>
</div>

<br/>

<div align="center">
  <samp>尽量少的设计，尽量准的工程。</samp>
</div>
