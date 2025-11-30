# IncidentBot – On-Call Incident Co-Pilot for Zoho Cliq

IncidentBot is an incident-management assistant built using **Zoho Cliq**, **Deluge**, and custom API integrations.  
It is designed to help teams respond to operational issues faster by providing **automated war rooms**,   **presence-based user addition**, and **slash-command driven workflows**.

This project was created as part of the **Zoho Cliqtrix Hackathon**, where the goal is to build a real-world  
automation or productivity extension using Zoho Cliq’s developer tools.

![Incident Bot Screenshot](https://github.com/muthumani-ravisankar/incidentbot/blob/main/images/Screenshot%202025-11-30%20175542.png)


---

## 🚀 Why This Project?

Managing production incidents involves a lot of repetitive steps:
- Checking who is currently available
- Finding the on-call engineer
- Creating an incident war room channel
- Inviting only the relevant engineers
- Maintaining an incident list
- Marking incidents as resolved
- Sending updates inside channels

Teams often waste several minutes on these tasks before they even begin solving the issue.

**IncidentBot automates the entire workflow.**

It turns Zoho Cliq into a **central control hub** for on-call engineering, enabling faster, consistent,  
and guided incident response.

---


## 🔥 Core Features Implemented

### ✔ Slash Command: `/incident`
A single command to control the entire lifecycle:

| Command | Meaning |
|--------|---------|
| `/incident create <name>` | Creates a new incident & war room |
| `/incident resolve <id>` | Marks an incident as resolved |
| `/incident list` | Shows all active war rooms |
| `/incident delete <id>` | Removes an incident |
| `/incident -madd` | Auto-adds available users to the war room |

This allows users to control everything without navigating menus or panels.

## ⚡ Presence-Based Member Assignment

IncidentBot dynamically checks:

- Which users are **online**
- Which users have **Available** status
- Which IDs belong to on-call personnel

## 🧠 Message Handler Support

The bot responds intelligently to keywords, for example:

- Greetings  
- Incident-related questions  
- Help prompts  

This provides a highly interactive experience even before completing all extension modules.

## 🏁 Conclusion

Due to a technical limitation in the Zoho Cliq Developer Console, I was unable to create and publish a full extension using the “My Extensions” option. Even after multiple attempts and troubleshooting steps, the “Create Extension” action was not available in my developer account.

To ensure I could still present my concept, implementation logic, workflows, bot scripts structure before the competition deadline, I prepared this GitHub repository as an alternative submission. It includes all the code, ideas, design decisions, and problem-solving approaches that would have gone into the final extension.


