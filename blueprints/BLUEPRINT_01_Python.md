
<a href=""><img src="../resources/blueprint.svg" alt="Blueprint Icon" width="100"/></a>

<br><br>

# Pandas Lecture - in Introductory Python Course

<br>

## 1. General Course and Lecture Description


|   |  |
|---------------------------|------------------------------------------------|
| **ACM Category:**         | Software Development Fundamentals (SDF)|
| **Knowledge Unit:**       | SDF-Programming Basics  |
| **Course Overview:**       |The introductory Python for Business Administration course offers students a foundation in core programming concepts, such as variables, control flow, and functions, based on examples from a business context. It emphasizes practical problem-solving skills and data-driven decision-making within a business context. |
| **Course Modalities:**       | Lab 90 min    |
| **Lecture Context:**       | The pandas lecture introduces students to the pandas library’s key data structures (Series and DataFrame) and fundamental operations, such as filtering, grouping, basic aggregation, plotting—enabling them to efficiently manipulate and analyze tabular data relevant to business scenarios.|
| **Keywords/Topics:**       |Python <br> Pandas <br> Data Analytics    |



<br><br>


## 2. Lecture Contents  & Learning Objectives





|    | **Lecture-related LO**    | Level | 
|---------------------------|------------------------------------------------|----|
| <a name="LO_C01"></a>LO_C1  | Students are able to describe the structure and purpose of a pandas DataFrame, explaining its components (index, columns, dtypes) and the role of key operations (loading, cleaning, filtering, grouping, plotting) within a business‐analytics workflow.  | [EXPLAIN]|
| <a name="LO_C02"></a>LO_C2  | Students are able to load tabular data into a DataFrame and perform basic cleaning operations to prepare it for analysis.|[APPLY]|
| <a name="LO_C03"></a>LO_C3  | Students are able to subset and transform their DataFrame by applying conditional filters and selecting columns. |[APPLY]|
| <a name="LO_C04"></a>LO_C4  | Students are able to group and aggregate data and then generate basic plots to communicate key business insights.  | [APPLY]|

<br><br>


|    | **AI-related LO**    |Level   | AI Usage |
|---------------------------|------------------------------------------------|----|---|
| <a name="LO_AI01"></a>LO_AI1  | Students are able to use an AI assistant to explore and explain the structure of a pandas DataFrame—including its index, columns, and dtypes—and to describe the effects of common operations. | [EXPLAIN]|[EXPLAIN]|
| <a name="LO_AI02"></a>LO_AI2  |Students are able to use an AI assistant to generate, execute, and adapt pandas code for concrete data-analysis tasks—such as loading a CSV, cleaning the data, grouping, and visualizing—and integrate those AI-provided code snippets into their own Jupyter notebooks.   |[APPLY] |[GENERATE]|
|<a name="LO_AI03"></a>LO_AI3 |Students are able to critically assess AI-generated pandas workflows by comparing the AI’s proposed approach against a hand-crafted solution—identifying any errors, inefficiencies, or questionable assumptions—and refining the code to ensure correctness. |[EVALUATE]|[EVALUATE] |



<br><br>

## 3. Lecture Activities

### Description

In these activities, students first use an AI assistant to explain pandas DataFrame structures by developing natural‐language prompts and reviewing the AI’s responses. Next, they individually generate, run, and modify AI‐created pandas code and share their adaptations. Finally, in small groups, they compare side‐by‐side AI‐generated and hand‐written solutions, annotate errors or inefficiencies, co‐create a refined “merged” solution, and discuss a best practice for reviewing AI code.


### Activities


