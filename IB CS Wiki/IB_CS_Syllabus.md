## A1.1 Computer hardware and operation 

A1.1.1 Describe the functions and interactions of the main CPU components. Units: ALU, CU. Registers: IR, PC, MAR, MDR, AC. Buses: address, data, control. Processors: single core, multi-core, co-processors.

A1.1.2 Describe the role of a GPU. Architecture for specific tasks and complex computations. Scenarios may include: video games, AI, large simulations.

(HL only) A1.1.3 Explain the differences between the CPU and the GPU. Design philosophies, usage scenarios , core architecture, processing power, memory access, power efficiency , task division, data sharing, coordinating execution.

A1.1.4 Explain the purposes of different types of primary memory. RAM, ROM, cache (L1, L2, L3), registers. Interaction of CPU with memory. "cache miss" and "cache hit".

A1.1.5 Describe the fetch, decode and execute cycle. Basic CPU operations for a single instruction. Interaction between memory and registers via the three buses.

(HL only) A1.1.6 Describe the process of pipelining in multi-core architectures. Instructions fetch, decode, execute, write-back stages. Cores working independently and in parallel.

A1.1.7 Describe internal and external types of secondary memory storage. Internal: SSD, HDD, eMMCs. External: SSD, HDD, optical drives, flash drives, memory cards, NAS. Scenarios in which various types are used.

A1.1.8 Describe the concept of compression. Differences between lossy and lossless compression methods. Run-length encoding and transform coding.

A1.1.9 Describe the different types of services in cloud computing. Services: SaaS, PaaS, IaaS. Differences between approaches in various real-world scenarios.

## A1.2 Data representation and computer logic 

A1.2.1 Describe the principal methods of representing data. Representation of integers in binary and hexadecimal. Conversion between binary, hexadecimal, and decimal.

A1.2.2 Explain how binary is used to store data. Fundamentals of binary encoding. Mechanisms for storing integers, strings, characters, images, audio, and video.

A1.2.3 Describe the purpose and use of logic gates. Functions and applications of logic gates. Role in binary computing. Boolean operators: AND, OR, NOT, NAND, NOR, XOR, XNOR.

A1.2.4 Construct and analyse truth tables. Predicting output of simple logic circuits. Determining outputs from inputs for a problem description. Relationship to Boolean expressions. Aiding simplification of logical expressions. Karnaugh maps and algebraic simplification.

A1.2.5 Construct logic diagrams. Demonstrating how logic gates are connected. Use of standard gate symbols. Combining gates for complex operations. Using Boolean algebra to simplify diagrams and expressions.

## A1.3 Operating systems and control systems 

A1.3.1 Describe the role of operating systems. Abstracting hardware complexities to manage system resources.

A1.3.2 Describe the functions of an operating system. Memory management, file system, device management, scheduling, security, accounting, GUI, virtualization, networking.

A1.3.3 Compare different approaches to scheduling. First-come first-served, round robin, multilevel queue scheduling, priority scheduling.

A1.3.4 Evaluate the use of polling and interrupt handling. Event frequency, CPU overheads, power source, event predictability, controlled latency, security concerns. Real-world scenarios may include: keyboard/mouse inputs, network communications, disk I/O operations.

(HL only) A1.3.5 Explain the role of the operating system in managing multitasking and resource allocation. Challenges include task scheduling, resource contention, and deadlock.

(HL only) A1.3.6 Describe the use of the control system components. Input, process, output, and feedback mechanism (open-loop, closed-loop). Controller, sensors, actuators, transducers, control algorithm.

(HL only) A1.3.7 Explain the use of control systems in a range of real-world applications. Examples may include: autonomous vehicles, home thermostats, automatic elevators, washing machines, traffic signals.

## A1.4 Translation

(HL only) A1.4.1 Evaluate the translation processes of interpreters and compilers. Mechanics and use-cases. Differences in error detection, translation time, portability. Must include: just-in-time compilation (JIT) and bytecode interpreters.  

## A2.1 Network fundamentals 

A2.1.1 Describe the purpose and characteristics of networks. Networks: LAN, WAN, PAN, VPN.

A2.1.2 Describe the purpose, benefits and limitations of modern digital infrastructures. Infrastructure: the internet, cloud computing, distributed systems, edge computing, mobile networks. Examples may include: WWW, cryptocurrency blockchains, smart traffic lights, a school.

A2.1.3 Describe the function of network devices. Gateways, hardware firewalls, modems, NICs, routers, switches, wireless access points. How devices map to the layers of the TCP/IP model.

A2.1.4 Describe the network protocols used for transport and application. Protocols: TCP, UDP, HTTP, HTTPS, DHCP.

