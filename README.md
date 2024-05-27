# Unattend
# Unattend
윈도우 설치를 부분 자동화하는 Unattend.xml 파일과 전체 자동화 AutoUnattend.xml 파일을 메뉴에서 선택하여 생성할 수 있습니다.
초급자 버전은 위험 때문에 디스크 파티션 작업과 install.wim index 선택 작업이 제외되었습니다.
전문가 버전에서 디스크 번호, EFI 파티션 크기, install.wim 이미지 번호를 선택할 수 있습니다.
초급자와 전문가 버전에 차이는 디스크 파티션 작업 자동화 여부에 있습니다.
잘못된 디스크 파티션 작업으로부터 자료를 보호하기 위해서 분리하였습니다.
무인설치에 적용되는 명령 옵션은 Specialize 구간과 OobeSystem으로 구분되어 있습니다.
Unattend_EN.ini 파일에 사용자가 원하는 명령을 수정 하여 커스터마이징할 수 있습니다.

언어 선택은 Unattend.ini에서 설정할 수 있다. (;으로 주석 처리)
[LanguageSettings]
Language=KO
;Language=EN

각 기본 옵션 선택은 Unattend_KO.ini에서 설정할 수 있다.
;체크 박스 선택 :"1", 미선택 "0"
Checked=1

You can create an Unattend.xml file that partially automates Windows installation and an AutoUnattend.xml file that fully automates it by selecting it from the menu.
The Beginner version excludes disk partitioning and install.wim index selection operations because of their risk.
In the expert version, you can choose the disk number, EFI partition size, and install.wim image number.
The difference between the Beginner and Expert versions is whether or not disk partitioning operations are automated.
It was separated to protect data from incorrect disk partition operations.
Command options applied to unattended installation are divided into Specialize section and OobeSystem.
You can customize it by modifying the command you want in the Unattend_EN.ini file.

Language selection can be set in Unattend.ini. (commented out with;)
[LanguageSettings]
Language=EN
;Language=KO

Each default option selection can be set in Unattend_EN.ini.
;Check box selected:"1", unchecked "0"
Checked=1
