# deploy chatbot to BYOA

#### deploy using cpd-cli command:
```
  cpd-cli manage create-gitapp-application --cpd_instance_ns=zen
    --app_name=chatbot
    --app_port=8080
    --repo_url=https://github.com/shixuguang/Industry-Accelerators.git
    --repo_branch=test
    --repo_app_dir=watsonx.ai/QnA_chatbot_app
    --cpu=400m
    --memory=200Mi
    --cpu_limit=500m
    --memory_limit=400Mi
```