# git_cheat_sheet
All about Git
![Git](./images/git-blog-header.png)

### Git Command

| Command       | Example                     | Description                                                                                                                 |
| ------------- | --------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| git init | `git init <directory>`| Repomuz icin gerekli olan git dosyalarini ekler.                                                   |
| git add * | `git add *`      | Her seyi eklemeyi gosterir bize asteriks(*)                                                                  |
| git commit -m "First commit" | `git commit -m "First commit"`      | Repomuza commit atmamiza yarar bu komut. |
| git status | `git status`      | Repomuzun status komutu ile not staged ya da up to date olup olmadigini gorebiliriz. |
| git branch | `git branch`      | Bu repoda branchler oldugunu ve hangi branchte calistiginizi gorebilirsiniz.  |
| git diff --cached --name-only   |    `git diff --cached --name-only`      | Degisikligin hangi dosyada oldugunu gosterir. |
| git checkout -b <branch_name>   |    `git checkout -b <branch_name>`    | Yeni bir branch olusturmak icin kullanilir.   |
| git merge <branch_name>  |    `git merge <branch_name>`    |   Branchi mergelemek icin kullanilacak komut.    |
| git stash save <branch_name>  |    `git stash save <branch_name>`    |   Stash icindeki degisiklikleri kaydetmemize yarar.   |
| git restore .  |    `git restore .`    |   Yapilan degisikliklerigeri almaya yarar.  |
| git stash apply  |    `git stash apply`    |   Yapilan degisiklikleri kaydetmemize yarar.  |

