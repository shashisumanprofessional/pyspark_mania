# pyspark_mania


### 🚀 **PySpark Detailed Syllabus (Batch + Streaming Focused)**

---

## 📌 **SECTION 1: PySpark Core Basics (Foundation – Must Know)**

🎯 **Goal:** Understand Spark execution model and core APIs

---

### 🔹 **1. Spark Architecture & Execution Model**

• What is **Apache Spark**? ⚡
• **Spark vs Hadoop MapReduce** ⚔️
• **Driver, Executors, Cluster Manager** 🧩
• **SparkSession & SparkContext** 🛠️
• **Lazy Evaluation** 💤
• **DAG (Directed Acyclic Graph)** 🔄
• **Job → Stage → Task** 📊
• **Narrow vs Wide Transformations** 🔀

---

### 🔹 **2. RDD (Resilient Distributed Dataset)**

📝 *Even if DataFrame is preferred, RDD knowledge is interview-critical*

• What is **RDD** & why it exists ❓
• Creating RDD (**parallelize, textFile**) 📂
• **RDD Transformations** 🔧
▸ map, flatMap
▸ filter
▸ distinct
▸ union, intersection

• **RDD Actions** ▶️
▸ collect
▸ count
▸ reduce
▸ take
▸ foreach

• **Pair RDDs** 🔑
▸ reduceByKey
▸ groupByKey
▸ mapValues
▸ join, leftOuterJoin

• When **NOT** to use RDD 🚫
• **RDD vs DataFrame vs Dataset** ⚖️

---

### 🔹 **3. DataFrame & Spark SQL (Most Used in Industry)** 🏭

• Creating DataFrames (**CSV, JSON, Parquet, ORC**) 📑 - (Lec_1_dataframe_struc.ipynb)[Lec_1_dataframe_struc.ipynb] 
• **Schema inference vs explicit schema** 🧠
• **Column operations** 🧱
▸ select, withColumn, drop
▸ alias
▸ cast, when, explode, coalesce, date functions

• **Filtering** 🔍
▸ where, filter

• **Aggregations** 📈
▸ groupBy, agg
▸ count, sum, avg, max, min

• **Joins** 🔗
▸ inner, left, right, full
▸ cross join
▸ join conditions

• **Handling Nulls** 🚿
▸ dropna, fillna

• **SQL Queries using Spark SQL** 🧾
• **Temporary views vs Global temp views** 🌍

---

### 🔹 **4. Functions & Expressions** 🧮

• **Built-in functions** ⚙️
• **Date & timestamp functions** ⏰
• **String functions** 🔤
• **Window Functions** 🪟
▸ row_number
▸ rank, dense_rank
▸ lead, lag

• **UDF vs Pandas UDF** 🧪
• Why **UDF is slow & alternatives** 🐢➡️🚀

