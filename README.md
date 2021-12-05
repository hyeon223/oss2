#### 오픈소스과제 vimgolf
---


**1) 1번 문제**


![1](https://user-images.githubusercontent.com/94741432/144711426-a9b63e8a-b2cb-463b-bd8a-7bf7b05b05bd.gif)




![1](https://user-images.githubusercontent.com/94741432/144711810-0d07db7a-f399-4e7e-9af2-730391903179.jpg)




1) G: 파일의 마지막 줄로 이동
2) W: 단어의 앞으로 이동(단어 시작)
3) i: 현재 커서의 위치에서 입력모드 전환(Esc키 누르면 입력모드 종료, 입력모드에서도 end키는 )
4) ZZ : 저장 후 종료


---


**2) 2번 문제**


![2](https://user-images.githubusercontent.com/94741432/144711559-180c47ae-8c7b-40bb-8424-983bd93b4ca6.gif)




![2](https://user-images.githubusercontent.com/94741432/144711835-d8898879-718f-4b0d-bffa-8a8d0cef3561.jpg)




1) :%s/sublime\|emacs/vim/g : sublime과 emacsdml 문서 전체를 vim으로 교체함(\|는 or을 의미함)
2) ZZ : 저장 후 종료


---


**3) 3번 문제**


![3](https://user-images.githubusercontent.com/94741432/144711578-028f39d8-1568-42f7-a3d5-72b1d4a9ba7e.gif)




![3](https://user-images.githubusercontent.com/94741432/144711852-51d25abb-2119-4cf1-811f-a8ef1306430a.jpg)




1) nG : n번째 줄로 이동
2) yw: 현재 커서 위치의 단어를 끝까지 복사
3) O : 커서의 이전행에 새로 줄을 만든후 입력
4) b : 이전 단어의 첫 글자로 이동
5) P : 현재 커서의 앞에 복사된 내용을 붙임
6) Y : 커서가 위치한 줄을 복사(또는 yy)
7) p : 현재 커서의 뒤에 복사된 내용을 붙임
8) w : 다음 단어의 첫 글자로 이동
9) dw : 현재 커서의 오른쪽 방향으로 단어 삭제
10) ZZ : 저장 후 종료


---


**4) 4번 문제**


![4](https://user-images.githubusercontent.com/94741432/144711588-fe457c80-4888-4232-885a-556bb640b564.gif)




![4](https://user-images.githubusercontent.com/94741432/144711859-80651d5f-a5fe-4166-aa46-60b83ea99d21.jpg)




1) :%s/y1/abs(y1) : y1을 abs(y1)으로 전부 교체함
2) :3s/1/2/g : 3행의 1을 2로 전부 교체함(즉, :ns/old/new/g 에서 n은 행의 번호를 지정하며, g는 모두 교체) 
3) /k : k로 시작하는 문자를 현재 커서에서 파일의 끝부터 문자열 찾음
4) r : 현재 커서 위치의 한 문자를 다른 문자로 교체함
5) ZZ : 저장 후 종료


---


**5) 5번 문제**


![5](https://user-images.githubusercontent.com/94741432/144711605-f4f26a42-97ba-4a71-90be-130bde8624b6.gif)




![5](https://user-images.githubusercontent.com/94741432/144711864-cfd9cce6-7f6a-4436-9d7f-bcb9edfcffe6.jpg)




1) nG : n번째 줄로 이동
2) yw : 한단어를 복사함
3) p : 현재 커서의 뒤에 복사된 내용 붙임
4) i : 입력모드로 전환
5) `` : 직전의 커서 위치로 이동함
6) ZZ : 저장 후 종료

