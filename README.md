# new-project-on-modification-of-bank-management-system
#its a project on basis of the regular banking working structure

import mysql.connector as mycon
connection = mycon.connect(
    host = "localhost",
    user = "root",
    paswd = "root",
    database ="bank",
)
cursor = connection.cursor()
cursor.execute()
cursor.commit()