(HL only) A2.1.5 Describe the function of the TCP/IP model. Application, transport, internet, network interface layers. Role of each layer and their interaction.

## A2.2 Network architecture 

A2.2.1 Describe the functions and practical applications of network topologies. Topologies: star, mesh, hybrid. Factors must include: reliability, speed, scalability, collisions, cost.

(HL only) A2.2.2 Describe the function of servers. Types: DNS, DHCP, file, mail, proxy, web. Factors must include: function, scalability, reliability, security.

A2.2.3 Compare and contrast networking models. Client-server and peer-to-peer models. Benefits and drawbacks of each.

A2.2.4 Explain the concepts and applications of network segmentation. For network performance and security, to reduce congestion, to manage resources. Must include: segmenting, subnetting, VLANs.

## A2.3 Data transmissions 

A2.3.1 Describe different types of IP addressing. IPv4 vs IPv6. Public vs private, static vs dynamic. Role of Network Address Translation (NAT).

A2.3.2 Compare types of media for data transmission. Wired (fibre optic, twisted pair) and wireless transmission. Factors must include: bandwidth, installation complexity, cost, range, interference, attenuation, reliability, security.

A2.3.3 Explain how packet switching is used to send data across a network. Segmenting data into packets with routing headers. Role of switches and routers.

(HL only) A2.3.4 Explain how static routing and dynamic routing move data across local area networks. Process, advantages, and disadvantages of static and dynamic routing. Factors must include: configuration, maintenance, complexity, resource usage, scalability, network size.

## A2.4 Network security

A2.4.1 Discuss the effectiveness of firewalls at protecting a network. Function of firewalls (inspecting/filtering traffic based on whitelists, blacklists, rules). Strengths and limitations. Role of NAT to enhance security.

(HL only) A2.4.2 Describe common network vulnerabilities. DDoS, insecure protocols, malware, MitM attacks, phishing, SQL injection, XSS, unpatched software, weak authentication, zero-day exploits.

(HL only) A2.4.3 Describe common network countermeasures. Content security policies, complex passwords, DDoS mitigation, email filtering, encrypted protocols, input validation, IDS/IPS, MFA, SSL/TLS, VPNs, software updates. Employee training. Wireless security measures (MAC whitelists/blacklists).

A2.4.4 Describe the process of encryption and digital certificates. Symmetric vs asymmetric cryptography. Role of digital certificates. Use of public and private keys. Significance of key management.

## A3.1 Database fundamentals 

A3.1.1 Explain the features, benefits and limitations of a relational database. Features: primary/foreign/composite keys, tables, relationships. Benefits: data integrity, consistency, security, scalability. Limitations: "big data" issues, design complexity, handling unstructured data.

## A3.2 Database design 

A3.2.1 Describe database schemas. Conceptual schema, logical schema, physical schema.

A3.2.2 Construct ERDs. Significance of entity relationship diagrams (ERDs) in design. Relationships between entities. Roles of cardinality and modality.

A3.2.3 Outline the different data types used in relational databases. Importance of data type consistency. Potential effects of choosing the wrong data type.

A3.2.4 Construct tables for relational databases. Relationship between tables using primary, foreign, composite, and concatenated keys.

A3.2.5 Explain the difference between normal forms. First normal form (1NF), second normal form (2NF), third normal form (3NF). Terms: atomicity, functional dependencies, transitive dependencies.

A3.2.6 Construct a database normalized to 3NF for a range of real-world scenarios. Examples may include: library management, e-commerce, school management, inventory management.

A3.2.7 Evaluate the need for denormalizing databases. Advantages and disadvantages of normalizing and denormalizing. Situations where denormalization can enhance performance.

## A3.3 Database programming 

A3.3.1 Outline the differences between data language types within SQL. Must include: Data Definition Language (DDL) and Data Manipulation Language (DML).

A3.3.2 Construct queries between two tables in SQL. Must include: joins, relational operators, filtering, pattern matching, ordering data. Commands: SELECT, FROM, WHERE, ORDER BY, JOIN, LIKE, AND, OR, NOT, etc..

A3.3.3 Explain how SQL can be used to update data in a database. INSERT INTO, UPDATE SET, DELETE. Performance implications of updating indexed columns.

(HL only) A3.3.4 Construct calculations within a database using SQL's aggregate functions. Aggregate commands: AVERAGE, COUNT, MAX, MIN, SUM.

(HL only) A3.3.5 Describe different database views. Virtual views and materialized (snapshot) views. Hiding complexity, security, performance, query simplification.

(HL only) A3.3.6 Describe how transactions maintain data integrity in a database. Role of Atomicity, Consistency, Isolation, Durability (ACID). TCL commands: BEGIN TRANSACTION, COMMIT, ROLLBACK.

