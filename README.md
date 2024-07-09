# AirOps-Workflows
These are the beginner workflows I created yesterday to study and get familiar with the platform.

## Latest News Tweet Bot

[Link To App](https://app.airops.com/public_apps/3e6357b9-e46a-4b20-920f-e3e7044804a2/run)

This app is to scrape the (x) latest articles on Google News about a topic, and generate (y) tweet threads that I have emailed to myself:

#### Step 1: Python Code to scrape Google News article links
<img width="1283" alt="Screenshot 2024-07-09 at 12 59 37 PM" src="https://github.com/Abdullahi-Elmi/AirOps-Workflows/assets/27597882/03351372-9252-4ad8-9d22-00e2a38f0683">

#### Step 2: Iteratively scrape the contents of each link
<img width="450" alt="Screenshot 2024-07-09 at 1 00 18 PM" src="https://github.com/Abdullahi-Elmi/AirOps-Workflows/assets/27597882/e636eb12-e367-45c8-bca7-686e49207d6a">

#### Step 3: Using K-Shot prompting, iteratively summarize every article.
<img width="444" alt="Screenshot 2024-07-09 at 1 03 53 PM" src="https://github.com/Abdullahi-Elmi/AirOps-Workflows/assets/27597882/d9e3f311-1898-43e8-8e85-b832f8d3cdb4">
<img width="646" alt="Screenshot 2024-07-09 at 1 04 22 PM" src="https://github.com/Abdullahi-Elmi/AirOps-Workflows/assets/27597882/71c556b1-eb0c-473d-aef4-e0108407e052">

#### Step 4: Using Chain Of Thought + K-Shot Prompting, write the tweet threads.
Note: Liquid Templating is used to combine the output of the iteration blocks

<img width="366" alt="Screenshot 2024-07-09 at 1 06 39 PM" src="https://github.com/Abdullahi-Elmi/AirOps-Workflows/assets/27597882/e70ad9ca-c22e-4587-9fc2-deb0be754ee2">
<img width="649" alt="Screenshot 2024-07-09 at 1 10 05 PM" src="https://github.com/Abdullahi-Elmi/AirOps-Workflows/assets/27597882/8182ec7a-140f-4b76-876b-a9f559da97a5">

#### Step 5: Gmail Integration to email the output to myself
Note: Liquid templating to fetch the links and titles from Step 1.

<img width="958" alt="Screenshot 2024-07-09 at 1 14 04 PM" src="https://github.com/Abdullahi-Elmi/AirOps-Workflows/assets/27597882/8b61acdd-793b-4753-a279-a5488cda9884">

## AirOps Docs Helper Bot

[Link To App](https://app.airops.com/public_apps/4c5e69e7-ed59-40b1-860e-940316bd5ed9/run)

This was just the 2nd workflow I created to practice and see the capability of memory stores, and what an Agent app looked like compared to a workflow app. The agent is incredibly simple, but I tried to create a memory store based on the AirOps docs.

Note: The chat bot isn't great at specific button directions as the docs have interactive panes for those portions, and I couldn't quickly translate that into the memory stores.

## YouTube Tutorial: Web Page to Article

[Link To App](https://app.airops.com/public_apps/ad39e2a5-e701-4666-b380-17a90b1fbabc/run)

I watched [this tutorial](https://www.youtube.com/watch?v=HRk2xRn1IWI). Then created the app from scratch to make sure I understood it.

## YouTube Tutorial: Airtable Q + A Workflow

[Link To App](https://app.airops.com/public_apps/f5bb5261-fec0-4e69-a3f9-30057e7b6510/run)

I watched [this tutorial](https://www.youtube.com/watch?v=SQvX_CzwKzk). Then created the app from scratch using the default Airtable memory store instead of biology notes to make sure I understood it.

Lastly I also watched [AirOps Studio v1.0 - Your First LLM Powered App with AirOps](https://www.youtube.com/watch?v=HtN2NWq30cE) at the very beginning to understand the platform.
