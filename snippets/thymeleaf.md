${stu.studentId}    

````java   
<tr th:each="student: ${std}">
   <td th:text="${student.studentId}"/>
````   

````java    

    @GetMapping("/")
    public String index(Model model) {
        model.addAttribute("std", students);
        return "index";
    }

````   
