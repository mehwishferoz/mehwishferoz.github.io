# 🌐 Computer Networks Portfolio
* * *
> 🚀 Exploring Advanced Algorithms for Computer Networks

## Course Information
- **Course Name:** Algorithmic Problem Solving
- **Course Code:** 23ECSE309
- **Course Instructor:** Prakash Hegade

## Personal Information
- **Name:** Mehwish Nidgundi
- **USN:** 01FE21BCI057
- **University:** KLE Technological University, Hubli

## Table of Contents
- [📖 Introduction](#introduction)
- [🌟 Why Computer Networks?](#why-computer-networks)
- [🎯 Objective](#objective)
- [💼 Use Cases](#use-cases)
- [📜 References](#references)

## Introduction
Welcome to my portfolio, where I showcase my learnings from the Algorithmic Problem Solving (APS) classes. The domain I've chosen to focus on is Computer Networks. Through this portfolio, I aim to demonstrate my understanding of advanced algorithms and their applications in solving real-world problems within the realm of computer networking.

## Why Computer Networks?

<img align="right" src="https://www.lifewire.com/thmb/TXVRTtkHvRpTjnRObQ3xm2VlsD0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/WirelessNetwork-5994852003f4020011db5333.jpg" width="180">

The domain of Computer Networks captivates me due to its profound impact on virtually every aspect of modern life. The idea of connecting millions of devices, enabling instant communication, and supporting the vast flow of information is fascinating. Moreover, the continuous evolution of networking technologies presents a constant stream of new challenges and innovations. My curiosity about how these systems work, combined with a desire to improve and innovate within this field, drives my passion for Computer Networks.

## Objective
The main goal of this portfolio is to show my understanding and use of advanced algorithms to solve real-world networking problems.

## Use Cases

### 1. 🌐 **Network Flow**

#### USE CASE:

Network flow management involves efficiently directing data through networks, ensuring optimal performance. Algorithms like Ford-Fulkerson, Edmonds-Karp, Dinic's, Push-Relabel, and Capacity Scaling are used to calculate maximum flow, optimize paths, and handle varying network demands.

#### CHALLENGES:

Efficiently optimizing flow paths while respecting network capacities requires algorithms that can handle dynamic changes in flow requirements. Ensuring fair distribution and prioritization of data flows based on application needs is crucial. Implementing these algorithms involves balancing computational efficiency with accuracy in flow calculations.

#### DSA USED:

- **Ford-Fulkerson Algorithm**: Finds the maximum flow in a flow network. [Code](./codes/1.md)
  
- **Edmonds-Karp Algorithm**: Uses BFS for maximum flow calculations. [1] [Code](./codes/2.md)
  
- **Dinic's Algorithm**: Combines BFS and DFS for efficient flow computations. [2] [Code](./codes/3.md)
  
- **Push-Relabel Algorithm**: Maintains a preflow to optimize flow in large graphs. [3] [Code](./codes/4.md)
  
- **Capacity Scaling Algorithm**: Scales capacities dynamically for efficient flow management. [4] [Code](./codes/5.md)


### 2. 🚦 **Routing Algorithms**

#### USE CASE:

Routing algorithms find the shortest paths in networks, crucial for efficient data transmission. Algorithms like Dijkstra's, Bellman-Ford, A*, and OSPF optimize route calculations based on network topology and traffic patterns.

#### CHALLENGES:

Developing algorithms that swiftly determine optimal routes while adapting to network changes and avoiding inefficiencies. Ensuring accurate route selection under varying conditions requires sophisticated algorithms capable of handling large datasets and diverse network topologies.

#### DSA USED:

- **Dijkstra's Algorithm**: Finds the shortest path using a priority queue. [5] [Code](./codes/5.md)

- **Bellman-Ford Algorithm**: Handles negative weights and dynamic networks. [6] [Code](./codes/6.md)

- **A* Algorithm**: Uses heuristics to enhance Dijkstra's efficiency. [7] [Code](./codes/7.md)

- **OSPF (Open Shortest Path First)**: Adapts to changing network states for optimal routing. [8] [Code](./codes/8.md)


### 3. ⏱️ **Packet Scheduling and Quality of Service (QoS)**

#### USE CASE:

Packet scheduling ensures timely delivery and prioritization of data packets in networks. Algorithms like Priority Queues, Round Robin, Weighted Fair Queuing (WFQ), Deficit Round Robin (DRR), and Leaky Bucket manage traffic efficiently.

#### CHALLENGES:

Designing scheduling algorithms that maintain fairness and prioritize critical data streams. Adapting to fluctuating network conditions while ensuring consistent quality of service. Balancing computational overhead with real-time responsiveness in packet scheduling.

#### DSA USED:

- **Priority Queues**: Manage packets with different priorities efficiently. [9] [Code](./codes/9.md)

- **Round Robin Scheduling**: Ensures fair resource distribution. [10] [Code](./codes/10.md)

- **Weighted Fair Queuing (WFQ)**: Allocates bandwidth based on packet weights. [11] [Code](./codes/11.md)

- **Deficit Round Robin (DRR)**: Fair queuing with deficit-based scheduling. [12] [Code](./codes/12.md)

- **Leaky Bucket and Token Bucket**: Controls data flow rates to prevent congestion. [13] [Code](./codes/13.md)


### 4. 📜 **Routing Tables and Address Resolution**

#### USE CASE:

Efficient routing table management and address resolution are essential for network connectivity. Data structures like Tries, Hash Tables, and Binary Search Trees (BST) optimize IP lookup and address mapping.

#### CHALLENGES:

Developing efficient data structures and algorithms for quick IP address resolution and routing table management. Balancing memory usage and lookup speed in routing operations. Implementing scalable and robust address resolution mechanisms across large networks.

#### DSA USED:

- **Tries**: Efficient for IP lookup and prefix matching. [14] [Code](./codes/14.md)

- **Hash Tables**: Fast address resolution in ARP. [15] [Code](./codes/15.md)

- **Binary Search Trees (BST)**: Hierarchical routing table management. [16] [Code](./codes/16.md)


### 5. 🚧 **Congestion Control**

#### USE CASE:

Congestion control manages data traffic to prevent network overload and ensure stable performance. Algorithms like Sliding Window Protocols, Leaky Bucket, AIMD, and RED dynamically adjust data rates to maintain optimal network conditions.

#### CHALLENGES:

Designing algorithms that dynamically adjust data rates to prevent congestion while maximizing throughput. Balancing proactive congestion avoidance with reactive congestion control strategies. Implementing robust congestion detection and response mechanisms in diverse network environments.

#### DSA USED:

- **Sliding Window Protocols**: Regulates data flow and ensures reliable transmission. [17] [Code](./codes/17.md)

- **Leaky Bucket Algorithm**: Controls data rate to prevent bursts. [18] [Code](./codes/18.md)

- **Additive Increase/Multiplicative Decrease (AIMD)**: TCP congestion control algorithm. [19] [Code](./codes/19.md)

- **Random Early Detection (RED)**: Detects and manages congestion proactively. [20] [Code](./codes/20.md)


### 6. 🛠️ **Error Detection and Correction**

#### USE CASE:

Ensuring data integrity during transmission is critical for reliable communication. Algorithms like CRC, Hamming Code, and Reed-Solomon detect and correct errors, minimizing data loss.

#### CHALLENGES:

Developing robust error detection and correction algorithms that efficiently identify and rectify transmission errors. Balancing overhead costs with error detection accuracy. Adapting error correction techniques to diverse data types and transmission conditions.

#### DSA USED:

- **Cyclic Redundancy Check (CRC)**: Detects errors in transmitted data blocks. [21] [Code](./codes/21.md)

- **Hamming Code**: Corrects single-bit errors in data transmission. [22] [Code](./codes/22.md)

- **Reed-Solomon Code**: Error correction for burst errors in data streams. [23] [Code](./codes/23.md)


### 7. 🔒 **Network Security**

#### USE CASE:

Protecting data and resources from unauthorized access and attacks is crucial in network security. Algorithms like Hash Functions and Encryption Algorithms (e.g., RSA, AES) ensure data confidentiality, integrity, and availability.

#### CHALLENGES:

Developing secure algorithms that resist attacks and vulnerabilities. Balancing encryption strength with performance overhead. Adapting security measures to evolving threat landscapes and regulatory requirements.

#### DSA USED:

- **Hash Functions**: Create digital signatures and verify message integrity. [24] [Code](./codes/24.md)

- **Encryption Algorithms**: Secure data transmission and storage. [25], [26] [Code](./codes/1.md)


### 8. 📡 **Multicast Routing**

#### USE CASE:

Efficiently routing data to multiple recipients is essential for multimedia and collaborative applications. Algorithms like Shortest Path Tree (SPT), Steiner Tree, DVMRP, and PIM optimize data distribution in multicast environments.

#### CHALLENGES:

Designing algorithms that efficiently manage multicast group communication. Balancing scalability with bandwidth efficiency in large-scale multicast networks. Implementing robust routing protocols that adapt to network dynamics and varying group sizes.

#### DSA USED:

- **Shortest Path Tree (SPT)**: Efficient routing tree for multicast groups. [27] [Code](./codes/27.md)

- **Steiner Tree**: Optimal tree for connecting multiple nodes in multicast scenarios. [28] [Code](./codes/28.md)

- **Distance Vector Multicast Routing Protocol (DVMRP)**: Routing protocol for multicast groups. [29] [Code](./codes/29.md)

- **Protocol Independent Multicast (PIM)**: Family of multicast routing protocols. [30] [Code](./codes/30.md)


### 9. 🚀 **Flow Control in Transport and Data Link Layer**

#### USE CASE:

Ensuring reliable data transmission and optimal performance in transport and data link layers is critical for network efficiency. Algorithms like Sliding Window Algorithm and Stop-and-Wait Protocol manage data flow and ensure error-free communication.

#### CHALLENGES:

Designing efficient flow control mechanisms that adapt to varying network conditions and traffic patterns. Balancing data transmission speed with error detection and correction capabilities. Implementing robust protocols that prevent congestion and ensure data integrity.

#### DSA USED:

- **Sliding Window Algorithm**: Regulates data flow and ensures reliable transmission. [31] [Code](./codes/31.md)

- **Stop-and-Wait Protocol**: Ensures data integrity by acknowledging each packet. [32] [Code](./codes/32.md)


### 10. 🛡️ **Intrusion Detection Systems (IDS)**

#### USE CASE:

Detecting and preventing malicious activities and security breaches is crucial for network security. Algorithms like Pattern Matching and Anomaly Detection identify potential threats and unauthorized access attempts.

#### CHALLENGES:

Developing algorithms that efficiently detect known attack patterns and anomalous behaviors. Balancing detection accuracy with computational efficiency and real-time responsiveness. Adapting detection mechanisms to evolving attack vectors and network environments.

#### DSA USED:

- **Pattern Matching Algorithms**: Detect known attack signatures efficiently. [33], [34] [Code](./codes/1.md)

- **Anomaly Detection**: Identifies unusual patterns indicating potential threats. [35], [36] [Code](./codes/1.md)


### 11. 🌍 **Content Delivery Networks (CDN)**

#### USE CASE:

Efficiently delivering web content to users worldwide requires robust content delivery networks. Algorithms like Caching Algorithms and Load Balancing ensure fast and reliable content distribution across geographically dispersed servers.

#### CHALLENGES:

Designing caching strategies that maximize hit rates and minimize latency. Balancing content replication and distribution costs with performance gains. Implementing load balancing algorithms that optimize server resource utilization and enhance content delivery speed.

#### DSA USED:

- **Caching Algorithms**: Store frequently accessed content for quick retrieval. [37] [Code](./codes/37.md)

- **Load Balancing**: Distributes incoming traffic across multiple servers. [38] [Code](./codes/38.md)


### 12. 🗜️ **Data Compression**

#### USE CASE:

Reducing data size for efficient storage and transmission is essential in data compression. Algorithms like Huffman Coding, Lempel-Ziv-Welch (LZW), and Burrows-Wheeler Transform (BWT) minimize data size while preserving data integrity.

#### CHALLENGES:

Developing compression algorithms that achieve high compression ratios without loss of data. Balancing compression speed with decompression efficiency. Adapting compression techniques to diverse data types and application scenarios.

#### DSA USED:

- **Huffman Coding**: Lossless data compression with variable-length codes. [39] [Code](./codes/39.md)

- **Lempel-Ziv-Welch (LZW)**: Dictionary-based compression for text and images. [40] [Code](./codes/40.md)

- **Burrows-Wheeler Transform (BWT)**: Data transformation technique for block sorting compression. [41] [Code](./codes/41.md)


## References

[1] J. Edmonds and R. M. Karp, "Theoretical improvements in algorithmic efficiency for network flow problems," *Journal of the ACM (JACM)*, vol. 19, no. 2, pp. 248-264, Apr. 1972.

[2] E. A. Dinic, "Algorithm for solution of a problem of maximum flow in a network," *Soviet Mathematics Doklady*, vol. 11, no. 5, pp. 1277-1280, 1970.

[3] J. Cheriyan and S. N. Maheshwari, "A note on two problems in connexion with graphs," *SIAM Journal on Computing*, vol. 18, no. 6, pp. 1057-1086, 1989.

[4] A. V. Goldberg and R. E. Tarjan, "A new approach to the maximum-flow problem," *Journal of the ACM (JACM)*, vol. 35, no. 4, pp. 921-940, Oct. 1988.

[5] E. W. Dijkstra, "A note on two problems in connexion with graphs," *Numerische Mathematik*, vol. 1, no. 1, pp. 269-271, Dec. 1959.

[6] R. Bellman, "On a routing problem," *Quarterly of Applied Mathematics*, vol. 16, no. 1, pp. 87-90, Mar. 1958.

[7] P. E. Hart, N. J. Nilsson, and B. Raphael, "A formal basis for the heuristic determination of minimum cost paths," *IEEE Transactions on Systems Science and Cybernetics*, vol. 4, no. 2, pp. 100-107, Jul. 1968.

[8] J. Moy, "OSPF Version 2," *RFC 2328*, Apr. 1998.

[9] J. F. Kurose and K. W. Ross, *Computer Networking: A Top-Down Approach*.

[10] W. Stallings, *Data and Computer Communications*.

[11] A. Demers, S. Keshav, and S. Shenker, "Analysis and simulation of a fair queueing algorithm," *ACM SIGCOMM Computer Communication Review*, vol. 19, no. 4, pp. 1-12, Aug. 1989.

[12] M. Shreedhar and G. Varghese, "Efficient fair queuing using deficit round-robin," *IEEE/ACM Transactions on Networking*, vol. 4, no. 3, pp. 375-385, Jun. 1996.

[13] A. S. Tanenbaum and D. J. Wetherall, *Computer Networks*.

[14] D. R. Morrison, "PATRICIA - practical algorithm to retrieve information coded in alphanumeric," *Journal of the ACM (JACM)*, vol. 15, no. 4, pp. 514-534, Oct. 1968.

[15] D. R. Cheriton and W. Zwaenepoel, "An efficient implementation of the smalltalk-80 system," *Proceedings of the ninth ACM symposium on Operating systems principles*, pp. 129-140, 1983.

[16] T. H. Cormen, C. E. Leiserson, R. L. Rivest, and C. Stein, *Introduction to Algorithms*.

[17] W. Stallings, *Data and Computer Communications*.

[18] A. S. Tanenbaum and D. J. Wetherall, *Computer Networks*.

[19] V. Jacobson, "Congestion avoidance and control," *ACM SIGCOMM Computer Communication Review*, vol. 18, no. 4, pp. 314-329, Aug. 1988.

[20] S. Floyd and V. Jacobson, "Random early detection gateways for congestion avoidance," *IEEE/ACM Transactions on Networking*, vol. 1, no. 4, pp. 397-413, Aug. 1993.

[21] W. W. Peterson and D. T. Brown, "Cyclic codes for error detection," *Proceedings of the IRE*, vol. 49, no. 1, pp. 228-235, Jan. 1961.

[22] R. W. Hamming, "Error detecting and error correcting codes," *Bell System Technical Journal*, vol. 29, no. 2, pp. 147-160, Apr. 1950.

[23] I. S. Reed and G. Solomon, "Polynomial codes over certain finite fields," *Journal of the Society for Industrial and Applied Mathematics*, vol. 8, no. 2, pp. 300-304, Jun. 1960.

[24] R. Rivest, "RFC 1321: The MD5 Message-Digest Algorithm," Apr. 1992.

[25] R. L. Rivest, A. Shamir, and L. Adleman, "A method for obtaining digital signatures and public-key cryptosystems," *Communications of the ACM*, vol. 21, no. 2, pp. 120-126, Feb. 1978.

[26] J. Daemen and V. Rijmen, "The design of Rijndael: AES - the advanced encryption standard," 2002.

[27] S. E. Deering and D. R. Cheriton, "Multicast routing in internetworks and extended LANs," *ACM Transactions on Computer Systems (TOCS)*, vol. 8, no. 2, pp. 85-110, May 1990.

[28] L. T. Kou, G. Markowsky, and L. Berman, "A fast algorithm for steiner trees," *SIAM Journal on Applied Mathematics*, vol. 40, no. 3, pp. 676-682, Jun. 1981.

[29] D. Waitzman, C. Partridge, and S. Deering, "Distance vector multicast routing protocol," *RFC 1075*, Nov. 1988.

[30] D. Estrin et al., "Protocol independent multicast-sparse mode (PIM-SM): Protocol specification," *RFC 2362*, Jun. 1998.

[31] A. S. Tanenbaum and D. J. Wetherall, *Computer Networks*.

[32] W. Stallings, *Data and Computer Communications*.

[33] A. V. Aho and M. J. Corasick, "Efficient string matching: An aid to bibliographic search," *Communications of the ACM*, vol. 18, no. 6, pp. 333-340, Jun. 1975.

[34] D. E. Knuth, J. H. Morris, and V. R. Pratt, "Fast pattern matching in strings," *SIAM Journal on Computing*, vol. 6, no. 2, pp. 323-350, Jun. 1977.

[35] D. E. Denning, "An intrusion detection model," *IEEE Transactions on software engineering*, no. 2, pp. 222-232, Apr. 1987.

[36] A. Lazarevic, V. Kumar, and J. Srivastava, "Intrusion detection: A survey," in *Managing Cyber Threats*, pp. 19-78, 2005.

[37] M. Rabinovich and O. Spatscheck, *Web caching and replication*.

[38] D. Karger et al., "Web caching and replication," in *Proceedings of the twenty-ninth annual ACM symposium on Theory of computing*, pp. 654-663, 1997.

[39] D. A. Huffman, "A method for the construction of minimum-redundancy codes," *Proceedings of the IRE*, vol. 40, no. 9, pp. 1098-1101, Sep. 1952.

[40] J. Ziv and A. Lempel, "A universal algorithm for sequential data compression," *IEEE Transactions on information theory*, vol. 23, no. 3, pp. 337-343, May 1977.

[41] M. Burrows and D. J. Wheeler, "A block-sorting lossless data compression algorithm," *Technical report, Digital Equipment Corporation*, 1994.