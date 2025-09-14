# SENECA-25-26-HACKATHON
THIS reposit is made to showcase the work we've accomplished in 40-hour  ON-SITE hackathon about NLP pipeline organised by SENECA  INSAT TUNIS 
Made by MOHAMED ALI MAATOUG
FEHRI YASSINE
AKREMI YOUSSEF
LAARIF TALEL
TO walk through this reposit we can start by the IDEA:
wW created a service that recommends users posts depending on their interests  and posts in sports field that can handle a big flux in data through our pipeline built on Apache. The model we built ia a powerful recommendation system that loops and feeds itself ensuring the model's continuous improveeent and real-time request handling.

THE ABSTRACT ARCHITECTURE IS SHOWN in the graph of the main folder followed by the pipeline architecture
The data that we have used for fine tuning is taken from https://www.kaggle.com/datasets/curiel/rfitness-posts-and-comments, we also did web crawling using Reddit's API, on the r/bodybuilding subreddit.
We used the T5 and GPT2 models for fine-tuning.

# Setup

## Server
### Kafka
Download Kafka 2.13