## A3.4 Alternative databases and data warehouses 

(HL only) A3.4.1 Outline the different types of databases as approaches to storing data. Models: NoSQL, cloud, spatial, in-memory.

(HL only) A3.4.2 Explain the primary objectives of data warehouses in data management and business intelligence. Roles of append-only, subject-oriented, integrated, time-variant, non-volatile data.

(HL only) A3.4.3 Explain the role of online analytical processing (OLAP) and data mining for business intelligence. Data mining techniques must include: classification, clustering, regression, association rule discovery, anomaly detection.

(HL only) A3.4.4 Describe the features of distributed databases. Need for data consistency. Role of ACID. Features: concurrency control, data partitioning, replication, fault tolerance, scalability.  

## A4.1 Machine learning fundamentals 

A4.1.1 Describe the types of machine learning and their applications in the real world. Deep learning (DL), reinforcement learning (RL), supervised learning, transfer learning (TL),  unsupervised learning (UL). Applications may include: medical imaging, NLP, object detection.

A4.1.2 Describe the hardware requirements for various scenarios where machine learning is deployed. Configurations from standard laptops to advanced infrastructure. Advanced infrastructure must include: ASICS, edge devices, FPGAs, GPUs, TPUs, cloud platforms, HPC centres.

## A4.2 Data preprocessing 

(HL only) A4.2.1 Describe the significance of data cleaning. Impact of data quality on model performance. Techniques for handling outliers, duplicates, incorrect/irrelevant data, and missing data. Normalization and standardization.

(HL only) A4.2.2 Describe the role of feature selection. Identifying and retaining informative attributes. Strategies: filter methods, wrapper methods, embedded methods.

(HL only) A4.2.3 Describe the importance of dimensionality reduction. "Curse of dimensionality" considerations (overfitting, complexity, etc.).

## A4.3 Machine learning approaches 

(HL only) A4.3.1 Explain how linear regression is used to predict continuous outcomes. Relationship between independent and dependent variables. Significance of slope and intercept.

(HL only) A4.3.2 Explain how classifications techniques in supervised learning are used to predict discrete categorical outcomes. K-Nearest Neighbours (K-NN) and decision trees algorithms.

(HL only) A4.3.3 Explain the role of hyperparameter tuning when evaluating supervised learning algorithms. Evaluation metrics: Accuracy, precision, recall, F1 score. Overfitting and underfitting.

(HL only) A4.3.4 Describe how clustering techniques in unsupervised learning are used to group data based on similarities in features. Clustering techniques group data based on feature similarities.

(HL only) A4.3.5 Describe how learning techniques using the association rule are used to uncover relations between different attributes in large data sets. Mining techniques using the association rule and interpretation of results.

(HL only) A4.3.6 Describe how an agent learns to make decisions by interacting with its environment in reinforcement learning. Principle of cumulative reward; concepts of actions, states, rewards, policies. Exploration vs exploitation trade-off.

(HL only) A4.3.7 Describe the application of genetic algorithms in various real-world situations. Example concepts: population, fitness function, selection, crossover, mutation. Example application: route planning (travelling salesperson problem).

(HL only) A4.3.8 Outline the structure and function of ANNs and how multi-layer networks are used to model complex patterns in data sets. Sketch of a single perceptron. Sketch of a multi-layer perceptron (MLP).

(HL only) A4.3.9 Describe how CNNs are designed to adaptively learn spatial hierarchies of features in images. Basic CNN architecture: convolutional layers, pooling layers, fully connected layers, etc.. Effect of number of layers, kernel size, stride, etc. on processing.

(HL only) A4.3.10 Explain the importance of model selection and comparison in machine learning. How different algorithms yield different results. Reasons for selecting specific models.

## A4.4 Ethical considerations

A4.4.1 Discuss the ethical implications of machine learning in real-world scenarios. Issues may include: accountability, bias, consent, privacy, security, societal impact. Challenges posed by biases in training data.

A4.4.2 Discuss ethical aspects of the increasing integration of computer technologies into daily life. Importance of reassessing ethical guidelines. Potential implications of emerging technologies (quantum computing, AR/VR, pervasive AI).

## B2.1 Programming fundamentals 

B2.1.1 Construct and trace programs using a range of global and local variables of various data types. Data types: Boolean, char, decimal, integer, string.

B2.1.2 Construct programs that can extract and manipulate substrings. Altering, concatenating, or replacing substrings.

B2.1.3 Describe how programs use common exception handling techniques. Potential failures must include: unexpected inputs, resource unavailability, logic errors. Constructs must include: try/catch (Java), try/except (Python), finally block.

B2.1.4 Construct and use common debugging techniques. Techniques may include: trace tables, breakpoint debugging, print statements, step-by-step execution.

