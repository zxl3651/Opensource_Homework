# Opensource_Homework
2021.1학기 오픈소스SW개론 과제.

---

### 문제 1
![image](https://user-images.githubusercontent.com/94293365/143690899-c2901fa9-2198-4041-aced-bb43d7e49ba6.png)
![image](https://user-images.githubusercontent.com/94293365/143690904-8aa4d5f2-e5f9-496a-9ec0-69e4ed406a54.png)

### 입력키

![image](https://user-images.githubusercontent.com/94293365/143691249-a7ad9366-76d7-4226-840b-a14a1a7ad13e.png)

+ G: 파일의 마지막 줄로 이동
+ W: 단어 단위 앞으로 이동(단어 시작)
+ i: 현재 위치에서 입력 모드 시작


### 해결영상

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/94293365/143691206-5d3cec9a-a76e-4d35-8051-b6cfb2d530b1.gif)

---

### 문제 2
![image](https://user-images.githubusercontent.com/94293365/143691367-5ff65ce3-0343-42db-a503-f6e98ec6d388.png)
![image](https://user-images.githubusercontent.com/94293365/143691371-ad4123de-dff4-434a-9476-227974af1cbc.png)

### 입력키

+ %s/str1\|str2/replace/g : str1과 str2를 replace로 치환함

### 해결영상

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/94293365/143694324-4fcfc75b-b7ec-49af-9ec4-91b5712a5ce3.gif)

---

### 문제 3
![image](https://user-images.githubusercontent.com/94293365/143694720-4e8e641f-38f2-4728-bcf4-80b1fe3034a5.png)
![image](https://user-images.githubusercontent.com/94293365/143694802-ad051cb7-5fff-4cc9-9a96-6974e1117f17.png)

### 입력키

![image](https://user-images.githubusercontent.com/94293365/143719945-4eeae7fb-7b50-434e-8b9b-6bdc7c81db32.png)

+ M: 현재 화면 기준 중간으로 이동
+ Y: 현재 라인을 복사
+ p: 현재위치 다음에 붙여넣기

![image](https://user-images.githubusercontent.com/94293365/143720297-ab88e3b1-b9b2-4c36-9cef-e8feaf2157ee.png)

+ cw: 다음 단어를 삭제후 입력모드로 들어감

### 해결영상

***해결영상1***

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/94293365/143720043-c2637e31-d497-4649-9037-acce8c387739.gif)

***해결영상2***

![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/94293365/143720423-889d5fa3-bdc1-4865-bba0-e3bbea8c03b1.gif)

---

### 문제 4

![image](https://user-images.githubusercontent.com/94293365/143720072-e97b8790-1df7-42a7-8d4c-e28f1f9ffa83.png)
![image](https://user-images.githubusercontent.com/94293365/143720077-7630b261-6a47-4421-93f0-4104bafccbf5.png)

### 입력키

#### 1번째 시도

![image](https://user-images.githubusercontent.com/94293365/143767733-52a552b3-2845-4fda-9d59-9ff275d929a8.png)

#### 2번째 시도

![image](https://user-images.githubusercontent.com/94293365/143767753-5f406e9e-61d6-490e-8d9a-63697799a1be.png)

#### 3번째 시도

![image](https://user-images.githubusercontent.com/94293365/143767764-346b17c3-a41a-4ab4-bae9-2f73ac3f25b3.png)

+ $ %s/str/replace : str을 replace로 바꿈
+ $ (number)s/str/replace/g : number라인의 str을 모두 replace로 바꿈
+ Ctrl + v : 비주얼 블록 모드로 들어감
+ (비주얼블록모드 상태일때) d : 삭제

### 해결영상

![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/94293365/143768665-8af875dd-e9ae-4348-b72d-e58333ad06cd.gif)

---

### 문제 5

![image](https://user-images.githubusercontent.com/94293365/143768713-be06a3f3-d209-4c53-9783-35f7acef317a.png)
![image](https://user-images.githubusercontent.com/94293365/143768718-231fb13f-3537-4b15-8310-8ccaa57b3c16.png)

### 입력키

#### 1번째 시도

![image](https://user-images.githubusercontent.com/94293365/143769075-7aa9ae14-032b-42dd-b79c-d7233fc41549.png)

+ (number)G : number 행으로 이동
+ <End> : $키와 동일함, 라인 끝으로 이동
+ 여기에선 그냥 입력해봄

#### 2번째 시도

![image](https://user-images.githubusercontent.com/94293365/143769096-98e7b740-cbf4-4b89-bcc5-5d6ed9fd9cb4.png)

+ yw : 앞에 한 단어를 복사함 (제일 긴 student_id를 치지않기 위해 복사함)
+ p : 붙여넣기 (복사한걸 붙여넣음)
+ a : 다음칸부터 insert 모드로 시작함
  
#### 3번째 시도
  
  ![image](https://user-images.githubusercontent.com/94293365/143769211-f02fb653-de5f-4d0a-a6a1-6281f035b66f.png)

  + 10G로 마지막 열로 이동하던걸 그냥 G로 고쳐서 횟수를 1 줄임
  
  ### 해결영상
  
  ![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/94293365/143769402-f5d05c48-b60c-41bd-bdaf-c0972bfe28ec.gif)
