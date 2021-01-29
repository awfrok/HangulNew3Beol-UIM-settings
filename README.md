작성: 2021.01.28.

# uim-byeoru script for Hangul new 3 beol type layout compatible with Dvorak



 ## 설명

필자가 개발해서 사용하는 한글 글쇠배열을 우분투20.04와 리눅스민트20.1에서 사용할 수 있도록 uim-byeoru 스크립트를 제작함.

> https://github.com/awfrok/HangulNew3onDvorak

![layout_HangulNew3onDvorak](https://user-images.githubusercontent.com/78065210/106119672-4fb8a400-610a-11eb-8ed2-8bb637b36941.jpg)

## 사용법

1. uim 과 uim-byeoru 를 설치한다.
2. byeoru.scm 과 byeoru-custom.scm 두 파일을 /usr/shard/uim 으로 복사한다.
3. uim 메뉴에서 New3onDvorak를 선택할 수 있다.



## 주의

리눅스의 다른 배포판에서 확인하지 않았음.



 ## 수정한 부분

- byeoru.scm: line # 390-482 추가
- byeoru-custom.scm: line # 44-46 추가

> 깃허브 사용법을 익히면 fork와 branch를 이용하겠음.



## References

https://kldp.org/node/160815

https://kldp.org/node/161067



## License

open-source에 대해 아직 license 등을 어떻게 지정해야 하는지 몰라서 추후에 하겠다.



#### 감사의 말씀

나빌레라님이 2019년에 KLDP에 작성한 글을 보고 용기를 얻어서 uim의 scheme script를 분석하기로 하였고, 어느정도 성공한 듯 하다. 오히려 윈도우에서 사용하는 날개셋입력기보다 uim이 더 가볍게 작동하는 듯 느껴진다. 나빌레라님과 uim개발자에게 감사하다.



