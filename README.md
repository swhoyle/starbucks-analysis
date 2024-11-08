# Mini Project DSE 200: Starbucks Customer Data Analysis

## Dataset Source
Dataset available on [Kaggle: Starbucks Customer Data](https://www.kaggle.com/datasets/ihormuliar/starbucks-customer-data)

## Business Context
Starbucks regularly sends out promotional offers to their customers through various channels (email, mobile, web, social media). These offers can be drink advertisements, discounts, or buy-one-get-one-free (BOGO) deals. Not all customers receive the same offer, and not all offers are equally effective. Understanding offer effectiveness and customer behavior can significantly impact business success.

## Project Objective
Analyze the Starbucks promotional offers dataset to derive actionable insights about customer behavior and offer effectiveness. Some potential areas to explore (but not limited to):

### Possible Analysis Directions
1. Offer Performance Analysis
   - Which types of offers are most successful?
   - How does offer success vary across different customer segments?
   - What is the optimal duration for different types of offers?

2. Customer Segmentation
   - Can we identify distinct customer groups based on their response to offers?
   - How do demographics influence offer effectiveness?
   - Which customer segments are most valuable to target?

3. Channel Effectiveness
   - Which communication channels are most effective for different customer segments?
   - Does multi-channel marketing improve offer success?

4. Customer Behavior Patterns
   - What is the typical customer journey from receiving to completing an offer?
   - Are there patterns in transaction behavior with and without offers?
   - How does membership tenure relate to offer response?

## Technical Requirements
Your analysis should include:
1. Data Cleaning & Preprocessing
   - Handle missing values
   - Convert data types appropriately
   - Create relevant features for analysis

2. Exploratory Data Analysis
   - Visualize key patterns and relationships
   - Identify significant trends
   - Support findings with statistical analysis

3. Advanced Analytics (choose at least one)
   - Customer Segmentation (e.g., clustering)
   - Offer Success Prediction
   - Customer Response Modeling
   - Promotional Impact Analysis

4. Business Recommendations
   - Clear, actionable insights
   - Data-driven recommendations
   - Potential impact assessment

## Deliverables
1. 5-minute presentation covering:
   - Key insights discovered
   - Methodology used
   - Business recommendations
   - Potential impact

2. Code submission including:
   - Well-documented notebooks
   - Clear explanation of analysis steps
   - Visualizations and results

## Evaluation Criteria
- Quality of analysis and insights
- Technical implementation
- Clarity of presentation
- Business value of recommendations
- Creativity in approach

Remember: While these directions provide structure, feel free to explore additional aspects of the data that you find interesting or valuable. The goal is to demonstrate both technical skills and business acumen in analyzing real-world marketing data.

## Dataset Structure
The dataset consists of three main files:

### 1. portfolio.csv
Contains offer details with columns:
- `id`: Unique offer ID
- `reward`: Points given for offer completion
- `channels`: Marketing channels used (web, email, mobile, social)
- `difficulty`: Minimum spend required
- `duration`: Time period for offer
- `offer_type`: Type of offer (BOGO, discount, informational)

### 2. profile.csv 
Customer demographic data with columns:
- `id`: Customer ID
- `gender`: Customer gender (M, F, O)
- `age`: Customer age (18-118)
- `became_member_on`: Account creation date
- `income`: Annual income (30k-120k)

### 3. transcript.csv
Transaction and offer interaction data with columns:
- `id`: Record ID
- `person`: Customer ID
- `event`: Type of record (transaction, offer received, offer viewed, etc.)
- `value`: Either offer ID or transaction amount
- `time`: Hours since start of data collection

## Project Goals
Create an analysis of the Starbucks customer data that includes:
1. Exploratory Data Analysis (EDA)
2. Data Preprocessing
3. Machine Learning
4. Analysis & Visualization
5. Business Insights

## Deliverables
1. 5-minute presentation of findings
2. Code submission for grading
   
## Project Requirements
Students should:
1. Fork the repository
2. Perform comprehensive data analysis
3. Present insights in a clear, concise manner
4. Submit code for evaluation

The project emphasizes practical application of data science techniques to gain meaningful business insights from real-world customer data.