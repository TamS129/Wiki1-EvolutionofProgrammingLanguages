# The Evolution of C++ Programming Language
## Written by: Ken Cage, Jackson Kettel, Kelvin Rajbhandari, Tamara Slone
![Intro Image](Images/06ff5852-8877-4504-a8b2-a61f884ad8cd.webp)
## Introduction
The creation of the original C programming language was created by Dennis Ritchie in 1970 at Bell Labs. Once the C programming language had been introduced, other programmers within Bell Labs began experimenting with the capabilities of their new program. This experimentation would later lead Danish computer scientist Bjarne Stroustrup in 1979 to create an expansion of the C language that allowed for both high-level and low-level programming (also known as Middle-level programming) called C++.
![The Creator](Images/images.jpg)

## The History of C++
During his time working for Bell Labs, Bjarne Stroustrup was working on his PHD thesis for the Computing Laboratory of Cambridge University. He originally worked with a programming language known as Simula and enjoyed the object-oriented class structure that Simula provided. However, during his thesis Bjarne noticed that the programming language did not scale well for the simulator he had created. Although Simula did not help him complete his thesis. Simula would inspire Bjarne to create a new C language that would allow for programmers to build complex systems using high-level abstract programming while also having an ability to access the hardware using low-level programming. 
    
### Pre-Public Release 
### (1979 - 1983)
This idea would lead him to create the first iteration of C++ known as C with classes. The name C with classes refers to the class structures that were implemented into the language. C with classes was an extension of the C language that included the above-mentioned class structures, polymorphism, abstraction, and inheritance. C with classes allowed programmers to write modular and efficient code without the limitations that other high-level programs such as Simula had. Due to the fact that C with classes was a language built using the already existing C language, compilers had already been implemented for many platforms at the time. Making the portability of C with classes much easier for general use programming. C with classes also improved the security issues that the original C language had been struggling with at the time. Leading for more efficient and safer features than its original predecessor.
    
However, before C with classes was released to the public in 1983 the language was renamed to C++ by Rick Mascitti. The ++ referencing the increment operator that was actually not existent in the previous C language. This version of C++ would also be given more additional features to the language like virtual functions, improved type-checking and C++ style comments, and references.

### Post Public Release and Pre-Standardization 
### (1983 - 1991)
It wouldn’t be until 1985 when C++ would become a mainstream programming language with the release of the first edition manual of 'The C++ Programming Language’. During this time period would also bring new features to C++ with a new system called CFont. CFont would allow the translation of C++ into C programs which aided in the development of complex programs. There would be another upgrade to C++ in 1989 called C++ 2.0. This 2.0 addition would upgrade the stability of it's definitions and implementations. Some of these upgrades included multiple inheritences, type-safe linkage, improvements to overload functions and user-defined memory management. This verison to C++ also brought in big changes to the language with the addition of the ability to overload the operator and pointers to memebers. 

However, this verison of C++ would once again be updated in 1991 with the addition of C++ 3.0. Although this verison of C++ did not add a lot of changes to the orginal verison. One big feature that was included in 3.0 was class and function templates.  This verison of C++ would be the last update to the language before it's offical global standardization. Although there were plans at Bell Labs to realease another verison of the language called C++ 4.0 in 1993. The plans for this verison of C++ never were released.

### Standardization to Embedded C++
### (1991 - 2003)

The standardization of C++ began in the 1989 with the work of Hewlett-Packard with Bell Labs, DEC, and IBM. In 1991 ISO standarization of C++ 98 had become offical and joint meetings are still held today to dicuss how to improve the language. Standardization of C++ was important because it allowed adding in new features that improved the language and also fixed issues regarding programmers who could not use C++ because of dialect differences. One of the major changes regarding the addition of the Standard Template Library (STL). The STL would add many features such as Real-time type information, Cast operators, Bools, declarations in conditions, and more. However, C++98 would soon be replaced by C++03 in 2003 as the standard language for C++. C++03 didn't add any new features to C++. Instead C++ 03 was focused on bug fixes that allowed for better consistency and portability. 

