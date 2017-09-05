${stu.studentId}    


<tr th:each="student: ${std}">
   <td th:text="${student.studentId}"/>
