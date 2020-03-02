
# Git
0. git 최초 설정
	```sh
	$ git config --global user.name "ID"
	$ git config --global user.email mail@example.com
	```
2. git 시작하기

   ```sh
   $ git init
   ```


3. 상태 확인하기

   ```sh
   $ git status
   ```

4. 스테이지에 올리기

	  ```sh
	$ git add 파일명
	 ```
	 auto crlf 켜기
	  ```sh
	$ git config --global core.autocrlf true
	 ```


5. 커밋하기

   ```sh 
   $ git commit -m "메세지"
   ```

6. 기록 확인하기

   ```sh 
   $ git log
   ```

7. 리모트(원격 저장소) 등록하기

   ```sh 
   $ git remote add origin 원격저장소 주소
   ```

8. 파일 푸쉬하기(업로드하기)

   ```sh
   $ git push origin master
   ```

