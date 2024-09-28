[![CodeFactor](https://www.codefactor.io/repository/github/XerosLab/XCryptor/badge)](https://www.codefactor.io/repository/github/XerosLab/XCryptor)
# XCryptor
Simple is best, XCryptor는 일반인도 금방 사용가능한 파일 암/복호화 소프트웨어입니다.

AES 암호화 알고리즘을 이용한 밀리터리 등급 암호화로, 안전하게 파일을 암호화할 수 있습니다.

모든 포맷(확장자)의 파일 암/복호화를 지원합니다. 

Windows, macOS, Linux/UNIX 운영체제를 모두 지원합니다.



<center>XCrypt를 이용한 파일 암호화</center>

<img src="https://xeroslab.github.io/assets/uploads/img-3.gif">

<center>XCryptor를 이용한 파일 복호화</center>

<img src="https://xeroslab.github.io/assets/uploads/img-4.gif">

## Usage

XCryptor는 단독으로 실행할 수 없습니다.
모든 사용은 반드시 각 OS별 명령 프롬프트 (터미널)을 이용하여 인자값을 사용하여 실행하여야합니다.

Options

- --input, -i 암/복호화할 대상 파일의 경로를 인자로 추가합니다. (필수 옵션)
- --output, -o 암/복호화 후 새로 생성될 파일의 경로를 인자로 추가합니다. (선택 옵션)
- --encrypt, -e 암호화 모드 (추가 옵션, 기본값)
- --decrypt, -d 복호화 모드 (추가 옵션)
  -e 혹은 -d 옵션이 별도로 지정되지 않았을 경우에는 -e 옵션이 기본값으로 선택됩니다.
- --remove, -r 암/복호화 완료 이후 원본 파일 삭제 (추가 옵션)
- --version, -v 프로그램 버전 정보를 출력합니다. (개별 명령어)
- --help, -h 프로그램의 사용법 정보를 출력합니다. (개별 명령어)

Mac / Windows /Linux

암호화 실행 방법 (최소한의 옵션)

```bash
XCryptor.exe -i foo.txt
```

복호화 실행 방법 (최소한의 옵션)

```bash
./XCryptor -i foo.txt.enc -d
```

## Version history & Download

[Release](https://github.com/XerosLab/XCryptor/releases)
