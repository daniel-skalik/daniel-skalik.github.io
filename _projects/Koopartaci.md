---
layout: project
order: 3

name: Koopartaci
image: /assets/images/koopartaci/thumbnail.webp
video: Oidoxk60COw
carousel_images:
        [
          /assets/images/koopartaci/1.png,
          /assets/images/koopartaci/2.png,
          /assets/images/koopartaci/3.png,
          /assets/images/koopartaci/4.png,
          /assets/images/koopartaci/5.png,
          /assets/images/koopartaci/6.png,
          /assets/images/koopartaci/7.png,
          /assets/images/koopartaci/8.png,
          /assets/images/koopartaci/9.png,
          /assets/images/koopartaci/10.jpg,
          /assets/images/koopartaci/11.jpg,
          /assets/images/koopartaci/12.png,
        ]
tools: [ Android, iOS ]
project_links: [ https://apkpure.com/koopar%C5%A5%C3%A1ci/com.kooperativa.koopartaci ]
client: Retrobot

description: >-
  A unique gamified application primarily designed for employees and traders of Kooperativa Insurance. \n
  It blends elements of gameplay with professional development. 
  Users create and customize a virtual avatar, which can be upgraded by earning points through a variety of tasks and challenges.
  The app features daily cognitive games that improve skills like attention, memory, and speed, as well as quizzes on insurance knowledge, company trivia, and product education. \n
  It encourages teamwork by allowing users to join or create clans, fostering collaboration and competition for in-game and real-world rewards across game seasons.
project_scope: Commercial
project_role: Unity Developer
project_duration: 2 years
team_size: 5
---

### My Contributions

- **Development of Cognitive Minigames**: Designed and implemented approximately 20 cognitive minigames aimed at training various brain functions, including reflexes, memory, speed, and pattern recognition.​
- **User Interface (UI) Design**: Created intuitive and engaging user interfaces to enhance player experience and accessibility.
- **Avatar Customization**: Developed a system allowing players to personalize their avatars with items unlocked through gameplay progression and seasonal achievements.
- **Live Operations (Live Ops)**: Implemented features such as events, daily games, seasons, leaderboards, and clans to maintain player engagement and retention.
- **Clan Messaging System**: Integrated SignalR to facilitate real-time communication among clan members.
- **Custom Login System**: Developed a bespoke authentication system tailored to the needs of Kooperativa's internal acquirers.
- **API Access**: Utilized Best HTTP on the client side to ensure efficient and secure API access.
- **Firebase Integration**: Integrated Firebase services to enhance app functionality and performance.

### Challenges and solutions

- **Seed-Based Minigame Scheduling**: The requirement was to have minigames scheduled based on a seed derived from the date, shuffled throughout the week, ensuring all players had access to the same games but not on the same day.
  - _Solution_: Implemented a deterministic algorithm that generates a weekly schedule of minigames based on a date-derived seed. This approach ensured consistency across the player base while introducing variability in daily game offerings.​