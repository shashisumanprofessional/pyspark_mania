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

• Creating DataFrames (**CSV, JSON, Parquet, ORC**) [Lec 1: DataFrame Structure](Lec_1_dataframe_struc.ipynb)

• **Schema inference vs explicit schema** 🧠 

• **Column operations** 🧱   [**Column operations**](column_operation(2).ipynb)
▸ select, withColumn, drop
▸ alias
▸ cast, when, explode, coalesce, date functions

• **Filtering** 🔍   [**Filtering**](join_handle_null.ipynb)
▸ where, filter

• **Aggregations** 📈        [**Aggregations**](aggregation.ipynb)
▸ groupBy, agg
▸ count, sum, avg, max, min

• **Joins** 🔗              [Joins](join_handle_null.ipynb)
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



---

---

---

---






### 📦 **SECTION 2: Batch Processing (Core Data Engineering Skill)**

🧠 *This is where **90% of real-world Spark jobs** lie*

---

### 🔹 **1. File Formats & Storage**

• **CSV vs JSON vs Parquet vs ORC** 📂
• Why **Parquet is preferred** ⭐
• **Columnar storage** concepts 🧱
• **Compression types** 🗜️
• **Schema evolution** 🔄
• **Partitioned data**
▸ date-based 📅
▸ region-based 🌍

---

### 🔹 **2. Reading & Writing Large Data**

• **Read / Write options** ⚙️
• **Write modes**
▸ append
▸ overwrite
▸ ignore

• **partitionBy** while writing 🧩
• **Bucketing** (concept + usage) 🪣
• **Handling corrupt records** 🚨
• **Handling late-arriving data** ⏳

---

### 🔹 **3. Batch ETL Design Patterns**

• **Ingestion → Transformation → Load** 🔄
• **Full load vs Incremental load** ⚖️
• **Delta load concepts** 📥
• **Deduplication logic** 🧹
• **SCD (Slowly Changing Dimensions)**
▸ Type 1
▸ Type 2
*(conceptual + Spark approach)*

• **Reprocessing strategy** ♻️
• **Idempotent jobs** ✅

---

### 🔹 **4. Batch Scheduling & Orchestration**

• Running Spark jobs via
▸ **spark-submit** ▶️

• **Parameterized jobs** 🎛️
• Integration with orchestration tools
▸ **Airflow** (conceptual) 🌬️
▸ **Azure Data Factory / Oozie** (conceptual) ☁️

• **Logging & monitoring** 📊
• **Handling job failures & retries** 🔁



