## Git 실습 - 문제풀기
> 아래에 있는 각각의 문제에 대해 답과 이유를 작성하시오.
> 함께 PR을 날리면서 집단지성을 통해 문제를 풀어 봅시다.

1. git은 무엇인가요?   
   - 답 : 분산 버전 관리 시스템
  
2. Staging Area의 역할은 무엇일까요?
   - 답 :  커밋을 위한 파일 및 폴더가 추가되는 곳

3. 변경사항을 기록하는 과정을 아래 코드 블록에 작성해 주세요.
   - 답
   ```bash
   git add
   git commit -m <>
  
   ```

4. 아래와 같은 메시지가 발생했을 때, 무엇을 해야 할까요?
![image](https://user-images.githubusercontent.com/98133984/181182281-4d01a374-62fe-4957-9a07-1efc005e35d3.png)
   - 답 깃에 등록해야함
   ```bash
   git config -global user.name <>
   git config -global user.email <>
   
   ```
5. clone과 pull의 차이는 무엇인가요?
   - 답 :  clone은 원격저장소 커밋을 그대로 로컬저장소로 가져옴 pull은 원격저장소 변경사항만 가져옴

   
6. branch를 만드는 목적은 무엇인가요?
    - 답 : 여러 갈래로 작업공간을 나누어 독립적으로 작업할 수 있도록 도와주는 git의 도구입니다. 독립된 공간을 형성하기 때문에 원본에 대해 안전합니다.

7. branch를 생성하는 동시에 이동하는 명령어는 무엇인가요?
    - 답 : git switch -c <>

8. 다음과 같은 상황이 나타났을 때 어떻게 해야 하나요?
   ![image](https://user-images.githubusercontent.com/98133984/181183354-df42d325-b839-48e1-a4c6-667c20b33d5c.png)
    - 답 : 로컬 저장소와 원격 저장소의 내용이 다르다면 일단 git pull을 통해 동기화를 시키고 새로운 커밋을 쌓아 나가야 합니다.

9.  소유권이 없는 협업을 하기 위해서 가장 먼저 해야 할 것은 무엇일까요? fork
10. 소유권이 없는 협업의 경우, `git push origin master`로 원격 저장소에 변경사항을 반영할 수 있다.
    - 답 : x
    - 이유 :pull request를 통해 복제 원격 저장소(origin)의 브랜치를 원본 원격 저장소(upstream)의 master에 반영해달라는 요청을 보냅니다
 
11. git reset 명령어의 옵션 중, staging area 상태로 돌아가는 옵션은 ______이다.
    - 답 : git reset --soft

12. 바로 직전 커밋을 수정하기 위해서 필요한 명령어를 작성하세요.
    - 답
    ```bash
    git commit --amend
    ```

13. merge와 rebase의 차이점은 무엇일까요? 
     - 답 : merge는 브랜치들을 하나로 합친다.
