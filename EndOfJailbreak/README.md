# [iOS] 탈옥의 끝 이제 구글링 안해💥

| Author   | [namki](https://github.com/namkiseung) |
| -------- | -------------------------- |
| Created  | Oct 29, 2019 11:17 AM      |
| Tags     | Daily, Special Event, Work |

> Original post : [https://www.notion.so/kiseungnam/iOS-cd3fc51eab1e467caebebeac531d85ba](https://www.notion.so/kiseungnam/iOS-cd3fc51eab1e467caebebeac531d85ba)

## 탈옥?

iPhone, iPod Touch, iPad같은 Apple 휴대용 기기에 사용되는 iOS의 제한을 임의로 푸는 행위

## 탈옥과정?

iOS의 경우 자체 보안이 강력하기 때문에 이 보안을 뚫고 들어가 Cydia 스토어를 설치하고 커널을 패치하여 순정 펌웨어로 보이도록 부트롬을 속인다. A4칩 이전에는 부트롬이 별도로 설치되어 있어서 부트롬 익스플로잇이 한번 뚫리면 이후 iOS버전에서는 반탈은 가능 하지만 부팅 과정을 속이지 못하면 재부팅시 벽돌 상태가 되는 이른바 반탈(Tethered Jailbreak)상태

## 탈옥 명분?

앱도 애플 정책상 추가될 수 없는 기능의 한계라는 게 존재한다. 때문에 '애플이 제한하고 있는 기능을 사용 가능하게 하는' 것이다. 좀더 엄밀히 말하면 OS 차원에서 지원하지 않는 기능을 지원하게끔 개조하는 것. 글꼴과 테마를 바꿀 수 있도록 한다거나. 시디아에서 애플 정책상 앱스토어를 통해 설치할 수 없던 유용한 프로그램을 찾아 설치하는 것이 주를 이룬다. 시스템 파일을 직접적으로 건드릴 수 있기 때문에 셔터음을 삭제한다던가 하는 행위도 가능

## 탈옥은 왜 하는가?

## 탈옥 Flow

> 1. windows pc 분석도구 **설치**(iTools, iTunes, plist Editor Pro , iFunbox 등)
>
> 2. pc와 기기 **연결**
>
> 3. **Impactor**.exe로 ipa 넣기(드래그 앤 드랍, **탈옥과정사진 참조**)<br />
> (탈옥 시 사용되는 .ipa 파일은 탈옥IPA.zip을 압축풀어 해당 테스트 기기의 버전에 맞게 사용)
>
> 4. apple ID /PW 입력 후 complete 완료된 후 기기 홈 화면에 회색 아이콘 생성됨 & 생성된 거 확인
>
> 5. `설정`-`일반`-`기기관리`에 들어가, 자신의 애플아이디로 된 앱을 선택한 뒤 `신뢰함` 설정
>
> 6. 신뢰가 되고 4에서 확인한 회색 아이콘 클릭 `go` 또는 `start`를 클릭하면 재부팅 진행됨.
>
> 7. 재부팅 되고 홈 화면에 cydia 앱 생성되는 것을 확인, `cydia 앱 실행시 느려질수도 있음` 메세지 무시
>
> 8. Cydia를 눌러 실행 시 업그레이드 알림 나타날 시 중요 패키지 업그레이드

## 탈옥방법?

### Case1. 임펙터

- 0.9.43, 0.9.44, 0.9.45, 0.9.51 을 주로 사용중
- Impactor에 Jailbreak 바이너리 파일을 드래그하면됨
※ 주의 `메뉴`-`Xcode`-`Revoke Certificates` 후 해야 안정됨

![CydiaImpactor](./images/CydiaImpactor.png)

### Case2. 3uTools 이용

- 따라하기

![3uTools](./images/3uTools.png)

### Case3. [Non-PC] ios-ninja 등 이용

> - iOS 11.x.x
>   1. [app.ignition.fun](https://app.ignition.fun)
> - All
>   1. https://iosninja.io/app
>   2. https://silzee.com/

- 따라하기(일부 방법은 광고앱 설치필요)
- https://iosninja.io/app
- https://silzee.com/
- https://cokernutx.com
- http://ijbelectra.com
- https://unc0ver.vip
- https://unc0ver.dev
- https://iphonecake.com
- https://ignition.fun
- http://cydia.club

![iOSNinja](./images/iOSNinja.png)

> ※ Sileo 앱은 iOS 11.x 버전대에 호환 가능

- **Appstore**를 거치지 않고 설치 시 **TrustAuth 과정**이 필요

![TrustAuth](./images/TrustAuth.png)

> 위 과정을 거치게 되면, 탈옥 디바이스에서 사용가능한 앱스토어가 설치됨.

**unc0ver 등** 으로 탈옥하면 **cydia** 가 설치되고
**chimera** 로 탈옥하면 **sileo** 로 설치
(chimera설치 : [https://chimera.sh/](https://chimera.sh/))

### Case4. AltStore 이용 (실습 iOS 13버전)

- Overview Step of Process
  - iTunes & iCloud **설치** → Altstore **설치** → unc0ver **탈옥**

  ![AltStore-1](./images/AltStore-1.png)

  ![AltStore-2](./images/AltStore-2.png)

  ![AltStore-3](./images/AltStore-3.png)

  ![AltStore-4](./images/AltStore-4.png)

  ![AltStore-5](./images/AltStore-5.png)

### Case5. checkra1n 이용

- Mac
- Linux
- Windows(xbuntu설치)
  - 설치파일: [https://github.com/ra1nstorm/ra1nstorm-helper/releases/tag/0.9.5](https://github.com/ra1nstorm/ra1nstorm-helper/releases/tag/0.9.5)
  - 방법: [https://www.techacrobat.com/checkra1n-jailbreak-for-windows/](https://www.techacrobat.com/checkra1n-jailbreak-for-windows/)

## 탈옥탐지?(DVIA.ipa기준)

![Cycript](./images/Cycript.png)

## 탈옥 프로그램 목록

| iOS 버전 | OS | 디바이스 | 개발자 |
| ------- | -- | ----- | ----- |
| iOS 9.2 - 9.3.3 | Pangu - iOS 내 탈옥 | 해당 버전 모든 기기(64-bit 기기 전용) | PanguTeam
| iOS 9.1 - 9.3.4 | JailbreakMe 4.0 - iOS 내 탈옥 | 해당 버전 모든 기기(32-bit 기기 전용) | tihmstar
| iOS 9.3.5 | Phoenix - iOS 내 탈옥 | 해당 버전 모든 기기(32-bit 기기 전용) | Siguza & tihmstar
| iOS 10.x | h3lix - iOS 내 탈옥 | 해당 버전 모든 기기(32-bit 기기 전용) | Tihmstar
| iOS 10.x | TotallyNotSpyware - iOS 내 탈옥 | 해당 버전 모든 기기 | Jake Blair 외 다수
| iOS 10.x | doubleh3lix - iOS 내 탈옥 | 해당 버전 모든 기기(64-bit A7-A9 전용) | Tihmstar
| iOS 10.x | Meridian - iOS 내 탈옥 | 해당 버전 모든 기기 | PsychoTea
| iOS 11.x | Electra - iOS 내 탈옥[주의!] | 해당 버전 모든 기기 | CoolStar
| iOS 12 - 12.1.2, iOS 12.1.3 - iOS 12.2[제한적], iOS 12.4[제한적] | Chimera - iOS 내 탈옥[주의!] | 해당 버전 모든 기기 | CoolStar
| iOS 11 - iOS 12.2, iOS 12.4" | unc0ver - iOS 내 탈옥[주의!] | 해당 버전 모든 기기 | pwn20wnd

## IPA 파일 추출 방법

1. ipainstaller
  - ipainstaller는 cydia 내에서 패키지로 설치할 수 도 있다.
  (추출경로: /private/var/mobile/Documents/~)

  ![ipainstaller.png](./images/ipainstaller.png)

2. Fastlane (AppStore용)
  - 참고 : [https://jepark-diary.tistory.com/20?category=874567](https://jepark-diary.tistory.com/20?category=874567)

## 추출한 IPA 설치 방법
> ※ 다양한 방법이 있음.

- ReProvision 이용방법(장점: Signing 까지 가능)

  ![ReProvision-1](./images/ReProvision-1.png)

  ![ReProvision-2](./images/ReProvision-2.png)

- 3uTools 이용방법(장점: 간편함. 드래그 하면되니까 설명안할게)

- impactor는...위에 방법이 있지만, 버전 호환 문제로 잘 안돼ㅠㅠ...

## 탈옥 후 필수 패키지 설치(앱등이들은 많이 알듯;)

- 저장소 이용한 설치는 다들 아시죠?

  ![source](./images/source.png)

※ 트윅이란? 탈옥 시 생성되는 Cydia에서 받을 수 있는 앱

### deb 파일 목록

1. **apt패키지**(Cydia)
2. **Apple File Conduit 2** 패키지(Cydia)
  1. cydia에서 위 설치(iFunBox 의 파일관리, 특히 디렉터리 이동이 가능해짐)
3. **open ssh** 터미널
  1. cydia에서 openssh 설치
4. **class-dump-z** / **class-dump /** classdump-dyld
  1. ios의 /private/var에 class-dump 디렉토리를 생성한다. mkdir class-dump
  2. class-dump-z_0.2a.tar.gz파일을 ftp(ifunbox, WinSCP, Filezila)를 이용해 ios의 /private/var/class-dump 디렉토리로 옮김
  3. tar -zxvf class-dump-z_0.2a.tar.gz 으로 압축을 푼다. 이후 iphone_armv6 폴더에 있는 class-dump-z를 /usr/bin으로 복사
5. **clutch**
  1. Clutch 바이너리 파일을 ifunbox, WinSCP, Filezila를 이용해 ios의 /private/var/ 디렉토리로 옮김(chmod 755 Clutch | mv Clutch clutch)
  2. cp clutch /usr/bin으로 복사
  ※ 공간이 없다고 하면 해당 위치에서 명령./clutch로 사용해도 무방
6. **cycript**
  1. cydia에서 cycript 설치
  - 사용법

    ![cycriptUsage](./images/cycriptUsage.png)

7. **명령어**
  1. zip, unzip, tar, vim, wget, Network Commands(SSL Kill Switch, gdb, cacert, libgcc, cycript) 등
8. **Hide기능을 포함**
  1. 공중제비(FlyJB, [https://repo.xsf1re.kr])(https://repo.xsf1re.kr), A-Bypass([https://repo.rpgfarm.com/](https://repo.rpgfarm.com/)), HideJB([https://repo.haka.se](https://repo.haka.se/)), Liberty([http://ryleyangus.com/repo/](http://ryleyangus.com/repo/)), Liberty lite 등

  2. 카카오 등 금융앱 탈옥 Hide는 [http://repo.rpgfarm.com](http://repo.rpgfarm.com/)

9. **반탈옥 상태를 유지시켜주는 tweak (탈옥상태의 인증서 기간 자동연장)**
  1. ReProvision ([https://repo.incendo.ws](https://repo.incendo.ws/))
10. **어플 속도 올리는 패키지**
  1. Nitrous ([http://repo.insanelyi.com/](http://repo.insanelyi.com/))

### 트윅 repo 목록

1. **기본 패키지**
  1. [http://cydia.radare.org](http://cydia.radare.org/)
2. **Bypass Tweak**

  (**cydia** **tweak이란**? S/W, H/W 를 미세하게 조정하는 작은변경을 시도하는 프로그램 그래서 때때로 원하는결과를 얻기위해 변수의 값을 약간 변형함)

  1. Flex 3 Beta

  ※ 설치 ([https://getdelta.co](https://getdelta.co/))

  2. K*Bank
  ※ 설치 ([http://cydia.myrepospace.com/kbanktweak/](http://cydia.myrepospace.com/kbanktweak/))

  3. Kaka*Bank
  ※ 설치 ([http://repo.rpgfarm.com](http://repo.rpgfarm.com/))

  4. tsProtector

  ※ 설치 ([typ0s2d10.appspot.com/repo/](http://typ0s2d10.appspot.com/repo/))

  5. JailProtect

  6. Tsprotector+8

3. **추천 패키지(트윅)**
  1. bigboss recommand tool
  경로 : [http://apt.thebigboss.org/repofiles/cydia](http://apt.thebigboss.org/repofiles/cydia)
  설명 : ssh를 이용한 접근 시 vi, wget, SQLite,GDB 등 사용가능
  2. dropbear(openssh)
  경로 : [http://cydia.ichitaso.com](http://cydia.ichitaso.com/)
  설명 : iOS 10 이상부터는 dropbear로 openssh사용가능
  3. AppSync Unified
  경로 : [https://cydia.angelxwind.net](https://cydia.angelxwind.net/)
  설명 : 애플로부터 비인가된 IPA 패키지를 설치 가능하게 해
  4. Filza
  경로 : [http://tigisoftware.com/cydia](http://tigisoftware.com/cydia)[/](https://cydia.angelxwind.net/)
  설명 : 아이폰에서 디렉터리 사용가능
  5. Keychain-Dumper
  경로 : [https://github.com/ptoomey3/Keychain-Dumper](https://github.com/ptoomey3/Keychain-Dumper)
  설명 : 탈옥 된 아이폰에서 Keychain 데이터 추출 툴
  6. otool
  경로 : [https://github.com/ptoomey3/Keychain-Dumper](https://github.com/ptoomey3/Keychain-Dumper)
  설명 : 실행파일 정보 조회 및 오브젝트 파일 디컴파일 후 어셈블리 코드 추출 툴

### repo 목록
- http://cydia.radare.org/
- https://getdelta.co/
- http://wiety.github.io/cydia/
- http://repo.xs1re.kr/
- https://repo.co.kr/
- https://repo.chariz.io/
- http://jonlu.ca/repo/
- https://rpetri.ch/repo
- https://ryleyangus.com/repo/
- https://build.frida.re/

## iOS Application Penetration Testing

- **Access Filesystem on iDevice**
  - FileZilla - FTP, SFTP, FTPS(FTP의 확장, TLS와 SSL 지원이 추가됨)
  - Cyberduck - Mac, Windows 용 FTP, SFTP
  - itunnel - SSH 도구(iOS 11 이상을 지원하지 않음)
  - iProxy
  - iTools (버전이 나뉨)
  - 3uTools
  - iFunbox - iPhone, iPad 용 파일 및 응용 프로그램 관리 도구
  - impactor

- **Reverse Engineering and Static Analysis**
  - otool - 바이너리에 로딩되어 있는 동적 라이브러리 확인 및 디스어셈블링(Cydia 설치)
  - Clutch / Cracker xi - 복호화 도구(동적/정적 분석 글에 정리되어 있음)
  - 명령어
      - `Clutch-2.0.4 -i`: 복호화 가능한 파일이 번호화 함께 나열됨
      - `Clutch-2.0.4 -b 1`: 해당 앱 바이너리 덤프
      - `Clutch-2.0.4 -d 1`: 해당 ipa 덤프(압축해제 후 리소스)
  - Dumpdecrypted
  - class-dump - 클래스 정보 추출, 보통 class-dump-z 사용(동적/정적 분석 글에 정리되어 있음)
  - Frida
    - bfinject
    - HopperApp
    - hopperscripts
    - Radare2
    - iRET

- **Dynamic and Runtime Analysis**
  - cycript
  - iNalyzer
  - Passionfruit
  - Introspy-iOS
  - Apple configurator 2
  - keychaindumper
  - BinaryCookieReader

- **Network Analysis and Server Side Testing**
  - Canape
  - Mallory
  - Burp Suite
  - OWASP ZAP
  - Charles Proxy

- **Bypassing Root Detection and SSL Pinning**
  - SSL Kill Switch 2
  - iOS TrustMe
  - Xcon
  - tsProtector
  - Frida CodeShare

- **Security Libraries**
  - PublicKey Pinning
  - OWASP iMAS

## 탈옥 에러해결

- Cydia에서 트윅 설치 시 `DPKG_LOCKED` 에러 발생 시
  - https://namkisec.tistory.com
- Cyida에서 트윅 설치 시 `Sub Process Error Code(1)` 에러 발생 시
  - 발생원인 : Cydia Eraser 를 잘못 사용하면서 시디아가 꼬이거나, 불법 크랙 소스와 트윅을 사용할때
  - 해결
    - MobileSubstrate 삭제후 재설치
    - Mterminal 을 이용한 방법

      ![Mterminal](./images/Mterminal.png)

- Cyida의 deb파일 의존성 문제
    - directory : `/var/lib/dpkg/status`

- iFunbox에서 Books 폴더에 lib드래그(복사) - **버전주의**
    - **Flow**

    1. ssh 터널링 이용 터미널 연결
    2. `cp -R /var/mobile/Media/Books/lib /var`
    3. `rm -rf /var/mobile/Library/Cydia/metadata.cb0`
    4. `rm -rf /var/mobile/Library/Caches/com.saurik.Cydia`

Signing

1. [MacOS 기반의 xcode사용](https://dantheman827.github.io/ios-app-signer)
2. [tweak사용 (appinst)](https://cydia.akemi.ai)
