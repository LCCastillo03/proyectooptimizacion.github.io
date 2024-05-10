## Machine Learning

https://lccastillo03.github.io/proyectooptimizacion.github.io/#home


## Learn About the Dataset Selection

The rationale behind choosing this dataset lies in its inclusion of a diverse array of columns, capturing essential facets of biodiversity occurrences. It encompasses identifiers like scientific names and occurrences, facilitating precise data referencing. Taxonomic details, including kingdom, phylum, class, order, family, genus, and species, offer insights into the biological classification of the recorded organisms.

Geographic information such as latitude and longitude provides a spatial context, crucial for understanding the distribution of species. Temporal aspects, represented by event date, day, month, and year, contribute to the dataset's temporal dimension, allowing for the analysis of seasonal patterns and trends.

Furthermore, attributes like country, locality, province, and recorded by add contextual information, enhancing the dataset's richness and spatiotemporal dynamics.

## The Team

Meet the minds behind this project:

- **Lena Castillo**  
  *Front-End Developer*  
  "A distinctive name that means 'ray of sunshine' in Hebrew, and I believe it characterizes who I am. I aspire to become a frontend developer, working with HTML, CSS, and JavaScript."

- **Edgar Garcia**  
  *Back-End Developer*  
  "I'm a 20-year-old Back-End developer. I'm into video games, music, and I really enjoy traveling. I aspire to be a Full-Stack developer, blending code with creativity and innovation to craft digital worlds."

- **Sebastián Maldonado**  
  *Machine Learning Engineer*  
  "I'm Sebas, a person who really enjoys theater. And I play the role of a Machine Learning Engineer. I'm currently working on developing models and solutions using advanced machine learning."

- **Aaron Rodríguez**  
  *Software Developer*  
  "My name is Aaron and I am 19 years old. I am a person capable of achieving everything that is proposed. I mostly do back-end development using Django, and my main programming language is Python."


## Our Work

### Statement of the Hypothesis

The hypothesis proposes that the migration patterns of the species *Passer domesticus* are influenced by the season of the year, particularly the month, and that the choice of destination countries is determined by specific characteristics. During winter, *Passer domesticus* is likely to migrate to countries situated closer to the equator. This implies a correlation between seasonal changes, geographical location, and the migratory behavior of *Passer domesticus*.

## Summary: Machine Learning Modeling for Passer domesticus Species

### Objectives
Our primary objective is to develop predictive models to estimate the geographic location (country) of the Passer domesticus species based on climatic and temporal variables. By leveraging environmental factors such as temperature, precipitation, and seasonality, we aim to understand and predict the migratory patterns and spatial distribution of this bird species, crucial for ecological and conservation studies.

### Model Selection
We have initially employed two distinct machine learning models:

1. **Multinomial Logistic Regression**:
   - Selected due to the multiclass classification nature of our target variable (country codes).
   - Effective for handling multiple possible classes (countries) in the classification problem.

2. **Random Forest Classifier**:
   - Chosen for its robustness in handling complex datasets and capturing nonlinear relationships.
   - Provides insights into feature importance and model interpretability.

### Validation Methods and Metrics
We utilize the following metrics to evaluate model performance:

- **Precision**: Measures the accuracy of positive predictions for each class.
- **Recall**: Reflects the model's ability to correctly identify all instances of a class.
- **F1-score**: Harmonic mean of precision and recall, offering a balanced measure of model performance across classes.

