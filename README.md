SysHX08
=======

HC08 like soft-processor system

The SysHX08 purpose is to collect and develop resources useful for designing and implementing 68HC08 like systems, using a hardware description language (HDL) based version of the processor. As of this writing the HC08, is still a current processor. Note that the 6808 was a variant of the 6802 processor. While it's unclear if tools were ever developed for the 6808, software developers have the confusing penchant for choosing names in reference to that other processor. The name of this project includes HX08 for the dual purposes of respecting Freescale and to distance itself from the 6808.

The intent of this project is that such systems will be configured into a field programmable gate array (FPGA) and will executes machine code in the same manner as other processors. The primary motivation for this project is teaching undergraduate students basic computer engineering concepts and provide practical experience in the design, implementation, and test a microprocessor based system.

The letters "Sys" in the name are borrowed from John Kent's System09 project, which inspired this project. Also, the word, "soft" is deliberately not used in the name. While a hard-ware description language is used, which is similar to software, the result can be used to configure hardware, which will execute software in real-time. Unless otherwise stated, content written for this project and posted here whill have a GPL license applied. Other content collected here will be licensed according to terms idicated by its author.

The use of modules in schematics is an option, allowing students to use schematics to design and implement a system. In other words, each component in the system is described with a HDL file, which is provided. Each instance of the component that students use can be represented as a block in a schematic. This project includes resources and practical examples for students to study. Such resources can also be used with independent student projects.
