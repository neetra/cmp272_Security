# Assignment 7 : Security
 - Team Name : Hakkuna Matata
 - Team Memebers : Zi Shun Yang, Rohan Patel,  Netra Amrale, Govinder Somal
 
 # Steps 
 - Clone repo and create root CA

    ![Step 1](output/1.png)
    
    ![Step 2](output/2.png)
 -  Create operating CA   
    ![Step 3](output/3.png)
- Create TLS Certificate    
    ![Step 4](output/4.png)
- Revoke certificate    
    ![Step 2](output/5.png)
- Create PKC12 certificate    
![Step 2](output/6.png)
- Create keystore
- Verify certificate in keystore 
    ![Step 2](output/7.png)
    ![Step 2](output/8.png)  
- Add entry in /etc/tomcat9/server.xml
    ![Step 2](output/servel.xml.confiuration.png)    
- Restart tomcat server
    ![Step 2](output/9.png)
- Now, tomcat server runs successfully on HTTPS
      ![image](output/outputimage.png)

