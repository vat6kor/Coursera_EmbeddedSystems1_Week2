
#### Coursera - Embedded Software - Course 1 Week 2 assignment <br /> ####

Vinay Sathyanarayana <br />

----

 Use: <br />
 `make [TARGET] [PLATFORM-OVERRIDES]`

 Example: <br />
 `$ make build PLATFORM=HOST 

----

* Build Targets:   
    * <FILE>.i - Generate <FILE>.i preprocessed output
    * <FILE>.asm - Generate <FILE>.asm assembly output
    * <FILE>.o - Builds <FILE>.o object file
    * compile-all - Compile all object files, but DO NOT link
    * build - Builds and links all source files
    * clean - Removes all generated files

----

* PLATFORM-OVERRIDES:
    * PLATFORM=HOST - Compile for HOST using gcc
    * PLATFORM=MSP432 - Compile for MSP432 using arm-none-eabi-gcc
