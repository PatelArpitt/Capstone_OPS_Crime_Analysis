# Capstone Project - OPS Ottawa Crime Analysis

- This project investigates the sentiment analysis of the OPS chief’s verbal reports, utilizing data extracted from the `Ottawa Police Services (OPS)` website to analyze community concerns related to crime in the city. The original data, consisting of archived PDF/Word documents in a chronology of events format, presented `strategic and operational concerns discussed by the OPS Chief of Police during regular briefings to the Ottawa Police Services Board.`

- The data extraction process involved web scraping using Python to collect information from the OPS website, followed by exporting the data to an Excel sheet for further analysis. The chief's verbal reports were analyzed using `Natural Language Processing (NLP)` techniques, which involved extracting relevant sentences containing information about crimes and identifying the type of crime that occurred. This was achieved through the use of related words and crime recognition libraries, as well as `tokenization and word recognition using the SKLearn library` to account for variations in language and descriptions of crimes.

- Furthermore, `Regular Expressions (REGEX)` were employed to extract the number of people involved in a crime from the sentences, automating the data collection process from all chief's verbal reports and categorizing the crimes accordingly. The combined dataset was then subjected to data cleaning to remove outliers and enhance accuracy.

- The model training process involved dividing the dataset into training and testing data, with careful examination and preprocessing of each sentence to determine its relevance to crimes. The accuracy of the model was improved iteratively, and `the final dataset`, comprising `approximately 4000 sentences`, was divided into `30% training data` and `70% testing data` for further refinement.

- **Also the model has achieved an accuracy of 73% to detect and tag a crime in a sentence.**

- The findings of this study contribute to a `better understanding of the OPS chief’s verbal reports` by doing sentiment analysis, as well as showcase the `use of NLP, machine learning, and data analysis techniques in the field of law enforcement.` The results highlight the potential of `utilizing web-scraped data from public sources for research purposes`, and the importance of data preprocessing and model refinement in achieving accurate outcomes.
