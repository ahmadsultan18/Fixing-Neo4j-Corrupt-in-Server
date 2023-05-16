# Fixing-Neo4j-Corrupt-in-Server
Fixing when u are already deleted the file before

#checking if there any running proccess in server
ps -ef | grep neo4j

#if there are running

'''kill -9 <Your PID>'''

#check if there still run or not
ps -ef | grep neo4j
