# 👀 VRCFaceTracking Old Version Portable 포터블 버전

Since VRCFaceTracking only provides portable executables from version 5.2.3.0 and I wanted to stick to the old version (after wiping my PC), I decided to unpack the .msix installers of some known stable old versions.

VRCFaceTracking 버전 5.2.3.0부터 포터블 실행파일을 제공하지만, 저는 예전 버전들이 더 안정적이게 작동했었기 때문에, 일부 옛 버전들을 직접 포터블 버전으로 배포하기로 했습니다.


##### (and also the installer signature is broken on any older versions... making all the old versions not installable... 그리고 모든 옛 버전의 설치파일에 서명된 인증서가 전부 만료되어버렸기에... 옛 버전을 쓰고 싶어도 쓸 수가 없었던...)

## Notes 알아둘 점

Installed modules are global and will stay even if you delete the executables and its folder.

모듈은 PC에 설치되며, 실행파일 및 폴더를 삭제해도 사라지지 않습니다.


Any new updates in the individual modules could break at any time since I nor VRCFT does not guarantee the full functionallity.

설치한 모듈이 업데이트될 때 마다 호환성이 깨질 수 있고 제대로 작동하지 않을 수 있습니다. 정확한 작동성은 저 또는 VRCFT가 보장하지 않습니다.

## [Download from releases  릴리즈에서 다운로드](https://github.com/github-harunadev/VRCFaceTrackingPortable/releases)

## TMI

All files are from official releases from original repository, and I only used this command 
`makeappx.exe unpack /p VRCFaceTracking_**_x64.msix /d unpack`
and compress the result folder to zip file.
If you wish to do it yourself and if you feel that it's safer, install Windows SDK and use command above to unpack it by yourself.

모든 파일은 공식 레포지토리의 공식 릴리즈에서 가져왔으며, 전 그저 위에 올려둔 unpack 명령어를 사용하여 압축을 푼 것 뿐입니다.
바이러스 등이 의심되어 직접 압축을 풀고자 하면, Windows SDK를 설치하고, 직접 unpack하세요.