During the same time of C++ 03's realease, Japanese companies Toshiba, Hitachi, Fujitsu, and NEC proposed for different subset of C++. This version of C++ would be known as Embedded C++. Embedded C++ was intended as a embedded systems programming language that restricted language features that could hurt performance or features that were precieved as too difficult for their programmers. Some of the features that were banned by Embedded C++ were multiple inheritance, templates, exceptions, RTTI, and more. This Embedded C++ was not recongized as a standardize language but it did encourage the committee to look into how many different ways C++ could be used to benefit businesses. The committee would release a technical report talking about the performance issues that C++ had current faced and would beginning planning on how to upgrade their language.

### C++11 to C++20
### (2011 - Present) 

After the realease of C++ 03 there would be a gap in time before the next verison of C++ would emerge. In 2011 C++ 11 would be released as the next standard version of C++. C++ 11 was a massive overhaul for the language and added a lot of new features. These features included Enum classes, template aliases, functions such as static_asert, lambdas, raw string literals, user-defined literals, and many other features that were added in. There was also a massive additions to the STL that allowed for an easier access to libraries. C++ 11 also improved it's efficency with allowing move semantics that limited the amount of unessiary copies of reasources within the code. Shortly after the release of C++ 11, in 2014 C++ 14 would be released. C++ 14 was implemented in order to "complete" C++11 and included even more features. Some of the new features would include function return type deduction, generic lambdas, binary literals, and more. 

In 2017 C++ 17 would be realeased as the next major update to C++. Although many programmers were expected major updates such as concepts and coroutines, sadly these did not appears within this verison of C++. However there were many other features added to the program such as inline variables, fold expressions, explicit test in conditions, and hexadecimal floating-point literals. However, the major features that were not included in C++17 would be found in the 2020 verison C++ 20. C++ 20 would include all the missing features such as cororoutines, concepts, and modules. 

## The Pros and Cons of C++

### Advantages

One of the primary advantages of C++ is allowing programs to have more control over memory management. The language allows you to create pointers, references, and dynamically allocate memory on the heap. These features can increase the performance of programs run on higher-level language programs such as Python, which does not give programs the same level of control over memory.
Along with this, C++ does not have a built-in garbage collector. While this may lead to memory leaks as a result of programmers forgetting to deallocate dynamic memory, it increases the performance of programs due to their being less overhead like in Python. Since C++ has been in use for a considerable amount of time, it boasts a very large ecosystem of libraries and frameworks, giving developers many tools for their application needs.


### Disadvantages

However, one of the main drawbacks of C++ is that it is syntactically much harder to learn than other languages like Python, which is comparatively much simpler to write similar algorithms. This can be attributed to it being a lower level language than Python, giving the application more control over the hardware components at the price of increased complexity of the code. Another disadvantage of the language is that not having a built-in garbage collector can result in more memory leaks if memory is not properly deallocated. Lastly, C++ is primarily used on platform specific programs and systems, which makes its use cases more limited than a language like Python that has a wide range of use cases.

![Pretty Picture](Images/1694874349830.jpg)

## What is C++ used for?
C++ is a general-purpose language developed whose design was motivated by a need for a language that provided high-level abstraction but also closely managed system resources and hardware at the lower levels. This blend of capabilities has made C++ suitable for several kinds of applications, notably including system software, mobile applications, mainframes and mission-critical applications.

### Computer Applications and Mobile Applications
The primary use case for C++ has traditionally been in system software development. The language’s rich set of built-in functionalities and its ability to operate close to system hardware make it an optimal choice for developing operating systems, file systems and system drivers. For example, much of Microsoft Windows and carious Unix/Linux systems have been extensively developed using C++. The ability to manage memory usage explicitly and optimize performance makes C++ particularly useful in these areas, where efficiency is crucial.

While not originally designed for mobile development, C++ has found a significant niche in this field. It’s commonly used for game development or applications requiring high performance on mobile platforms. The language’s speed and the control it offers over system resources make it ideal for mobile games or applications that demand high-performance computation and graphics processing. Developers can use C++ to build parts of their applications that need to maximize the hardware’s capabilities, often in combination with higher-level languages.

### Mainframe Computers and Mission Critical Applications
Mainframe computers, which are critical for large-scale and enterprise-level applications requiring robust processing power, also rely on C++. Although not the most highlighted use case, C++ is used in mainframe environments to leverage its performance efficiency and low-level operation capabilities. Mainframes typically run applications such as large databases, transaction processing systems and applications requiring high-speed data processing. C++ features support these needs very effectively.

