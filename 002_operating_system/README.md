## 운영체제
- 운영체제의 역할은 __다양한 하드웨어를 관리__ 하고, 그 위에서 __사용자가 다양한 어플리케이션__ 을 사용할 수 있도록하는 소프트웨어다.

- shell : bash, ash, csh ....
- util-linux
- GNU libc
- 개발환경 : gcc, binutils, make....
- X window system
- Gnome

## 커널
- 커널: 운영체제의 중심
>
> ls /vimlinuz : 커널의 본체<br>
>

#### 커널의 중요한 역할 : 컴퓨터의 하드웨어를 관리하는 것

- CPU
- 메모리
- HDD
- SSH
- DVD-ROM
- CD-ROM
- 네트워크 어뎁터
- 그래픽 어뎁터


## 시스템 콜 
#### 시스템 콜 : __커널을 부른다__ 뜻으로 디바이스 조작작업을 의뢰하기위해서 시스템 콜을 해야한다.
- open
- read 
- write
- fork
- exec
- unlink

## C 표준라이브러리 : libc
- /lib/libc.so.6 -> libc-2.23.so 와 소프트링크 되어있다.

## API(Application Programming Interface)
- 프로그래밍을 통해 무언가를 사용할 때의 인터페이스를 말한다.


