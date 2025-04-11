
---

# 💡 Git: 초기 설정 및 협업 안내  
_TouchDesigner 프로젝트를 위한 팀 협업 가이드_

---

## 🧩 Git 초기 설정

```bash
git config --global user.name "Velislava Kapran"
git config --global user.email "velislava@kapran.net"
git config --global color.ui auto
```

---

## 📁 터미널에서 폴더 열기 (Midnight Commander)

### mc 사용 방법:

```bash
mc  # 터미널에서 파일 탐색기 실행
```

### 단축키:
- `Ctrl + O` — 창 전환 (패널 열기/닫기)

### `mc` 설치:

- **Linux (Ubuntu/Debian):**
  ```bash
  sudo apt update
  sudo apt install mc
  ```

- **macOS:**
  ```bash
  brew install mc
  ```

- **Windows (WSL):**
  ```bash
  sudo apt install mc
  ```

---

## 🔗 프로젝트 클론하기

```bash
git clone ssh://프로젝트-주소
cd 프로젝트-폴더명
```

---

## 🌱 브랜치 만들고 작업하기

### 브랜치 생성 및 전환:

```bash
git checkout -b 브랜치이름
git push origin 브랜치이름
```

> 💡 각자 브랜치를 만들어서 작업해 주세요!

---

## ✏️ 변경사항 저장 (커밋)

1. 상태 확인:
```bash
git status
```

2. 변경사항 추가:
```bash
git add .
```

3. 커밋 작성:
```bash
git commit -m "무엇을 했는지 간단한 영어로 작성"
```

> ⚠️ 커밋하지 않으면 GitHub에 저장되지 않아요!

---

## 📤 작업 완료 후 main 브랜치에 병합하기

```bash
git checkout main              # main 브랜치로 전환
git pull origin main           # 최신 상태로 업데이트
git merge 브랜치이름            # 자신의 브랜치와 병합
git push origin main           # GitHub에 업로드
git checkout 브랜치이름         # 다시 자신의 브랜치로 전환
```

> 🗂️ 모든 이미지나 리소스는 `TouchDesign` 폴더에 저장해주세요.  
> 그러면 모두가 같은 구조로 작업할 수 있어요!

---


```bash
git config --global user.name "Velislava Kapran"
```
```
git config --global user.email "velislava@kapran.net"
```
```
git config color.ui auto
```

To open folders inside terminal:
``brew install mc

``mc - open folders inside terminal
``ctr+O close/open panel with folders


To connect for our project:
``` bash
git clone ssh(link)

```

For working with GIT

Your main line

```bash
git checkout -b NAME
git push origin NAME
```

After you changed file go to terminal and check git status, save changes and comment it

```bash
git status
git add .
git commit -m "something in english what u did"
```

Without comimit you can't save in GitHub
Everthing that we need for the project, like images, save in one folder "TouchDesign"
If everything that you did push your changes in main line, when you did it in our computers we will have same project with your, same images etc.

```bash
git checkout main          # перейти в ветку main
git pull origin main       # обновить main (если кто-то ещё менял её)
git merge Velislava-line  # слить изменения из своей ветки
git push origin main       # запушить обновлённую main
git checkout NAME         # Вернуться на свою ветку
```
