### CoopOS

                
                Links:
                Same in German:                     https://github.com/MacLeod-D/CoopOS-Kurs-Deutsch
                With Stackframes (Arduino):         https://github.com/MacLeod-D/Arduino-Multitasking-CoopOS
                With Stackframes (ESP8266):         https://github.com/MacLeod-D/ESP8266-Multitasking-CoopOS
                
                
                

## This is the fast* and universal CoopOS-version without stackchange  for ALL CPUs -in English

                      
An extensive course, which starts very simple

   **Fast and powerful cooperative multitasking for Arduino-IDE**
   
   **8 Lessons with all sources** 
   
   **For Beginners und Professionals gleichermaßen**
   
   **Complete Sources**
   
   **60 Pages Documentation**
              
              
On more than **60 pages** of PDF-Documentation and 8 Demo sources **CoopOS** - a tool for cooperative multitasking - is presented in great detail and comprehensible for beginners.

Cooperative multitasking does not need its own stack for each task. Therefore, it is so compact that it works even on an **AtTiny45**!

Since the stack areas and thus the processor registers are not switched, CoopOS is extremely fast.

In addition, it contains many options that are otherwise only found on RTOSs:

            * while (1) {...}
            * taskSwitch
            * taskDelay
            * taskStop
            * taskResume
            * taskWaitSignal
            * taskSetSignal (also from interrupt routines)
            * taskWaitResource
            * taskFreeResource

It just annoyed me that it seems to be modern to declare RTOS for the sacred cow, whose results
can not be achieved with cooperative multitasking - because that's nonsense!

Certainly, I did not want to do without an RTOS in embedded systems where it exists.
But CoopOS is available even when space is tight - and easily offers the possibility of 10 tasks
where an RTOS does not exist.

Another advantage is the complete independence of the processor type.
The programs are very easy to transfer.

And it can complement a RTOS well - especially where there are multiple processor cores.

The lssons parts 0-6 run on each processor - without change - for which the Arduino IDE is available!

The best method is:
Read PDF, then - when prompted - execute the corresponding course part in the Arduino IDE.

Although executable with each processor, one obtains particularly impressive results with an ESP8266,
to which also the demo pictures refer.

It is strongly recommended to use a Logic Analyzer or an oscilloscope. Simple versions are
enough! Who dares: in China there are very cheap clones;)

Installation:

The PDF can be read directly.
The demos should be unzipped directly into the Arduino-Sketches folder.

http://HelmutWeber.de
