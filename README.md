# Customizing Wiki using GPT
1. gpt_for_study.py
  - function as a module
  - functions : generate_chapter / generate_outline / generate_handbook / gpt_for_book
  - 주제와 제작 대상에 맞게 스터디에 필요한 자료를 생성하는 함수
2. app.py
  - 앞서 제작한 함수를 기반으로 app 실행하는 스크립트
3. index.html
  - 파라미터를 입력할 수 있는 창
4. result.html
  - 입력한 결과가 나오는 창
  - python 상의 변수를 html로 가져와 생성
5. style.css
  - html에 반영할 스타일 생성 스크립트
