<h3 style="border-bottom:none;color:blue;">ACM CoNEXT Workshop on In-Network Computing and AI for Distributed Systems (INCAS 2025)</h3>

---
**Steering Co-Chairs**  
Deke Guo (National University of Defense Technology)  
Dezun Dong (National University of Defense Technology)  
Theophilus A. Benson (Carnegie Mellon University)  

**Organization Co-Chairs：**

**Wenfei Wu (Peking University)**  
Dr. Wenfei Wu is a Boya young scholar and an assistant professor in the School of Computer Science at Peking University. He received his PhD from University of Wisconsin-Madison. His research focuses on computer networks and distributed systems and published more than 50 papers. His research about In-Network Computing (INC) received several awards, including NSDI’21 best paper award for INC-accelerated distributed training, ASPLOS’21 distinguished paper award for INC-accelerate data analytics, and CPCC’24 (Chinese Computation Power Conference) best academic paper for RDMA-compatible collective communication. Dr. Wu is the leading the INC workgroup in Ethernet+ Consortium.

**Xiaoxi Zhang (Sun Yat-sen University)**  
Xiaoxi Zhang received the B.E. degree in electronics and information engineering from the Huazhong University of Science and Technology in 2013 and the Ph.D. degree in computer science from The University of Hong Kong in 2017. She was a postdoctoral researcher in the Department of Electrical and Computer Engineering at Carnegie Mellon University from 2017 to 2020. She is currently an associate professor in the School of Computer Science and Engineering at Sun Yat-sen University. She has published more than 70 papers and was a recipient of the Young Outstanding Award of the Guangdong Province, Best Student Paper Award of IEEE MSN 2024, Best Paper Award of IEEE BigCom 2024, and Best Paper Nominee of IEEE/ACM IWQoS 2023. She is currently an Area Editor of Elsevier Computer Networks an Associate Editor of IEEE Networking Letters. She is broadly interested in optimization, algorithm design, and implementation for networked systems, including cloud and edge computing networks, distributed machine learning systems, and vehicular networks.

**Yiran Zhang (Beijing University of Posts and Telecommunications)**  
Yiran Zhang received the Ph.D. degree from Institute for Network Sciences and Cyberspace, Tsinghua University. She is an Assistant Professor with the State Key Laboratory of Networking and Switching Technology, Beijing University of Posts and Telecommunications, Beijing, China. Her research work has published on premier journals and premier conferences, such as ToN, JSAC, SIGCOMM, NSDI, MOBICOM, INFOCOM, ICNP, and ICWS. Her research interests include datacenter network, traffic control and management and was awarded the Euro-Par Best Paper Award and 2024 N2Women Rising Star.

**Qingkai Meng (Nanjing University)**  
Qingkai Meng is an Assistant Professor (Ph.D. Advisor) at the School of Intelligent Software and Engineering, Nanjing University. He obtained his Ph.D. from Tsinghua University in June 2022, under the supervision of Prof. Fengyuan Ren. From September 2019 to October 2020, he was a visiting scholar at the University of Wisconsin-Madison, working with Prof. Aditya Akella. His research interests include data center networks, transport protocols, and machine learning systems. His work has appeared at top system and networking venues such as USENIX NSDI, IEEE INFOCOM, and IEEE/ACM ToN. He actively contributes to the academic community by serving as a technical program committee member and reviewer for top-tier conferences and journals.

**Motivation of the workshop**  
The rise of programmable network devices -- such as switches and SmartNICs -- has enabled a new computing paradigm: **In-Network Computing (INC)**. By performing computation directly in the data plane, INC can reduce communication overhead, accelerate distributed coordination, and improve the efficiency of system-wide operations. **Distributed systems** stand to benefit significantly from this paradigm shift. Many of their core functions—such as replication, consensus, scheduling, aggregation, and load balancing—are communication-heavy and latency-sensitive. In-network computing provides a compelling opportunity to rethink these mechanisms by pushing parts of their logic into the network fabric. While recent research has demonstrated the feasibility of INC for specific tasks (e.g., cache indexing, gradient aggregation, distributed counters), broader system-level integration remains challenging. Open questions span from programming abstractions and hardware constraints to performance modeling, security, and compatibility with evolving distributed runtimes. This workshop focuses on **in-network computing and AI for distributed systems (INCAS)**. We aim to bring together researchers and practitioners to share emerging ideas, explore new design patterns, and identify key challenges at the intersection of programmable networks and distributed system architecture.  

