# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting
### DATE: 09-11-2026                                                                         
### REGISTER NUMBER : 212225040344
### Aim: To write the prompt for the following prompt types and compare that with different AI tools and evaluate that using any one evaluation method (Ex. Rubrics). Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting 

### Explanation - Any one use case from Unit 5 and write the prompt for that with the unit 2 Prompt types given above.

Procedure:
1.	Define the Scenario and Use Case:
Scenario:
The manufacturing industry is looking to reduce manual monitoring and increase efficiency through automation. The system will utilize IoT devices and embedded controllers to automate equipment, monitor performance, and enable predictive maintenance. The goal is to streamline the production process, minimize downtime, and enhance energy efficiency.
Target Audience:
Manufacturing companies, specifically in sectors like automotive, electronics, and food processing, where automation can significantly improve productivity.

Main Objectives:

•	Improve production efficiency by 30%.
•	Minimize machinery downtime with predictive maintenance.
•	Enable real-time monitoring and remote control of manufacturing systems.
•	Reduce energy consumption by optimizing processes.
 
2.	Identify Prompt Patterns for Each Design Aspect:
Idea Generation Prompts:

Comparative Analysis Prompt
Definition: Asking for a comparison between two or more concepts, often highlighting similarities and differences.
•	"Compare and contrast deep learning and machine learning."
•	"How do renewable and non-renewable energy sources differ?"

Experiential Perspective Prompt:
> 	“As a software engineer, what are the benefits of using cloud computing in your projects?”
>  “From a student’s perspective, describe the challenges of online learning.”

Everyday Functioning Prompts:
*	  “Describe the role of machine learning in everyday apps like YouTube or Netflix."
*	 	“How is encryption used in daily life when sending WhatsApp messages?”

Universal Prompt Structures:
^ 	“Explain [concept] in simple terms with an example.”
^  “Explain the process of [task] step by step.”

Prompt Size Limitations:
&  	“Translate this 5000-word essay into Tamil.”
→ Manageable chunks: “Translate the first 1000 words into Tamil, then continue.”
&  “Give me 50 examples of AI applications.”
→ Adjust for size: “Give me 10 AI applications at a time.”

# EX.NO.4 – GENERATING AND EVALUATING DIFFERENT PROMPT PATTERNS FOR MANUFACTURING AUTOMATION

## 1. AIM

To design and evaluate different prompt patterns, namely Zero-Shot Prompting, Few-Shot Prompting, Chain-of-Thought Prompting, Persona Pattern, Reverse Prompting, Graph Prompting, and Active Prompting, using multiple AI tools for a manufacturing automation application.

The generated responses are compared using a rubric-based evaluation method to identify the effectiveness of each prompting technique.

## 2. SELECTED SCENARIO

**Project Title: IoT-Based Smart Manufacturing Automation and Predictive Maintenance System**

### Problem Statement

Manufacturing industries such as automotive, electronics, and food processing depend on machines and equipment for continuous production. Manual monitoring of machinery can result in delayed fault detection, unexpected equipment failures, increased maintenance costs, and energy wastage.

To overcome these challenges, an IoT-based smart manufacturing automation system is proposed. The system uses IoT sensors, embedded controllers, and AI-based analysis to monitor machine performance, automate equipment operations, and predict possible failures.

### Main Objectives

1. Improve production efficiency by 30%.
2. Minimize machinery downtime through predictive maintenance.
3. Enable real-time monitoring and remote control.
4. Reduce energy consumption through process optimization.
5. Identify abnormal machine conditions at an early stage.
6. Improve equipment reliability and production quality.

## 3. SYSTEM OVERVIEW

The proposed system collects machine data using IoT sensors and sends it to a central monitoring platform. The embedded controller processes sensor readings and controls connected equipment. AI-based analysis identifies unusual operating conditions and predicts possible maintenance requirements.

### System Architecture

```text
       MANUFACTURING MACHINERY
                 |
                 v
          IoT SENSORS
      (Temperature, Vibration,
        Pressure, Energy)
                 |
                 v
       EMBEDDED CONTROLLER
                 |
                 v
        DATA COMMUNICATION
                 |
                 v
       CLOUD / MONITORING
             PLATFORM
                 |
                 v
        AI-BASED ANALYSIS
                 |
          +------+------+
          |             |
          v             v
    Fault Detection  Energy Analysis
          |             |
          v             v
   Maintenance Alert  Optimization
          |             |
          +------+------+
                 |
                 v
       AUTOMATION DASHBOARD
```

