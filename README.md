# dialogflow
Implementing Dialogflow with Webex. Wish me luck.

## Proxy Settings
https://cloud.google.com/sdk/docs/proxy-settings

## Start with this video series. 

https://developers.google.com/codelabs/chatbots-dialogflow-appointment-scheduler?continue=https%3A%2F%2Fdevelopers.google.com%2Flearn%2Fpathways%2Fchatbots-dialogflow%23codelab-https%3A%2F%2Fdevelopers.google.com%2Fcodelabs%2Fchatbots-dialogflow-appointment-scheduler#0

### Github Dialogflow Integration 

https://github.com/GoogleCloudPlatform/dialogflow-integrations#readme

### Google Calendar Integration

https://www.youtube.com/watch?v=4_MvIf_ULgc

https://codelabs.developers.google.com/codelabs/chatbots-dialogflow-fulfillment#2

### Install Google Cloud CLI

https://cloud.google.com/sdk/docs/install-sdk

* Click **Guide me**
>[Google Cloud Shell](

## Webex and Dialogflow

https://help.webex.com/en-us/article/m2az0i/Cisco-Webex-Hybrid-Calendar-Service-with-Google-Calendar-integration-reference

## Build an Agent

https://cloud.google.com/dialogflow/es/docs/quick/build-agent

You need to copy the JSON and google calendar ID to later add to the Fulfillment. 
>**WARNING**: Must Open accounts with Google. While they are free it is something to consider for the future. At this time they are offering a $300 credit, so I am using it with the credit. Also, you will need to interact with the gCloud CLI. It is easier to depoy with with Google's system.
>Go over documentation and trying to break this in sequence.

## Google Runner Set up

Running core commands
Run core commands to view information about your gcloud CLI installation:

List accounts whose credentials are stored on the local system:


gcloud auth list
The gcloud CLI displays a list of credentialed accounts:


Credentialed Accounts
ACTIVE             ACCOUNT
*                  example-user-1@gmail.com
                   example-user-2@gmail.com
List the properties in your active gcloud CLI configuration:


gcloud config list
The gcloud CLI displays the list of properties:


[core]
account = example-user-1@gmail.com
disable_usage_reporting = False
project = example-project
View information about your gcloud CLI installation and the active configuration:


gcloud info
The gcloud CLI displays a summary of information about your installation. This includes information about your system, the installed components, the active user account and current project, and the properties in the active configuration.

View information about gcloud commands and other topics:


gcloud help
For example, to view the help for gcloud compute instances create:


gcloud help compute instances create
The gcloud CLI displays a help topic that contains a description of the command, a list of command flags and arguments, and examples of how to use the command.

