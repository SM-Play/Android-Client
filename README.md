# Android-Client
Smart Mirror android app

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Install List

- Android Studio `3.2.1`
- Java `1.8.0_181`
- Android SDK `4.4 Kitkat, CMAKE, NDK, LLDB` [Reference](http://hellogohn.com/post_one271)
- Android OpenCV `3.4.4`

### And coding style 

JAVA Language Rules
----------------------------

### Remark

모든 클래스, 메소드는 해당하는 소스의 상단에 클래스, 메소드에 대한 내용에 대한 주석을 단다

### JAVA Naming Conventions

CamelCase : 변수 이름중 새로운 단어가 시작될 때 맨 처음 알파벳은 대문자로 표기한다

Name|Conventions|examples
-----|----------|--------
class|대문자로 시작하고, 명사입니다|String, Color, Button...
interface|대문자로 시작하고, 형용사입니다|Runnable, Remote, ActionListener...
method|소문자로 시작하고, 동사입니다|actionPerformed(), main(), print, println()...
variable|클래스의 약어로 시작합니다|int형 : iCount, double형 : dRate...
Package|소문자로 시작합니다|java, lang, sql, util...
constant|대문자로 표시하며, 단어와 단어 사이에 '_'를 넣습니다|RED, MAX_PRORITY...

Github Commit Message Rule
--------------------------

    [State] : [File]

        [State] : [class/method/...]

            >>>[내용]


- State

    State|When
    -----|----
    Add|새로운 파일, 클래스, 메소드 등이 추가된 경우
    Fix|기존의 파일, 클래스, 메소드 등이 수정된 경우
    Remove|기존의 파일, 클래스, 메소드 등이 제거된 경우

- File

    해당되는 파일 이름

- [class/method/...]

    해당되는 클래스, 메소드 이름

- 내용(단순하게)

    State|설명
    ------|---------
    제거|제거하는 이유
    수정|수정한 부분에 대한 설명
    추가|해당 파일, 클래스, 메소드에 대한 내용

## Deployment

N/A

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details