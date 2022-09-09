# day-37-mongodb-task-2


Quaries:


db.topics.find({schedule:"june"})


db.tasks.find({schedule:"july"})


db.codekata.find({},{codekata_solved:1,name:1})


db.mentor.find({mentees:{$gt:15}})


db.company_drives.find({date:{$gt:ISODate("2022-10-15T00:00:00Z"),$lt:ISODate("2022-11-20T00:00:00Z")}},{placement:0})


db.company_drives.find({},{company_name:1,placement:1})


db.attendance_new.find({date:{$gt:ISODate("2022-06-15T00:00:00Z"),$lt:ISODate("2022-06-30T00:00:00Z")},attendance:"apsent"})