## 4. ZERO-SHOT PROMPTING

**Definition:**

Zero-Shot Prompting is a technique in which an AI model receives a direct instruction without any examples. The model uses its existing knowledge to generate the requested response.

**Prompt:**

"Design an IoT-based smart manufacturing automation system that monitors machine performance, predicts equipment failures, reduces downtime, and improves energy efficiency. Explain its architecture, important components, working process, and advantages."

**AI-Generated Output:**

An IoT-based smart manufacturing automation system uses sensors to continuously monitor machinery conditions such as temperature, vibration, pressure, and energy consumption. The collected data is transferred to an embedded controller and monitoring platform. AI-based analysis identifies abnormal machine behaviour and predicts possible equipment failures.

The system generates maintenance alerts before serious breakdowns occur. It also monitors energy consumption and helps optimize machine operations. A centralized dashboard allows operators to view equipment status and control supported operations remotely.

The system improves production efficiency, reduces unexpected downtime, supports predictive maintenance, and minimizes energy wastage.

**Observation:**

- Generates a direct solution without examples.
- Suitable for basic system descriptions.
- Provides a quick overview of the proposed application.
- May require additional instructions for technical details.

## 5. FEW-SHOT PROMPTING

**Definition:**

Few-Shot Prompting provides examples before the actual question. These examples guide the AI in understanding the expected format and response style.

**Prompt:**

"Generate manufacturing automation solutions by following the examples below.

Example 1:

Problem: High machine temperature.

Solution: Install temperature sensors and generate alerts when the temperature exceeds the permitted limit.

Example 2:

Problem: Unexpected machine vibration.

Solution: Use vibration sensors to detect abnormal movement and schedule maintenance.

Now identify five problems in a manufacturing industry and provide suitable IoT-based automation solutions in the same format."

**AI-Generated Output:**

| Manufacturing Problem | IoT-Based Solution |
|---|---|
| High machine temperature | Install temperature sensors and generate alerts |
| Excessive vibration | Use vibration sensors to detect abnormal conditions |
| Unexpected equipment failure | Apply predictive maintenance using sensor data |
| High energy consumption | Monitor energy usage and optimize machine operations |
| Production delays | Use real-time production monitoring and automated alerts |

**Observation:**

- Follows the given examples.
- Produces consistent and structured responses.
- Helps generate multiple solutions in a common format.
- Output quality depends on the examples provided.

## 6. CHAIN-OF-THOUGHT PROMPTING

**Definition:**

Chain-of-Thought Prompting encourages the AI to approach a complex problem through organized stages before presenting the final answer.

**Prompt:**

"Analyze the manufacturing automation problem systematically.

1. Identify the main challenges in manufacturing.
2. Identify suitable IoT sensors and embedded controllers.
3. Explain how machine data can be collected and monitored.
4. Explain how abnormal machine conditions can be detected.
5. Describe how predictive maintenance can reduce downtime.
6. Suggest methods to optimize energy consumption.

Based on this analysis, prepare a complete smart manufacturing automation solution in simple technical English. Provide the final answer in clearly organized sections."

**AI-Generated Output:**

The manufacturing industry faces challenges such as unexpected machine failures, manual monitoring, production delays, and high energy consumption.

An IoT-based automation system can address these challenges using temperature, vibration, pressure, and energy sensors. These sensors collect machine operating information and transmit it to embedded controllers.

The collected information is stored and analyzed by a monitoring platform. AI-based analysis detects abnormal operating conditions and identifies possible equipment failures. Maintenance alerts are generated so that technicians can inspect machines before major breakdowns occur.

Energy monitoring helps identify unnecessary consumption and supports efficient machine operation. A centralized dashboard provides real-time equipment information and remote monitoring capabilities.

This system supports better production management, reduced downtime, and improved energy efficiency.

**Observation:**

- Breaks a complex problem into manageable stages.
- Helps cover multiple aspects of the engineering problem.
- Produces organized explanations.
- Useful for system design and technical analysis.

## 7. PERSONA PATTERN

**Definition:**

Persona Pattern assigns a particular professional role to the AI. The response is generated from the perspective of that role.

**Prompt:**

"Act as an experienced Industrial Automation Engineer with expertise in IoT, embedded systems, predictive maintenance, and smart manufacturing. Design an IoT-based automation system for an automotive manufacturing industry. Explain the required hardware, software, sensor technologies, communication methods, predictive maintenance process, and energy optimization techniques. Present the solution in a professional engineering report format."

**AI-Generated Output:**

