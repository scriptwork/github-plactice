github-plactice
===============

GitHub練習中のメモです。

Gitクライアントは Emacs + Magit で試行錯誤中。


SSH鍵の生成
---

	% ssh-keygen
	
	Generating public/private rsa key pair.
	Enter file in which to save the key (/home/user/.ssh/id_rsa):
	Created directory '/home/user/.ssh'.
	Enter passphrase (empty for no passphrase): **********
	Enter same passphrase again: **********
	
	Your identification has been saved in /home/user/.ssh/id_rsa.
	Your public key has been saved in /home/user/.ssh/id_rsa.pub.
	The key fingerprint is:
	66:83:fe:73:c0:24:88:0c:df:9e:1f:ef:6f:7d:7b:63 user@linux
	The key's randomart image is:
	+--[ RSA 2048]----+
	|                 |
	|.                |
	| + o .           |
	|  + o ...        |
	|   . ..+S        |
	|    o..oo.       |
	|     ..o . .     |
	|      ..o o . .E.|
	|       .o=.  .oo.|
	+-----------------+


.gitconfig 設定
---

	git config --global user.name "ユーザー名"
	git config --global user.email メールアドレス


練習用リポジトリのクローン
---

	git clone git://github.com/scriptwork/github-plactice.git
