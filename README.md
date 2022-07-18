# census-api-data-abs

## **Description**

Data analysis project which compares demographics of business ownership in the United States from the 2020 and 2019 census (2020 census represents data from 2019 and 2019 census represents data from 2018). 12 questions were asked about the data, and twelve visualizations were made to answer those questions.

Uses data from the [Annual Business Survey](https://www.census.gov/data/developers/data-sets/abs.2019.html) for the United States in the 2020 and 2019 datasets from the Company Summary section.

## **Usage**

1. Clone the repository.

```shell
git clone https://github.com/ColeBallard/census-api-data-abs
```

2. Install the latest version of python.
[Downloads](https://www.python.org/downloads/)

3. Install Anaconda.
[Distribution](https://www.anaconda.com/products/distribution)

4. Install dependencies.
```shell
pip install pandas
pip install matplotlib
pip install requests
```

5. [Sign up for an API Key.][https://api.census.gov/data/key_signup.html]

6. Create config.py file.
```shell
touch config.py
```

7. Insert API Key into variable in config.py file.
```dosini
apiKey = 'yourapikey'
```

8. Start the Jupyter Notebook server.
```shell
jupyter notebook
```

9. Run the ETL notebook.
```shell
jupyter run ETL.ipynb
```

10. Run the visualizations notebook.
```shell
jupyter run visualizations.ipynb
```

## **Contribution**

If you have an idea or want to report a bug, please create an issue.

## **Contributors**
[@AzurePython](https://github.com/AzurePython)
[@ColeBallard](https://github.com/ColeBallard)
[@seungmin478](https://github.com/seungmin478)
[@widnie890](https://github.com/widnie890)

## **[Contact](https://coleb.io/contact)**
