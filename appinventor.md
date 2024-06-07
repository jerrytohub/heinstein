# 전체 교육 과정
* 인공지능과 앱 인벤터 이해하기
* 밝기 측정 앱 만들면서 앱 인벤터 기초 사용방법 알기
  *  LightSensor 사용하기
* 인공지능을 사용해서 얼굴 꾸미기 앱 만들기
  * MediaPipe 이해하기 
* FACE ID 잠금장치 앱 만들기
  * 머신러닝과 딥러닝 이해하기
  * 직접 얼굴을 학습 시키기
* 미세먼지 그래프 앱 만들기
  * 데이터 과학 이해하기
  * 데이터 시각화하기
  * 인공지능 윤리교육
* 앱 개발하기
* 개발한 앱 발표하기 

# 앱인벤터 시작하기
* 구글 아이디와 안드로이드 핸드폰이 필요합니다.
* 인터넷 브라우저에서 ```앱인벤터```를 검색합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/a22a1d0b-a774-4ff7-97ea-213b7b58e3d3)
* ```Create Apps!```를 클릭합니다.      
![image](https://github.com/itple-sw/appinventer/assets/76088532/9d388472-8c40-44b0-bbab-65652ad3a9c2)
* 구글 아이디로 로그인을 합니다.
* English에서 한국어로 바꿉니다.      
![image](https://github.com/itple-sw/appinventer/assets/76088532/3fdf1fcc-5f5b-4749-8426-e4dedd1837c5)   
![image](https://github.com/itple-sw/appinventer/assets/76088532/80c814fb-d0c2-43ea-9638-415631cd5ee9)
* ```새 프로젝트 시작하기```를 클릭합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/b726482e-3731-41c9-9977-df9a78df92d9)
* 프로젝트 이름을 정합니다. 프로젝트 이름을 정할 때 한글은 사용할 수 없습니다. 그리고 공백, 특수문자, 숫자로 시작하면 안 됩니다.

# 앱인벤터 사용법 알기
![image](https://github.com/itple-sw/appinventer/assets/76088532/f7340508-1003-4073-9423-1e9dd8c2b65f)
![image](https://github.com/itple-sw/appinventer/assets/76088532/f663f1c1-da00-4fac-8fee-2c39704f88c4)
* ```디자이너```에서 앱 UI를 꾸미고 ```블록```에서 코딩을 합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/2e8439aa-9024-4ec6-8425-abb457c921b7)
* 앱인벤터에서 컴포넌트를 잘 이해해야 합니다.
* 앱을 만들 때 필요한 부품(기능)이 컴포넌트입니다. 마치 레고 블록을 쌓듯이 필요한 컴포넌트를 추가해서 앱을 만듭니다.
* 컴포넌트를 뷰어에 드래그해서 사용합니다. 
  * 버튼과 같은 사용자 인터페이스, 레이아웃, 센서 등이 모두 컴포넌트입니다.
  * 컴포넌트는 보이는 컴포넌트와 보이지 않는 컴포넌트가 있습니다. 버튼는 보이는 컴포넌트이고 센서는 보이지 않는 컴포넌트입니다.
  * 사람의 키, 몸무게, 나이처럼 컴포넌트는 여러가지 속성이 있습니다.
* 미디어에 소리, 인공지능 모델 등 여러 파일을 업로드해서 사용합니다.   
![image](https://github.com/jerrytohub/heinstein/assets/127598703/59aaadcb-5dbe-4dc6-92b2-3497d81bd32d)
* 오른쪽 위에서 블록을 클릭합니다. 앱을 만들 때 필요한 블록이 있습니다.
  * 추가한 컴포넌트에 따라서 사용할 수 있는 블록이 달라집니다.

# 밝기 측정 앱 만들기
* LightSensor의 값에 따라서 모양과 메시지가 달라지는 앱입니다. 
![image](https://github.com/jerrytohub/heinstein/assets/127598703/c3f849a6-5fd0-406f-8866-80dbffbbab5f)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/56adfec8-fda8-45e7-978b-ef68a4bd0965)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/b6525a56-1694-4de1-b768-727e7d234c25)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/626d2690-062a-44a2-9670-feb973dcfb39)
* 컴포넌트의 이름을 잘 정해야 코딩할 때 편합니다.   
![image](https://github.com/jerrytohub/heinstein/assets/127598703/0afd8aa9-c97b-45fe-9963-0c639bd137db)
* 부모 요소에 맞추면 부모의 크기가 맞게 최대한 커집니다.
* Project Properties를 클릭해서 앱 제목을 바꿉니다.   
![image](https://github.com/jerrytohub/heinstein/assets/127598703/d962c910-efad-47a1-a6bf-84c0205773a7)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/4ad0167a-7193-420c-a2a4-cee18361d56f)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/1b991e56-9b43-448d-a8cc-a3e0ed2e4480)
* 코딩할 때는 컴포넌트를 선택하고 코딩합니다.
* 컴포넌트마다 사용할 수 있는 블록이 달라집니다.
* 키보드로 입력해서 원하는 블록을 찾을 수 있습니다.
![image](https://github.com/jerrytohub/heinstein/assets/127598703/a8477907-b4d5-4c17-be94-2e1762f2d477)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/ee6dc229-1e46-4db3-89bf-22de786b70c8)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/19d75d1a-423b-49fe-942d-bbeaf5cef1b8)
![image](https://github.com/jerrytohub/heinstein/assets/127598703/85816937-a7ae-4b2e-af6f-cb95db6140e4)
* 노트북과 스마트폰이 같은 와이파이를 사용하는 경우 AI 컴패니언을 사용해서 확인을 쉽게 할 수 있습니다.   
![image](https://github.com/jerrytohub/heinstein/assets/127598703/a3616094-e8a1-49b6-b932-4c6de49d80f3)
* 와이파이 사용이 어려운 경우 apk로 빌드하고 QR 코드를 찍어서 스마트폰에 앱을 설치할 수 있습니다.
* 무시하고 다운로드를 합니다.
* 무시하고 설치를 합니다.
* 세부 정보 더 보기를 선택합니다. 검사 없이 설치를 합니다.   
![image](https://github.com/jerrytohub/heinstein/assets/127598703/75cf9af9-7691-4c05-a264-792027993811)

# 인공지능을 사용해서 얼굴 꾸미기 앱 만들기
* FaceExtension을 사용해서 얼굴필터앱을 만들겠습니다.
* https://youtu.be/Or6lFyo3phU   
![image](https://github.com/itple-sw/appinventer/assets/76088532/68c8b573-a8ad-40ee-b64d-c34c81bba936)
* 얼굴을 인식하고 이마 양쪽에 귀 사진이 나오고, 코에 수염 사진이 나오도록 하겠습니다.
* 스마트폰의 운영체제나 기종에 따라서 작동하지 않을 수 있습니다.
* 프로젝트를 시작합니다. FaceMesh라고 이름을 정합니다.
* FaceMesh를 실행하려면 웹뷰어가 필요합니다.
* 캔버스를 사용하면 여러 가지 그림을 그릴 수 있고, 사진(이미지 스프라이트)를 움직일 수 있습니다.
* 웹뷰, 캔버스, FaceExtension의 크기가 같아야 얼굴을 쉽게 인식할 수 있습니다.
* https://github.com/mit-cml/yrtoolkit/tree/master/yr/images/facemesh/imageLibrary 에서 고양이 사진을 다운로드 받습니다.
* ```도움말 > 확장기능```을 클릭하고 Facemesh.aix 파일을 다운로드 받습니다. 확장기능 추가하기를 클릭하고 Facemesh.aix 파일을 import(가져오기)합니다. 파일을 가져오는데 시간이 걸립니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/c7a7edb8-528b-48e7-9b8d-61364d650302)
* 캔버스에 보이는 사진을 스마트폰에 저장합니다.
* Screen1 속성에서 수평정렬 가운데로 합니다.
* 그리기 & 애니메이션에서 캔버스 컴포넌트를 추가합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/5f13c688-7bb7-4f7a-abb6-07107cc375cd)
* 캔버스1의 높이와 너비를 350픽셀로 합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/0daea1dc-75b4-44e0-9caa-2acb90ac018f)
* 캔버스에 이미지스프라이트를 3개 추가합니다. 이름을 왼쪽귀, 오른쪽귀, 수염으로 정합니다.
![image](https://github.com/itple-sw/appinventer/assets/76088532/97859295-7429-46a1-b5e1-48c70e420bdd)
* 미디어에 고양이 사진을 업로드합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/a89016a3-f1bd-41ad-9746-62423497df50)
* 이미지스프라이트의 사진을 정합니다.
* 왼쪽귀와 오른쪽귀는 높이와 너비를 200픽셀로 합니다.
* 수염은 높이를 자동으로 하고 너비를 300픽셀로 합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/e6b1ee9b-7889-438f-9985-9ce9cd2542d6)
* 수평배치를 사용해서 가운데 정렬합니다. 사진찍기 버튼을 만듭니다. 이름을 사진찍기로 정합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/66624141-f6d9-4681-bc79-c11974086c67)   
![image](https://github.com/itple-sw/appinventer/assets/76088532/b9aac4a5-4de5-47e7-a277-72c97cf487eb)
* 웹뷰어를 가져옵니다. 속성을 바꿔서 보이지 않도록 합니다. 높이와 너비를 캔버스와 같게 350픽셀로 정합니다.
* 확장기능에서 FaceExtension을 추가합니다. 높이와 너비를 캔버스와 같게 350픽셀로 정합니다.  
![image](https://github.com/itple-sw/appinventer/assets/76088532/96168f1a-a05a-4b0d-97a4-8ae901052305)
* 추가한 웹뷰어를 선택합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/d41a7635-892a-4ee7-bc46-b24fe2debb1d)
* 미디어에서 음성변환 컴포넌트를 추가합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/9ef952f1-bc9a-4286-8dd0-2ede1671bfac)
* 사진을 찍을 때마다 다른 이름으로 저장하기 위해서 ```사진개수``` 변수를 만듭니다. 1로 정합니다. 사진을 찍을 때마다 1씩 커집니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/c6198fdd-73ba-497d-b8a2-dbdc8112cd4a)   
![image](https://github.com/itple-sw/appinventer/assets/76088532/db0233aa-ca0d-4be2-9fcf-4496f3191c26)
* 얼굴인식하고 좌표(위치)를 계산해서 이미지스프라이트의 좌표를 정합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/8153052e-9df7-42b5-93e1-c6b35834d58a)
* ```이미지 배치``` 함수는 이미지의 중심을 얼굴에 위치하도록 합니다.
* 이미지스프라이트는 왼쪽 위를 기준으로 좌표를 정합니다.
* 왼쪽귀는 얼굴좌표에서 이미지스프라이트의 가로 또는 세로의 반을 빼서 좌표를 정합니다.
* 인자를 추가해서 함수를 만들 수 있습니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/20b6ff55-5d16-497e-a8e3-0590b858c7d0)
* 블록 메뉴에서 모든 컴포넌트를 선택합니다. 여러 개의 같은 종류의 컴포넌트를 코딩할 때 사용합니다. 모든이미지스프라이트를 선택합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/d4661a83-6e15-422e-979f-0c7606f6a3d7)   
![image](https://github.com/itple-sw/appinventer/assets/76088532/a2c09d18-000e-4f2e-adfd-5b16c013290a)
* 정해진 좌표로 이동하는 함수를 만듭니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/9b54eafe-4c9f-4f2f-bb48-0a85b659f15e)
* 얼굴 크기에 따라서 이미지 크기가 바뀌는 함수를 만듭니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/305c3e69-f273-4b42-adef-58e3ea01e453)
* 얼굴을 인식하면 이미지가 얼굴을 따라가도록 합니다.   
![image](https://github.com/itple-sw/appinventer/assets/76088532/fbb2bc8a-9012-442e-83d6-3fd6ed8e8b32)
* 다른 버튼을 추가해서 귀와 수염 이미지가 바뀌도록 합니다.
