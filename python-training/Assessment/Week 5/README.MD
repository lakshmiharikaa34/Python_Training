#  Week 5 Assessment

##  Section 1: Multiple Choice Questions

### 1. **Which of the following is used to open a file for reading in Python?**
- ✅ open('file.txt', 'r')
- B. open('file.txt', 'w')
- C. open('file.txt', 'a')
- D. open('file.txt', 'x')

### 2. **What method is used to read all lines from a file into a list?** 
- A. read()
- B. readline()
- ✅ readlines()
- D. readfile()

### 3. **Which function is used to install external Python libraries?** 
- A. get
- B. request
- ✅ pip
- D. import

### 4. **What keyword is used to define a class in Python?** 
- A. function
- B. def
- C. struct
- ✅ class

### 5. **What is the correct method name for object initialization in a class?** 
- A. `__create__`
- ✅ `__init__`
- C. `constructor()`
- D. `init()`

### 6. **Which of the following will write data to a file and overwrite existing content?** 
- A. open('file.txt', 'a')
- B. open('file.txt', 'r')
- C. open('file.txt', 'x')
- ✅ open('file.txt', 'w')

### 7. **Which module is used to work with CSV files in Python?** 
- A. os
- B. json
- ✅ csv
- D. file

### 8. **Which method in unittest module is used to check if two values are equal?** 
- A. assertSame()
- ✅ assertEqual()
- C. assertTrue()
- D. assertCompare()

### 9. **In requests module, which method is used to send a POST request?** 
- A. requests.fetch()
- B. requests.get()
- ✅ requests.post()
- D. requests.send()

### 10. **What is the output of `type([])`?** 
- ✅ <class 'list'>
- B. <class 'tuple'>
- C. <class 'dict'>
- D. <class 'set'>

### 11. **Which method is called when an object is deleted in Python?** 
- A. `__remove__`
- ✅ `__del__`
- C. `__destroy__`
- D. `__delete__`

### 12. **What is the correct way to write a dictionary to a JSON file?** 
- A. json.write(file, dict)
- B. file.write(json(dict))
- ✅ json.dump(dict, file)
- D. file.dump(dict, json)

### 13. **Which access modifier is used for private members in Python?** 
- A. _
- B. __
- ✅ private
- D. protect

### 14. **How do you handle setup and teardown in unittest?** 
- A. init() and destroy()
- B. start() and stop()
- ✅ setUp() and tearDown()
- D. begin() and end()

### 15. **Which request method is used to fetch data from a REST API?** 
- ✅ GET
- B. POST
- C. PUT
- D. PATCH

### 16. **What is the result of `open('file.txt', 'w+').read()` if file exists?**
- A. FileNotFoundError
- B. File content
- ✅ ''
- D. None

### 17. **Which of the following best describes method resolution order (MRO)?** 
- A. The order in which methods are compiled
- ✅ The order of method inheritance in multiple inheritance
- C. The order classes are defined
- D. None of the above

### 18. **What is the result of `json.loads('{"a":1, "b":2}')['c']`?** 
- ✅ KeyError
- B. None
- C. 'c'
- D. 0

### 19. **Which of these methods from `unittest.TestCase` checks if a statement raises an error?** 
- ✅ assertRaises()
- B. assertThrows()
- C. expectError()
- D. assertFail()

### 20. **Which method is used internally to return a string representation of an object?** 
- ✅ `__str__`
- B. `__repr__`
- C. `__display__`
- D. `__show__`

---

##  Section 2: Coding Questions

1.  Write a Python function that reads a file and prints its content.

2.  Write a class `Rectangle` with `length` and `width`, and a method to calculate area. Create an object and show usage.

3.  Write a unit test using `unittest` module to test a function `add(a, b)` that returns the sum of two numbers.

---