One of the most essential critical areas for C++ is in mission-critical applications where performance, reliability and direct hardware interaction are of utmost importance. Examples include applications for aviation control systems, medical systems and automotive safety systems. The reliability and fine control over hardware interactions that C++ offers are indispensable in these situations where a failure could result in significant consequences.

### The Legacy of C++
C++ remains a significant and actively used programming language in the software development landscape as of 2023. Its usage spans various domains, illustrating its adaptability and enduring relevance. Notably, C++ is not just maintained for legacy systems but is also employed in modern software development, including systems programming, game development, and real-time applications.

The adoption of new C++ standards like C++20 and C++23 shows a vibrant and evolving ecosystem. Innovations in these standards, such as modules and ranges, are designed to improve code quality and maintainability. According to a 2023 developer ecosystem survey by JetBrains, a majority of C++ users have transitioned to the more recent standards (C++14 and later), indicating that the language is far from being merely legacy.

In terms of tooling and integration, the landscape is diverse. Modern C++ development environments support extensive toolchains that include advanced IDEs like CLion and Visual Studio, which offer features tailored to contemporary C++ programming needs. These tools facilitate better code management and integration with other programming languages and technologies, which is crucial given the language's widespread use in complex and varied projects. C++ also plays a pivotal role in educational and professional development contexts, with continuous updates and features that cater to both new and seasoned developers. 

In summary, while C++ was originally designed with systems programming in mind, its versatility has allowed it to be adapted successfully across various other domains, including mobile development, mainframes and mission-critical applications. This adaptability and performance-oriented nature confirm C++ as a foundational tool in the many options of modern programming languages. C++ continues to be a cornerstone in the programming world, adapting to new challenges and technological advances while supporting a wide array of applications and development needs.

## The Future of C++

### Where C++ will be used

It is likely that C++ will remain prominent in many applications in the future due to its ability to have low-level interaction with hardware. Its use in developing operating systems, embedded systems, and other low-level software that interfaces hardware will likely remain for the foreseeable future as many other competing languages do not have the ecosystem or performance capabilities. Another area C++ will continue to grow in is game development and virtual reality. Due to the high performance demands of modern video games and simulations in virtual/augmented reality, having the ability to improve performance is critical for games to run smoothly. Lastly, C++ will still be widely used in performance critical applications and back-end infrastructure for artificial intelligence infrastructure as a result of needing a high degree of optimization for performance.

### Where C++ will be replaced

Despite having such a large presence in the current developer landscape, there are some indications that C++ may start to decline in popularity in favor of other languages. The main applications that will likely see a major decline in C++ will be desktop, mobile, and web applications. Many of these types of applications do not require a high degree of optimization in order to function properly, so developers prefer to use languages with more readable and simplistic syntax like Python, Swift, or Kotlin. As the frameworks and libraries for these applications grow for other languages, C++ will likely become more obsolete in the future. For the future of applications that C++ excels at, Rust is a programming language that is growing in popularity in system programming and embedded systems. While it currently does not have the same size of ecosystem and amount of legacy code as C++, its improved memory safety and modern tooling makes it a serious contender to potentially overtake C++ on many different applications.

![TimelineGraph](Images/TimelineGraphic.png)


## Sources
[1]
F. van den Beuken, “History of C++ | Perforce,” www.perforce.com, Nov. 29, 2023. https://www.perforce.com/blog/qac/misra-cpp-history

[2]
S. Goyal, “The History Of C++ (With Timeline Infographic) ,” unstop.com, Apr. 17, 2023. https://unstop.com/blog/history-of-cpp (accessed Apr. 15, 2024).

[3]
“Advantages and Disadvantages of C++,” GeeksforGeeks, Dec. 30, 2020. https://www.geeksforgeeks.org/advantages-and-disadvantages-of-cpp/

[4]
“Will C++ Be Replaced? Predicting The Future Of The Language - Code With C,” Dec. 29, 2023. https://www.codewithc.com/will-c-be-replaced-predicting-the-future-of-the-language/

[5]
“What Is C++ Used For? Top 12 Real-World Applications and Uses of C++,” Softwaretestinghelp.com, Nov. 10, 2019. https://www.softwaretestinghelp.com/cpp-applications/
