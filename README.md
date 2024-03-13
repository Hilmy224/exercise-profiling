## MODULE 05  REFLECTION

### == J meter TestPlans == 
> Before optimisation
+ GUI Test_Plan
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/17c41c57-768a-40f5-b522-f44180659541)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/b721df2a-8083-4973-a992-d73acf31fd13)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/c0291471-701a-4213-b18a-93d9842e9cbe)

+ CLI Test Plan
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/3aed498e-2eba-46e7-ad44-b8c7af565b99)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/8b9adbc1-f090-42f0-9ec2-4799a3eb4ba3)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/dfb7a28f-8f4f-4f6d-99ea-ebaaf6bc230e)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/1b05fcf4-6c89-473c-b969-36b43de9ff5b)



### == Java profiling ==
+ Base `/all-student`
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/1bf51b57-650e-43fb-9e25-f247270c6a0c)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/9fe6fbac-12df-4594-b863-45c953e0323d)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/9a86c0f3-f5f8-4c83-901a-2bf483a8c70e)

+ Optimized `/all-student`
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/2bd1f4df-2406-4dc8-8407-e2a7b9a60c2e)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/bdb14c87-75b9-49ce-ac4f-29052c1d3dcf)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/f3a75c7d-ddc3-4f21-ba29-4e25d2f76463)

+ Base `/all-student-name`
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/5a5768b3-9a95-4b54-8285-93f44310b2a1)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/5ec62fe4-3b3f-45b5-8329-a7cfe9495d6c)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/ce1ab22e-9ab9-47c3-8cc7-ef7878a86d3c)

+ Optimized `/all-student-name`
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/0e435f67-42e9-4acd-8e8b-4190f8b0f458)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/26a4db15-e24b-4fda-aa73-3478ea8ddf41)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/7afed996-7e42-4bb4-9caa-e02124a9aac9)

+ Base `/highest-gpa`
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/ba4d9242-48f8-4575-9a63-e6eaa967db37)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/866dbb50-58f8-45d0-9467-266405e379e2)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/bc7e58fb-af26-49a9-8a28-d1a6c02b0a8b)

+ Optimized `highest-gpa`
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/baa9d2d1-bf95-466d-be17-184174b8e451)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/9edc2163-1172-4165-a575-1dc0e7a46a83)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/64ac1d5f-bcf7-4a0d-b0ee-20be098bc661)

### == J meter TestPlans == 
> After optimisation
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/19ef95a4-84d6-4636-acc0-3895f43604ec)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/4f1dd93e-fe28-4f2f-a570-16e1daf530e7)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/7e1e3acb-bfae-4b33-87d7-1fa3e2b8af01)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/5b8e7ef9-fc96-4594-8433-61809aac2131)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/3d2154ef-2352-4fa7-8463-676cd73c2864)
![image](https://github.com/Hilmy224/exercise-profiling/assets/108089955/fec1600d-005e-46cc-b8bf-1176da3e4a1f)

### Reflection 
1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance? <br>
   JMeter perfomance test reveals general statistics while Intellij's Profiler provides detailed insights that can help developers make targeted optimisation.
2. How does the profiling process help you in identifying and understanding the weak points in your application? <br>
   With Intellij's Profiling it helps me accurately which part of the code I need to optimise. Intellij also provides a variety of ways to present the profiler data such as flame graph, Tree view, Timeline view, method list, and Events. For example with method list i can see the order of Elapsed time for each function.
3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code? <br>
   Yes I think Intellij Profiler is excellent in analyzing and identiying bottle necks within the application.
4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges? <br>
   The main challenges I find myself struggling are identifying whether performance issues are genuine bottlenecks or false alarms can be  quite challenging. Another issue are large and complex applications may require more intricate analysis, making it harder to pinpoint specific performance issues.
5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code? <br>
   Intellij's built in profiler provides detailed information about code performance while also offering various visualization options such as flame graphs, tree views, and timelines. Other benefits could be because it is a built in profiler developers can comfortably peform profiling within a familiar IDE enviroment.
6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter? <br>
    First is to make sure I set up the profiling/testing correctly and also adhere to best pracitices when using them, afterwards close any application that may cause overheads. It is also good to consider that JMeter works diffrently than profiling where JMeter stimulates external user interaction whilst profiling.
7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality? <br>
   A good startegy is to identify and priotize optimizing critical or significant bottle necks and to make sure the refactored code does not introudce any new bugs or negatively impact the applications functionality it is best practice to run the test to ensure that does not happen.
