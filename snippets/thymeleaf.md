
````java    

    @GetMapping("/")
    public String index(Model model) {
        model.addAttribute("std", students);
        return "index";
    }

````  


````java   
   ${stu.studentId} 
````    

````java   
<tr th:each="student: ${std}">
   <td th:text="${student.studentId}"/>
````   
 
* [Standard Expression Syntax](http://www.thymeleaf.org/doc/tutorials/2.1/usingthymeleaf.html#standard-expression-syntax)
