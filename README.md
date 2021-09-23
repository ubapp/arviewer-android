# arviewer-android
Android arviewer sdk

# Android ARViewer 임포트 가이드

## Overview

SDK 사용을 위한 가이드 문서로서 SDK 사용에 대한 전반적인 import 방법이 기술 되어 있습니다.

<br><br>

## Getting Started

ARViewer 는 Android 의 Sceneform 에 기반한 정적 라이브러리입니다.   
아래의 조건에서 정상적으로 동작합니다.   

* 필수 조건 (sdk 기능이 필수 기능으로 적용되는 경우)   
  * Android 24 이상 단말기   
  * Google Play AR Service 지원 단말기   
  * OpenGL 3.0 이상 지원 단말기   
  * com.google.ar.core meta-data : required
  * android.hardware.camera.ar feature : true

<br>

* 선택 조건 (sdk 기능이 필수 기능으로 적용되는 경우가 아닐 때)   
  * Android 18 이상 단말기
  * com.google.ar.core meta-data : optional
  * android.hardware.camera.ar feature : false

> 'SDK 를 사용하기 위해 Api Key 및 패키지명 인증을 거친 후 사용 가능 합니다.'

<br><br>
