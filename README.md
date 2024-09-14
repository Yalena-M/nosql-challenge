# nosql-challenge
notes
#net user administrator /active:yes
#"C:\Program Files\MongoDB\Server\7.0\bin\mongod.exe" --dbpath="c:\data\db"
#mongosh
#import establishments.json file  :
mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json



# Command Prompt: first run administration
# second cd:
# C:\Windows\System32>cd C:\Users\jacya\.ssh\.ssh\nosql-challenge\Resources
# import:
# C:\Users\jacya\.ssh\.ssh\nosql-challenge\Resources>mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
