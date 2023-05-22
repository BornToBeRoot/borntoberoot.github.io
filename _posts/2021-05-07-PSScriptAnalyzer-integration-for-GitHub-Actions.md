---
title: PSScriptAnalyzer integration for GitHub Actions
tags: [GitHub Actions, PowerShell, PSScriptAnalyzer, CI/CD]
style: 
color: 
description: PSScriptAnalyzer integration for GitHub Actions
---
[PSScriptAnalyzer](https://github.com/PowerShell/PSScriptAnalyzer) is a static code checker for PowerShell modules and scripts. PSScriptAnalyzer helps you maintain a minimum code quality standard by running a set of rules. Combined with GitHub Actions, you can automatically check your PowerShell code on every commit or pull request. 

To get started, you can use this template: [GitHub-Actions_PSScriptAnalyzer](https://github.com/BornToBeRoot/GitHub-Actions_PSScriptAnalyzer)

```
git clone https://github.com/BornToBeRoot/GitHub-Actions_PSScriptAnalyzer PROJEKTNAME
cd PROJEKTNAME
git remote set-url origin https://github.com/USERNAME/PROJEKTNAME
git remote -v
git push
```