---
**Web Chair**  
Songjun Huang (Sun Yat-sen University)

**Publication Chair**  
Jianqiang Zhong (Sun Yat-sen University)

**Publicity Chair**  
Haoran Xu (Sun Yat-sen University)

**Program Committee Members**  
Gianni Antichi (Politecnico di Milano and Queen Mary University of London)  
Wenxue Cheng (MSRA)  
Lin Cui (Jinan University)  
Jingpu Duan (Pengcheng Laboratory)  
Jiawei Huang (Zhongnan University)  
Jiayi Huang (HKUST-Guangzhou)  
Wanchun Jiang (Central South University)  
Zhuo Jiang (ByteDance)  
Wenxin Li (Tianjin University)  
Jiaxin Lin (Cornell University)  
Shinan Liu (HKU)  
Shuo Liu (Huawei)  
Youyou Lu (Tsinghua University)  
Zhixiong Niu (MSRA)  
Kun Qian (Alibaba)  
Yiming Qiu (HKU)  
Danfeng Shan (Xi'an Jiao Tong University)  
Haifeng Sun (NUS)  
Xiaoliang Wang (Nanjing University)  
Xingda Wei (Shanghai Jiaotong)  
Wenfei Wu (Peking University)  
Yongji Wu (UC Berkeley)  
Yunming Xiao (CUHK(SZ))  
Jiarong Xing (UC Berkeley)  
Hong Xu (CUHK)  
Lei Xue (Sun Yat-sen University)  
Gaoxiong Zeng (Huawei)  
Rongfei Zeng (Northeastern University)  
Menghao Zhang (Beihang University)  
Xiaoxi Zhang (Sun Yat-sen University)  
Gongming Zhao (USTC)  
Shizhen Zhao (Shanghai Jiao Tong University)  
Jiaqi Zheng (Nanjing University)  
Yang Zhou (UCB & UCD)  
**Potential committee members will be finalized soon*  

---
**Call for Papers**  
In-network computing (INC) has emerged as a powerful paradigm that integrates computation directly into the network fabric. By leveraging programmable switches, SmartNICs, and other data plane devices, INC enables unprecedented opportunities to accelerate distributed systems, data analytics, and AI workloads. As modern applications demand lower latency, higher throughput, and greater resource efficiency, INC is rapidly gaining traction in both academia and industry.
INCAS 2025 aims to bring together researchers and practitioners at the intersection of networking, systems, and AI to explore how INC can reshape the architecture of distributed computing. We invite original research contributions that investigate the design, implementation, and deployment of in-network computing, especially in the context of real-world constraints such as limited hardware resources, system-level integration, and stringent performance requirements. Topics of interest include, but are not limited to: 

   **1. INC for AI workloads**  
      -	In-network acceleration of machine learning inference (e.g., CNNs, RNNs, transformers)
      -	In-network acceleration for distributed model training, e.g., efficient in-network execution of collective operations
      -	Explorations on deploying large vision and language models with INC

<div style="margin-left: 30px;">

**2. INC for distributed data analytics**  
-	In-network support for real-time data aggregation, transformation, and filtering
-	Acceleration of stream and batch processing pipelines
-	Integration of INC into distributed query execution and analytics engines

</div>

**3. AI with INC for network management**  
-	AI-enhanced network traffic engineering using INC, intelligent traffic prediction, advanced telemetry, and AI-enabled use of INC for real-time anomaly detection and fault diagnosis
-	AI-driven network management, orchestration, and resource optimization leveraging INC, including applications of AI/ML with INC for efficient network control and automated management
-	Predictive network maintenance using INC and AI for proactive fault prediction and intelligent maintenance scheduling
-	On-path enforcement of routing, access control, and QoS policies 
-	AI-assisted and INC-enabled smart cloud-edge network management and coordination
-	Programmable fault monitoring and distributed failure response mechanisms
-	Protocol enhancement via INC, e.g., redesign of end-to-end protocols to take advantage of programmable dataplanes

**4. INC for data storage and caching**  
-	In-network support for key-value lookups, metadata indexing, and content-addressable storage
-	Programmable data paths for consistency enforcement, replication, and coordination in distributed storage
-	On-path caching, coherence, and eviction mechanisms for latency-sensitive workloads
-	Acceleration of storage systems and protocols (e.g., NFS, NVMe-over-Fabrics), including those leveraging RDMA-based transports
-	Offloading I/O processing and load balancing in large-scale storage clusters using programmable switches or SmartNICs

**5. Protocol and system-level innovations for INC**  
-	INC-aware routing protocol design, including programmable control over path selection, route updates, and fast failoverIn-network support for congestion control, reliability, and flow scheduling
-	In-network support for transport-layer functions, such as congestion control, reliability, and flow scheduling
-	Task coordination, pipelining, and batching mechanisms within in-network systems
-	Adaptive resource allocation and scheduling for switch/NIC/FPGA-based environments

**6. Tooling and development support for INC**  
-	Compilers, debuggers, and developer tools for INC platforms
-	Using foundation models (e.g., LLMs or diffusion models) to assist INC system design, and their application for intelligent network operations, management, and AI-powered assistants in INC environments.

**7. Security and robustness enhancement for INC**  
-	In-network security policies and anomaly detection mechanisms
-	Fault isolation, recovery, and robustness in deployed programmable networks
-	Experiences and lessons from production-level or testbed-scale INC deployments

---
We will follow the submission format requirements of previous CoNEXT workshops:
Submissions must be original, unpublished work, and not under consideration at another
conference or journal. Submitted papers must be at most six (6) pages long, excluding
references and appendices, in two-column 10pt ACM format. Authors of accepted
submissions are expected to present and discuss their work at the workshop.
All submissions will be peer-reviewed, and the review process will be double-blind. Per the
anonymity guidelines, please prepare your paper in a way that preserves the anonymity of
the authors. No information will be shared with third parties.

---
**Expected Number of Submissions and Participants**  
We anticipate receiving around 30 paper submissions with an acceptance rate of 40-50%
(select eight papers for oral presentations; the remaining as posters). Besides organizers,
we expect around 50 participants.

---
**Planned Format (Length: Half Day)**

**13:30 - 14:00**: Registration & Welcome Refreshments. Check-in and informal networking

**14:00 - 14:10**: Opening Remarks. Introduction to the organizers and the goals of the Workshop

**14:10 - 14:40**: [Keynote 1] Speaker: Prof. Wenfei Wu (Peking University)  
Topic: The Trend, Challenges, and Opportunities of In-Network Computing 

**14:40 - 15:20: [Session 1] INC for Diverse Applications in Distributed Systems**  
This session features invited talks and paper presentations on the use of in-network computing across various distributed system domains, such as AI workloads, data analytics, storage, and caching. Speakers from both academia and industry will share recent research, system architectures, and deployment experiences. An interactive discussion segment will follow to encourage cross-domain knowledge exchange.

**15:20 - 15:50**: [Keynote 2] Speaker: Prof. Gianni Antichi (Politecnico di Milano and Queen Mary University of London)  
Topic: Advancing Networked Systems: The Role of Programmable Data Planes, Monitoring, and Offloading

**15:50 - 16:20: [Session 2] Networking, Systems, and Tooling Innovations for INC**  
This session highlights advances in protocol design, task scheduling, routing, and transport innovations that enable or optimize in-network computing. It also covers tooling and compiler support for programmable dataplanes, security mechanisms for in-network operations, and integration with distributed runtimes. Topics include protocol offloading, coordination mechanisms, fault tolerance, and the development ecosystems for INC platforms.

**16:20 - 17:00: [Session 3] Poster Poster & Interactive Session**  
This session features posters and informal discussions on deployment experiences, system prototypes, and early-stage ideas. Topics include INC use cases in distributed systems, integration challenges, and the intersection of large models and INC -- both for accelerating models and using them to enhance INC design and control.

**17:00 - 17:30**: Closing Remarks. 

---
**Additional Requirements Specific to the Workshop**  
The workshop will include a poster session where all poster papers are expected to be
presented.

---
**Publicity Plan**  
To ensure strong participation and broad visibility, the **INCAS 2025** workshop will be promoted through multiple channels, including the official ACM CoNEXT website, academic mailing lists, and a range of social media platforms (e.g., LinkedIn, Twitter/X, WeChat, and others). We will also conduct direct outreach to leading researchers and industry professionals in relevant fields.

---
**Important Date (All AoE Time)**  
Workshop paper abstract registration: July 8th, 2025  
Workshop paper submission: July 15th, 2025  
Notification of acceptance: August 31st, 2025  
Camera-ready workshop papers: September 25th, 2025  
Program available online: October 12th, 2025  
List of organization details: October 12th, 2025
