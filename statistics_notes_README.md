# 📊 Statistics --- Ongoing Notes

> **A clean, practical reference based on the Statistics notes covered
> in class.**
>
> This README organizes the concepts into direct definitions, meanings,
> examples, and quick comparisons for revision and Data Analysis
> practice.

------------------------------------------------------------------------

## 📌 Table of Contents

1.  [What is Statistics?](#-what-is-statistics)
2.  [What is Data?](#-what-is-data)
3.  [Applications of Statistics](#-applications-of-statistics)
4.  [Types of Statistics](#-types-of-statistics)
5.  [Population and Sample](#-population-and-sample)
6.  [Sampling Techniques](#-sampling-techniques)
7.  [Types of Data](#-types-of-data)
8.  [Scales of Measurement](#-scales-of-measurement)
9.  [Quick Comparison](#-quick-comparison)
10. [Key Terms to Remember](#-key-terms-to-remember)

------------------------------------------------------------------------

# 📖 What is Statistics?

### Definition

**Statistics is the science of collecting, organizing, and analyzing
data to support decision-making.**

In simple words:

> Statistics helps us turn **raw data → useful information → insights →
> decisions**.

### Main stages

``` text
Collect Data
     ↓
Organize Data
     ↓
Analyze Data
     ↓
Interpret Results
     ↓
Make Decisions
```

### Example

Suppose we collect the heights of students in a class:

``` text
175 cm, 180 cm, 140 cm, 135 cm, 160 cm, 120 cm, 88cm, ...
```

Statistics can help us find:

-   Average height
-   Minimum and maximum height
-   Spread of heights
-   Distribution of heights
-   Whether the sample represents a larger population

------------------------------------------------------------------------

# 📦 What is Data?

### Definition

**Data is a collection of facts or pieces of information that can be
measured, collected, and analyzed.**

### Examples

#### Student weight

``` text
60 kg, 50 kg, 45 kg, 30 kg, ...
```

#### Student IQ

``` text
100, 90, 95, 99, ...
```

### Example: House Price Dataset

  City          Area   No. of Rooms      Price
  ----------- ------ -------------- ----------
  Bangalore     1000              2   45 Lakhs
  New York      1270            2.5   50 Lakhs
  Mumbai          \-             \-         \-

This dataset can be analyzed to understand relationships between:

``` text
Area + Number of Rooms
          ↓
        Price
```

A **Data Analyst** can use the data to produce reports and
visualizations that help with management decisions.

A **Data Scientist** may use the data to build a model that predicts
something such as house price.

------------------------------------------------------------------------

# 🎯 Applications of Statistics

Statistics is useful in many areas:

### 1. Data Exploration and Summarization

Understanding what the collected data looks like.

Examples:

-   Mean
-   Median
-   Mode
-   Variance
-   Standard deviation
-   Charts and graphs

### 2. Model Building and Validation

Statistics can be used when building and evaluating models.

### 3. Statistical Analysis

Using a **sample** to learn about a **population**.

### 4. Hypothesis Testing

Testing whether there is enough evidence to support a claim about a
population.

### 5. Optimization and Efficiency

Using data to improve processes and make better decisions.

### 6. Reporting

Presenting findings in a way that others can understand and use.

------------------------------------------------------------------------

# 📊 Types of Statistics

There are two major types:

``` text
                 Statistics
                     │
          ┌──────────┴──────────┐
          ↓                     ↓
   Descriptive              Inferential
   Statistics               Statistics
```

------------------------------------------------------------------------

## 1. Descriptive Statistics

### Direct Definition

**Descriptive statistics involves methods for summarizing and organizing
data to make it understandable.**

It describes the basic features of the data we have.

### Main areas

#### A. Measures of Central Tendency

Used to describe the center or typical value of data.

-   **Mean**
-   **Median**
-   **Mode**

#### B. Measures of Dispersion

Used to understand how spread out the data is.

-   **Range**
-   **Variance**
-   **Standard deviation**

#### C. Data Distribution

Common ways to visualize or understand distributions:

-   Histogram
-   Box plot
-   Pie chart
-   PDF
-   PMF


#### D. Summary Statistics

A **five-number summary** commonly includes:

``` text
Minimum
Q1
Median (Q2)
Q3
Maximum
```

### Example

Suppose the heights of six students are:

``` text
175, 180, 140, 135, 160, 120
```

A descriptive question is:

> **"What is the average height of the students in this classroom?"**

You are describing the data you already collected.

------------------------------------------------------------------------

# 🔍 Inferential Statistics

### Direct Definition

**Inferential statistics uses sample data to make predictions,
estimates, or conclusions about a larger population.**

The basic idea is:

``` text
Sample
  ↓
Analysis
  ↓
Inference / Conclusion
  ↓
Population
```

### Common topics

-   Hypothesis testing
-   P-value
-   Confidence interval
-   Statistical analysis tests
    -   Z-test
    -   t-test
    -   ANOVA / F-test
    -   Chi-square test

### Example

Suppose a college has thousands of students.

You collect the heights of only 100 students.

You ask:

> **"Are the heights of these 100 students representative of what we
> would expect for the entire college?"**

This is an **inferential** question because you are using a sample to
draw a conclusion about a larger population.

------------------------------------------------------------------------

# 🧠 Descriptive vs Inferential Statistics

  -----------------------------------------------------------------------
  Descriptive                         Inferential
  ----------------------------------- -----------------------------------
  Describes collected data            Draws conclusions beyond the
                                      collected sample

  Summarizes data                     Makes estimates/inferences

  Mean, median, mode                  Hypothesis testing

  Variance, standard deviation        P-value

  Histogram, box plot                 Confidence interval

  Five-number summary                 Z-test, t-test, ANOVA, Chi-square
  -----------------------------------------------------------------------

### Easy memory trick

> **Descriptive = Describe what you have.**

> **Inferential = Infer something about a larger population.**

------------------------------------------------------------------------

# 👥 Population and Sample

This is one of the most important concepts in statistics.

``` text
              POPULATION
        ┌─────────────────────┐
        │                     │
        │    ┌───────────┐    │
        │    │   SAMPLE  │    │
        │    │           │    │
        │    └───────────┘    │
        │                     │
        └─────────────────────┘
```

------------------------------------------------------------------------

## Population

### Definition

**A population is the entire set of individuals or objects of interest
in a particular study.**

It contains all members of the defined group we want to study or collect
information about.

### Examples

#### School study

Population:

> All students enrolled in the school.

#### Market research

Population:

> All consumers in a city.

Purpose:

> Understand the purchasing behavior of all consumers.

#### Medical study

Population:

> All patients with a specific disease.

Purpose:

> Study the effectiveness of a drug.

------------------------------------------------------------------------

## Sample

### Definition

**A sample is a subset of the population selected to represent the
entire group.**

Instead of studying everyone, we study a smaller group.

### Examples

#### School study

Population:

``` text
All students in the school
```

Sample:

``` text
50 randomly selected students
```

Purpose:

> Estimate the average height of students in the school.

#### Market research

Population:

``` text
All consumers in a city
```

Sample:

``` text
500 consumers from the city
```

Purpose:

> Study consumer behavior and infer something about the population.

#### Medical study

Population:

``` text
All patients with a specific disease
```

Sample:

``` text
200 selected patients
```

Purpose:

> Test the effectiveness of the drug.

------------------------------------------------------------------------

# 🔑 Parameter vs Statistic

These terms are connected to population and sample.

## Parameter

A **parameter** is a numerical value that summarizes a population.

Examples:

-   Population mean: **μ**
-   Population variance: **σ²**

``` text
Population → Parameter
```

## Statistic

A **statistic** is a numerical value that summarizes a sample.

Examples:

-   Sample mean
-   Sample variance

``` text
Sample → Statistic
```

### Easy memory trick

> **Parameter → Population**

> **Statistic → Sample**

------------------------------------------------------------------------

# 🎲 Sampling Techniques

Sampling means selecting a sample from a population.

There are two major categories:

``` text
Sampling
   │
   ├── Probability Sampling
   │
   └── Non-Probability Sampling
```

------------------------------------------------------------------------

# 1️⃣ Probability Sampling

In probability sampling, members of the population are selected using a
random/probability-based process.

The notes cover five techniques:

1.  Simple Random Sampling
2.  Systematic Sampling
3.  Stratified Sampling
4.  Cluster Sampling
5.  Multi-Stage Sampling

------------------------------------------------------------------------

## A. Simple Random Sampling

### Definition

**Every member of the population has an equal chance of being
selected.**

### Example

Suppose you have a list of 1,000 students.

You randomly select 100 names.

``` text
1000 students
     ↓
Random selection
     ↓
100 students
```

Another example:

> Randomly drawing names from a class list.

### Key idea

**Random + equal chance**

------------------------------------------------------------------------

## B. Systematic Sampling

### Definition

**Select every nth member of the population after choosing a random
starting point.**

### Example

Suppose you decide to select every 10th person.

``` text
Random starting point
        ↓
10th → 20th → 30th → 40th → ...
```

Example from a feedback survey:

> Select every 10th customer for the survey.

### Key idea

**Every nth member**

------------------------------------------------------------------------

## C. Stratified Sampling

### Definition

**Divide the population into strata (groups) based on a specific
characteristic, then randomly sample from each stratum.**

### Example

Suppose employees are divided by department:

``` text
Employees
   │
   ├── HR
   ├── Finance
   ├── IT
   └── Marketing
```

Then randomly select an appropriate number of employees from each
department.

Another example is dividing people by age:

``` text
< 12
12–18
> 18
```

and sampling from each group.

### Key idea

**Divide into groups → randomly sample from every group**

------------------------------------------------------------------------

## D. Cluster Sampling

### Definition

**Divide the population into clusters, randomly select some clusters,
and then sample all members from the selected clusters.**

### Example

Suppose you want to survey teachers in a district.

Instead of selecting individual teachers from every school:

``` text
District
   ↓
Schools = clusters
   ↓
Randomly select several schools
   ↓
Survey all teachers in those selected schools
```

### Key idea

**Select whole groups/clusters**

------------------------------------------------------------------------

## E. Multi-Stage Sampling

### Definition

**Multi-stage sampling combines multiple sampling methods in stages,
usually selecting clusters first and then randomly sampling within those
clusters.**

### Example

To survey households in a city:

``` text
City
 ↓
Randomly select areas
 ↓
Randomly select neighborhoods
 ↓
Randomly select households
 ↓
Survey selected households
```

### Key idea

**Sampling happens in multiple stages.**

------------------------------------------------------------------------

# 2️⃣ Non-Probability Sampling

### Definition

**Non-probability sampling selects individuals without giving every
member a known or equal probability of selection.**

The notes cover:

1.  Convenience Sampling
2.  Judgmental / Purposive Sampling
3.  Snowball Sampling
4.  Quota Sampling

------------------------------------------------------------------------

## A. Convenience Sampling

### Definition

**Selecting individuals who are easiest to reach.**

### Example

> Surveying people at a shopping mall because they are easily
> accessible.

### Key idea

**Easy to reach**

------------------------------------------------------------------------

## B. Judgmental / Purposive Sampling

### Definition

**Selecting individuals based on the researcher's judgment or specific
purpose.**

### Example

If a study needs expert opinions:

> Select experienced experts in the field to participate.

### Key idea

**Researcher chooses based on purpose/judgment**

------------------------------------------------------------------------

## C. Snowball Sampling

### Definition

**Existing study participants recruit or identify additional
participants from among their acquaintances.**

### Example

Suppose researchers are studying people with a rare disease.

``` text
Participant A
      ↓
recruits B and C
      ↓
B recruits D
      ↓
C recruits E
```

This creates a "snowball" effect.

### Key idea

**Participants help find more participants.**

------------------------------------------------------------------------

## D. Quota Sampling

### Definition

**Select participants to meet predefined quotas for specific
characteristics.**

Examples of characteristics:

-   Age
-   Gender
-   Group
-   Caste

Example:

Suppose a survey requires:

``` text
50% Group A
30% Group B
20% Group C
```

Participants are selected until those quotas are filled.

### Key idea

**Fill predefined group quotas**

------------------------------------------------------------------------

# 📚 Types of Data

The notes classify data into two major categories:

``` text
                       DATA
                        │
              ┌─────────┴─────────┐
              ↓                   ↓
         Quantitative          Qualitative
          Numerical            Categorical
              │                   │
        ┌─────┴─────┐       ┌─────┴─────┐
        ↓           ↓       ↓           ↓
     Discrete   Continuous Nominal    Ordinal
```

------------------------------------------------------------------------

# 🔢 Quantitative Data

### Definition

**Quantitative data is numerical data representing quantities that can
be measured or counted.**

Examples:

-   Weight
-   Height
-   Temperature
-   Speed
-   Number of bank accounts
-   Number of children

Quantitative data has two major types:

-   Discrete
-   Continuous

------------------------------------------------------------------------

## A. Discrete Data

### Definition

**Discrete data consists of countable values, typically whole numbers.**

Think:

> **Counting**

### Examples

Number of:

-   Bank accounts
-   Children in a family
-   Students in a class
-   Cars owned by a household

Example:

``` text
0, 1, 2, 3, 4, ...
```

You generally cannot have:

``` text
2.5 children
```

### Key idea

**Discrete = Count**

------------------------------------------------------------------------

## B. Continuous Data

### Definition

**Continuous data can take any value within a range and is obtained
through measurement.**

Think:

> **Measuring**

### Examples

-   Weight
-   Height
-   Temperature
-   Speed

Example:

``` text
60.1 kg
60.15 kg
60.153 kg
...
```

### Key idea

**Continuous = Measure**

------------------------------------------------------------------------

# 🏷️ Qualitative Data

### Definition

**Qualitative data is categorical data that describes qualities, labels,
or groups rather than numerical quantities.**

Examples:

-   Gender
-   Blood group
-   PIN code
-   Customer feedback category

Qualitative data in these notes is divided into:

-   Nominal
-   Ordinal

------------------------------------------------------------------------

# 1️⃣ Nominal Data

### Definition

**Nominal data classifies observations into distinct categories that
have no inherent or meaningful order.**

### Characteristics

-   Categories are labels or names.
-   Categories do not have a meaningful rank.
-   There is no logical ordering between categories.

### Examples

#### Gender

``` text
Male
Female
```

#### Blood group

``` text
A
B
AB
O
```

#### PIN code

A PIN code may contain numbers, but those numbers act as **labels**, not
quantities.

### Important

A value looking like a number does **not** automatically make it
quantitative.

For example:

``` text
PIN code: 110001
```

You do not calculate an average PIN code.

It is a label.

### Another example

Favorite color:

``` text
Red
Blue
Pink
```

There is no natural:

``` text
Red < Blue < Pink
```

### Key idea

**Nominal = Name / Label / No Rank**

------------------------------------------------------------------------

# 2️⃣ Ordinal Data

### Definition

**Ordinal data classifies observations into categories that can be
ranked or ordered, but the differences between ranks are not necessarily
equal.**

### Characteristics

-   Categories have an order.
-   Ranking is meaningful.
-   The difference between ranks is not necessarily equal or measurable.

### Example: Customer Feedback

``` text
Not Satisfied
Very Satisfied
```

Or:

``` text
Bad
Good
Better
```

The categories can be ordered, but the difference between them is not a
fixed numerical amount.

### Example: Education Level

``` text
High School
Bachelor
Master
Doctorate
```

There is an order:

``` text
High School → Bachelor → Master → Doctorate
```

But the "distance" between these categories is not necessarily equal.

### Key idea

**Ordinal = Order / Rank**

------------------------------------------------------------------------

# 📏 Scales of Measurement

### Definition

**Scales of measurement describe the nature of information contained in
the values assigned to variables.**

There are four primary scales:

``` text
1. Nominal
2. Ordinal
3. Interval
4. Ratio
```

A useful way to remember them is:

``` text
Nominal → labels
Ordinal → order
Interval → equal intervals
Ratio → equal intervals + true zero
```

------------------------------------------------------------------------

# 1️⃣ Nominal Scale

### Definition

**Nominal scale classifies data into distinct categories that do not
have an intrinsic order.**

### Characteristics

-   Data is categorized using labels, names, or qualities.
-   Categories are mutually distinct.
-   There is no logical rank among categories.

### Examples

-   Gender
-   Blood group
-   Colors
-   Cuisine type

Example:

``` text
Color:
Red
Blue
Pink
```

There is no meaningful ranking.

### Memory

> **Nominal = Name**

------------------------------------------------------------------------

# 2️⃣ Ordinal Scale

### Definition

**Ordinal scale classifies data into categories that can be ranked or
ordered.**

### Characteristics

-   Data is categorized and ranked.
-   The intervals between ranks are not necessarily equal.

### Examples

#### Education

``` text
High School → Bachelor → Master → Doctorate
```

#### Customer satisfaction

``` text
Not Satisfied
      ↓
Satisfied
      ↓
Very Satisfied
```

### Memory

> **Ordinal = Order**

------------------------------------------------------------------------

# 3️⃣ Interval Scale

### Definition

**Interval scale has ordered values with equal differences between
values, but it does not have a true zero point.**

### Characteristics

1.  Values are ordered.
2.  Differences between values are meaningful and consistent.
3.  There is no true zero point.
4.  Ratios are not meaningful.

### Example: Temperature in Fahrenheit

``` text
10°F
20°F
30°F
```

The difference is:

``` text
20 - 10 = 10
30 - 20 = 10
```

The intervals are equal.

But:

``` text
0°F
```

does not mean "no temperature."

Therefore, saying:

> 40°F is twice as hot as 20°F

is not a meaningful ratio interpretation.

### Another example: Calendar years

``` text
2016
2020
2024
```

The difference between years is meaningful:

``` text
2020 - 2016 = 4 years
2024 - 2020 = 4 years
```

But there is no meaningful "year 0" representing the absence of time.

### Memory

> **Interval = Equal intervals, but no true zero**

------------------------------------------------------------------------

# 4️⃣ Ratio Scale

### Definition

**Ratio scale has ordered values, equal intervals, and a true zero
point, which allows meaningful ratio comparisons.**

### Characteristics

-   Order matters.
-   Differences are meaningful.
-   There is a true zero.
-   Ratios are meaningful.

### Examples

#### Weight

``` text
10 kg
20 kg
40 kg
```

There is a true zero:

``` text
0 kg = no weight
```

And ratio comparisons are meaningful:

``` text
40 kg is 2 times 20 kg.
```

#### Income

``` text
₹10,000
₹20,000
₹30,000
₹40,000
```

A meaningful ratio can be calculated:

``` text
₹40,000 / ₹20,000 = 2
```

So ₹40,000 is twice ₹20,000.

### Memory

> **Ratio = Equal intervals + True zero + meaningful ratios**

------------------------------------------------------------------------

# 🧠 The Four Scales --- One Table

  ----------------------------------------------------------------------------
  Scale          Categories   Order       Equal       True Zero   Meaningful
                                          Intervals               Ratio
  -------------- ------------ ----------- ----------- ----------- ------------
  **Nominal**    ✅           ❌          ❌          ❌          ❌

  **Ordinal**    ✅           ✅          ❌          ❌          ❌

  **Interval**   ❌\*         ✅          ✅          ❌          ❌

  **Ratio**      ❌\*         ✅          ✅          ✅          ✅
  ----------------------------------------------------------------------------

\* Interval and ratio variables are numerical measurement scales rather
than merely categorical scales.

### The progression

``` text
Nominal
   ↓
+ Order
   ↓
Ordinal
   ↓
+ Equal intervals
   ↓
Interval
   ↓
+ True zero
   ↓
Ratio
```

------------------------------------------------------------------------

# 🔥 Quick Decision Guide

When you encounter a variable, ask these questions:

### Question 1

**Is it just a label/name?**

``` text
Yes → Nominal
```

Example:

``` text
Blood group = A, B, AB, O
```

------------------------------------------------------------------------

### Question 2

**Can the categories be ranked?**

``` text
Yes → Ordinal
```

Example:

``` text
Poor → Average → Good → Excellent
```

------------------------------------------------------------------------

### Question 3

**Are the differences between values equal?**

``` text
Yes → Interval or Ratio
```

------------------------------------------------------------------------

### Question 4

**Does zero mean a complete absence of the quantity?**

``` text
Yes → Ratio
No  → Interval
```

------------------------------------------------------------------------

# ⚡ Super-Fast Examples

  -----------------------------------------------------------------------
  Variable                Type / Scale            Why?
  ----------------------- ----------------------- -----------------------
  Blood group             Nominal                 Labels, no order

  Gender                  Nominal                 Categories, no order

  PIN code                Nominal                 Numbers used as labels

  Customer satisfaction   Ordinal                 Categories can be
                                                  ranked

  Education level         Ordinal                 Levels have an order

  Temperature °F          Interval                Equal differences, no
                                                  true zero

  Calendar year           Interval                Equal year differences,
                                                  no true zero

  Height                  Ratio                   True zero and
                                                  meaningful ratios

  Weight                  Ratio                   True zero and
                                                  meaningful ratios

  Income                  Ratio                   True zero and
                                                  meaningful ratios

  Number of children      Ratio / discrete        Count with a meaningful
                          quantitative            zero

  Number of bank accounts Ratio / discrete        Countable and zero is
                          quantitative            meaningful
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🎯 Quick Revision: Sampling

  -----------------------------------------------------------------------
  Technique               Core Idea               Example
  ----------------------- ----------------------- -----------------------
  **Simple Random**       Everyone has an equal   Randomly select
                          chance                  students

  **Systematic**          Select every nth member Every 10th customer

  **Stratified**          Sample from every       Sample from each
                          subgroup                department

  **Cluster**             Select whole            Select schools, survey
                          groups/clusters         teachers

  **Multi-Stage**         Sampling in multiple    City → area → household
                          stages                  

  **Convenience**         Choose easiest people   People at a mall
                          to reach                

  **Judgmental**          Researcher chooses      Select experts
                          based on purpose        

  **Snowball**            Participants recruit    Rare-disease study
                          others                  

  **Quota**               Fill predefined group   50% A, 30% B, 20% C
                          quotas                  
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🧩 Key Terms to Remember

### Statistics

Science of collecting, organizing, and analyzing data for
decision-making.

### Data

Facts or pieces of information that can be collected, measured, and
analyzed.

### Population

The entire group of interest.

### Sample

A subset selected from the population.

### Parameter

A numerical summary of a population.

### Statistic

A numerical summary of a sample.

### Descriptive Statistics

Describes and summarizes collected data.

### Inferential Statistics

Uses sample data to make inferences about a population.

### Quantitative Data

Numerical data representing quantities.

### Qualitative Data

Categorical data representing labels or qualities.

### Discrete Data

Countable values.

### Continuous Data

Measurable values that can take values within a range.

### Nominal

Categories with **no order**.

### Ordinal

Categories with **order/rank**.

### Interval

Equal intervals but **no true zero**.

### Ratio

Equal intervals + **true zero** + meaningful ratios.

------------------------------------------------------------------------

# 🧠 One-Page Mental Map

``` text
                         STATISTICS
                              │
             Collect → Organize → Analyze → Decide
                              │
                ┌─────────────┴─────────────┐
                ↓                           ↓
          DESCRIPTIVE                  INFERENTIAL
          "Describe data"              "Infer about population"
                │                           │
       Mean / Median / Mode          Hypothesis Testing
       Variance / SD                 P-value
       Histogram / Box Plot          Confidence Interval
       Five-number summary           Z / t / F / Chi-square
                │
                ↓
             DATA
                │
        ┌───────┴────────┐
        ↓                ↓
 Quantitative        Qualitative
 Numerical           Categorical
        │                │
   ┌────┴────┐      ┌────┴────┐
   ↓         ↓      ↓         ↓
Discrete Continuous Nominal Ordinal
   │         │      │         │
 Count     Measure  No Rank   Has Rank


              SCALES OF MEASUREMENT
                       │
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
     Nominal        Ordinal        Interval
     No order       Has order      Equal gaps
                                      │
                                      ↓
                                    Ratio
                               + true zero
                               + ratios
```

------------------------------------------------------------------------

# 💡 Final Memory Tricks

``` text
STATISTICS
= Data → Information → Decision

DESCRIPTIVE
= Describe what you have

INFERENTIAL
= Infer about a bigger population

POPULATION
= Everyone / Everything of interest

SAMPLE
= Smaller part of the population

PARAMETER
= Population number

STATISTIC
= Sample number

DISCRETE
= Count

CONTINUOUS
= Measure

NOMINAL
= Name

ORDINAL
= Order

INTERVAL
= Equal intervals, NO true zero

RATIO
= Equal intervals + TRUE zero
```

------------------------------------------------------------------------

## 📌 Course Scope Covered in These Notes

This README covers the topics present in the provided class notes:

-   Statistics and Data
-   Applications of Statistics
-   Descriptive Statistics
-   Inferential Statistics
-   Population and Sample
-   Parameter and Statistic
-   Probability Sampling
    -   Simple Random Sampling
    -   Systematic Sampling
    -   Stratified Sampling
    -   Cluster Sampling
    -   Multi-Stage Sampling
-   Non-Probability Sampling
    -   Convenience Sampling
    -   Judgmental / Purposive Sampling
    -   Snowball Sampling
    -   Quota Sampling
-   Types of Data
    -   Quantitative
    -   Qualitative
    -   Discrete
    -   Continuous
    -   Nominal
    -   Ordinal
-   Scales of Measurement
    -   Nominal
    -   Ordinal
    -   Interval
    -   Ratio