As an industrial automation engineer, I recommend an IoT-based smart manufacturing architecture consisting of sensors, embedded controllers, communication networks, and a centralized monitoring platform.

Temperature and vibration sensors monitor equipment conditions, while energy sensors measure electrical consumption. Embedded controllers collect sensor readings and communicate with the monitoring platform through suitable industrial communication protocols.

The platform analyzes operating data and identifies abnormal patterns. Predictive maintenance algorithms help estimate possible equipment failures and generate maintenance alerts.

An automation dashboard provides machine status, energy reports, and maintenance notifications. Remote control should be implemented with appropriate access control and safety interlocks.

The proposed system can improve equipment monitoring, reduce unplanned downtime, and support efficient manufacturing operations.

**Observation:**

- Generates professional and domain-specific responses.
- Uses terminology relevant to industrial automation.
- Provides solutions from an engineering perspective.
- Suitable for technical reports and project development.

## 8. REVERSE PROMPTING

**Definition:**

Reverse Prompting is a technique in which the AI is asked to identify or construct the prompt that could generate a given output. It helps understand the instructions and requirements behind a particular response.

**Prompt:**

"Consider the following proposed solution:

An industrial monitoring system uses temperature and vibration sensors to collect machine data. An embedded controller sends the information to a cloud platform. AI algorithms analyze the data, predict equipment failures, and generate maintenance alerts. A dashboard allows operators to monitor machinery and energy consumption.

Create a detailed prompt that could generate this solution. Include the role, context, objectives, technical requirements, and expected output format."

**AI-Generated Output:**

**Reverse-Generated Prompt:**

"Act as an industrial IoT engineer. Design a smart manufacturing monitoring system that uses temperature and vibration sensors to collect real-time machine data. Include an embedded controller for data acquisition, a cloud-based monitoring platform, and AI algorithms for predictive maintenance. Explain how the system identifies abnormal machine conditions, predicts possible equipment failures, generates maintenance alerts, and monitors energy consumption. Present the solution using a system architecture, component table, working procedure, and expected benefits."

**Observation:**

- Helps identify the requirements behind a solution.
- Converts an existing description into a reusable prompt.
- Supports prompt improvement and refinement.
- Useful when the desired output is already known.

## 9. GRAPH PROMPTING

**Definition:**

Graph Prompting represents information through nodes and relationships. It helps the AI understand how different components of a system are connected.

**Prompt:**

"Represent an IoT-based smart manufacturing automation system as a directed graph. Use the following components as nodes: Manufacturing Machines, IoT Sensors, Embedded Controller, Cloud Platform, AI Analysis, Predictive Maintenance, Energy Monitoring, and Automation Dashboard. Show the relationships and data flow between these components. Explain the role of each node."

**AI-Generated Output:**

### Graph Representation

```text
       [Manufacturing Machines]
                  |
                  v
             [IoT Sensors]
                  |
                  v
        [Embedded Controller]
                  |
                  v
           [Cloud Platform]
                  |
                  v
             [AI Analysis]
                  |
          +-------+-------+
          |               |
          v               v
 [Predictive          [Energy
  Maintenance]        Monitoring]
          |               |
          v               v
 [Maintenance         [Energy
     Alerts]          Reports]
          |               |
          +-------+-------+
                  |
                  v
       [Automation Dashboard]
```

### Component Relationship Table

| Node | Connected Component | Relationship |
|---|---|---|
| Manufacturing Machines | IoT Sensors | Provides machine operating conditions |
| IoT Sensors | Embedded Controller | Sends sensor readings |
| Embedded Controller | Cloud Platform | Transfers collected data |
| Cloud Platform | AI Analysis | Provides data for analysis |
| AI Analysis | Predictive Maintenance | Identifies possible equipment failures |
| AI Analysis | Energy Monitoring | Analyzes energy consumption |
| Predictive Maintenance | Automation Dashboard | Displays maintenance alerts |
| Energy Monitoring | Automation Dashboard | Displays energy reports |

**Observation:**

- Shows relationships between system components.
- Makes complex architectures easier to understand.
- Helps identify the data flow.
- Useful for system design and technical documentation.

## 10. ACTIVE PROMPTING

**Definition:**

Active Prompting is a technique in which the AI requests additional information or clarification when important details are missing. This helps produce more relevant and accurate responses.

**Initial Prompt:**

"Design an IoT-based smart manufacturing automation system to reduce machine downtime and energy consumption."

**AI Clarification Questions:**

