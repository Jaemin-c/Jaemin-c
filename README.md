# 👋 Hi, I'm Jaemin Chung

I'm a curious and persistent developer who loves building things and learning along the way.  
Currently focused on backend development, data engineering, and sharpening my problem-solving skills.

## 📚 Academic Projects
> 📌 **Note:** Due to university policies and academic integrity guidelines, the source code for course projects is not publicly available. 

> 📌 **안내:** 학교의 정책 및 학업 윤리 규정에 따라, 수업 프로젝트의 소스 코드는 공개하지 않습니다. 이 레포지토리에는 프로젝트 설명과 개인적인 회고만 포함되어 있습니다.

### EECS 497: Human-Centered Software and Design and Development (Capstone) (W2025)
**Description:** 사용자가 가진 스킬(Offered)과 배우고 싶은 스킬(Wanted)의 **교집합**으로 멘토·멘티를 매칭하는 스킬 교환/멘토링 웹앱

**주요 기능**
- **회원가입/로그인**: 스킬(Offered/Wanted) 등록, 스킬별 설명·카테고리 입력
- **Discover 추천**: 내 Wanted ↔ 상대 Offered 교집합 우선 노출, 카테고리/최소 평점 필터
- **Explore/검색**: 카테고리별 사용자 탐색, 키워드 검색(카테고리·바이오)
- **프로필/리뷰**: 스킬 설명, 별점·코멘트, 평균 평점 표시
- **메시지**: 1:1 채팅 및 인박스(최근 대화 목록)

**Languages/Technologies**
- Backend: Flask(Blueprints), Flask-Login, Flask-Bcrypt, SQLAlchemy ORM  
- Frontend: Jinja Templates, HTML/CSS/JS

**역할/기여**
- SQLAlchemy 기반 **데이터 모델링**(User, Skill, UserSkill, Review, Message)
- **추천 로직(Discover)** 및 카테고리/평점 필터링 구현
- **메시징 API/인박스**와 프로필 편집 흐름 구현에 기여
- 인증/세션 흐름 정리, 기본 보안(비밀번호 해시, 접근 보호) 적용

**데모/자료**
- 데모 영상: https://docs.google.com/document/d/1-0upy6Su_gEjm8MBUlSahS6GtrKJKgYRONeiVBdsMps/edit?tab=t.0
- 프로젝트 설명서: https://github.com/Jaemin-c/uni-project/blob/main/497/README-497.md

### EECS 489: Computer Networks (W2025)
[수업 프로제트 상세보기](https://github.com/Jaemin-c/uni-project/blob/main/489/README-489.md)
**Languages/Technologies:** C++, spdlog, cxxopts, pugixml, boost::regex, Mininet/POX  
**Project 2 -  Adaptive Video Streaming via CDN**
**Description:**  
구현한 HTTP Proxy(**miProxy**)와 **Load Balancer**를 통해 CDN 환경에서 **Adaptive Bitrate Streaming (ABR)**을 지원.  
프록시는 클라이언트의 세그먼트 수신 속도를 측정해 비트레이트를 동적으로 선택하며,  
로드 밸런서는 Round-Robin/Geographic 모드로 비디오 서버를 배정.  

**Algorithms / Focus:**  
- HTTP/1.1 파싱 및 manifest/segment 요청 가로채기  
- EWMA 기반 **throughput 추정** & 비트레이트 선택 규칙 (1.5× margin)  
- `select()` 기반 멀티플렉싱으로 다중 클라이언트 처리  
- 로드 밸런서 프로토콜 구현 (Round-Robin / Geographic Shortest Path)  


### EECS 281: Data Structures and Algorithms (자료 구조와 알고리즘) (F2024)
**Languages/Technologies:** C++
Undergraduate course covering essential data structures, algorithm design strategies, and complexity analysis for solving programming problems.
[수업 프로제트 상세보기](https://github.com/Jaemin-c/uni-project/blob/main/281/README-overview.md)

#### Projects Overview

| Project | Title | Language | Algorithms / Focus |
| --- | --- | --- | --- |
| **1** | Back to the Ship! | C++ | BFS, DFS, 3D Maze Navigation |
| **2A** | Stock Market Simulator | C++ | Priority Queue, Heap, Median Maintenance |
| **2B** | Priority Queue Implementations | C++ | Sorted Array, Binary Heap, Pairing Heap |
| **3** | 281Bank: Transaction System Simulator | C++ | File Parsing, Timestamp Comparison, Priority Queue, Fee Calculation, Session Tracking |
| **4** | Pokemon TSP | C++ | Minimum Spanning Tree (Prim), Greedy Insertion, Branch and Bound with Pruning |



### EECS 370: Intro to Computer Organization (F2024)
**Languages/Technologies:** C

### EECS 389: Practical Data Science (SS2025)


### EECS 484: Database Management Systems (W2025)









## 📫 Contact
- Email: [jaeminjaemin200@gmail.com]
- GitHub: [https://github.com/Jaemin-c](https://github.com/Jaemin-c)



<!--
**Jaemin-c/Jaemin-c** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
