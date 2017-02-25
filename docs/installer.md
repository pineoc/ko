<h1>SDKBOX CLI 인스톨러</h1>
<h4>third-party SDK들을 자동으로 구성</h4>

### 인스톨러 설치

* [python](https://www.python.org) 설치
* SDKBOX 인스톨러 다운로드 [this link](http://download.sdkbox.com/installer/v1/sdkbox_installer.zip)
* 또는 아래의 스크립트를 터미널 프롬프트에 붙여 넣으십시오. 무엇을 하는지 설명하고 당신을 위해 모든 것을 설정합니다:
```
python -c "import urllib; s = urllib.urlopen('https://raw.githubusercontent.com/sdkbox-doc/en/master/install/install.py').read(); exec s"
```


### 플러그인 설치
* 커맨드라인을 통해, `cd` 어플리케이션 root 디렉토리로 이동하세요. 예:
```sh
cd MyGame
```

* 그리고, SDKBOX 인스톨러를 통해 플러그인을 설치 할 수 있습니다. 예:
```sh
sdkbox import facebook
```

### 다음은?
SDKBOX 설치 프로그램은 필요한 대부분의 과정을 처리합니다. 그러나 아직 진행해야하는 몇 가지 수동 단계가 있습니다. 설치 프로그램을 실행하면 플러그인 번들 PDF를 참조하여 수행해야하는 나머지 단계 목록이 출력됩니다. 명령을 실행했을 때의 출력입니다:
```sh
$ sdkbox import facebook
 _______ ______  _     _ ______   _____  _     _
 |______ |     \ |____/  |_____] |     |  \___/
 ______| |_____/ |    \_ |_____] |_____| _/   \_
Copyright (c) 2015 Chukong Technologies Inc. v0.5.7.1


  *****************************
  ******** Manual Step ********
  *****************************

1. Edit "project.properties"
   Set "target=android-15"

Please reference the online documentation to finish the integration:
http://sdkbox-doc.github.io/en/plugins/facebook/v3-cpp/
Installation Successful :)
```

### 다른 인스톨러 옵션.

#### 명령어:
SDKBOX Installer에는 사용할 수있는 몇 가지 명령이 있습니다. `sdkbox` 명령어로 자체적으로 실행 하거나 `-h` 도움말 스위치를 사용하여 도움말을 볼 수 있습니다.

| 명령어            | 설명  |
| :--------------------- | :----------- |
| list | 컴퓨터에 설치된 사용 가능한 패키지와 캐시된 패키지를 나열합니다. 패키지 저장소는 홈 디렉토리에 있습니다. |
|  import [name] |  'name' 패키지를 프로젝트로 가져옵니다. 이름 목록은 list 명령을 참조하십시오. -b 옵션을 지정하여 로컬 아카이브 패키지 또는 디렉토리를 지정할 수도 있습니다 (위 참조). |
| update | 가져온 모든 패키지를 다시 가져와 최신 버전으로 업데이트합니다. SDKBOX v0.5.6.19 이전에 패키지를 가져온 경우 수동으로 패키지를 가져 와서 패키지 매니페스트에 추가해야합니다. |
| info | 프로젝트로 가져온 패키지를 표시합니다. 가져온 패키지가 패키지 매니페스트에 없는 경우, SDKBOX는 가져온 것으로 간주되는 패키지를 알려줍니다. |
| restore | 프로젝트를 찾을 수 있는 최신 백업으로 복원합니다. import 한 후 프로젝트 파일을 변경 한 경우 변경 사항을 덮어 쓰게되므로 신중하게 사용하십시오. |
| clean [N] | N 일보다 오래된 모든 패키지를 제거합니다. |
| symbols | import 프로세스를 실행하는 데 사용되는 기호가 표시됩니다. 이 기호는 디버깅에 매우 유용하므로 문제가 있는 경우 포럼에 게시하려면 가능한 경우 기호를 포함하십시오. |

#### 스위치
SDKBOX 인스톨러에는 사용할 수 있는 몇 가지 스위치가 있습니다. `sdkbox` 명령어를 실행하거나 `-h` 도움말 스위치를 통해 항상 볼 수 있습니다.:

| 스위치  | 대체 스위치  | 설명 |
| :------------- | :------------------------| :-----|
| -h      | --help          |도움말 메세지를 보여줍니다. |
| -v      | --verbose       |로그의 정보 수준을 지정합니다. |
| -p PROJECT | --project PROJECT |프로젝트의 root를 지정합니다. (기본값은 .) |
| -b PLUGIN | --plugin PLUGIN |플러그인의 경로 지정 (기본값은 .) |
| -D SYMBOL | --symbol SYMBOL |패키지 스크립트에 대한 심볼을 정의합니다. |
| -q | --nohelp |설치 후 온라인 문서를 보여주지 않습니다. |
| -d [DAYS] | --days [DAYS] |보관할 로그 및 패키지 일 수를 지정합니다. |
|         | --china        |미국 대신 중국 기반 서버 사용 |
|         | --dryrun        |수행하기 전에 테스트 설치. |
|         | --forcedownload |패키지가 이미 다운로드 되었더라도 강제로 다운로드합니다 |
|         | --noupdate        |사용가능한 업데이트를 무시합니다. |
|         | --alwaysupdate    |항상 최신버전으로 업데이트 합니다. |
|         | --jsonapi        |명령을 API 호출로 처리하고 JSON 형식의 출력을 반환합니다. |
|         | --patcherrors        |패치 실패는 경고 대신 오류로 계산합니다. |
|         | --nopatching        |패키지 스크립트를 실행할 때 모든 패치 명령을 생략합니다. |

예시:
```sh
Add 'In App Purchase' plugin to your game
$ sdkbox import -b iap -p /path/to/your/cocos2dx/game/
```
```sh
#The -b option may be omitted and -p too if you are in your project directory
$ sdkbox import iap
```
```sh
#If you want to install a earlier version of the plugin
$ sdkbox import -b /path/to/your/package
```
```sh
#List all available packages on the server
$ sdkbox list
```
```sh
#Show all package imported into your project
$ sdkbox info
```
```sh
#clean logs and packages older than 5 days
$ sdkbox clean 5
```
```sh
#use playphone as your store for android
$ sdkbox set store playphone
```

### 최신 상태 유지
SDKBOX 인스톨러는 자동으로 자체 업데이트를 확인합니다. 업데이트하기 전에 당신의 허락을 요청할 것입니다. 이렇게하면 최신 상태를 유지할 수 있고, 플러그인 번들의 업데이트를 자동으로 가져올 수 있습니다.
```sh
$ sdkbox
 _______ ______  _     _ ______   _____  _     _
 |______ |     \ |____/  |_____] |     |  \___/
 ______| |_____/ |    \_ |_____] |_____| _/   \_
Copyright (c) 2015 Chukong Technologies Inc. v0.5.6.24

A newer version of SDKBOX is available, would you like to update to v0.5.7.1?
Please type Yes, No or Quit Yes
updated SDKBOX v0.5.6.18 to v0.5.7.1 at sdkbox
```
