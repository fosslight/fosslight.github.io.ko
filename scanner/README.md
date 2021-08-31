---
layout: page
title: FOSSLight Scanner
description: >
  Introduce the FOSSLight Scanner.
hide_description: true
sitemap: false
permalink: /scanner/
---

* toc
{:toc}

## Introduction

![](../assets/img/fosslight_scanner.jpg)

FOSSLight Scanner는 Open Source Compliance를 위한 분석 과정을 한번에 수행 가능한 툴입니다. 소스코드, 바이너리, 디펜던시에 대한 Open Source 분석을 수행하고, 저작권/License 표기 규칙 준수 여부를 체크할 수 있습니다.

## Features

<div class="flex-container">
  <div class="flex-contents">
    <div>
      <div id="feature_title">
        Inclusive Scanning
      </div>
      <div id="feature_img">
        <img src="https://img.icons8.com/dotty/80/000000/check-all.png"/>
      </div>
      <div id="feature_content">
        소스코드, 바이너리<br>그리고 디펜던시 분석까지<br>수행할 수 있습니다.
      </div>
    </div>
  </div>

  <div class="flex-contents">
    <div>
      <div id="feature_title">
        Integrated One
      </div>
      <div id="feature_img">
        <img src="https://img.icons8.com/wired/64/000000/workspace-one.png"/>
      </div>
      <div id="feature_content">
        하나로 통합된 패키지로<br>단 한줄의 명령어로<br>실행 가능합니다.
      </div>
    </div>
  </div>

  <div class="flex-contents">
    <div>
      <div id="feature_title">
        Independent Module
      </div>
      <div id="feature_img">
        <img src="https://img.icons8.com/dotty/80/000000/module.png"/>
      </div>
      <div id="feature_content">
        스캐너 모듈은 독립적으로,<br>가볍게 사용할 수 있습니다.
      </div>
    </div>
  </div>
</div>

## Description

FOSSLight Scanner 프로젝트는 다른 오픈 소스 프로젝트를 **상속**합니다.

- FOSSLight Source Scanner는 소스코드 스캔 작업을 위해 **[scancode-toolkit](https://github.com/nexB/scancode-toolkit)** 오픈 소스를 이용합니다.
- FOSSLight Dependency Scanner는 Package manager에 따라 다음 오픈소스를 이용하여 디펜던시 분석을 수행합니다.
  - NPM : **[NPM License Checker](https://github.com/davglass/license-checker)**
  - Pypi : **[pip-licenses](https://github.com/raimon49/pip-licenses)**
  - Gradle : **[License Gradle Plugin](https://github.com/hierynomus/license-gradle-plugin)**
  - Maven : **[license-maven-plugin](https://github.com/mojohaus/license-maven-plugin)**
  - Pub : **[flutter_oss_licenses](https://github.com/espresso3389/flutter_oss_licenses)**
  - Android(gradle) : **[android-dependency-scanning](https://github.com/fosslight/android-dependency-scanning)**

## Scanner Projects

- [**FOSSLight Source Scanner**](https://github.com/fosslight/fosslight_source_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_source_scanner/blob/main/LICENSE))
- [**FOSSLight Dependency Scanner**](https://github.com/fosslight/fosslight_dependency_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_dependency_scanner/blob/main/LICENSE))
- [**FOSSLight Reuse**](https://github.com/fosslight/fosslight_reuse) (License: [**GPL-3.0-only**](https://github.com/fosslight/fosslight_reuse/blob/main/LICENSE))

- 곧 release 예정 프로젝트 목록
  - FOSSLight Binary Scanner
  - FOSSLight Scanner

<br/>
<br/>
<div class="right"><a href="https://icons8.com/icon">&lt;Icons by Icons8&gt;</a></div>
