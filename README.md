<div align=center>

![](/assets/images/tech_interview_main.png)

</div>

# Thunder-search-system

<div align=center>

[![author](https://img.shields.io/badge/author-jbee-ff69b4.svg?style=flat-square)](http://friendly-belief.surge.sh/)
[![CONTRIBUTORS](https://img.shields.io/badge/contributors-40-green.svg?style=flat-square)](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/blob/master/CONTRIBUTING.md)
[![LICENSE](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/blob/master/LICENSE)
[![HitCount](http://hits.dwyl.io/JaeYeopHan/Interview_Question_for_Beginner.svg)](http://hits.dwyl.io/JaeYeopHan/Interview_Question_for_Beginner)

<a href="https://github.com/JONGSKY/Thunder-search-system/graphs/contributors"><img src="https://opencollective.com/interview_question_for_beginner/contributors.svg?width=720"></a>

</div>

> contributer :pray:

</br>

## :memo: 개요
해당 프로젝트는 Elastic search와 cosine 유사도를 기반으로 한 특허 검색 프로그램 개발 프로젝트 입니다. 


</br>

</br>

## :memo: 기술

> example :thumbsup:

## :sparkles: 언어
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/5c058a388828bb5fde0bcafd4bc867b5bb3f26f3/topics/html/html.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/bootstrap/bootstrap.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/django/django.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png"></code>

</br>

## :sparkles: 기능

### :large_orange_diamond: patent-search
Patent Search에서는 검색어 입력을 통해 원하는 특허 정보 리스트를 출력 받을 수 있다.

#### 특허 검색

→ 해당 데이터가 존재하는 경우 : 관련 특허(데이터) 리스트를 출력 해준다.

→ 해당 데이터가 존재하는 경우 : 관련 특허(데이터)가 없다는 안내 페이지를 출력한다.

#### 검색 결과 화면

→ 특허마다 [특허 제목], [특허 등록 날짜], [특허 소속 국가], [특허 번호], [특허에 대한 간단한 요약(약 2줄 정도)], [read more 버튼]이 출력된다.

→ [read more 버튼]을 클릭하면 상기 내용과 함께, 구체적인 [특허 설명], [특허 category] [more 버튼]까지 출력된다.

→ [more]버튼을 누르면, 해당 특허 설명이 있는 google patents 페이지로 이동하게 된다.

### :large_orange_diamond: trademark-search
Trademark에서는 로고 이미지 업로드를 하여 검색 결과로 다음과 같은 결과물을 도출해준다.

#### Logo Search

→ 로고 이미지 간의 유사성을 계산하여 타겟 이미지와 비슷한 로고 이미지를 출력 해준다.

→ 로고 이미지의 [특허 번호], [이름]을 보여주고, 해당 특허 페이지와 연결해준다.

#### Image Search

→ 로고 이미지를 묘사할 수 있는 단어들을 표로 표현해준다.

→ 검색 결과를 CSV파일로 저장 가능하다.

## :sparkles: 실행
- docker db build
    - docker-compose up —build db
    - docker-compose up —build elasticsearch kibana logstash
    - docker-compose up —build web adminer
- docker web build 
    - docker-compose up --build web
    - docker-compose down -v

## :memo: 환경 및 버전
### Docker

- 모든 시스템은 Docker 컨테이너로 실행된다.

### Port

- db : 3306
- django : 8000
- elasticsearch : 9200
- kibana : 5601
- adminer : 8080

### 버전

- Django : 3.1.1
- ELK : 7.6.1


