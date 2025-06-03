
<a href=""><img src="blueprint.svg" alt="Blueprint Icon" width="100"/></a>

<br><br>

# Binary Trees Lecture - in Algorithms and Data Structures Course

<br>




## 1. General Course and Lecture Description


|   |  |
|---------------------------|------------------------------------------------|
| **ACM Category:**         | Algorithmic Foundations (AL)|
| **Knowledge Unit:**       | AL-Foundational |
| **Course Overview:**       | Algorithms and Data Structures 2 provides students with advanced knowledge of algorithms and data structures, such as specialized tree variants and hashing. Students will learn graph principles, implementation, applications, and advanced algorithms for analyzing graph structures. Ultimately, they will be able to adapt and combine existing algorithms and data structures to derive problem-specific solutions. |
| **Course Modalities:**       | Lab, 90 min      |
| **Lecture Context:**       | The lecture introduces height-balanced trees, exemplified by AVL trees. Students will revisit binary trees, understand the height-balance property, and learn to implement AVL trees. Key outcomes include the ability to assess AVL tree validity (with justification) and perform operations to maintain or restore all AVL properties.|
| **Keywords/Topics:**       | Binary Trees <br> Height-Balanced Trees <br> Tree Rotation |



<br><br>


## 2. Lecture Contents  & Learning Objectives





|    | **Lecture-related LO**    | Level | 
|---------------------------|------------------------------------------------|----|
| <a name="LO_C01"></a>LO_C1  | Students can explain the fundamental concepts of binary trees, which form the basis for AVL trees  | [EXPLAIN]|
| <a name="LO_C02"></a>LO_C2  | Given a set of trees, students are able to distinguish which are general trees, binary trees, or AVL trees by analyzing their respective properties, such as height-balancedness, and justifying their classifications. |[EVALUATE]|
| <a name="LO_C03"></a>LO_C3  | Given a valid AVL tree, students can apply the necessary rotation operations to restore AVL integrity after an insert or delete operation. |[APPLY]|
| <a name="LO_C04"></a>LO_C4  | Students can implement an AVL tree data structure, including methods for insertion, deletion, and the associated rebalancing operations (rotations), in a specified programming language (e.g., Java or Python). | [CREATE]|



|    | **LAI-related LO**    |Level   | AI Usage |
|---------------------------|------------------------------------------------|----|---|
| <a name="LO_AI01"></a>LO_AI1  | tudents can use AI tools to generate checklists for assessing the conformance of data structures (e.g., AVL trees) to their defining properties. | [EXPLAIN]|[Explain]|
| <a name="LO_AI02"></a>LO_AI2  | Students can employ AI tools to generate visual representations of tree structures and modify these.  |[APPLY] |[Generate]|
|<a name="LO_AI03"></a>LO_AI3 | Students can leverage AI tools to validate their assumptions and seek clarification on tree concepts, thereby resolving misunderstandings. |[EXPLAIN]|[Explain] |
|<a name="LO_AI04"></a> LO_AI4  |  Students can utilize AI tools to review their source code and receive suggestions for its refinement (e.g., regarding style, correctness, or efficiency).   | [EVALUATE] |[Refine]|



<br><br>

## 3. Lecture Activities

### Description

Students start the lecture by self-critically analyzing their prior knowledge using AI-generated checklists. They will then meet the DOT graph definition language for the first time and will use AI tools to visualize and modify these trees. The students will then use their visualization prompts to visualize a given set of trees, which they will then inspect regarding their properties together with AI. Finally, we will develop the core of the cut-and-link technique together, yet the implementation will contain room for improvement that should be explored using AI.

### Activities


