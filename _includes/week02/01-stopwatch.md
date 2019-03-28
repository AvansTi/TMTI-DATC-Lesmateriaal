>> ### Exercise 2-1 Stopwatch
>>
>> Design a class named `StopWatch`. The class contains:
>>
>> * Private data fields `startTime` and `endTime`, including getters.
>> * A constructor without any parameters that initialize the `startTime` with the current time.
>> * Method `void start()` thats reset the `startTime` to the current time.
>> * Method `void stop` that sets the `endTime` to the current time.
>> * Method `getElapsedTime()` that returns the elapsed time for the stopwatch in miliseconds.
>>
>> Implement the class. Write a test program that measure the execution time of sorting 100000 numbers using [sort](http://www.cplusplus.com/reference/algorithm/sort/).
>>
>> ```cpp
>> bool search(std::string& s, char& key);
>> ```
>>
>> Write a test program that prompts the user to enter the string and character and display if the character is found.
>>
>>> hint: Take a look at the [high resolution clock](https://en.cppreference.com/w/cpp/chrono/high_resolution_clock).
>>{: .tip}
>>
>{: .exercise}