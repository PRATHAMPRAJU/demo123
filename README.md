#                                             FOR JAVA BASED REPO
# Install maven plugin then and put git repo url in SCM section after that in build step enter clean package command
![Screenshot from 2024-08-22 21-52-18](https://github.com/user-attachments/assets/02a393c4-dd86-42fc-a41a-d466627819a6)
![Screenshot from 2024-08-22 21-52-41](https://github.com/user-attachments/assets/2b6bd2b8-799d-4db4-95c2-9b69d9a9e2b4)
![Screenshot from 2024-08-22 21-52-55](https://github.com/user-attachments/assets/3ab4056d-f6d4-4e99-a006-f04f0bbf7d17)
![Screenshot from 2024-08-22 21-53-03](https://github.com/user-attachments/assets/ab0cd4b7-0bee-4f68-8e03-9f828a379f17)
# create a new job java test and install junit plugin in workspace put above job workspace and in trigger section cfg upstrem downstream concept in maven goal put test command and in post build action section generate junit report.
![Screenshot from 2024-08-22 22-02-57](https://github.com/user-attachments/assets/5bef05fd-2994-46ff-85f8-1ee5d71e514b)
![Screenshot from 2024-08-22 22-03-21](https://github.com/user-attachments/assets/3e21a654-6dcc-4ec7-a116-175c81ef836b)
![Screenshot from 2024-08-22 22-03-29](https://github.com/user-attachments/assets/7b2cd770-fc62-4687-8a82-b86a8d1d51f1)
![Screenshot from 2024-08-22 22-03-53](https://github.com/user-attachments/assets/c7f0384e-151c-4fbf-b196-96d28ad57ea9)
# create a new job java credential  and  in workspace put above job  java compile workspace and in trigger section cfg upstrem downstream concept in Execute shell put gitleaks detect -v --report-path=gitleaks-report.json --report-format=json command.
![Screenshot from 2024-08-22 22-09-29](https://github.com/user-attachments/assets/1a3892d0-8f63-443c-8c70-66cf0db27144)
![Screenshot from 2024-08-22 22-09-45](https://github.com/user-attachments/assets/3c05f581-f643-4277-a479-25d79007fa2f)
![Screenshot from 2024-08-22 22-10-00](https://github.com/user-attachments/assets/2a870f90-db5a-4d74-a5c0-ec7f316fbc0c)
# create a new job java dependancy and install owasp plugin in workspace put java compile job workspace and in trigger section cfg upstrem downstream concept in Execute shell put mvn org.owasp:dependency-check-maven:6.0.3:check command.
![Screenshot from 2024-08-22 22-15-56](https://github.com/user-attachments/assets/49846e34-a46d-4e2c-9a92-079d8647a8aa)
![Screenshot from 2024-08-22 22-16-32](https://github.com/user-attachments/assets/146bd080-cd71-4983-986a-502636b16ec9)
![Screenshot from 2024-08-22 22-16-26](https://github.com/user-attachments/assets/00d99dea-6a3c-4ffe-acf5-27031674190f)
![Screenshot from 2024-08-22 22-16-19](https://github.com/user-attachments/assets/ea461e83-0051-464b-bf35-f3a28970c16f)
# create java SCA put java compile workspace in general section section after that in build step enter checkstyle:checkstyle command
![Screenshot from 2024-08-22 22-22-28](https://github.com/user-attachments/assets/7a2e7aa4-862b-4ea4-b970-39fdbd36afa8)
![Screenshot from 2024-08-22 22-22-38](https://github.com/user-attachments/assets/e831e1c7-0704-4838-9759-5c0524efce0d)
![Screenshot from 2024-08-22 22-22-46](https://github.com/user-attachments/assets/a704b445-10fe-4210-9ea0-cfe654d5602d)
# create a new job java code covarage and in workspace put java compile job workspace and in trigger section cfg upstrem downstream concept and in post build action section generate code covarage report.
![Screenshot from 2024-08-22 22-28-22](https://github.com/user-attachments/assets/9fcaa6e5-3f6b-43a0-af85-dbe99f68b84c)
![Screenshot from 2024-08-22 22-28-40](https://github.com/user-attachments/assets/43124e16-86e7-4989-b414-1c420acbe5e9)
![Screenshot from 2024-08-22 22-28-49](https://github.com/user-attachments/assets/ee7d51d3-04bb-48a0-bd51-c83d64e1792b)
