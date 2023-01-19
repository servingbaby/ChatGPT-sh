** Check out the screenshots! I documented how I got here using ChatGPT :D

## Originally created this repo as a proof of Concept. 
Will likely use as a dumping ground till I can organize all the things. Fun stuff for sure! Original README Down below

------------------------------------------------------

## Introduction
This is a bash script that makes an API call to the OpenAI API to generate text using the ChatGPT model.

## Prerequisites
Before using this script, you will need:
- An API key for the OpenAI API. You can get one by signing up for an account on the OpenAI website.
- `curl` command line tool. This is used to make the API call.

## Usage
To use the script, you will need to replace "API_KEY" with your key in the script. Executing the script will then make an API call to the OpenAI API, using the provided prompt to generate text using the ChatGPT model.

Here's an example of how to use the script:

./chatgpt.sh "What would you like to know?"


## Additional parameters
The script also accept some additional parameters such as temperature, max_tokens, top_p, frequency_penalty, presence_penalty, etc.

./chatgpt.sh "What would you like to know?" -t 0.7 -m 20 -p 1 -f 0 -r 0

You can find more information about these parameters in the OpenAI API documentation.

## Disclaimer
It's important to note that the content generated by the API is provided under the OpenAI API Service Agreement, which can be found here: https://beta.openai.com/terms/api-service-agreement/

Please consult the OpenAI API Service Agreement and the GitHub Terms of Service to ensure that you are in compliance with both agreements before using this script or any generated content.

## Conclusion
This script provides a simple way to use the OpenAI API to generate text using the ChatGPT model. By providing your API key and prompt to the script, you can quickly generate text without having to manually make an API call.
