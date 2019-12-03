# 1.
```
John is analyzing strange behavior on computers in his network. 
He believes there is malwareon the machines.
The symptoms include strange behavior that persists,
even if heboots the machine to a Linux Live CD. 

What is the most likely cause?
A. Ransomware (勒索軟體)
B. Boot(啟動區) sector virus
C. Rootkit   
D. Key logger  (鍵盤側錄)

analyzing    strange behavior   malware    include  symptoms    machines
分析          奇怪的    行為     惡意軟體     包含     徵狀          機器
  
答案:B(最有可能的原因)
```

# 2. 
```
Ahmed is a sales manager with a major insurance company. 
He has received an email thatis encouraging him to click on a link and fill out a survey. 
He is suspicious of the email,
but it does mention a major insurance association, 
and that makes him think it might be legitimate.

Which of the following best describes this attack?
A. Phishing  (網路釣魚(不分對象))
B. Social engineering  (社交工程)
C. Spear phishing (魚叉式網路釣魚)
D. Trojan horse(特洛伊木馬)

sales    manager     suspicious     association   encouraging     link     legitimate
 銷售     管理者         懷疑            保險          鼓勵          連結        合法
 Which of the following     best     describes
     下列何者                最佳       描述
                            
 答案:C (特定對象)
```
# 3. 
```
You are a security administrator for a medium-sized bank. 
You have discovered a piece of software on your bank’s database server that is not supposed to be there.
It appears that the software will begin deleting database files if a specific employee is terminated.


What best describes this?
A. Worm(蠕蟲)
B. Logic bomb
C. Trojan horse
D. Rootkit

medium-sized   bank    a piece of   database    supposed 
  中型          銀行      一塊        數據庫      應該
appears    begin   deleting  specific   employee    terminated
  出現      開始     刪除中     具體       員工        已終止
    

```
# 4.
```
You are responsible for incident response at Acme bank. The Acme bank website has been attacked. 
The attacker used the login screen, 
but rather than enter login credentials, 
he or she entered some odd text: ' or '1' = '1. 

What is the best description for this attack?
A. Cross-site scripting
B. Cross-site request forgery
C. SQL injection
D. ARP poisoning

responsible  incident   response  website   rather    credentials
負責任的        事件        響應      網站     寧可         證明
```
# 5.
```
Juanita is a network administrator for a small accounting firm. 
The users on her network are complaining of slow connectivity. 
When she examines the firewall logs, 
she observes a large number of half-open connections. 

What best describes this attack?
A. DDoS
B. SYN flood
C. Buffer overflow
D. ARP poisoning


complaining    firm     accounting   observes    connectivity
   抱怨         公司        會計        觀察          連接
 examines    connections
   檢查         連線
   
答案:B (一堆半開放的連線)
   
```

# 10.

```
Your company outsourced development of an accounting application to a local programming firm. 
After three months of using the product, 
one of your accountants accidently discovers a way to log in and bypass all security and authentication. 


What best describes this?

A. Logic bomb (邏輯炸彈)
B. Trojan horse
C. Backdoor   (後門程式)
D. Rootkit


 outsourced  development   accounting  accidently  product   bypass
     外包       發展          會計        偶然地       產品      繞過
 discovers    way
    發現      方法
     
     
答案:c ()

```
# 61. 
```
You are performing a penetration test of your company’s network. 
As part of the test, you will be given a login with minimal access and will attempt to gain administrative access with this account.

What is this called?

A. Privilege escalation(特權提升)
B. Session hijacking(工作階段攔截)
C. Root grabbing
D. Climbing

performing    penetration test    part   given   minimal      access
    執行            滲透測試        部分   給予     最小的       訪問
  attempt       gain       account
    嘗試        獲得        帳戶
    
    What is this called?(這個行為叫甚麼?)
    
    答案:A(得到管理員帳戶)
    
```

# 62.
```
Mary has discovered that a web application used by her company does not always handle multithreading properly, 
particularly when multiple threads access the same variable.
This could allow an attacker who discovered this vulnerability to exploit it and crash the server. 

What type of error has Mary discovered?
A. Buffer overflow (緩衝區溢位)
B. Logic bomb  (邏輯炸彈)
C. Race conditions (資源競爭)
D. Improper error handling

discoverded  handle   multithreading   properly
  發現        處理          多執行緒     適當地
   
particularly   multiple threads     same  variable
    尤其            多執行緒         相同     變量
   
 allow    discovered   vulnerability  exploit  crash
  允許        發現        脆弱性         利用    崩潰
  
  答案:A(利用發現的弱點讓伺服器崩潰)
```

# 63.
```
An attacker is trying to get access to your network. 
He is sending users on your network a link to a freeware stock-monitoring program.
However, 
that stock-monitoring program has attached to it software that will give the attacker access to any machine that it is installed on. 

What type of attack is this?
A. Rootkit  (隱藏其他程式行程的軟體)
B. Trojan horse
C. Spyware  (間諜軟體)
D. Boot sector virus (開機型病毒)

sending   freeware   program    However  software
 發送      免費軟體    程序       然而      軟體
 
 答案:C
```

# 64.

```
Acme Company uses its own internal certificate server for all internal encryption.
However,
their certificate authority only publishes a CRL once per week

Does this pose a danger, and if so what?

A. Yes, this means a revoked certificate could be used for up to seven days.
B. No, this is standard for all certificate authorities.
C. Yes, this means it would be easy to fake a certificate.
D. No, since this is being used only internally.

internal  own    certificate   encryption
  內部    擁有       證書         加密
authority   publishes   once    per     CRL
  權力        公布       一旦     每   證書吊銷列表
 danger   means revoked  standard   authorities
  危險    方法   被撤銷    標準         當局
  
  答案:A(7天發布一次吊銷列表 所以失去效力的最多可以使用七天)
```

# 65.

```
When a program has variables, 
especially arrays, 
and does not check the boundary values before inputting data, 

what attack is the program vulnerable to?
A. XSS (過利用網頁開發時留下的漏洞，通過巧妙的方法注入惡意指令程式碼到網頁)
B. CRSF (跨站請求偽造)
C. Buffer overflow (緩衝區溢位)
D. Logic bomb

vulnerable   boundary   values  inputting  variables
    弱點        邊界     價值       輸入       變數
especially    arrays
    特別       矩陣
    
  答案:c(程式設計缺陷)
```
