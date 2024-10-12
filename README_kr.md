# 📜 달의 모양 위젯

`달의 모양은`의 무료 버전 iOS 애플리케이션입니다.  
앱 스토어에서 확인하세요: [Moon Shape Widget](https://apps.apple.com/kr/app/moon-shape-widget/id1665266588?l=kr)

## ✨ 소개

`달의 모양 위젯`은 달의 위상을 보여주는 간단하고 직관적인 iOS 위젯입니다. 이 프로젝트는 SwiftUI를 사용하여 개발되었습니다. 핵심 기능인 잠금화면 위젯을 통해, 사용자가 달의 현재 상태를 손쉽게 확인할 수 있도록 도와줍니다.

## 📂 프로젝트 구조
```plain text
moonShapeWidget_Light/
├── moonShapeLight/
│   ├── ContentView.swift
│   ├── moonShapeLightApp.swift
│   ├── Assets.xcassets/
│   │   ├── Contents.json
│   │   ├── AccentColor.colorset/
│   │   │   └── Contents.json
│   │   └── AppIcon.appiconset/
│   │       └── Contents.json
│   ├── en.lproj/
│   │   ├── InfoPlist.strings
│   │   └── Localizable.strings
│   ├── ko.lproj/
│   │   ├── InfoPlist.strings
│   │   └── Localizable.strings
│   └── Preview Content/
│       └── Preview Assets.xcassets/
│           └── Contents.json
└── moonShpaeWidgetLight/
    ├── Info.plist
    ├── moonShpaeWidgetLight.swift
    ├── moonShpaeWidgetLightBundle.swift
    ├── moonShpaeWidgetLightLiveActivity.swift
    └── Assets.xcassets/
        ├── Contents.json
        ├── AccentColor.colorset/
        │   └── Contents.json
        ├── AppIcon.appiconset/
        │   └── Contents.json
        └── WidgetBackground.colorset/
            └── Contents.json
```
## 🌐 언어 지원(Localization)
프로젝트는 영어(`en.lproj`)와 한국어(`ko.lproj`)를 지원하도록 설정되어 있습니다. 필요한 경우 `Localizable.strings` 파일을 편집하여 번역을 추가하거나 수정할 수 있습니다.

## 🛡️ 라이선스