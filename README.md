- π Hi, Iβm @yinks94
- π Iβm interested in ...
- π± Iβm currently learning ...
- ποΈ Iβm looking to collaborate on ...
- π« How to reach me ...

<!---
yinks94/yinks94 is a β¨ special β¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# Git Server λ³κ²½νκΈ°
1. ν°λ―Έλμ μ½λλ€.

2. λ³΅μ¬νκ³ μ νλ μ μ₯μ(gitlab)μ bare cloneμ μμ±ν©λλ€.

 git clone --bare https://gitlab.com/exampleuser/old-repository.git

3. μλ‘μ΄ μ μ₯μ(github)λ‘ mirror-pushλ₯Ό μ§νν©λλ€.

 cd old-repository.git
 git push --mirror https://github.com/exampleuser/new-repository.git
