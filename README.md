				JSON-Data-Transformation-Project



Overview :


This project involves the transformation of unstructured raw JSON data into structured tables in Snowflake. The raw JSON data contains information about individuals, including their personal details, job information, spoken languages, and previous job history.

Process :


1)	Data Extraction: The raw JSON data was extracted and loaded into Snowflake for further processing.

2)	Data Transformation: The unstructured raw JSON data was transformed into structured tables using Snowflake's capabilities. This involved parsing the JSON data and extracting relevant fields to populate the tables.

3)	Table Creation :

	Main Table: A main table was created to store individual details such as ID, first name, last name, gender, city, job title, and salary.

	Previous Job Table: Another table was created to store previous job history, if available, for each individual.

	Languages Table: A table was created to store spoken languages and proficiency levels for each individual.

4)	Data Loading : The transformed data was loaded into the respective tables in Snowflake.



Table Structure :


![image](https://github.com/Jay-05022000/JSON-Data-Transformation-Project/assets/110780565/b1da5ffd-a66a-4c2a-a000-120d37175953)

![image](https://github.com/Jay-05022000/JSON-Data-Transformation-Project/assets/110780565/3b6fbee1-4b9b-4d0f-bf72-6a9c3f05fa2c)


Usage :


1)	Accessing the Data: Users can query the tables in Snowflake to retrieve information about individuals, their previous job history, and spoken languages.

2)	Analyzing the Data: The structured data allows for easy analysis and reporting, providing insights into various aspects such as demographics, job trends, and language proficiency.


Contributing :


Contributions to this project are welcome. If you encounter any issues or have suggestions for improvement, please feel free to submit a pull request.

