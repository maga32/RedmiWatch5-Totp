# 레드미워치5 OTP앱
![thumbnail](./imgs/watch5totp.png)
###
###
## 0. 들어가기에 앞서
- 해당 앱을 시계에 설치함으로써 발생하는 기기 오작동 및 모든 불이익에 대해 개발자는 책임을 지지 않습니다.
- 수정된 Mi Fitness 앱을 휴대폰에 설치함으로써 발생하는 기기 오작동 및 모든 불이익에 대해 글 작성자는 책임을 지지 않습니다.

###
###
## 1. 설치방법
### 1.1. release탭의 최신버전 rpk 파일을 휴대폰에 받아주세요.

### 1.2. 수정된 Mi Fitness 앱을 설치해주세요.
> - 수정된 Mi Fitness앱은 네이미카페 샤오미스토리에 업로드 하였습니다.
> - 위 앱은 중국 개발자가 수정한 앱으로, 어떠한 내용들이 수정되었는지 정확히 알 수 없습니다.
>   - 추후 시간이 날 때 직접 앱을 수정하여 업로드하겠습니다.

### 1.3. Mi Fitness 앱에서 시계 연동 후 Profile - about this app - user agreement 로 들어가주세요

### 1.4. Third App Support가 뜨면 아래와 같이 설치해주세요.
> - click to input package name : org.duckdns.sung-a.rw5totp
> - install third app : 다운로드한 rpk파일 선택
- 만약 설치가 안됐다면 시계를 재부팅 해주시거나 settings - layout 을 변경하시면 TOTP 아이콘이 보일겁니다.
- 그래도 설치가 안된다면 앱과 통신이 불안정한 상태이니 다시한번 설치 후 시계를 재부팅 해보시기 바랍니다.

###
###
## 2. 삭제방법
### 1.2, 1.3을 진행 후 아래와 같이 삭제해주세요.
> - click to input package name : org.duckdns.sung-a.rw5totp
> - uninstall third app  클릭
- 만약 삭제가 안됐다면 시계를 재부팅 해주시거나 settings - layout 을 변경하시면 TOTP 아이콘이 사라질겁니다.
- 그래도 삭제가 안된다면 앱과 통신이 불안정한 상태이니 다시한번 재설치 후 삭제 해보시기 바랍니다.

###
###
## 3. OTP 셋팅방법
### 3.1. 시계 앱에서 +버튼을 누른 후 나온 qr코드를 폰으로 인식하여 웹페이지를 엽니다.

### 3.2. 이름, 시크릿키, 타임아웃(기본30초)을 입력하고 전송버튼을 누릅니다.

### 3.3. 시계 앱에서 Touch here to save after submit in the web 버튼을 누릅니다.

### 3.4. 시계 앱에 입력한 otp정보가 저장됩니다.

###
###
## 4. 기타정보
- 위 앱은 샤오미 vela 프레임워크로 개발되었습니다 : https://iot.mi.com/vela/quickapp
- 수정된 Mi Fitness 앱 정보 : https://www.bandbbs.cn/threads/9893/