| **1-Activity**    |  Data Loading & Cleaning | 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_C2](#LO_C02)) |
| **Description:**   |   Distribute a CSV with missing values, duplicate rows, and mixed types (e.g. dates as strings). The students are tasked to load the data from the CSV and perform basic data cleaning operations. This activity can be performed in pairs. |
| **Resources:**   |  - CSV file with sales data|
| **Assessment:**   |  Each pair shares their Jupyter Notebook (or Collab file) with another pair for review. |


<br><br>




| **2-Activity**    | Filter & Transform | 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_C3](#LO_C03)) |
| **Description:**   |Subset and modify data via conditional filters and column operations. Each pair of students gets a card with a different task to be performed, e.g. "Show me only the rows where revenue > 1000.”, “Create a new column profit = revenue – cost.”|
| **Resources:**   |  CSV file with sales data, cards with tasks|
| **Assessment:**   |Each pair shares their Jupyter Notebook (or Colab file) with another pair for review. |

<br><br>


| **3-Activity**    |  Group-Aggregate-Visualize | 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_C4](#LO_C04)) |
| **Description:**   | Aggregate by category and create a business-focused plot. The students get a business question, e.g. “Which product category generated the highest average monthly sales?” In pairs they develop the Python code and create a plot suitable for the business question.  |
| **Resources:**   | CSV file with sales data, set of business-relevant questions |
| **Assessment:**   |  Each pair prepares a one-minute insight pitch and presents it to the other teams. |

<br><br>

| **4-Activity**    |AI-based Explanation of Pandas Concepts| 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_AI1](#LO_AI01)) |
| **Description:**   | Use an AI assistant to explore DataFrame structure and operation semantics. Individually, students write a natural-language prompt such as P1. In pairs, they submit their prompt to ChatGPT (or Github Copilot) and read the explanation.  |
| **Resources:**   |  - Sample Prompt: <br> `“You are a pandas expert and instructor, known for clear and concise explanations of DataFrame internals and operations. Explain what df.dtypes tells me about my DataFrame, and how I might change a column’s dtype.”` [EXPLAIN] [Persona Pattern]  |
| **Assessment:**   | Each pair quickly presents something they learned that was new or well explained and something they found confusing, wrong, or incomplete. |


<br><br>

| **5-Activity**    |AI-based Code Generation| 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_AI2](#LO_AI02)) |
| **Description:**   |Use AI to generate, execute, and adapt pandas snippets for concrete tasks. Students get a CSV file and individually prompt the AI—e.g. P2. They paste the AI’s suggestion in their Jupyter notebook, run it, then manually modify one parameter (e.g. change the plot to a horizontal bar, add labels) to fit a new requirement.   |
| **Resources:**   |  - Sample Prompt: <br> `“Write pandas code to load a CSV, drop duplicate rows, group sales by region, and plot them. I am going to provide a code template. Everything in ALL_CAPS is a placeholder. Please preserve the structure exactly. ”` [GENERATE] [Template Pattern] <br> - CSV file with sales data  |
| **Assessment:**   | Volunteers briefly show their adapted snippet.|

<br><br>

| **6-Activity**    |Review of AI-generated Code| 
|---------------------------|------------------------------------------------|
| **Constr. Alignment:**  |([LO_AI3](#LO_AI03)) |
| **Description:**   |Provide groups of students with two notebook cells side-by-side: one hand-written, one AI-generated, solving the same task. Groups annotate both versions—highlighting logical errors, inefficiencies, or wrong assumptions. They collaboratively write a “merged” solution that corrects the AI version.    |
| **Resources:**   |  Jupyter notebooks |
| **Assessment:**   | Each group states one best practice for reviewing AI code.|

<br><br>



### Assignment/Homework/Additional Activities


A take-home notebook in which students must:
 - Use an AI assistant to generate pandas code for a specified task. ([LO_AI2](#LO_AI02))
 - Integrate and run that code.
 - Critically reflect the generated code. ([LO_AI3](#LO_AI03))
 - Make at least two nontrivial manual adaptations and comment why. ([LO_AI3](#LO_AI03))


<br><br>


## 4. Lecture Reflection

### Discussion

- In what scenarios did the AI help you most?
- Where did you need to intervene or correct its suggestions?
- How will you integrate AI support in your future analyses?
- Can AI tools fully replace manual coding?


### Critical Thinking

- In which situations would I trust AI-generated code without a manual review?
- How might unnoticed AI-introduced errors impact real business decisions?
- Could using AI in data analysis introduce bias or privacy risks? How would I detect them?



<br><br>



## 5. Miscellaneous



- Prompt Pattern Catalog: https://arxiv.org/abs/2302.11382
- Pandas documentation: https://pandas.pydata.org/docs/

- Literature:
   * https://doi.org/10.1109/FIE61694.2024.10893561
