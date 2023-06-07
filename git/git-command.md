# git 기본 명령어


- **```init```** : git 저장소를 초기화한다.

-  **```status```** : 현재 작업중 ```(working diretory)```인 파일 상태를 확인한다

- **```add```** : 현재 상태를 추적한다.(스테이지에 올린다)
    - **[```add .```]** : 현재 위치에 모든 파일을 추적
- **```commit```** : 인덱스에 변경된 값을 저장한다.(스냅샷을 찍는다)
    - **[`commit -m`]** : 커밋 메세지를 등록한다.

- ```remote```: 원격 저장소를 저장함
    - **```add origin  https://...```** :  https://... 주소를 origin이라는 별명으로 저장한다.
- **```push```** : 원격저장소에 저장한다.
    - **```origin master```** : master를 origin이라는 원격저장소에 업로드한다


# github 업로드 순서

![순서](https://git-scm.com/book/en/v2/images/areas.png)
1. **Working Directory** : 현재 작업중인 파일
    - ```Stage fixes``` : stage의 변경사항을 보냄
2. **Staging Area** : 커밋할 대상을 저장하는곳  ```index```라고도 불림.
    - **```commit```** : 변경된 값을 저장한다.
3. **git directory** : 원격 저장소 