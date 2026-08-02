# README

## 프로젝트 개요(미션 목표 요약)

## 터미널 조작 로그
1. 폴더 (생성/이동/삭제)
        hauteville18620603@c3r1s2 repository-for-evaluation-m1 % git init


2. 파일 (생성/이동/삭제)

## Docker 운영 및 검증 로그
    1. 설치 점검 결과
        (1) docker --version
        (2) docker info
    2. 운영 명령 실행
        (1) docker images
        (2) docker ps -a
        (3) docker logs
        (4) docker stats 

## 트러블슈팅 2건 이상(문제 → 원인 가설 → 확인 → 해결/대안)
기술 문서만 읽어도 전체 수행 내용을 파악할 수 있어야 한다.

---
# 터미널 기본명령어 
### 파일의 현재 위치
```bash
% pwd
/Users/hauteville18620603/Desktop/eval
```
### 파일 생성
```bash
% touch 파일
% ls -al 파일 
-rw-r--r--  1 hauteville18620603  hauteville18620603  0  8  2 16:07 파일
```

### 폴더 생성
```bash
% mkdir 폴더
% ls -ald 폴더
drwxr-xr-x  2 hauteville18620603  hauteville18620603  64  8  2 16:08 폴더
```
### 파일 & 폴더 이동
```bash
% mv 파일 폴더/
% cd 폴더
% ls          
파일
```
### 파일 & 폴더 삭제
```bash
% rm 파일
% ls -al
total 0
drwxr-xr-x  2 hauteville18620603  hauteville18620603   64  8  2 16:14 .
drwxr-xr-x  5 hauteville18620603  hauteville18620603  160  8  2 16:11 ..

% rm -r 폴더
% ls -al
total 8
drwxr-xr-x   4 hauteville18620603  hauteville18620603  128  8  2 16:18 .
drwx------+  8 hauteville18620603  hauteville18620603  256  8  2 16:02 ..
drwxr-xr-x  12 hauteville18620603  hauteville18620603  384  8  2 16:02 .git
-rw-r--r--   1 hauteville18620603  hauteville18620603  640  8  2 16:02 README.md
```
# 파일 & 폴더 권한 변경
### 권한 개념 
```
-                    ---        --- ---
파일 속성(폴더/파일/링크) 사용자       그룸 그외?
                     2^22^12^0
ex>권한 예시
drwxr-xr-x 
-rw-r--r-- 
 
```
### 파일 권한 변경
```bash

```
### 폴더 권한 변경
```bash

```
