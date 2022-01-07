### Over the wire passwords
  
bandit0		bandit0  
bandit1 	boJ9jbbUNNfktd78OOpsqOltutMc3MY1  
bandit2		CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9  
bandit3		UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK  
bandit4 	pIwrPrtPN36QITSp3EQaw936yaFoFgAB  
bandit5		koReBOKuIDDepwhWk7jZC0RTdopnAYKh  
bandit6		DXjZPULLxYr17uwoI01bNLQbtFemEgo7  
bandit7		HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs  
bandit8		cvX2JJa4CFALtqS87jk27qwqGhBM9plV  
bandit9		UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR		sort | uniq -u (command to find only unique occurances)  
bandit10	truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk 		strings command  
bandit11 	IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR		regex for finding base64 texts (grep -E '[A-Za-z0-9+/]{4}*([A-Za-z0-9+/]{4}|[A-Za-z0-9+/]{3}=|[A-Za-z0-9+/]{2}==)')  

bandit12 	5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu		rot 13 cipher tr '[a-zA-z]' '[n-za-mN-ZA-M]'  
bandit13	8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL		reversing a hexdump and many other decompressions => http://hexjump.blogspot.com/2014/12/bandit-level-12-to-level-13.html  
bandit14	4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e		ssh to server and get password from /etc/bandit_pass/bandit14
			4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e  

PicoCtf - g3duuj5eET%kLEV
bandit15	BfMYroe26WYalil77FoDi9qh59eK5xNr		echo password | nc localhost 30000  
bandit15	BfMYroe26WYalil77FoDi9qh59eK5xNr		echo password | nc localhost 30000
bandit16	cluFn7wTiGryunymYOu4RcffSxQluehd		use openssl command => openssl s_client -crlf -connect localhost:30001
bandit17	id_rsa file from openssl				nmap and then same as b16
bandit 18	kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd		diff b/w 2 files 
bandit19 	IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x		chain commands with ssh by putting them in 'quotes' 
bandit20 	GbKksEFF4yrVs6il55v6gwY5aVje5f0j		run command via setuid
bandit21 	gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr		set up nc with password from prev level and then run setuid
bandit22 	Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI		look at cron job find file and see path
bandit23 	jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n		run cronjob get md5sum 
bandit24 	UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ		made smol bash script which gets executed and gets password