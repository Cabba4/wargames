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