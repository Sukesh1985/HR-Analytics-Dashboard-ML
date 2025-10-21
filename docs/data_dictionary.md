# Data Dictionary

## HR Analytics Dataset Schema

### Employee Demographics

| Column Name | Data Type | Description | Example Values |
|------------|-----------|-------------|----------------|
| Age | Integer | Employee age in years | 18-60 |
| Gender | Text | Employee gender | Male, Female |
| MaritalStatus | Text | Marital status | Single, Married, Divorced |
| Education | Integer | Education level (1-5) | 1=Below College, 5=Doctor |
| EducationField | Text | Field of education | Life Sciences, Medical, Marketing |

### Job Information

| Column Name | Data Type | Description | Example Values |
|------------|-----------|-------------|----------------|
| Department | Text | Department name | Sales, R&D, HR |
| JobRole | Text | Specific job role | Sales Executive, Research Scientist |
| JobLevel | Integer | Job level hierarchy (1-5) | 1-5 |
| BusinessTravel | Text | Travel frequency | Non-Travel, Travel_Rarely, Travel_Frequently |

### Compensation

| Column Name | Data Type | Description | Example Values |
|------------|-----------|-------------|----------------|
| MonthlyIncome | Decimal | Monthly salary | 1,000-20,000 |
| HourlyRate | Integer | Hourly wage rate | 30-100 |
| DailyRate | Integer | Daily wage rate | 100-1,500 |
| MonthlyRate | Integer | Monthly rate | 2,000-27,000 |
| PercentSalaryHike | Integer | Last salary increase % | 11-25 |
| StockOptionLevel | Integer | Stock options tier (0-3) | 0-3 |

### Performance & Satisfaction

| Column Name | Data Type | Description | Example Values |
|------------|-----------|-------------|----------------|
| PerformanceRating | Integer | Annual performance rating | 3, 4 |
| JobSatisfaction | Integer | Job satisfaction score (1-4) | 1=Low, 4=Very High |
| EnvironmentSatisfaction | Integer | Workplace environment score (1-4) | 1=Low, 4=Very High |
| WorkLifeBalance | Integer | Work-life balance score (1-4) | 1=Bad, 4=Best |
| RelationshipSatisfaction | Integer | Relationship satisfaction (1-4) | 1=Low, 4=Very High |

### Tenure & Development

| Column Name | Data Type | Description | Example Values |
|------------|-----------|-------------|----------------|
| YearsAtCompany | Integer | Total years at company | 0-40 |
| YearsInCurrentRole | Integer | Years in current position | 0-18 |
| YearsSinceLastPromotion | Integer | Years since last promotion | 0-15 |
| YearsWithCurrManager | Integer | Years with current manager | 0-17 |
| TotalWorkingYears | Integer | Total work experience | 0-40 |
| TrainingTimesLastYear | Integer | Training sessions in last year | 0-6 |
| NumCompaniesWorked | Integer | Number of previous employers | 0-9 |

### Attrition & Risk

| Column Name | Data Type | Description | Example Values |
|------------|-----------|-------------|----------------|
| Attrition | Text | Employee left company | Yes, No |
| OverTime | Text | Works overtime regularly | Yes, No |
| DistanceFromHome | Integer | Distance from home (km) | 1-29 |
| Attrition_Risk_Score | Decimal | ML-calculated risk score | 0.0-1.0 |
| Predicted_Attrition | Text | ML prediction | Yes, No |

---

**Total Columns**: 31  
**Total Records**: 3,000 employees  
**Target Variable**: Attrition (Yes/No)
