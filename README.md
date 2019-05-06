# cs301


###############################################################
1.用wisc ip 连接chtc database
cd ./hcai43_project
docker-compose up -d mysql

./mysql/mysql.sh

SELECT * FROM users;' | ./mysql/mysql.sh

docker-compose stop mysql

###############################################################
2.用terminal git 使用github private-report 里的文件和代码
cd chtc/private-reports/data/hrs

python scripts/xls_to_csv.py data/xls/2018-2019_365.xls

python scripts/chtc_hrs.py data/csv/2016_365.csv
