# PharmoGen-Solutions

In modern medicine, the lack of efficient tools for drug discovery and diagnostic testing, alongside traditional lab methods, hampers timely identification of effective treatments and accurate diagnoses. Moreover, the absence of streamlined platforms for molecular data analysis impedes medical research progress and optimal patient care. Recognizing this challenge, our project “PHARMOGEN SOLUTIONS” leverages machine learning to predict compound bioactivity, particularly for a protein related to the SARS-CoV-2 virus, using data from the ChEMBL database. The project progresses through stages including data collection, model building, comparison, and deployment as a web application. We are designing a multifunctional medicine laboratory website to address the challenges faced in modern medicine. With features like a comprehensive test catalog, report analysis, specimen handling, appointment alerts,schedule check-ups, check doctor availability and customer support platform, our platform aims to streamline processes for healthcare professionals.

Welcome to the groundbreaking website of our **PharmoGen Solutions**, where innovation meets excellence in healthcare. Our website, crafted using HTML, CSS, JavaScript, Python and Jupyter, serves as a dynamic platform designed to cater to the diverse needs of healthcare professionals and patients alike.

**Some of the functionalities are:** 

Test Catalog:
Explore our extensive test catalog, meticulously curated to encompass a wide range of diagnostic tests tailored to meet the evolving needs of modern medicine. From routine screenings to specialized assays, our comprehensive test catalog offers vital diagnostic tools to assess patient health with precision and accuracy.

Specimen Handling:
Discover our rigorous specimen handling protocols, meticulously designed to ensure the integrity and accuracy of each sample. With attention to detail and adherence to industry standards, we safeguard the quality of specimens, enabling reliable diagnostic testing and confident clinical decisions.

Customer Service:
Experience unparalleled customer service excellence with our dedicated team of professionals committed to providing prompt and personalized assistance. Whether you have inquiries, require assistance, or seek guidance, our customer service team is here to ensure a seamless experience and foster strong partnerships with our valued clients.

Check-Ups:
The website simplifies appointment management by allowing users to easily book appointments, view doctor schedules, and receive automated notifications. Users can also access detailed doctor profiles and utilize robust search functionality to find healthcare providers. Integration with Electronic Health Records streamlines the process for existing patients.

BioActivity Prediction Model:
At the heart of our innovation lies our pioneering BioActivity prediction model, revolutionizing drug discovery for better patient outcomes. With top-tier expertise and innovative tools, we accelerate drug discovery timelines and empower healthcare providers to deliver superior care efficiently. 

Model Insights

Here the bioactivity prediction option is using molecular descriptors (PADEL) and supervised machine learning (ML) and DL. The project allow you to extract and clean data from Chembl database in order to obtain IC50 of every studied molecule relative to a target protein of interest. IC50 values are associate to molecular and lipinski descriptors in order to generate a model that can predict bioactivity values of new single molecules or library of compounds.

The following Modules must be used consequently, in order:

PharmoGen_part1: Search Chembl database for target data, create dataframe with IC50 and SMILES values, calculate molecular descriptors using PADEL. Save dataset_with_padel_pIC50.csv before closing.
PharmoGen_part2: Upload dataset_with_padel_pIC50.csv, compare ML models to find the best for the project.
PharmoGen_part3: Generate descriptors from SMILES notation.
PharmoGen_part4: Conduct linear regression with RandomForest regressor, create model (pkl), predict IC50 of new molecules in Colab.
PharmoGen_part5: Compare model performance using lazy predict library.
PharmoGen_part6: Web app allows uploading pickle object (model) and SMILES file for predictions on target protein models.

This website serves as a beacon of innovation and excellence in healthcare, embodying our commitment to advancing medical science and improving patient outcomes. Explore our website to discover how we're pioneering the future of medicine and join us in our mission to revolutionize healthcare, one breakthrough at a time.

PharmGen platform with functionalities
![pg1](https://github.com/Sehal-Saxena/PharmoGen-Solutions/assets/140236967/d39b3f01-e443-44eb-96eb-092760ff40de)
![pg2](https://github.com/Sehal-Saxena/PharmoGen-Solutions/assets/140236967/caae0ce3-d6ff-4dfb-83fa-f0f17effe068)
![pg3](https://github.com/Sehal-Saxena/PharmoGen-Solutions/assets/140236967/7fe7a335-b1f3-4da5-9cd2-93678035ae28)

Bioactivity Prediction Tool
![pg4](https://github.com/Sehal-Saxena/PharmoGen-Solutions/assets/140236967/87484597-4618-4ea2-b0de-8b870e481314)

Performance Analysis of different ml models
![pg5](https://github.com/Sehal-Saxena/PharmoGen-Solutions/assets/140236967/06390674-9b5d-4ed3-a97a-462af87e1ff2)

