# tar_iso_centos7
# Changelog

## [Unreleased]


## [0.1.0] - 2018-05-02


# 安裝方法
	1. mkdir /tmp/Hardening
	2. 把 tar_iso_centos7.tar  跟 create_iso_env_centos7.sh 放到 /tmp/Hardening
	3. chmod u+x create_iso_env_centos7.sh
	4. ./create_iso_env_centos7.sh
		* 如果出現 Failed to execute operation: No such file or directory ，表示要關閉某服務時，該系統上沒有那種服務。既然沒有就不用關了。可忽略此訊息
	5.  給帳號 spos2 設定一個新的密碼 passwd spos2
	6.   重開機
	7.   用spos2 登入
	8.   切換到 root
	9.   執行 /tmp/Hardening/iso_chk_linux_centos7.sh
	10.  在 /tmp/Hardening/ 裡面會產生一個 xxx_iso_chk_linux.txt

