# GIT 개념 잡기
## git <br>
소스코드 관리 프로그램 (저장소가 아님)<br>
용도: 소스코드를 날리는 경우 방지, 소스코드의 변경점을 기록하기 위함<br>
컴퓨터 내 폴더를 Local Repository로 만들 수 있음 <br>
또한 github (Remote Repository)에 소스코드를 push할 수 있다. <br>
<br>

# 문서 or 소스코드를 저장하는 두 가지 금고
내 컴퓨터 저장소: Local Repository  <br>

원격지 저장소: Remote Repository  <br>
> 외부에 있는 더 안전한 금고

## Add
파일의 변경이나 추가 시 Staging Area에 변경사항이 저장 된다. <br>
Commit 하기 전 특정 파일을 ignore 할지 선택하는 등 유저가 Commit할지 여부 선택함

## Commit 
git을 이용하여 내 소스코드를 'Local Repository'에 저장하는 명령 <br>

## push
git을 이용하여 내 소스코드를 'Remote Repository'에 보내는 명령어 <br>

## 정리

> 개발자들은 본인의 소스코드를 local repository에 commit 후, Commit된 소스코드를 모아서 remote repository에 push 한다.

<br>

# Remote Repository와 관련한 여러 용어

## Clone
Remote Repository의 오픈소스나 팀 공개 소스코드 등을 복제하여 내 Local Repository에 가져오는 과정 <br>

## Pull
Remote Repository의 최신 업데이트를 확인 후 기존 Local repository에 합치는 과정

## Fetch
Remote Repository의 최신 업데이트를 다운로드 후 확인만 함 (적용X)

## Merge
Fetch로 확인한 업데이트를 내 Local repository에 합침
<br>
<br>

# 기타 용어
## Factor 
password나 홍채 인식과 같은 보안 인증 방식을 뜻함 <br>여러 팩터를 사용할 시 Two-Factor, Multi-Factor 등으로 칭함 

## Ignore 
커밋을 원하지 않는 파일을 커밋 대상에서 제외시킴 <br>
메모장 .git을 만든 후 커밋 원하지 않은 파일명을 쓰거나 github desktop 내 기능 이용.
