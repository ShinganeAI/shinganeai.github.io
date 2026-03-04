# **The Genesis of Substrate One: Early Milestones in AI for Embedded Systems**

The journey of **Substrate One** began with a series of discussions and opportune moments, culminating in a focused vision for leveraging Artificial Intelligence in the realm of embedded systems. This essay highlights the foundational ideas and pivotal developments that shaped our company.

## **The Seed of Collaboration**

For months, Alireza Goudarzi and Babak Kia had explored potential avenues for collaboration. The turning point arrived in the fall of 2024 when Babak Kia was approached by an investor with a compelling proposition: the integration of AI into embedded systems. This encounter narrowed our collective focus, leading us to investigate the application of AI for either optimization or code generation within this specialized domain.

## **Identifying Market Challenges and Forces**

Following extensive market research, Babak Kia conceived an initial pitch deck that meticulously outlined the significant challenges inherent in digital design for embedded systems. These challenges were threefold:

1. **Huge and Growing Demand:** The continuous expansion of IoT, smart devices, and interconnected technologies creates an insatiable demand for embedded systems.  
2. **Lack of Talent:** A significant shortage of skilled engineers proficient in embedded systems design and programming exacerbates development bottlenecks.  
3. **Long Development Cycles:** The intricate nature of embedded systems often leads to protracted development timelines, impacting time-to-market.

Concurrently, several powerful market forces underscored the urgency and potential impact of our proposed solutions:

* Massive investments in customized chips for **Large Language Model (LLM) inference**.  
* Substantial investments in new waves of **robotics**, including robotaxis, humanoids, and other advanced robotic systems.

---

## **Ideation and Initial Product Concepts**

After much deliberation, Alireza Goudarzi and Babak Kia formulated several innovative ideas to address these challenges:

### **1\. Automatic Code Conversion (Python to Verilog)**

This concept aimed to facilitate the automatic porting of compute-intensive applications to **Field-Programmable Gate Arrays (FPGAs)** to accelerate application performance.

Unlike ASICs (Application-Specific Integrated Circuits), which are designed for a fixed function, FPGAs offer flexibility as their internal connections and logic blocks can be reconfigured. This makes them ideal for prototyping and custom hardware acceleration.

### **2\. Conversion of C/C++ to Rust**

**Rust** is gaining traction in embedded systems due to memory safety and performance. However, converting legacy C/C++ codebases is a colossal task hindered by a scarcity of personnel. **Substrate One** aims to bridge this gap through automated migration.

### **3\. Coding Assistant for Embedded Engineers**

Many tasks in embedded programming are mundane, such as initial project configuration and writing basic drivers to control hardware. These tasks are prime candidates for automation via an AI-powered assistant.

Each of these ideas was swiftly transformed into a simple demonstration, which proved instrumental in engaging both potential customers and investors.

---

## **The Emergence of Appledore**

More recently, our exploration led to the discovery of a straightforward method to enhance existing coding agents in generating code for hardware: creating specialized context that can be retrieved in real-time through an **MCP (Multi-Contextual Processing) server**. This breakthrough spurred the development of our new product, which we proudly call **Appledore**.

