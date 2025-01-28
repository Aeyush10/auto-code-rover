# Environment variables to be set to use managed identity

AZURE_DEPLOYMENT: the model to be used (eg: deepprompt-gpt-4o-2024-05-13-global)
ENDPOINT_URL: the endpoint url to be used

Make sure to perform az login before running autocoderover


# Variable info

main.py: ENV_SETUP: if True, runs pip install for the repo with the swe-bench task. If False, skips the installs

gpt.py: USE_MANAGED_IDENTITY: if True, uses azure identity for authentication, else uses openAI key