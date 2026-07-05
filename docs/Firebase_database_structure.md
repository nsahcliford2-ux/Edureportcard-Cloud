# Firebase Database Structure

## Collections

### schools
- schoolId
- schoolName
- motto
- address
- phone
- email
- logo
- createdAt

### users
- userId
- fullName
- email
- phone
- role
- schoolId
- active

### students
- studentId
- admissionNumber
- fullName
- gender
- dateOfBirth
- classId
- parentName
- parentPhone
- schoolId

### teachers
- teacherId
- fullName
- email
- phone
- subjects
- classes
- schoolId

### classes
- classId
- className
- section
- classTeacher

### subjects
- subjectId
- subjectName
- classId

### results
- resultId
- studentId
- subjectId
- term
- session
- CA
- Exam
- Total
- Grade
- Remark

### attendance
- attendanceId
- studentId
- date
- status

### report_cards
- reportCardId
- studentId
- term
- session
- average
- position
- pdfUrl
