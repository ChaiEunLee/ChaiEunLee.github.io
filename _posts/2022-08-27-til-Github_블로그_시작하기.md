---
title: "[Github] Github 블로그 시작하기"
excerpt: "Start"

categories:
  - til
tags:
  - [tag1, tag2]

permalink: /til/githubstart/

toc: true
toc_sticky: true

date: 2022-08-27
last_modified_at: 2022-09-23
---

## 깃허브 블로그 시작   
여러가지 오류를 겪으며 우여곡절 끝에 블로그 완성했다.   
원래 자잘한 오류들이 가장 화나는 법. 블로그를 만들면서 마주했던 오류들을 정리해보았다.   

# 1. github token 사용   
   
2021년 중반부터 인증에 token이 사용될 것이라는 github의 공지가 떴다.   
2021년 중반 이전에 작성된 블로그들을 보면서 만들고 있었기에 예상치 못한 오류였다.   
**해결방법**   
 github 홈페이지에서 token 만들기 (참고한 링크 : )   
   
# 2. Not empty Error   
    
 **해결방법**   
 github.io에 아무것도 없어야함. readme도 지우고 다시 실행 후 해결   
    
# 3. Error: Please append '--trace' to the 'serve' command #8710   
**해결방법**   
하단의 명령어 추가 후 재진행   
```bash
$ bundle add webrick
```
   
# 4. 테마 적용 안 됨.   
**해결방법**   
config.yml 파일에서 theme 앞에 # 붙여서 빼고 remote_theme은 살림.   
   
# 5. css만 반영 안 됨.   
**해결방법**   
   
# 6. main page에서 sidebar가 나오지 않는 오류   
기다리니까 나옴.     

# 7. 미해결 오류    
메인 페이지에 사진이 나오지 않음.    



