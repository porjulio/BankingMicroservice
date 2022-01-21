# BankingMicroservice
Capstone Proj for DevOps Training
By: Kevin Lawrence C. Manipula
Date: 21/01/2022 DD-MM-YYY

1366  git clone https://github.com/porjulio/BankingMicroservice.git
 1367  ls
 1368  cd BankingMicroservice/
 1369  mvn archetype:generate
 1370  ls
 1371  ls capstone/
 1372  ls capstone/src/
 1373  ls capstone/src/test/
 1374  ls capstone/src/test/java/\
 1375* ls capstone/src/test/java/com/bankingmicro/AppTest.java 
 1376  cd ..
 1377  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 >> token.txt
 1378  echo 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 >> token.txt
 1379  ls
 1380  cd BankingMicroservice/
 1381  git status
 1382  git add .
 1383  git commit -am "commit"
 1384  git config --global user.email "kevincezar28@gmail.com"
 1385  git config --global user.name "porjulio"
 1386  git commit -am "commit"
 1387  git push
 1388  git checkout dev1
 1389  echo "Developed by dev1" >> dev1.txt
 1390  git add dev1.txt
 1391  git commit -m "commit made by dev1"
 1392  git push -u origin dev1
 1393  git checkout dev2
 1394  echo "Developed by dev2" >> dev2.txt
 1395  git add dev2.txt
 1396  git commit -m "commit made by dev2"
 1397  git push -u origin dev2
 1398  git checkout main
 1399  git checkout master
 1400  git merge dev1
 1401  git merge dev2
 1402  git push -u origin master
 1403  mvn package
 1404  ls
 1405  ls capstone/
 1406  cd capstone/
 1407  mvn package
 1408  ls
 1409  cd ..
 1410  git push
 1411  git add .
 1412  git commit -am "commit"
 1413  git push
 1414  cat /root/.ssh/id_rsa.pub
 1415  git add .
 1416  git commit -am "commit"
 1417  ls
 1418  cat README.md 
 1419  nano README.md 
 1420  git add .
 1421  git commit -am "commit"
 1422  git push
 1423  git remote -v
 1424  git remote set-url origin
 1425  git remote set-url origin git@github.com:porjulio/BankingMicroservice.git
 1426  nano README.md 
 1427  git add .
 1428  git commit -am "commit"
 1429  git push
 1430  cd ..
 1431  systemctl status jenkins
 1432  apt update
 1433  java -version
 1434  sudo ufw allow 8080
 1435  vi /etc/sudoers
 1436  history

