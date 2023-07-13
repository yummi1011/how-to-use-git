# <center>How-to-use-git</center>

## 1 ��װgit<br>
* #### ��¼git���� https://git-scm.com/<br>
![https://git-scm.com/](res/git-scm.com.png)<br>
* #### ѡ�����ض�Ӧ�İ汾<br>
![https://git-scm.com/download/win](res/git-download.png)<br>
* #### ��װ<br>
* 
## 2 ��ʼʹ��git<br>
### 2.1 ʹ��git bash<br>
* #### ��Ŀ���ļ��У��Ҽ�-->��ʾ����ѡ��(win11)-->Open Git Bash Here<br>
![open-git-bush](res/open-git-bash.png)<br>
* #### �򿪳ɹ�<br>
![open-git-bush-2](res/open-git-bash2.png)<br>
### 2.2 ��vscode��ʹ��git<br>

## 3 git ʹ�÷���<br>
### 3.1 ������Ϣ����<br>
```
$ git config --global user.name <username> # �����û���
$ git config --global user.email <usermail> # �����û�����
# �û���������������ʵ����
$ git config --global -l # �鿴�û���Ϣ
```
### 3.2 �������زֿ�<br>
```
$ git init # ��ʼ��һ���ղֿ�
```
```
$ git clone <url> # �������˵Ĳֿ�
```
### 3.3 �ļ�״̬ --> `git add` �� `git commit`<br>
## ʡ����
```
$ git add .
$ git commit -m ""
# ����ô���������
```
#### ��ʡ����
�ֿ��ڵ��ļ������ĸ�״̬��<b>δ����</b>��<b>δ�޸�</b>��<b>���޸�</b>��<b>�ݴ�</b>��
���ļ�ת��״̬ͼ�������¡�<br>
![sequ](res/sequenceFile.png)<br>
* ���½�һ���ֿ⣬����ֿ����һ���µ��ļ�ʱ������ļ�����<b>`δ���� <Untracked files>`</b>״̬���ڡ�
* ���Բֿ��ڵ��ļ������޸ĺ��ļ����ͻ��Ϊ<b>`���޸� <Changes not staged for commit>`</b>״̬��
* ����������Ҫʹ��<b>`"git add <file>"`</b>��<b>`"git add ."`</b>�������ǰĿ¼������Ŀ¼��ȫ���ļ�����ʹ���������͵��ļ������<b>`�ݴ� <Changes to be committed>`</b>״̬��

ͨ��<b>`"git status"`</b>����鿴�ֿ�״̬��
```
$ git status    # �鿴�ֿ�״̬
----------------- ����Ϊ������Ϣ -------------------------------------------
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:    # �ݴ���ļ�
  (use "git restore --staged <file>..." to unstage)
        new file:   gitadd.txt

Changes not staged for commit:  # ���޸ĵ��ļ�
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:    # δ׷�ٵ��ļ�
  (use "git add <file>..." to include in what will be committed)
        newfile.txt
---------------------------------------------------------------------------
# һ���������Ӣ�ﶼ���Կ���ʲô��˼
```

���ļ�����Ϊ<b>`�ݴ� <Changes to be committed>`</b>״̬�����ǾͿ���ʹ��<b>`"git commit -m "<update notes>"`</b>�ύ�ˡ����е��ļ�Ҳ������δ�޸�״̬��

<b>`"git log"`</b> ���Բ鿴���е��ύ��ʷ��<b>`"git reset head~ --soft"`</b>���Գ�����һ���ύ��
```
& git log                       # �鿴�ύ��¼
commit 9b26f8a111af2cb509a4b8269b42b23289a54769 (HEAD -> main, origin/main)
Author: sunlin <123@163.com>
Date:   Fri Jul 14 00:34:34 2023 +0800

    update README.md

commit d25b1dd69e6c31e07b3830d95ce4cf4b9c5a8d02
Author: sunlin <zbsl1@163.com>
Date:   Thu Jul 13 23:30:18 2023 +0800

    update
.....
$ git reset head~ --soft        # ������һ���ύ
$ git log                       # �鿴�ύ��¼
commit d25b1dd69e6c31e07b3830d95ce4cf4b9c5a8d02 (HEAD -> main)
Author: sunlin <zbsl1@163.com>
Date:   Thu Jul 13 23:30:18 2023 +0800

    update
...
```
�����Կ��Կ����������һ���ύ�������ˣ�ͬʱ�ļ�״̬Ҳ������ύǰ��״̬��<br>

### 3.4 ����Զ�ֿ̲� GitHub
## ʡ����
�ϻ�����˵��ֱ�ӿ�GitHub�ٷ��̡̳�<br>
![remote](res/remote.png)<br>

### ˵ʵ�����������������ȫ�����ˡ�
## ��Ϊ����̳̾�����ôpush�����ġ�

