# Documents
Fresh university graduates in 2020/2021 or up to March.2022 with major in ELECTRONICS, TELECOMMUNICATIONS, MECHATRONICS, AUTOMATION, COMPUTER SCIENCE, COMPUTER ENGINEERING, INFORMATION TECHNOLOGY, MATHEMATICS – COMPUTER SCIENCE, PHYSICS – ELECTRONICS, and PHYSICS – COMPUTER SCIENCE
• Good at English in both writing and speaking skills, distinguished competence, consistent in pursuing of excellence, professional behavior, and good relationships with others and society.
• Have strong passion in technical field, especially embedded software and application development, Multimedia development.
• Have logical thinking and explanation; be serious and mature in working attitude
• Have good working attitude, diligence, can-do attitude, proactive approach, team work spirit and creativity.
• Long term working commitment (at least two years after completion of the training program) with company is a MUST.
## Software Test
Knowledge for Software test
• [Endian](https://embetronicx.com/tutorials/p_language/c/little-endian-and-big-endian/)
  - Little Endian: In Little-endian, LSB (Least significant byte) is stored to a `higher memory address`. Intel x86, Pentium are using this Little Endian. Thus, the little-endian byte order means, when the computer writes a word (Multi Byte) into memory, it begins by writing the Lowest byte to the lowest memory address and continues until it has written the highest byte to the highest memory address. It does this by writing subsequent and ascending memory addresses, no matter the endianness. Example 0x11223344
  - If you see the output, 0x44 (LSB) in the `Lowest Address` and 0x11 (MSB) in the `Highest Address`. So this system is the `Little Endian System`.

   ![image](https://github.com/hieunguyen0202/Upload/blob/main/Annotation%202023-11-28%20094339.png)

  ```c
  #include <stdio.h>
  
  int main(void)
  {
      unsigned int value = 0x1;
      char *r = (char *) &value;
   
      if (*r == 1) 
          printf("Your system is Little Endian\n");
      else
          printf("Your system is Big Endian\n");
      return 0;
  }
  ```
  > Byte High - Highest Address and Byte Low - Lowest Address
  - In Big Endian, MSB (Most significant byte) is stored to a lower memory address. Big-endian is implemented in PowerPC and most networking devices. The big-endian byte order means, when the computer writes a word (Multi Byte) into memory, it begins by writing the highest byte to the lowest memory address and continues until it has written the lowest byte to the highest memory address. Example 0x11223344
  - If you see the output, 0x44 (LSB) in the `Highest Address` and 0x11 (MSB) in the `Lowest Address`. So this system is the `Big Endian System`.
    
   ![image](https://github.com/hieunguyen0202/Upload/blob/main/Annotation%202023-11-28%20094325.png)
  
• Basic SW technical terms
• Basic mathematics
• SW design flow
• Binary, Hexadecimal, Decimal conversion
• Binary calculation
• True table
• C language – basic
  - [Data Type](https://www.geeksforgeeks.org/data-types-in-c/) in C
    
    ```c
    #include <stdio.h>

    int main() {
        char character = 'A';
        int integerNumber = 42;
        unsigned int unsignedNumber = 100;
        float floatingPoint = 3.14;
        double doubleNumber = 2.71828;
        char string[] = "Hello, World!";
        int *pointer = &integerNumber;
    
        printf("Character: %c\n", character);
        printf("Integer (decimal): %d\n", integerNumber);
        printf("Unsigned Integer: %u\n", unsignedNumber);
        printf("Floating Point: %f\n", floatingPoint);
        printf("Double: %lf\n", doubleNumber);
        printf("String: %s\n", string);
        printf("Pointer Address: %p\n", (void *)pointer);
    
        return 0;
    }

    ```
• C language – variables and pointers
• Interrupt
Knowledge for English test
• Grammar
• Reading
• Essay writing

- Technical Skills:
  - Programming Languages: C/C++, Python, Java, Linux, Bash script
  - Have a knowledge in Software Testing (C++/Python unit testing, integration test..
  - Exposure to Micro-controller or Microprocessor (STM32, Raspberry…
  - Strong in C/C++ programming language for embedded software, compiler, makefile
  - Microcontroller programing ( familiar with STM32, raspberry, nucleo)
  - Experience in simulators, debugging and test equipment.

- Soft Skills:
  - Well communication and reading document in English (TOEIC 855)
  - Excellent debugging & Problem-solving skills
  - Time Management and Teamwork
