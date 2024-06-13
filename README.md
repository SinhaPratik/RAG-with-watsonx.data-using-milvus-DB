# Retrieval Augmentation Generation with watsonx.data using Milvus vector Database 

## This notebook walks through the RAG approach to demonstrate the integration of watsonx.ai and watsonx.data platform through the milvus vector database.


#### How to download the certificate to connect the Presto engine and Milvus?
To externally connect to Milvus and the watsonx.data Presto engine, you will need to copy over a certificate for authentication. 
1. Open this URL in your preferred browser- https://techzone.ibm.com/my/reservations
2. Click on your reserved instance to view the list of services.
3. Click on ```Jupyter Notebook - Server``` to launch the Jupyter Notebook Server interface connected to the notebooks in the TechZone VM.
4. Navigate to the watsonx.data credentials tab.
3. Click on ```presto.crt``` file and it should be downloaded automatically.
4. Save this file on your local machine in the same location as this repository and rename this certificate to ```cert.crt```.



### Fill in the configuration details required in the ```config.env``` file before running the notebook by creating a new project inside watsonx.ai and through the list of services mentioned in watsonx.data


