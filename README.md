# 러스트 프로그래밍 언어

"The Rust Programming Language" 2판의 한국 번역입니다.

[1판은 여기서 볼 수 있습니다][first].

[first]: https://www.penflip.com/sarojaba/rust-doc-korean

[영어 버전은 공식 홍페이지에서 볼 수 있습니다][english].

[english]: http://rust-lang.github.io/book

## 준비

책을 만들기 위해서는 v0.0.13 버전 이상의 [mdBook]가 필요합니다. 아래의 명령어를 입력하면
[mdBook]을 설치합니다.

```bash
$ cargo install mdbook
```

[mdBook]: https://github.com/azerupi/mdBook

## 빌드

책을 만들기 위해서, `first-edition`이나 `second-edition`로 `cd`를 사용하여 이동합니다. 그리고
아래의 명령어를 치면 됩니다.

```bash
$ mdbook build
```

결과물은 하위 폴더 `book` 안에 있습니다. 결과는 웹 브라우저에서 확인할 수 있습니다.

_Firefox:_
```bash
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_
```bash
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```

테스트하기 위해서 아래의 명령을 치면 됩니다.

```bash
$ mdbook test
```

## 기여하기

더 자세한 내용은 [CONTRIBUTING.md][contrib]을 봐주세요.

[contrib]: ./CONTRIBUTING.md

### 번역

[the frozen column]에 있는 챕터부터 번역합니다.

[the frozen column]: https://github.com/rust-lang/book/projects/1
