# uim-byeoru script and NGS input setting file for Hangul new 3 beol layout compatible with Dvorak



 ## 설명

- 필자가 개발해서 사용하는 한글 글쇠배열을 우분투20.04, 민트20.1, 아치에서 사용하려고 uim-byeoru 스크립트를 수정함. 
- 윈도우용 날개셋 입력기 설정파일을 추가함.

> https://github.com/awfrok/HangulNew3onDvorak

![KeyboardLayout_HangulNew3onDvorak_v0.3.3.jpg](https://github.com/awfrok/HangulNew3onDvorak/raw/master/KeyboardLayout_HangulNew3onDvorak_v0.3.3.jpg?raw=true)

## 사용법 - uim, uim-byeoru

1. `uim` 과 `uim-byeoru` 를 설치한다.
2. `byeoru.scm` 과 `byeoru-custom.scm` 두 파일을 `/usr/local/share/uim` 으로 복사한다.
3. uim 메뉴에서 New3onDvorak를 선택할 수 있다.



## 사용법 - 날개셋입력기

1. 설정파일을 부른 후, 빠른설정에저 신세벌식을 고른다. (자음 연타와 복모음을 설정한다.)



## 주의

1. 우분투 20.04, 민트 20.1, 아치 i3wm 에서 사용할 수 있음을 확인하였음. 다른 배포판에서 확인하지 않았음.
2. 윈도우10 pro 영문판 64-bit, 날개셋입력기 10.2에서 만든 설정파일임.



 ## 수정한 부분 - uim, uim-byeoru

- `byeoru.scm`: line # 386-422 추가
- `byeoru-custom.scm`: line # 43-46 추가

> 깃허브 사용법을 익히면 fork와 branch를 이용하겠음.



## References

https://kldp.org/node/160815

https://kldp.org/node/161067



## License

open-source에 대해 아직 license 등을 어떻게 지정해야 하는지 몰라서 추후에 하겠다.



#### 감사의 말씀

나빌레라님이 2019년에 KLDP에 작성한 글을 보고 용기를 얻어서 uim의 scheme script를 분석하기로 하였고, 어느정도 성공한 듯 하다. 오히려 윈도우에서 사용하는 날개셋입력기보다 uim이 더 가볍게 작동하는 듯 느껴진다. 나빌레라님과 uim개발자에게 감사하다.



