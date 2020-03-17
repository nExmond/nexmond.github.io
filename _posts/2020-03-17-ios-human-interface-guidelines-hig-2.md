---
layout: post
title: "iOS Human Interface Guidelines (HIG) 2"
description: "그렇다면 iOS의 테마를 실현하기 위해서는 어떤 것이 필요할까요?"
date: 2020-03-17T23:25:00+09:00
tags: [HIG, iOS, Essentials, UIKit]
comments: true
share: true
---

**[이전 포스팅](/ios-human-interface-guidelines-hig-2/)**에서는 iOS의 핵심을 언급했습니다.

그렇다면 iOS의 테마를 실현하기 위해서는 어떤 것이 필요할까요?

사용자에게 컨텐츠를 보여 주거나 사용자가 상호작용 할 수 있게끔 하는 무언가가 필요합니다.

그것은 바로 모두 잘 알고 계신 프레임워크, **UIKit**입니다.

대부분의 iOS 앱은 UIKit의 구성 요소로 만들어 집니다.

UIKit은 iOS 앱 공통의 인터페이스 요소를 정의하는 프레임워크입니다. 쉽게 말하면 앱과 사용자를 연결하는 역할을 하는 기능들을 모아 놓은 것이라고 할 수 있습니다.

UIKit을 구성하는 요소는 크게 세 가지 범주로 나눌 수 있습니다.

## 1. 바 (Bars)

주로 사용자가 앱을 여행하는 과정에서 현재 위치를 알려주는 역할을 수행합니다. 중요한 명령을 모아 놓기도 합니다.

UINavigationBar, UITabBar, UIToolbar, UISearchBar 가 있습니다.

## 2. 뷰 (Views)

텍스트, 그래픽 등 앱에 표시되는 기본 컨텐츠를 담는 영역입니다.

UIView, UIScrollView, UIStackView 등이 있습니다.

## 3. 컨트롤 (Controls)

사용자가 조작할 수 있는 뷰의 한 종류입니다. 컨트롤을 통해서 앱을 통제하는 느낌을 받습니다.

UIButton, UISwitch, UITextView, UISlider 등이 있습니다.

UIKit은 그 외에도 사용자가 위의 요소들과 상호작용 할 수 있도록 보조하는 여러 기능을 포함하고 있습니다.

뷰에 제스쳐 기능 부여 등, 기능을 쉽게 사용할 수 있습니다.

UIKit은 iOS를 이루는 프레임워크 중 하나일 뿐입니다. UIKit을 기반으로 제공되는 다른 프레임워크와 결합하여 탄탄한 앱을 제작할 수 있습니다.

---

스토리보드 기반으로 화면을 구성하다 보면, 여러 인터페이스 구성 요소를 살펴볼 수 있습니다. 

UI 구성요소들을 자연스럽게 사용하고는 있었지만, 어떤 기준으로 분류되어 있는 지 까지는 알지 못했습니다.

저만의 기준으로 분류를 하다보니 적재적소에 사용하지 못할 때가 있었는데, 이제는 명확한 목적을 가지고 사용할 수 있을 것 같습니다.

**참고**: [Human Interface Guidelines: iOS](https://developer.apple.com/design/human-interface-guidelines/ios/overview/interface-essentials/)