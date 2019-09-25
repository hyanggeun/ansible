1. m1, m2 => web그룹
2. m3 =>db그룹

=========first.yml=========
3. web 그룹에서 httpd 제거
   db그룹에서 maria-server제거

========second.yml=========
4. web그룹에 httpd 구성
5. /var/www/html/index.html ==> ansible 
curl m1 ==> ansible이라는 페이지가 나오도록해라

2. db그룹에 mariadb-server구성