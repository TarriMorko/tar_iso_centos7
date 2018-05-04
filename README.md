# tar_iso_centos7
# Changelog

## [Unreleased]


## 1.0.0] - 2018-05-04


# 安裝方法
	mkdir /tmp/Hardening
	把 tar_iso_centos7.tar iso_chk_linux_centos7.sh create_iso_env_centos7.sh 放到 /tmp/Hardening
	chmod u+x create_iso_env_centos7.sh
	./create_iso_env_centos7.sh
		* 如果出現 Failed to execute operation: No such file or directory ，表示要關閉某服務時，該系統上沒有那種服務。既然沒有就不用關了。可忽略此訊息
	給帳號 sposXXX 設定一個密碼，預設是 1qaz2wsx  不改也可以
	重開機
	用 sposXXX 登入
	切換到 root
	執行 /tmp/Hardening/iso_chk_linux_centos7.sh
	在 /tmp/Hardening/ 裡面會產生一個 xxx_iso_chk_linux.txt
	

