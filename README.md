# Math-Blog
- Description
a\&nbsp;a\
[개발환경]
- Windows: RubyInstaller (WITH DEVKIT 버전)
- VS Code (가장 추천): 무료, 마크다운 미리보기, Git 통합
- Windows: Git for Windows

[설치방법]
- https://rubyinstaller.org/downloads/ 접속
- Ruby+Devkit 3.0.x (x64) 버전 다운로드
1. 모든 기본 설정 그대로 두고 설치
2. MSYS2 설치 (자동으로 나타남)
3. 설치 완료 후 검은 창(Command Prompt)이 뜨면
  - 1, 2, 3을 차례로 입력하여 모든 구성요소 설치
4. PowerShell이나 Command Prompt를 열고:
  - ruby --version
  - gem --version

5. gem install bundler jekyll
6. jekyll new my-math-blog # or jekyll new . --force 
7. bundle exec jekyll serve

[추가 생성 파일]
- _includes/mathjax.html 파일 만들기 <??>
- _layouts/default.html 파일 만들기 <레이아웃 템플릿 (모든 페이지의 기본 구조)>

[블로그 포스트 생성 방법]
- _posts 폴더 안에 .md 파일로 작성

[확인하기]
- 기존 서버 종료 : Ctrl+C 
- 서버 재시작: bundle exec jekyll serve

[브라우저에서 확인]
http://localhost:4000 접속

[Terminal 명령어로 add and push 방법]
```git add .
git commit -m "Add MathJax support and first math post"
git push origin main
```
[Markdown basic 명령어]
```
# 제목
## 부제목
**굵게** *기울임*
[링크](URL)
![이미지](이미지URL)
```

