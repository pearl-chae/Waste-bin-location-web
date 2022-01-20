# Waste bin Location guide 프로젝트 목적

● 요즘 기업에서 ESG(Environment, Society, Goverment) 환경 사회 지배구조를 일컫는 말로 투자의사 결정시 고려하도록 하는 핵심 요소입니다.

● Waste bin Location guide 프로젝트를 통해 많은 사람들이 환경보호에 쉽게 참여하게 되어 기업 환경 사회 긍정적 방향을 이끌어 낼 수 있습니다.

● 사람들이 길가에 쓰레기를 무단 투기하지 않게 하기 위해 쓰레기통 위치를 안내하도록 개발하였습니다.

● 쓰레기를 버릴 때 어떤 종류의 쓰레기인지, 쓰레기 분리수거 방법에 대해 헷갈릴 때가 많습니다. 쓰레기 사진을 업로드하면 쓰레기 종류와 분리수거 방법을 안내하여 올바른 분리수거를 할 수 있도록 안내하도록 개발하였습니다.

# WASTE BIN LOCATION GUIDE WEB (PC)

![Alt Text](https://github.com/pearl-chae/Waste-bin-location-web/blob/96ba79ca9540cb872dd219815d9a7af1651f7146/test/Waste%20bin%20Location%20guide%20PC.gif)

# HOME - 메인 페이지 (mobile)

● 메인 페이지는 Waste bin Location guide 홈페이지에 대해 간략한 소개 하였습니다.

![Alt Text](https://github.com/pearl-chae/Waste-bin-location-web/blob/0bbbfb974d6278969f51a083bba62fade51b2870/test/mobile_home.gif)

# WASTE BIN MAP - 쓰레기통 위치 안내 (mobile)

● 카카오 api, 서울시 구로구 가로쓰레기통 공공데이터 api를 활용하여 지도에 쓰레기통 위치를 마커와 세부주소 인포윈도우를 함께 표시하여 안내합니다.

![Alt Text](https://github.com/pearl-chae/Waste-bin-location-web/blob/0bbbfb974d6278969f51a083bba62fade51b2870/test/mobile_map.gif)

# WASTE SORTING - 쓰레기 종류 와 분리수거 방법 안내 (mobile)

● teachable machine을 통해 플라스틱,담배꽁초,캔,유리 등 쓰레기 이미지를 분류할 수 있도록 기계학습을 학습이 된 모델을 시작 버튼을 클릭하여 불러 옵니다. 이미지 업로드를 한 다음 예측 버튼을 눌러야 쓰레기 종류와 분리수거 방법에 대한 결과 값을 얻을 수 있습니다.

![Alt Text](https://github.com/pearl-chae/Waste-bin-location-web/blob/0bbbfb974d6278969f51a083bba62fade51b2870/test/mobile_sorting.gif)

# 프로젝트 배포 사이트

● https://wastebinlocationguide.netlify.app

● 반응형 웹(웹앱)으로 모바일,테블릿, PC 기기 어느 곳에서 다 사용가능합니다.

# 사용한 API

● Kakao map api (http://apis.map.kakao.com/)

● 서울 구로구가로휴지통 정보조회서비스 (https://www.data.go.kr/tcs/dss/selectFileDataDetailView.do?publicDataPk=15087773#tab-layer-openapi)

# 저작권, 라이선스 정보

● 아이콘

<a href="https://www.flaticon.com/kr/free-icons/" title="폐물 아이콘">폐물 icons created by Skyclick - Flaticon</a>
"https://www.flaticon.com/kr/free-icons/" title="폐물 아이콘"
폐물 icons created by Skyclick - Flaticon

● 홈페이지 배경화면

https://grafolio.naver.com/wallpaper/256918

Copyright © 폼실 All Rights Reserved.

● 홈페이지 템플릿

The MIT License (MIT)

Copyright (c) 2013-2021 Start Bootstrap LLC

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

● 쓰레기통 마커 이미지

https://cdn0.iconfinder.com/data/icons/small-n-flat/24/678095-trashcan-256.png

Attribution 3.0 Unported (CC BY 3.0)
You are free to:
Share — copy and redistribute the material in any medium or format
Adapt — remix, transform, and build upon the material
for any purpose, even commercially.
This license is acceptable for Free Cultural Works.
The licensor cannot revoke these freedoms as long as you follow the license terms.

● 이미지 업로드

Copyright (c) 2020 by Aaron Vanston (https://codepen.io/aaronvanston/pen/yNYOXR)
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

● teachable machine

Copyright [2022] [ChaeJinju]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# 제작자(EL)

● 채진주
