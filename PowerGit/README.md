#  PowerGit 0.1.0

Author: PowerGit

A PowerShell module to wrap common Git commands into PowerShell syntax for ease of use

## Introduction

Introduction Text

## Getting Started

``` PowerShell
Import-Module .\PowerGit\PowerGit.psd1
Get-Command -Module PowerGit
```

### Get-PowerGitCommitStatistics

Enumerates the child items of a location and invokes  git status on each item

```PowerShell
PS C:\Dev\Github\PowerGit> Get-PowerGitCommitStatistic

Location                Author       Commits
--------                ------       -------
C:\Dev\Github\PowerGit  Mark Warneke      1
```

### Get-PowerGitStatus

Enumerates the child items of a location and invokes  git status on each item

```PowerShell
PS C:\Dev\Github\PowerGit> Get-PowerGitStatus

Location               Status
--------               ------
C:\Dev\Github\PowerGit {On branch master, Your branch is up to date with 'origin/master'., , Changes not staged for commit:...}
```

## Build and Test

Run tests from folder ```.\PowerGit\Test```

``` PowerShell
Invoke-Pester .\PowerGit\Test
```