1. Which manufacturing industry is the system designed for?
2. What type of machinery should be monitored?
3. Which operating parameters should be measured?
4. Should the system support real-time remote monitoring?
5. What is the expected maintenance alert method?
6. Should the system include energy consumption monitoring?

**User's Clarified Requirements:**

| Question | Selected Requirement |
|---|---|
| Manufacturing industry | Automotive manufacturing |
| Machinery | Industrial production machines |
| Parameters | Temperature, vibration, pressure, energy |
| Monitoring | Real-time monitoring |
| Alert method | Dashboard and maintenance notifications |
| Energy monitoring | Required |

**Final Prompt:**

"Design an IoT-based smart manufacturing automation system for an automotive manufacturing industry. Monitor temperature, vibration, pressure, and energy consumption using IoT sensors. Use embedded controllers to collect data and transmit it to a centralized monitoring platform. Include real-time dashboards, predictive maintenance, abnormal-condition alerts, and energy optimization. Explain the architecture, hardware, software, and working process."

**AI-Generated Output:**

The proposed system uses IoT sensors installed on industrial production machines to monitor temperature, vibration, pressure, and energy consumption. Embedded controllers collect and transmit the sensor data to a centralized monitoring platform.

The platform analyzes machine conditions and identifies unusual operating patterns. Predictive maintenance algorithms generate alerts when potential equipment failures are detected. Energy monitoring identifies inefficient machine operations and supports energy optimization.

A dashboard displays real-time machine status, maintenance notifications, and energy reports. Authorized operators can monitor the system remotely, while safety controls prevent unsafe machine operations.

**Observation:**

- Improves output by collecting missing requirements.
- Reduces ambiguity in broad prompts.
- Produces solutions that match the selected industry.
- Useful for real-world engineering problem solving.

## 11. COMPARISON OF ALL SEVEN PROMPT PATTERNS

| S.No. | Prompt Pattern | Main Purpose | Major Advantage |
|---|---|---|---|
| 1 | Zero-Shot | Direct instruction | Quick response generation |
| 2 | Few-Shot | Learning from examples | Consistent output format |
| 3 | Chain-of-Thought | Organized problem analysis | Better coverage of complex tasks |
| 4 | Persona Pattern | Assigning a professional role | Domain-specific responses |
| 5 | Reverse Prompting | Creating a prompt from an output | Prompt reconstruction |
| 6 | Graph Prompting | Representing relationships | Clear system visualization |
| 7 | Active Prompting | Asking for missing information | More relevant responses |

## 12. COMPARISON OF DIFFERENT AI TOOLS

The same seven prompt patterns can be tested using ChatGPT, Google Gemini, Claude, and Microsoft Copilot.

| AI Platform | Purpose of Evaluation |
|---|---|
| ChatGPT | Evaluate prompt understanding and technical explanation |
| Google Gemini | Compare generated solutions and structured outputs |
| Claude | Evaluate clarity, coherence, and detailed explanations |
| Microsoft Copilot | Compare technical responses and practical suggestions |

### Cross-Platform Execution Table

| Prompt Pattern | ChatGPT | Gemini | Claude | Copilot |
|---|---|---|---|---|
| Zero-Shot | Test response | Test response | Test response | Test response |
| Few-Shot | Test response | Test response | Test response | Test response |
| Chain-of-Thought | Test response | Test response | Test response | Test response |
| Persona | Test response | Test response | Test response | Test response |
| Reverse | Test response | Test response | Test response | Test response |
| Graph | Test response | Test response | Test response | Test response |
| Active | Test response | Test response | Test response | Test response |

## 13. RUBRIC-BASED EVALUATION

A rubric is used to evaluate the quality of AI-generated responses.

### Evaluation Criteria

| Parameter | Description | Maximum Score |
|---|---|---:|
| Accuracy | Correctness of technical information | 5 |
| Relevance | Suitability for the manufacturing scenario | 5 |
| Clarity | Ease of understanding | 5 |
| Completeness | Coverage of important requirements | 5 |
| Structure | Organization and presentation | 5 |
| **Total** | | **25** |

### Rubric Rating Scale

| Score | Performance Level |
|---|---|
| 5 | Excellent |
| 4 | Very Good |
| 3 | Good |
| 2 | Needs Improvement |
| 1 | Poor |

### Sample Evaluation of Prompt Patterns

The following scores are illustrative ratings based on the sample responses, not measured results from all four platforms.

