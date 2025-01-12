---
title: 金丝雀部署
status: Completed
category: 概念
---

## 是什么

金丝雀部署是一种部署策略，开始时有两个环境：一个有实时流量，另一个包含没有实时流量的更新代码。
流量逐渐从应用程序的原始版本转移到更新版本。
它可以从移动 1% 的实时流量开始，然后是 10%，25%，以此类推，直到所有流量都通过更新的版本运行。
企业可以在生产中测试新版本的软件，获得反馈，诊断错误，并在必要时快速回滚到稳定版本。 

“金丝雀” 一词是指 “煤矿中的金丝雀” 的做法，即把金丝雀带入煤矿以保证矿工的安全。
如果出现无味的有害气体，鸟就会死亡，而矿工们知道他们必须迅速撤离。
同样，如果更新后的代码出了问题，现场交通就会被 "疏散" 回原来的版本。

## 解决的问题

无论测试策略多么彻底，在生产中总是会发现一些bug。
将100%的流量从一个应用程序的一个版本转移到另一个版本，可能会导致更有影响的失败。

## 如何帮助

金丝雀部署允许企业在将大量流量转移到新版本之前，查看新软件在真实世界场景中的表现。
这种策略使企业能够最大限度地减少停机时间，并在新部署出现问题时快速回滚。
它还允许更深入的生产应用测试，而不会对整个用户体验产生重大影响。
