- 👋 Hi, I’m @yinks94
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
yinks94/yinks94 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# Git Server 변경하기
1. 터미널을 엽니다.

2. 복사하고자 하는 저장소(gitlab)의 bare clone을 생성합니다.

 git clone --bare https://gitlab.com/exampleuser/old-repository.git

3. 새로운 저장소(github)로 mirror-push를 진행합니다.

 cd old-repository.git
 git push --mirror https://github.com/exampleuser/new-repository.git