| **1-Activity**    |  AI-Powered DOT Visualization and Modification | 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_C1](#LO_C01)/[LO_AI1](#LO_AI01)) |
| **Description:**   |   Students will prompt an AI tool to generate a checklist of binary and binary search tree properties. They will then use this AI-generated list to self-critically assess their existing knowledge.|
| **Resources:**   | - A sample AI prompt will be displayed on a lecture slide after the task.<br> - Tool use: Chatbot (Google Gemini / ChatGPT / Claude / ...)|
| **Assessment:**   | Observe students' interaction with the AI for checklist generation. Briefly review a few generated checklists for completeness. Ask 1-2 students to share a key property their AI identified for binary trees. Initial discussion on prompt engineering will happen. |


<br><br>




| **2-Activity**    | AI-Powered DOT Visualization and Modification | 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_AI2](#LO_AI02)) |
| **Description:**   |Students will use AI tools to render initial DOT graph descriptions. They will then instruct the AI to modify these DOT structures and observe the resulting visual changes to understand the language.|
| **Resources:**   |  - DOT graph provided via LMS (Learning Management System)<br> - Initial prompt for refinement via LMS ("... Provide your visualization in a single, self-contained HTML file")<br> - Tool use: Chatbot with "Canvas" functionality, i.e., immediate display of generated HTML files.|
| **Assessment:**   | Monitor if students can successfully use AI to render and modify DOT strings. Spot-check visualizations and ask students to explain a modification they made (or more specifically how they instructed the AI) and its effect.
 |

<br><br>


| **3-Activity**    | AVL Tree Validation with AI Dialogue| 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_C2](#LO_C02)/[LO_AI3](#LO_AI03)) |
| **Description:**   | Students will visualize provided DOT tree structures, manually analyze them for AVL properties (including balance factors), and then use an AI tool to validate their assessments and clarify any misunderstandings.  |
| **Resources:**   |- A sample AI prompt will be displayed on a lecture slide after the task.<br> - Tool use: Chatbot with "Canvas"<br> functionality, i.e., immediate display of generated HTML files. |
| **Assessment:**   | Circulate and observe students' manual AVL property checks. Listen to their prompts and the AI's explanations. Ask targeted questions like, "Why did you conclude this tree was/wasn't an AVL tree before asking the AI?" or "What was a key insight the AI provided for tree X?" |


| **4-Activity**    | Rotation Implementation and AI Refinement| 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  | ([LO_C3](#LO_C03)/[LO_C4](#LO_C04)/[LO_AI4](#LO_AI04)) |
| **Description:**   |Students will complete a partially implemented AVL rotation function. Subsequently, they will use an AI tool to review their code, receiving suggestions for correctness, style, and efficiency.  |
| **Resources:**   | - Code skeleton via LMS <br>- Two tool usages for comparison: General Chatbot (Google Gemini / ChatGPT / Claude / ...) and built-in coding tool (GitHub Co-Pilot) |
| **Assessment:**   | Observe students' attempts at completing the rotation code. Check if they can identify the correct rotation type. Review their interaction with AI for code refinement, asking what kind of feedback they received and found useful. Initiate a discussion on chatbot VS coding tool. |




<br><br>



### Assignment/Homework/Additional Activities


__Problem 1 (Tree Analysis & Justification):__
([LO_C1](#LO_C01)/[LO_C2](#LO_C02)) : Provide 2-3 new tree structures (in DOT or descriptive format). Students must:
Classify each as general tree, binary tree, BST, and/or AVL tree.
Provide detailed written justification for their AVL tree classifications, including calculated balance factors for all nodes.

__Problem 2 (AVL Operations & Visualization):__
([LO_C3](#LO_C03)/[LO_AI02](#LO_AI02)): Given an initial AVL tree and a sequence of 2-3 insertions/deletions, students must:
Show the state of the tree after each operation, clearly indicating any rotations performed.
Use an AI tool to generate a DOT visualization of the final AVL tree and submit both the DOT string and the image.

__Problem 3 (Partial AVL Implementation & AI Reflection):__
([LO_C4](#LO_C04)/[LO_AI04](#LO_AI04)): Students will be asked to implement a different AVL rotation (e.g., double rotation) or a full insertion function (if single rotations were covered in class). They must submit:
Their working code.
A brief report detailing how they used an AI tool to review/refine their code, including the prompt(s) used, a summary of AI feedback, and which suggestions they incorporated (and why).


<br><br>


## 4. Lecture Reflection

### Discussion

- What was the most challenging aspect of getting the AI to generate a useful checklist for tree properties in Activity 1? Did anyone's AI miss a crucial property initially?
- For Activity 2, how intuitive did you find using AI to generate and modify DOT visualizations? Were there any surprising or unexpected behaviors from the AI when you asked it to modify the tree structure?
- In Activity 3, when validating AVL trees, were there instances where your manual assessment differed from the AI's? How did the AI dialogue help clarify the height-balance property or balance factor calculation?
- Regarding Activity 4, what kind of suggestions did the AI provide for your rotation code? Were they focused on correctness, efficiency, style, or something else? How effective was this feedback?
- Did anyone develop a particularly effective prompt for any of today's AI interactions that they'd like to share?


### Critical Thinking

- Beyond what we did today, what other ways can you imagine AI tools supporting your learning of complex data structures and algorithms? 
- What are you curious to try?
- What do you see as the potential pitfalls or limitations of relying on AI for understanding or implementing things like AVL trees? 
- Where should we be cautious?
- Could AI help in designing new data structures or optimizing existing algorithms? What would be needed for that?
- How can we ensure we are still developing deep understanding and not just 'outsourcing thinking' to AI when learning these topics?


<br><br>



## 5. Miscellaneous



- Prompt Pattern Catalog: https://arxiv.org/abs/2302.11382
- Prompt Engineering Techniques slides (own material)

- GraphViz online: https://dreampuf.github.io/GraphvizOnline

