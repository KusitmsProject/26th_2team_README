### 📑 서비스 소개

### 

# _Bring_

상기 이미지는 프로젝트 대표 이미지로, (선택) 사항에 해당합니다.
### 📑 팀명 : 🌼 스물여섯, 스물하나 🌼
#### R&R
|분야|이름|포지션|
|:------:|:---:|:---------:|
|기획|윤지원|😻서비스 기획, 사업 파트 담당|
|기획|최윤아|😻서비스 기획, 리서치 담당|
|디자인|나태진|✒️프로토타입, 서비스 디자인 담당|
|개발|박영민|💻서버, 개발리더 담당|
|개발|김다형|💻iOS 개발 담당|
|개발|오예진|💻PM, iOS 개발 담당|
|개발|이정민|💻 서버 개발 담당|


### 📑 목적 및 필요성 :

### 📑 기술 스택
#### 💻 BackEnd
![Java](https://img.shields.io/badge/Java-3776AB?style=flat-square&logo=mysql&logoColor=white)
![Springboot](https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=IntelliJ%20IDEA&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-%23ED8B00.svg?style=flat-square&logo=jpa&logoColor=white)
![mysql](https://img.shields.io/badge/Mysql-4479A1?style=flat-square&logo=mysql&logoColor=white)
![RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=flat-square&logo=Amazon%20RDS&logoColor=white)
![S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=Amazon%20S3&logoColor=white)
![docker](https://img.shields.io/badge/docker-007396?style=flat-square&logo=docker&logoColor=white)
![gradle](https://img.shields.io/badge/gradle-02303A?style=flat-square&logo=gradle&logoColor=white)


#### 💻 FrontEnd
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=Swift&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB.svg?style=flat-square&logo=Xcode&logoColor=white)
#### 📡 배포
<img src="https://img.shields.io/badge/AWS EC2-232F3E?style=flat-square&logo=amazon%20aws&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=Jenkins&logoColor=white"/></a>
#### 👨‍👩‍👧‍👦 협업툴
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat-square&logo=github&logoColor=white)
<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/></a>
#### 🎨 Design
![Figma](https://img.shields.io/badge/Figma-F24E1E.svg?style=flat-square&logo=Figma&logoColor=white)
![Adobe Illustrator](https://img.shields.io/badge/AdobeIllustrator-FF9A00.svg?style=flat-square&logo=AdobeIllustrator&logoColor=white)


#### 📌 기술 스택 선정 이유
- Back
    - Docker와 Jenkins를 이용해 Springboot CI/CD를 자동화하였습니다.
    - Github Webhook을 이용해 push시 서버 배포까지 자동화하였습니다.
    - AWS EC2, RDS, S3를 이용해 서버, DB, 객체를 클라우드로 24시간 관리/배포가 가능하도록 하였습니다.
    - aQuerytool을 사용해 DB 아키텍처 설계 후 개발을 진행할 예정입니다.
    - Github를 통해 버전관리와 분산관리를 진행할 예정입니다.
- Front
    - 사용성을 고려하여 iOS 기반 어플리케이션 개발을 정했습니다.
    - API 통신을 위해서는 URLSession, URLRequest를 사용하고 추가적으로 Alamofire 라이브러리를 통해 구현할 예정입니다.
    - 빠르고 효율적인 개발을 위해 MVC 패턴을 적용할 예정입니다.
- Design
    - 백터이미지를 활용한 도형의 응용을 위해 Adobe Illustrator를 활용하여 로고와 이미지를 제작하였습니다.
    - 자세한 화면정의가 가능하고 협업이 용이한 figma를 사용하였습니다.
    - Blender를 활용하여 3d 디자인을 제작할 예정입니다.

### 📑 커밋 컨벤션
#### 📌 Branch
- "main"에는 배포 했을 시에만(서버 연동), 모든 PR & Merge는 "develop" 에서 이루어진다.
- "yejin" 등 자신의 이름의 브랜치를 따 개인 작업 진행 -> "develop" 브랜치로 PR
- “develop” → "main" 의 Merge 작업은 한 사람이 진행한다.

#### 📌 Commit message
- "[기능] 제목 - 부연설명" 형식으로 이루어진다.
- “[기능] 제목” → 필수
- "- 부연설명" → 선택
- 15자 이상 X

#### 📌 [기능]
- FEAT : 새로운 기능의 추가
- ADD : 단순 코드 추가
- FIX: 버그 수정
- DOCS: 문서 수정
- STYLE: 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)
- REFACTOR: 코드 리펙토링
- TEST: 테스트 코트, 리펙토링 테스트 코드 추가
- CHORE: 빌드 업무 수정, 패키지 매니저 수정(ex .gitignore 수정 같은 경우)


### 📑 소프트웨어 아키텍처

### 📑 주요 기능 명세서
