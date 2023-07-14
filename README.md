# <center>How-to-use-git</center>

## 1 安装git<br>
* #### 登录git官网 https://git-scm.com/<br>
![https://git-scm.com/](res/git-scm.com.png)<br>
* #### 闁瀚ㄩ獮鏈电瑓鏉炶棄顕惔鏃傛畱閻楀牊婀�<br>
![https://git-scm.com/download/win](res/git-download.png)<br>
* #### 鐎瑰顥�<br>

## 2 瀵偓婵濞囬悽鈺t<br>
### 2.1 娴ｈ法鏁it bash<br>
* #### 閸︺劎娲伴弽鍥ㄦ瀮娴犺泛銇欓敍灞藉礁闁匡拷-->閺勫墽銇氶弴鏉戭樋闁銆�(win11)-->Open Git Bash Here<br>
![open-git-bush](res/open-git-bash.png)<br>
* #### 閹垫挸绱戦幋鎰<br>
![open-git-bush-2](res/open-git-bash2.png)<br>
### 2.2 閸︹暡scode娑擃厺濞囬悽鈺t<br>

## 3 git 娴ｈ法鏁ら弬瑙勭《<br>
### 3.1 娑擃亙姹夋穱鈩冧紖闁板秶鐤�<br>
```
$ git config --global user.name <username> # 鐠佸墽鐤嗛悽銊﹀煕閸氾拷
$ git config --global user.email <usermail> # 鐠佸墽鐤嗛悽銊﹀煕娣囷紕顔�
# 閻€劍鍩涢崥宥勭瑢娣囷紕顔堥弮鐘绘付閻喎鐤勭€涙ê婀�
$ git config --global -l # 閺屻儳婀呴悽銊﹀煕娣団剝浼�
```
### 3.2 閸掓稑缂撻張顒€婀存禒鎾崇氨<br>
```
$ git init # 閸掓繂顫愰崠鏍︾娑擃亞鈹栨禒鎾崇氨
```
```
$ git clone <url> # 閹风柉绀夐崚顐℃眽閻ㄥ嫪绮ㄦ惔锟�
```
### 3.3 閺傚洣娆㈤悩鑸碘偓锟� --> `git add` 閸滐拷 `git commit`<br>
## 閻焦绁﹂敍锟�
```
$ git add .
$ git commit -m ""
# 鐏忚精绻栨稊鍫熸偠鐏忓崬鐣禍瀣╃啊
```
#### 闂堢偟娓峰ù渚婄窗
娴犳挸绨遍崘鍛畱閺傚洣娆㈤崗杈ㄦ箒閸ユ稐閲滈悩鑸碘偓渚婄礉<b>閺堫亣绐￠煪锟�</b>閿涳拷<b>閺堫亙鎱ㄩ弨锟�</b>閿涳拷<b>瀹歌弓鎱ㄩ弨锟�</b>閿涳拷<b>閺嗗倸鐡�</b>閵嗭拷
閸忚埖鏋冩禒鎯版祮閹广垻濮搁幀浣告禈婢堆嗗毀婵″倷绗呴妴锟�<br>
![sequ](res/sequenceFile.png)<br>
* 瑜版挻鏌婂杞扮娑擃亙绮ㄦ惔鎿勭礉閹存牕鎮滄禒鎾崇氨濞ｈ濮炴稉鈧稉顏呮煀閻ㄥ嫭鏋冩禒鑸垫閿涘矁绻栨稉顏呮瀮娴犳湹绱版禒锟�<b>`閺堫亣绐￠煪锟� <Untracked files>`</b>閻樿埖鈧礁鐡ㄩ崷銊ｂ偓锟�
* 瑜版挸顕禒鎾崇氨閸愬懐娈戦弬鍥︽鏉╂稖顢戞穱顔芥暭閸氬函绱濋弬鍥︽缁鐎锋导姘綁娑擄拷<b>`瀹歌弓鎱ㄩ弨锟� <Changes not staged for commit>`</b>閻樿埖鈧降鈧拷
* 閹存垳婊戞＃鏍у帥闂団偓鐟曚椒濞囬悽锟�<b>`"git add <file>"`</b>閹达拷<b>`"git add ."`</b>閿涘牏鍋ｆ禒锝堛€冭ぐ鎾冲閻╊喖缍嶉崣濠傚従鐎涙劗娲拌ぐ鏇炲敶閸忋劑鍎撮弬鍥︽閿涘绱濇担鑳箹娑撱倗顫掔猾璇茬€烽惃鍕瀮娴犺绱濋崣妯诲灇<b>`閺嗗倸鐡� <Changes to be committed>`</b>閻樿埖鈧降鈧拷

闁俺绻�<b>`"git status"`</b>閸涙垝鎶ら弻銉ф箙娴犳挸绨遍悩鑸碘偓渚婄窗
```
$ git status    # 閺屻儳婀呮禒鎾崇氨閻樿埖鈧拷
----------------- 娴犮儰绗呮稉楦跨箲閸ョ偘淇婇幁锟� -------------------------------------------
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:    # 閺嗗倸鐡ㄩ惃鍕瀮娴狅拷
  (use "git restore --staged <file>..." to unstage)
        new file:   gitadd.txt

Changes not staged for commit:  # 瀹歌弓鎱ㄩ弨鍦畱閺傚洣娆�
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:    # 閺堫亣鎷烽煪顏嗘畱閺傚洣娆�
  (use "git add <file>..." to include in what will be committed)
        newfile.txt
---------------------------------------------------------------------------
# 娑撯偓閼割剚鍎忛崘鍨櫐閻愮瀚崇拠顓㈠厴閸欘垯浜掗惇瀣櫐娴犫偓娑斿牊鍓伴幀锟�
```

瑜版挻鏋冩禒鍫曞厴閹存劒璐�<b>`閺嗗倸鐡� <Changes to be committed>`</b>閻樿埖鈧礁鎮楅敍灞惧灉娴狀剙姘ㄩ崣顖欎簰娴ｈ法鏁�<b>`"git commit -m "<update notes>"`</b>閹绘劒姘︽禍鍡愨偓鍌涘閺堝娈戦弬鍥︽娑旂喖鍏樻导姘綁閹存劖婀穱顔芥暭閻樿埖鈧降鈧拷

<b>`"git log"`</b> 閸欘垯浜掗弻銉ф箙閹碘偓閺堝娈戦幓鎰唉閸樺棗褰堕妴锟�<b>`"git reset head~ --soft"`</b>閸欘垯浜掗幘銈夋敘娑撳﹣绔村▎鈩冨絹娴溿們鈧拷
```
& git log                       # 閺屻儳婀呴幓鎰唉鐠佹澘缍�
commit 9b26f8a111af2cb509a4b8269b42b23289a54769 (HEAD -> main, origin/main)
Author: sunlin <123@163.com>
Date:   Fri Jul 14 00:34:34 2023 +0800

    update README.md

commit d25b1dd69e6c31e07b3830d95ce4cf4b9c5a8d02
Author: sunlin <zbsl1@163.com>
Date:   Thu Jul 13 23:30:18 2023 +0800

    update
.....
$ git reset head~ --soft        # 閹俱倝鏀㈡稉濠佺濞嗏剝褰佹禍锟�
$ git log                       # 閺屻儳婀呴幓鎰唉鐠佹澘缍�
commit d25b1dd69e6c31e07b3830d95ce4cf4b9c5a8d02 (HEAD -> main)
Author: sunlin <zbsl1@163.com>
Date:   Thu Jul 13 23:30:18 2023 +0800

    update
...
```
瀵板牊妲戦弰鎯у讲娴犮儳婀呴崙鐚寸礉閺堚偓鏉╂垹娈戞稉鈧▎鈩冨絹娴溿倛顫﹂幘銈夋敘娴滃棴绱濋崥灞炬閺傚洣娆㈤悩鑸碘偓浣风瘍閸欐ɑ鍨氭禍鍡樺絹娴溿倕澧犻惃鍕Ц閹降鈧拷<br>

### 3.4 闁剧偓甯存潻婊呪柤娴犳挸绨� GitHub
## 閻焦绁﹂敍锟�
鎼寸喕鐦芥稉宥咁樋鐠囪揪绱濋惄瀛樺复閻┇itHub鐎规ɑ鏌熼弫娆戔柤閵嗭拷<br>
![remote](res/remote.png)<br>

### 鐠囨潙鐤勭拠婵撶礉閸掓媽绻栭柌灞芥皑閻喓婀＄€瑰苯鍙忔径鐔烘暏娴滃棎鈧拷
## 閸ョ姳璐熸潻娆庨嚋閺佹瑧鈻肩亸杈ㄦЦ鏉╂瑤绠瀙ush娑撳﹥娼甸惃鍕┾偓锟�

### 3.5 閸掑棙鏁� branch
#### 娴犫偓娑斿牊妲搁崚鍡樻暜閿涳拷

#### 濡備綍鎿嶄綔鍒嗘敮锛