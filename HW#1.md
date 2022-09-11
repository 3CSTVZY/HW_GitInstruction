# Git instruction

## Basic commands

_git init – инициализация локального репозитория_

_git status – получить информацию от git о его текущем состоянии_

_git add – добавить файл или файлы к следующему коммиту_

_git commit -m “message” – создание коммита_

_git log – вывод на экран истории всех коммитов с их хеш-кодами_

_git status – получить информацию от git о его текущем состоянии_

_git checkout master – вернуться к актуальному состоянию и продолжить работу_

_git diff – увидеть разницу между текущим файлом и закоммиченным файлом_

## Description

Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development

## History

Git development began in April 2005, after many developers of the Linux kernel gave up access to BitKeeper, a proprietary source-control management (SCM) system that they had been using to maintain the project since 2002. The copyright holder of BitKeeper, Larry McVoy, had withdrawn free use of the product after claiming that Andrew Tridgell had created SourcePuller by reverse engineering the BitKeeper protocols. The same incident also spurred the creation of another version-control system, Mercurial.

Linus Torvalds wanted a distributed system that he could use like BitKeeper, but none of the available free systems met his needs. Torvalds cited an example of a source-control management system needing 30 seconds to apply a patch and update all associated metadata, and noted that this would not scale to the needs of Linux kernel development, where synchronizing with fellow maintainers could require 250 such actions at once. For his design criterion, he specified that patching should take no more than three seconds, and added three more goals:

- Take Concurrent Versions System (CVS) as an example of what not to do; if in doubt, make the exact opposite decision.
- Support a distributed, BitKeeper-like workflow.
- Include very strong safeguards against corruption, either accidental or malicious.

## Data structure

![image](gitstructure.png)

## Git for everyone

https://github.com/topics/social-network

# Links

## Tutorials

- Interactive tour of Git How To
- Pro Git tutorial

## Official sites

- Git home page
- Git page on kernel.org

## Interview

- Linus Torvalds on git
- Ten Years of Git: An Interview with the Founder - Linus Torvalds
- Linus Torvalds on Git - Linus Torvalds talk about git and other version control systems
- Randal Schwartz on Git
- Contributing with Git