## B2.2 Data structures

B2.2.1 Compare static and dynamic data structures. Differences in memory allocation and resizing. Advantages/disadvantages regarding speed, memory usage, flexibility.

B2.2.2 Construct programs that apply arrays and Lists. 1D and 2D arrays/Lists. Add, remove, and traverse elements in a dynamic list.

B2.2.3 Explain the concept of a stack as a "last in, first out" (LIFO) data structure. Must include operations: push, pop, peek, isEmpty.

B2.2.4 Explain the concept of a queue as a "first in, first out" (FIFO) data structure. Must include operations: enqueue, dequeue, front, isEmpty.

## B2.3 Programming constructs

B2.3.1 Construct programs that implement the correct sequence of code instructions to meet program objectives. Impact of instruction order on functionality.

B2.3.2 Construct programs utilizing appropriate selection structures. Must include: if, else, else if (Java), elif (Python). Use with Boolean and/or relational operators.

B2.3.3 Construct programs that utilize looping structures to perform repeated actions. Counted loops and conditional loops. Conditional statements within loops.

B2.3.4 Construct functions and modularization. Defining reusable blocks of code. Principles of scope (local vs global).

## B2.4 Programming algorithms

B2.4.1 Describe the efficiency of specific algorithms by calculating their Big O notation to analyse their scalability. Time and space complexities.

B2.4.2 Construct and trace algorithms to implement a linear search and a binary search for data retrieval. Differences in efficiency between the methods.

B2.4.3 Construct and trace algorithms to implement bubble sort and selection sort, evaluating their time and space complexities. Time and space complexities (Big O). Advantages and disadvantages.

(HL only) B2.4.4 Explain the fundamental concept of recursion and its applications in programming. Fundamentals, advantages, and limitations. Applications include fractal image creation, traversing binary trees, sorting algorithms (e.g., quicksort).

(HL only) B2.4.5 Construct and trace recursive algorithms in a programming language. Simple, non-branching recursive algorithms only.

## B2.5 File processing 

B2.5.1 Construct code to perform file-processing operations. Manipulating text files. Opening a file in read, write, append modes. Reading from, writing to, appending, and closing files.

## B3.1 Fundamentals of OOP for a single class 

B3.1.1 Evaluate the fundamentals of OOP. Concepts: classes, objects, inheritance, encapsulation, polymorphism. Advantages and disadvantages of OOP.

B3.1.2 Construct a design of classes, their methods and behaviour. Use of UML class diagrams.

B3.1.3 Distinguish between static and non-static variables and methods. Differences in usage and scope.

B3.1.4 Construct code to define classes and instantiate objects. Role of constructors in initializing an object's state.

B3.1.5 Explain and apply the concepts of encapsulation and information hiding in OOP. Apply access modifiers (private, public). Controlling access to class members.

## B3.2 Fundamentals of OOP for multiple classes

(HL only) B3.2.1 Explain and apply the concept of inheritance in OOP to promote code reusability. Hierarchical relationship between parent and child classes. Impact on access with different access modifiers (private, public, protected, default).

(HL only) B3.2.2 Construct code to model polymorphism and its various forms, such as method overriding. Principle of polymorphism for code flexibility. Dynamic polymorphism (method overriding). Static polymorphism.

(HL only) B3.2.3 Explain the concept of abstraction in OOP. Significance for modular code. Use of abstract classes to establish common interfaces.

(HL only) B3.2.4 Explain the role of composition and aggregation in class relationships. Aggregation: subcomponents can function independently. Composition: subcomponents are tightly coupled.

(HL only) B3.2.5 Explain commonly used design patterns in OOP. Key patterns such as singleton, factory, and observer. 

## B4.1 Fundamentals of ADTs 

(HL only) B4.1.1 Explain the properties and purpose of ADTs in programming. Core principles, high-level description of data structures and their operations.

(HL only) B4.1.2 Evaluate linked lists. Must include: singly, doubly, circular. Diagrammatic sketch and implementation of operations (insertion, deletion, traversal, search).

(HL only) B4.1.3 Construct and apply linked lists: singly, doubly and circular. Basic operations: insertion, deletion, traversal, search.

(HL only) B4.1.4 Explain the structures and properties of BSTs. Operations: insert, delete, traverse, search nodes. Sketching a BST as a tree diagram.

(HL only) B4.1.5 Construct and apply sets as an ADT. Unordered nature and uniqueness of elements. Operations: union, intersection, difference.

(HL only) B4.1.6 Explain the core principles of ADTs. Underlying mechanics of hash tables (hashing functions, collision resolution). Underlying mechanics of sets. HashMap/HashSet (Java); dict/set (Python).