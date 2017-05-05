# 2016년 여름: Ansible로 살펴보는 Automated Configuration Management

*****************************************************************

* 이 저장소는 OpenStack 자동 배포와 관련된 여러 구성 관리 도구 중
  Ansible을 스터디한 자료를 모아둔 곳입니다.
* This repository data is for studying Ansible to broaden the
  knowledge on automated OpenStack deployment.

*****************************************************************

* 본 스터디는 NAVER D2 개발자 지원 프로그램과 함께 하였습니다.
 * 커뮤니티 지원: http://developer.naver.com/wiki/pages/communityStatus
 * NAVER D2 공식 홈페이지: http://d2.naver.com/

## 스터디 개요 (Overview)

* 스터디 주제 : Studying __Ansible__

  * 책 :
    * 다니엘 홀 지음, 김용환 옮김, "Ansible 설정 관리", 에이콘출판사, 2015.

  * 진행 방식 :
    * 모두 책 읽어보기
    * 주 단위로 1명씩 돌아가면서 책 1장에 대한 전체적인 진행을 맡음
     (단, 양이 많은 장은 절반 등으로 나누어 진행)
    * 서로 긍정적인 피드백 및 토론하기

  * 내용
    * [1장: 앤시블 시작](Chap1/Ansible\ Configuration\ Management_chat1.md)
    * [2장: 간단한 플레이북](Chap2/Ansible\ Configuration\ Management_chat2_Simple_Playbooks.md)
    * 3장: 플레이북 심화 내용
      * [ansible.cfg - 설정 파일](Chap3-peter/ansible.cfg)
        * inventory 내용을 git clone 후 이동한 폴더로 변경 필요
      * [apt-loop.yml - Debian/Redhat 구분 실행 파일](Chap3-peter/apt-loop.yml)
      * [demo-commands.txt - 실습 명령어 모음](Chap3-peter/demo-commands.txt)
      * [hosts - 실습 대상 호스트](Chap3-peter/hosts)
        * 연결 가능한 Debian 2대, Redhat 1대를 준비하여 해당 IP 주소로 적절히 변경 필요
    * [4장: 대규모 프로젝트](Chap4/Chapter4_Large_Project.md)
    * [5장: 사용자 정의 모듈](Chap5/Chapter5_Custom_Modules.md)

  * 스터디 진행
    * 2016-08-09: 1장 앞 부분
    * 2016-08-18: 1장 뒷 부분
    * 2016-08-23: 2장
    * 2016-08-29: 3장 앞 부분
    * 2016-09-06: 3장 뒷 부분
    * 2016-09-20: 3장 뒷 부분 추가
    * 2016-09-30: 4장
    * 2016-10-04: 5장


## 참고 자료 (Reference)

* Ansible, Getting Started
  * http://docs.ansible.com/ansible/intro_getting_started.html

* Ansible의 이해와 활용, DEVIEW 2014
  * http://www.slideshare.net/deview/1a7ansible

* 네떡지기, Automation for Networker[2] - Ansible : Part 1 ~ 7
  * Part 1: http://zigispace.net/800
  * Part 2: http://zigispace.net/809
  * Part 3: http://zigispace.net/836
  * Part 4: http://zigispace.net/840
  * Part 5: http://zigispace.net/846
  * Part 6: http://zigispace.net/849
  * Part 7: http://zigispace.net/850
