# <center>How-to-use-git</center>
***
## 1 ��װgit<br>
* #### ��¼git���� https://git-scm.com/<br>
![https://git-scm.com/](res/git-scm.com.png)<br>
* #### ѡ�����ض�Ӧ�İ汾<br>
![https://git-scm.com/download/win](res/git-download.png)<br>
* #### ��װ<br>
***
## 2 ��ʼʹ��git<br>
### 2.1 ʹ��git bash<br>
* #### ��Ŀ���ļ��У��Ҽ�-->��ʾ����ѡ��(win11)-->Open Git Bash Here<br>
![open-git-bush](res/open-git-bash.png)<br>
* #### �򿪳ɹ�<br>
![open-git-bush-2](res/open-git-bash2.png)<br>
### 2.2 ��vscode��ʹ��git<br>
***
## 3 git ʹ�÷���<br>
### 3.1 ������Ϣ����<br>
```
$ git config --global user.name <username> # �����û���
$ git config --global user.email <usermail> # �����û�����
# �û�������������Ϊ��
$ git config --global -l # �鿴�û���Ϣ
```
***
### 3.2 �������زֿ�<br>
```
$ git init # ��ʼ��һ���ղֿ�
```
```
$ git clone <url> # �������˵Ĳֿ�
```
***
### 3.3 �ļ�״̬ --> `git add` �� `git commit`<br>
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
