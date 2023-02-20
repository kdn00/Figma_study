# Figma_study
### 모바일 작업 단위
---
- 모바일은 가이드라인을 만들 때 8의 배수로 작업하면 좋다.

### 단축키
---
![필수 단축키](https://user-images.githubusercontent.com/89984853/219985330-2938155f-158b-4d0d-938d-91192c48ae84.png)

### 1. 설치 및 인터페이스
---
- 전체적인 툴의 구성은 한 번 들어보면 좋음 [참고 강의](https://ossam5.tistory.com/267)

### 2. Frame/Guide/Grid
---
- 최근 웹 디자인에 호환되는 규격 : Frame → Presentation탭의 Slide 16:9(1920*1080)
- Shift + R로 눈금자 생성(눈금자에서 커서를 끌어오면 가이드선을 쓸 수 있다.)
- Design탭에서 Layout grid 추가 : Grid, Columns, Row 기능으로 균일한 위치를 잡기 좋음
#### Grid
![image](https://user-images.githubusercontent.com/89984853/219985674-97767691-4510-4cf2-8657-35a6e79f0b51.png)
#### Colums
![image](https://user-images.githubusercontent.com/89984853/219985654-06bb93c0-2a3d-4cdf-9c17-d2b6d33cd491.png)
#### Row
![image](https://user-images.githubusercontent.com/89984853/219985724-ea2f008f-3ac5-46e3-89a2-7d8500a92a86.png)

### 3. 도형툴
---
- 선을 면으로 처리(정렬할 때) : 선을 오른쪽 클릭한 후 Outline Stroke 옵션을 클릭한다.
- 메인 컬러(주로 쓰는 스타일)는 Fill의 Styles에 따로 저장해서 쓰면 편하다.   
![image](https://user-images.githubusercontent.com/89984853/219992639-371e201e-3b46-439e-bf9b-2bc2dcc657e7.png)

### 컴포넌트
---
- 재사용 가능한 디자인을 등록해서 사용하는 것   

**Master component**
- 웹 디자인에 필요한(자주 쓰는) 도형, 아이콘 등을 미리 만들어 페이지에 둘 수 있다.(복사 붙여넣기 기능으로 편하게 사용할 수 있음)
- 주로 헤더와 푸터, 레이아웃 템플릿, 자주 쓰이는 UI 요소(검색, 사이드바 등)를 만들어 놓는다.
- [참고 사이트](https://yozm.wishket.com/magazine/detail/1187/)
- [참고 강의](https://www.youtube.com/watch?v=Z1mapqjOIEA&list=PLdwQP35_Nz9eMN9K82jNFBJ4xqJUMoXm8&index=12)
   
**Detach Instance**
- 인스턴스를 컴포넌트로부터 불리시키는 기능

**컴포넌트 안의 컴포넌트**
- 컴포넌트를 또다시 컴포넌트로 등록이 가능함
- 컴포넌트를 더욱 재사용하게 해주는 기능이다.
- 컴포넌트를 만들면 왼쪽의 Assets탭에서 끌어오기로 사용할 수 있다.   
![image](https://user-images.githubusercontent.com/89984853/220018417-ea88ef92-44dd-458c-809a-bba35419f8bb.png)
 
- 같은 프레임 안에 컴포넌트를 지정해놓으면, 해당 컴포넌트를 더블클릭하여 변경할 수 있다.   
![image](https://user-images.githubusercontent.com/89984853/220021316-2a989bdf-0f53-4830-bd8c-5ededd918171.png)

### 인스턴스
---
- 컴포넌트로 등록한 것을 복제해서 재사용하는 것

### Auto Layout과 Constraints
---
**Auto Layout의 기능**
- Padding : 여러 개의 컨텐츠가 있는 경우 뒤의 기본이 되는 컨텐츠와 앞쪽 컨텐츠와의 패딩 간격을 동일하게 조절할 수 있다.
- Space between : 기본이 되는 도형 위에 여러 개의 컨텐츠가 있는 경우 간격을 자동으로 맞춰주는 기능으로, 오브젝트의 방향에 따라 레이어패널의 아이콘이 다르게 보인다.
- Resizing : Resizing을 Fill Container로 변경하면 된다. 예전에는 컴포넌트 추가 후 오토레이아웃을 해야 가능했으나, 최근에는 기능이 변경되어 그냥도 가능하다.
   
**Constraints** --> 중요!!!!
- 부모요소[근간요소]를 기준으로 자손요소[위쪽요소]의 위치를 어디로 맞출지 지정
- Auto Layout에도 있고, 컴포넌트로 만들어도 되는 기능이다.
- 반응형 웹에서도 유용하게 사용하는 기능
- 프레임 자체도 근간으로 사용해서 위의 오브젝트들을 컨트롤할 수 있다.

**Absolute position**
- 유료 기능 같음
- 개체를 자동 레이아웃 프레임에 유지하면서 자동 레이아웃 흐름에서 제외

### Variants
---
- 2개 이상의 컴포넌트를 선택하면 Varients 버튼이 활성화된다.
- 
