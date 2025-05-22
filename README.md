# Git & Github

**git** 은 도구 **github**는 클라우드(저장소)
**git** 은 형상관리도구 = 분산형 버전관리도구

1. main 브랜치에서 choii 브랜치 내용을 합치기

```bash
git merge choii
```

2. choii 브랜치 삭제

```bash
git branch -D choii
```

3. choii 브랜치 생성

```bash
git branch choii
```

4. 초기화

```bash
git init
```

5. 모든 파일을 다

```bash
git add .
```

6. 상태 확인

```bash
git status
```

7. add 와 commit 둘다 한번에 !

```bash
git commit -am ""
```

```bash
git commit -m ""
```

```bash
git log
git log --oneline
```

8. 커밋의 기록만 삭제

```bash
git reset --soft
```

9. 커밋 + 내용 전부 삭제

```bash
git reset --hard
```

10. 브랜치를 새로 만들고 거기로 이동

```bash
git checkout -b `choii`
```

11. main 브랜치로 이동

```bash
git checkout `main`
git switch `main`
```

<hr>

git add .
git commit
git push origin `main`

~~<단축키>~~
`<ctrl> + <w>` : 해당 창 닫기
