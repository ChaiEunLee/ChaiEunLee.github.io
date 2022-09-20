---
title: "[오류] vscode에서 C++ 사용하기"
excerpt: "compile error"

categories:
  - c++
tags:
  - [tag1, tag2]

permalink: /c++/c++-error-mac/

toc: true
toc_sticky: true

date: 2022-09-20
last_modified_at: 2022-09-20
---

## C++ Shell에서는 잘 돌아가는데 VSCode에서는 안 돌아간다     
(아마) C++ 컴파일을 지원하는 무언가를 해줬어야하는것 같다.
Terminal > Run and Build Task > C/C++ clang++ build activate file -> tasks.json이 생기는데 이걸 해주니까 해결됨    
     
## C++ Shell에서는 잘 돌아가는데 VSCode에서는 안 돌아간다      
> ld symbol(s) not found for architecture arm64 clang error linker command failed with exit code 1 vscode    
     
tasks.json에서 하단의 한줄을 .cpp로 변경해주니 해결     
```c++
"${fileD}”, 
//→ 
"${fileDirname}/*.cpp",
```
