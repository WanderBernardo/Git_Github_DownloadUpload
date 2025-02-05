# Git and Github: Download and Upload remote with local
The goal this repository is show how make download and Upload of the project remote and local.


1 - Make sure all folder, files already to be save in the project local. Use Command: ``` git status ``` to check. Case, you need save so, use commands below:

- ``` git add . ```
- ``` git commit -m"files save" ```

https://github.com/WanderBernardo/Git_Github_WorkingProject/blob/main/Git_SaveLocal.md

2 - Now, we're conect remote project with local project. Use command: ``` git git remote add origin  ```

https://github.com/WanderBernardo/Git_Github_WorkingProject/blob/main/Git_CreateClone.md

### Send local project to remote project

3 - Let's use command: ``` git push -u origin main ```. This command to go send local project to remote project

Before (Remote):

![image](https://github.com/user-attachments/assets/9a4b8328-0ee5-46e0-bd85-3cb5a195768e)


After (Remote):

![image](https://github.com/user-attachments/assets/91209d83-d76b-4359-9e2a-338353f9a9f4)

### Send remote project to local project

4 - After modification in the portal GitHub. Use command in the command screem (Bash): ``` git push -u origin main ```

![image](https://github.com/user-attachments/assets/83f5e15a-ebd0-46f7-b953-c8c07db928ec)

Before:

![image](https://github.com/user-attachments/assets/be68788a-a9b5-4425-8b1e-5c8a836ff28c)

After:

![image](https://github.com/user-attachments/assets/b344216e-8578-4dfd-8c4e-443376c547f7)


# Case it be with conflit between merge. Use command: ``` git push --help ```




