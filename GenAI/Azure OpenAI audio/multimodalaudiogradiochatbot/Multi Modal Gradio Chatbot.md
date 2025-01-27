# Setup and Usage of MultiModal Audio Chatbot powered by Azure OpenAI  gpt-4o-audio-preview model

This guide provides step-by-step instructions to set up  MultiModal Gradio  Audio Chatbot


 

## Prerequisites

- For Prerequisites and to learn more about the gpt-4o-audio-preview [Get started using Azure OpenAI audio generation](https://docs.docker.com/engine/install/)

## Things to Note 

This Sample Code is provided for the purpose of illustration only and is not intended to be used in a production environment. THIS SAMPLE CODE AND ANY RELATED INFORMATION ARE PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF MERCHANTABILITY AND/OR FITNESS FOR A PARTICULAR PURPOSE. We grant You a nonexclusive, royalty-free right to use and modify the Sample Code and to reproduce and distribute the object code its authors,or anyone else involved in the creation, production, or delivery of the scripts be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or inability to use the sample scripts or documentation, even if its has been advised of the possibility of such damages

#### The User Audio input and Model Audio ouput are playable only for the latest conversation 


## Steps

### Step 1

Clone the Python sample Repo from [here](https://github.com/mahes-a/multimodalaudiogradiochatbot)

### Step 2

Add a env file and add the key "AZURE_OPENAI_ENDPOINT" and add your endpoint , The code uses Microsoft Entra ID for authentication . Please refer [here](https://learn.microsoft.com/en-us/azure/ai-services/openai/audio-completions-quickstart?tabs=keyless%2Cwindows%2Ctypescript-keyless&pivots=rest-api#microsoft-entra-id-prerequisites) to setup the Microsoft Entra ID authentication 

### Step 3
Run the python file using python multimodal-audiotext-gptaudio.py and start testing 


### Step 4

To Deploy the Gradio App to a Azure App Service refer [here](https://datasciencedojo.com/blog/web_app_for_gradio/)


