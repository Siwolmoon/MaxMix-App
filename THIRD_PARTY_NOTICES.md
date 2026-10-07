# MaxMix 라이선스 및 구성 안내

Copyright (C) 2026 Siwolmoon. All rights reserved.
SPDX-License-Identifier: LicenseRef-MaxMix-Proprietary

MaxMix 0.2.0 이상은 독점 라이선스로 제공합니다. 공식 앱의 개인 및 내부 업무용 사용은
허용하며, 코드 재사용·수정·재배포에는 저작권자의 사전 서면 허가가 필요합니다.
전체 조건은 LICENSE에 있습니다. 이전에 공개된 버전에는 그 버전의 라이선스가 적용됩니다.

## 오디오 처리와 외부 장치

앱별 오디오 처리와 마이크 EQ는 MaxMix의 DSP 및 Apple Core Audio API를 사용합니다.
마이크 EQ는 사용자가 직접 선택한 출력장치로 전달합니다. 특정 외부 드라이버를 자동으로
선택하거나 설치하지 않습니다. 외부 드라이버의 소스·라이브러리·바이너리·설치 프로그램은
포함하지 않습니다. 사용자가 별도로 설치한 장치는 해당 공급자의 사용 조건을 따릅니다.

## 시스템 구성 요소

MaxMix는 macOS에 포함된 Apple 시스템 프레임워크와 런타임을 사용합니다.
해당 구성 요소는 Apple의 별도 조건을 따릅니다.
