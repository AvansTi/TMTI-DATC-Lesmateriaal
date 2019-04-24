>> ### Exercise 3-1 Dynamic array
>>
>> Revise the `Course` class implementation given on the Github examples in week 3 (HelloConstructor) as follows:
>>
>> * When adding a student to the course, check if the array capacity is execeeded, increase the array size by creating a new larger array and copying the contents of the current array to it.
>> * Implement the `dropStudent` function.
>> * Add a new function named `clear()` that removes all students from the course.
>> * Implement the destructor and copy constructor to perform a deep copy in the class.
>>
>> Write a test program that creates a course, add three students, removed one and display the students in the course.
>>
>> ```cpp
>> bool search(std::string& s, char& key);
>> ```
>>
>> Write a test program that prompts the user to enter the string and character and display if the character is found.
>>
>{: .exercise}