| Prompt Pattern | Accuracy | Relevance | Clarity | Completeness | Structure | Total |
|---|---:|---:|---:|---:|---:|---:|
| Zero-Shot | 4 | 4 | 4 | 3 | 4 | 19/25 |
| Few-Shot | 4 | 5 | 5 | 4 | 5 | 23/25 |
| Chain-of-Thought | 5 | 5 | 4 | 5 | 5 | 24/25 |
| Persona | 5 | 5 | 5 | 5 | 5 | 25/25 |
| Reverse | 4 | 5 | 5 | 4 | 5 | 23/25 |
| Graph | 5 | 5 | 5 | 5 | 5 | 25/25 |
| Active | 5 | 5 | 5 | 5 | 5 | 25/25 |

**Evaluation Formula:**

Percentage score = (Obtained Score / Maximum Score) × 100

For example, if a prompt receives 24 out of 25:

Percentage = (24 / 25) × 100 = 96%

## 14. ANALYSIS AND OBSERVATIONS

1. Zero-Shot Prompting generated a basic manufacturing automation solution using a direct instruction.
2. Few-Shot Prompting produced structured solutions by following the given examples.
3. Chain-of-Thought Prompting organized the manufacturing problem into logical stages.
4. Persona Pattern generated professional explanations from an industrial automation engineer's perspective.
5. Reverse Prompting reconstructed a detailed prompt from an existing system description.
6. Graph Prompting represented the relationships between sensors, controllers, cloud platforms, and maintenance modules.
7. Active Prompting collected missing requirements and improved the relevance of the final solution.
8. The same prompt pattern may produce different outputs across AI platforms.
9. Rubric-based evaluation helps compare the generated responses using common criteria.
10. The choice of prompting technique depends on the complexity and expected output of the task.

## 15. ADVANTAGES

1. Improves the quality of AI-generated engineering solutions.
2. Supports technical problem-solving and system design.
3. Produces structured and understandable reports.
4. Helps identify missing requirements.
5. Supports visual representation of system architecture.
6. Allows comparison of multiple AI platforms.
7. Reduces the effort required to prepare technical documentation.

## 16. LIMITATIONS

1. AI-generated technical solutions may contain incorrect assumptions.
2. Few-Shot Prompting depends on the quality of examples.
3. Chain-of-Thought prompts may require longer processing time.
4. Persona Pattern does not guarantee professional-level correctness.
5. Reverse Prompting may generate a prompt that differs from the original instructions.
6. Graph Prompting requires clearly defined nodes and relationships.
7. Active Prompting may require multiple interactions before producing the final answer.
8. Generated engineering designs must be validated before actual industrial implementation.

## 17. FINAL SELECTED PROMPT PATTERN

**Selected Pattern: Active Prompting combined with Persona Pattern**

The combination is selected because Active Prompting helps collect missing project requirements, while Persona Pattern provides domain-specific engineering guidance.

**Final Combined Prompt:**

"Act as an experienced Industrial Automation Engineer specializing in IoT and predictive maintenance. Before preparing the solution, identify any missing requirements related to the manufacturing industry, machine types, sensors, communication methods, safety requirements, and energy monitoring. After obtaining the necessary details, design a complete smart manufacturing automation system. Include system architecture, hardware components, software modules, predictive maintenance, real-time monitoring, and energy optimization. Present the final solution in a structured engineering report."

## 18. RESULT

The seven prompt patterns, namely Zero-Shot, Few-Shot, Chain-of-Thought, Persona Pattern, Reverse Prompting, Graph Prompting, and Active Prompting, were successfully designed and demonstrated using the IoT-based smart manufacturing automation scenario. The generated outputs were compared using a rubric-based evaluation method covering accuracy, relevance, clarity, completeness, and structure. The experiment demonstrated how different prompting patterns can support engineering problem-solving, system design, and technical report development.

## 19. CONCLUSION

This experiment demonstrates the importance of selecting suitable prompt patterns for solving real-world engineering problems. Each prompting technique provides a different approach to generating AI responses. Zero-Shot Prompting is suitable for direct instructions, Few-Shot Prompting provides examples, Chain-of-Thought Prompting supports systematic analysis, and Persona Pattern generates role-specific responses. Reverse Prompting helps reconstruct prompts, Graph Prompting represents system relationships, and Active Prompting improves responses by collecting missing information.

The rubric-based evaluation provides a structured method for comparing AI-generated outputs. The combination of Active Prompting and Persona Pattern is particularly useful for manufacturing automation because it gathers the necessary requirements and generates a domain-specific solution.

# Result: The various types of Prompts are executed successfully with generated the report.
