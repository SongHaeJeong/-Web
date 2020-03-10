## Open API + Docker를 활용하여 나만의 알고리즘 웹 개발

## 나만의 알고리즘 채점 사이트 만들기

>Open API + Docker 사용



- Open API - https://github.com/QingdaoU/OnlineJudgeDeploy
  - git clone https://github.com/QingdaoU/OnlineJudgeDeploy
  - 기본 채점 사이트에 대한 베이스 완성

- Docker (Window 기반 설치 및 개념) - [https://github.com/SongHaeJeong/Tech-Repository/tree/master/Docker%20%EA%B0%9C%EB%85%90](https://github.com/SongHaeJeong/Tech-Repository/tree/master/Docker 개념) 참고



>docker-machine ls를 통해 현재 돌아가고 있는 도커 머신의 종류 확인 가능
>
>![image](https://user-images.githubusercontent.com/59730002/76313929-41f30800-6319-11ea-981f-f3d208b4d4c5.png)





>docker ps -a를 통해 컨테이너 내부 확인 
>
>docker-machine ip - 어떤 IP를 사용하는지 확인
>
>![image](https://user-images.githubusercontent.com/59730002/76314052-75ce2d80-6319-11ea-9a1f-68ee05d23f1f.png)



>IP주소로 접속하면 메인페이지 Qingdao 대학에서 개발한 사이트 뜸<img src="https://user-images.githubusercontent.com/59730002/76314288-d78e9780-6319-11ea-9fcb-490a480b5cd0.png" alt="image" style="zoom:100%;" />



> 이 후 접속하여 로그인 ID : root / pw : rootroot (관리자 모드로 로그인)![image](https://user-images.githubusercontent.com/59730002/76314382-03aa1880-631a-11ea-8d69-b99090cf96a1.png)



>문제를 추가하기 위해서 Problems -> Create 
>
>![image](https://user-images.githubusercontent.com/59730002/76315092-60f29980-631b-11ea-816b-07ea56b42b4c.png)
>
>>문제 생성 후 다음과 같이 테스트케이스 등록에 필요한 파일 작성 이 후 파일들을 알집 형태로 압축
>
>Choose File에 등록되면 알아서 인식한다.
>
>![image](https://user-images.githubusercontent.com/59730002/76315186-8c758400-631b-11ea-84d4-491741f85f91.png)
>
>



>문제를 풀고 옆에 합격한 표시가 뜬다.
>
>![image](https://user-images.githubusercontent.com/59730002/76315351-dc544b00-631b-11ea-85ba-3a44665b583c.png)



