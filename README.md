### 1. 로컬 프로젝트 폴더로 이동

```bash
cd C:/Users/new/Desktop/python/multi-news-agent
```

---

### 2. Git 초기화

프로젝트 폴더를 git 관리 대상으로 등록

```bash
git init
```

---

### 3. 파일 추가

모든 파일을 커밋할 준비.
.env 파일에 API KEY가 있으면, .gitignore 파일 추가 후 아래 단계 진행!

```bash
git add .
```

---

### 4. 첫 커밋 만들기

```bash
git commit -m "<Message>"
```

---

### 5. 원격 저장소 연결

GitHub에서 만든 새 repository의 주소를 연결

```bash
git remote add origin https://github.com/<yourname>/<your repository>
```

---

### 6. GitHub에 푸시!

```bash
git branch -M main
git push -u origin main
```

---

### `.gitignore` 설정 방법

```gitignore
# ============================
# Python 기본 설정
# ============================
__pycache__/
*.py[cod]
*$py.class

# ============================
# 가상환경
# ============================
venv/
env/
.venv/
multi-news-agent/

# ============================
# IDE / 편집기 관련
# ============================
.vscode/
.idea/
*.sublime-project
*.sublime-workspace

# ============================
# OS 기본 생성 파일
# ============================
.DS_Store
Thumbs.db

# ============================
# 환경 변수 파일
# ============================
.env
*.env

# ============================
# 로그 / 캐시 / 임시파일
# ============================
*.log
*.tmp
*.bak
*.swp
.cache/
dist/
build/
*.egg-info/

# ============================
# Jupyter 관련
# ============================
.ipynb_checkpoints/

# ============================
# LangChain / AI 관련 캐시
# ============================
.langchain/
outputs/
logs/
```


