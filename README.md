![프로필 이미지](./증명사진2025.jpg)

README 파일이란?

이 곳은 저장소에 대한 설명을 작성합니다.

# 제목1

## 제목2

###### 제목6

일반 텍스트

# 가로줄 넣기

---

- - - - 

****

# 깃허브

- 원격저장소 만들기
    - origin 연결하기
    - push
3. origin 연결하기
4. push/pull
5. 협업하기

# 텍스트 꾸미기

**Github**는 *원격저장소*를 제공하~는 서비스이~기 ***때문이다.***

# 소스코드 입력

한줄짜리 소스코드는 `function add(x,y) { return x+y; };`처럼 사용
```Javascript
<script>
  let now = new Date();
</script>
```

# 링크 입력하기

<https://seungwonsong2.tistory.com/>
[하루하루 스터디 노트](https://doit-fwd.tistory.com/, "프런트엔드 개발 팁")



---
# 깃 기초
## 명령 연습
- pwd : 현재 위치 경로
- ls : 현재 디렉토리 내 파일,경로
  - ls -a : 숨긴 파일,디렉토리 표시
  - ls -l : 파일이나 디렉토리 상세정보 표시
  - ls -r : 정렬 순서 거꾸로
  - ls -t : 파일 작성 시간순 나열
- clear : 터미널 창 지우기(라샛)
- cd .. : 상위 디렉토리 이동
- cd ~ :  홈 디렉토리 이동
- mkdir (이름) : 디렉토리 생성
- rm -r (이름) : 디렉토리 삭제
- exit :  터미널 종료
## 빔 명령
- vim 이름.txt : 빔 문서 만들기
- A 혹은 I : 입력모드 상태로 변경
- [esc] : ex모드로 복귀
  - :w : 편집 문서 저장
  - :q : 편집기 종료
  - :wq : 저장 후 종료
  - :q! : 저장없이 종료
  - :wq 파일명 : 지정 파일로 저장
- cat 이름.txt : 문서 내용 확인

# 깃 버전 관리
## 깃 저장소
- git init : 현재 디렉토리에서 깃 사용하도록 초기화
  - .git 디렉토리가 생기며 내부에 스테이지와 저장소가 존재
- git status : 현재 깃 상태
- git add 파일.txt : 스테이징
- git commit -m "message" : 커밋 + 메시지 남기기
- git commit -am "message" : 스테이징 + 커밋 + 메시지 남기기
- git log : 커밋기록 확인
- git log --stat : 커밋 자세한 통계 확인
- git diff : 변경사항 확인
- git restore 이름.txt :  수정 사항 취소
- git restore --staged 이름.txt :  스테이징 되돌리기
- 
- 
