## Git 실습 - 문제풀기
> 아래에 있는 각각의 문제에 대해 답과 이유를 작성하시오.
> 함께 PR을 날리면서 집단지성을 통해 문제를 풀어 봅시다.

1. git은 무엇인가요?   
   - 답 : 분산 버전 관리 시스템
  
2. Staging Area의 역할은 무엇일까요?
   - 답 : Working Directory에서 작성된 파일 등을 commit하기 위해 올려주는 공간으로
   - 묶어서 올리거나 수정을 용이하게 하는 장점이 있음

3. 변경사항을 기록하는 과정을 아래 코드 블록에 작성해 주세요.
   - 답
   ```bash
   `git add <file> or git add .`
   `git commit -m "Commit Message"`
  
   ```

4. 아래와 같은 메시지가 발생했을 때, 무엇을 해야 할까요?
![image](https://user-images.githubusercontent.com/98133984/181182281-4d01a374-62fe-4957-9a07-1efc005e35d3.png)
   - 답
   ```bash
   `$ git config --global user.email {email@email.com}
   $ git config --global user.name {uesr_name}`
   ```

5. clone과 pull의 차이는 무엇인가요?
   - 답 : clone는 보통 원격 저장소의 repository를 새로 로컬 디렉토리에 가져오는 반면
   - pull은 주로 기존에 연결된 디렉토리에서 업데이트 내용을 받을 때 사용된다.
   - (clone는 git으로 관리되지 않는 로컬 디렉토리에 적용해야 오류 발생 안함)
  
6. branch를 만드는 목적은 무엇인가요?
    - 답 : branch를 만들지 않고 master에서만 작업하고 수정하는 경우 오류가 발생했을 시
    - 메인 서비스를 제공할 수 없는 치명적인 문제가 발생할 수 있어서 별도의 작업 공간인 branch를 생성해서
    - 작업한다.

7. branch를 생성하는 동시에 이동하는 명령어는 무엇인가요?
    - 답 :
    - `git switch -c {branch_name}`

8. 다음과 같은 상황이 나타났을 때 어떻게 해야 하나요?
   ![image](https://user-images.githubusercontent.com/98133984/181183354-df42d325-b839-48e1-a4c6-667c20b33d5c.png)
    - 답 : 

9.  소유권이 없는 협업을 하기 위해서 가장 먼저 해야 할 것은 무엇일까요?
10. 소유권이 없는 협업의 경우, `git push origin master`로 원격 저장소에 변경사항을 반영할 수 있다.
    - 답 : O/X
    - 이유 :
 
11. git reset 명령어의 옵션 중, staging area 상태로 돌아가는 옵션은 ______이다.
    - 답 : 

12. 바로 직전 커밋을 수정하기 위해서 필요한 명령어를 작성하세요.
    - 답
    ```
    ```

13. merge와 rebase의 차이점은 무엇일까요? 
     - 답 : 
