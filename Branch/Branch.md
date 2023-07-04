# Branch

git branch: 이 명령은 저장소의 모든 분기를 나열합니다.

git checkout: 이 명령은 분기 간에 전환하는 데 사용됩니다. 작업 디렉터리와 지정된 분기에 대한 분기 포인터를 업데이트합니다.

예를 들어:

    git checkout <branch-name>

git merge: 이 명령은 한 분기의 변경 사항을 다른 분기로 결합합니다. 소스 브랜치의 커밋을 대상 브랜치로 통합합니다.

예를 들어:

    git merge <source-branch>

git push: 이 명령은 로컬 커밋을 원격 저장소로 푸시하는 데 사용됩니다. -u 옵션과 함께 사용하면 로컬 브랜치를 해당 원격 브랜치에 연결하여 업스트림 브랜치를 설정합니다.

예를 들어:

    git push -u origin <branch-name>

git push: 이 명령은 로컬 커밋을 원격 저장소로 푸시하는 데 사용됩니다. -u 옵션과 함께 사용하면 로컬 브랜치를 해당 원격 브랜치에 연결하여 업스트림 브랜치를 설정합니다.

예를 들어:

    git push -u origin <branch-name>

git pull: 이 명령은 원격 저장소의 변경 사항을 가져와서 현재 브랜치로 통합합니다. 일반적으로 원격 저장소의 최신 변경 사항으로 로컬 분기를 업데이트하는 데 사용됩니다.

예를 들어:

    git pull origin <branch-name>

git branch -d: 이 명령은 다른 브랜치에 병합된 로컬 브랜치를 삭제합니다. 분기 참조 및 관련 커밋을 제거합니다.

예를 들어

    git branch -d <branch-name>

git branch -D: 이 명령은 병합되지 않은 변경 사항이 있더라도 로컬 분기를 강제로 삭제합니다. 이 명령은 병합되지 않은 커밋을 영구적으로 버리므로 주의하여 사용하십시오.

예를 들어:

    git branch -D <branch-name>
