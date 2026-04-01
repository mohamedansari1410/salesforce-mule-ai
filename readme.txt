
NOTE:

For API Config:

Inside SRC/MAIN/RESOURCES 
=> Create a JSON FIle Called - llm-config.json

{
  "GROQAI_OPENAI": {
    "GROQ_API_KEY": "your_api_key"
  }
}


For Salesforce Config:

Inside SRC/MAIN/RESOURCES/PROPERTIES
 => Create YAML File Called - CRED.yaml

salesforce:
  clientid: "Salesforce Org ClientId"
  clientsecret: "Salesforce Org ClientSecret"
  tokenurl: "tokenUrl"