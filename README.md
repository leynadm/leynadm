# Hi, I'm Daniel Matei 

**Full-Stack Engineer | Technical Consultant | Product Builder**

I am currently a Technical Consultant at **Boehringer Ingelheim**, a leading pharmaceutical company, where I support various IT transformation projects.

My career journey has spanned multiple industries over the past decade, including BPOs, e-commerce, and enterprise IT. From operations management in the BPO sector to project management at fast-paced e-commerce startups, I have developed a blend of business awareness and technical expertise that I bring to every project. 

This professional trajectory has also allowed me to live and work in three different countries, giving me a global perspective and fluency in four languages.

Three years ago, supported by a nurturing environment at Boehringer Ingelheim, I transitioned into full-stack software development to act upon a long-standing passion for engineering. My focus is now on creating modern, scalable web applications, specializing in the **React** and **Node.js** ecosystems.

- 
### :loudspeaker: Reach out to me and I'll make sure to reply back:
<div id="badges">
  <a href="https://www.linkedin.com/in/matei-daniel/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>

### :hammer_and_wrench: Languages and Tools:

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-plain.svg" title="Typescript" alt="Typescript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-plain.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;  
  <img src="https://github.com/devicons/devicon/blob/master/icons/jest/jest-plain.svg" title="Jest" alt="Jest" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain.svg" title="Firebase" alt="Firebase" width="40" height="40"/>&nbsp;
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg" title="Node.js" alt="Node.js" width="40" height="40"/>&nbsp;
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" title="MongoDB" alt="MongoDB" width="40" height="40"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/supabase/supabase-original.svg" title="Supabase" alt="Supabase" width="40" height="40"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original-wordmark.svg" title="Express" alt="Express" width="40" height="40"/>&nbsp;
  
</div>

### :computer: Projects I've built 

### *<a href="https://myfootballlegacy.com/" target="_blank">My Football Legacy - A Football Management Simulator</a>*

My Football Legacy is a football simulator app, allowing users to act as managers and simulate football seasons. I built this up with the objective of supporting the Pro Evolution Soccer football community series that was discontinued. 

My goal was to leverage and perfect using the technologies that stand today at the heart of the modern web, specifically React via Next.js + SQL database in the form of Supabase.

The app overview:
- It's a Progressive Web App
- It is built with Next.js and Supabase
- It uses Shadcn as a component library, together with Tailwind
- I decided to using React Tanstack Query for state management (avoid fetching through useEffect and sharing contenxt via useContext).
- It handles server-side authentication via Supabase auth
- Users can choose a league and team and start their season
- I recreated the structure of up-to-date competitions (all major leagues in Europe + Uefa Champions League, Europa League and Champions League, including the cup competitions as well)
- Users have an AI based management board that they can interact with through an email system
- It has a very comprehensive analytics dashboard, covering a series of KPIs related to football (using Recaharts)
- Users can perform player transfers, buying, selling and releasing players, and a lot more actions

Current registered users: 1000+
Weekly Active Users: 500+ (during weekends)

### *<a href="https://footballevolved.app/" target="_blank">Football Evolved - Tracker App For Amateur footballers</a>*

Football Evolved is a full-stack app, working as a stats tracker for amateur footballers. It combines utility with a series of gamification elements, the idea being to provide amateur footballers a means to monitor their performance during matches over time.

My profile: https://footballevolved.com/share?user=sS2Rowgi5igY1K4JbWhjmioI6Su1&token=c98b6b6bef21a5f10afee90d4f4c979d

The app overview:
- Works as a Progressive Web App
- Relies fully on client-side rendering, built with Vite + React
- Uses Firebase (BaaS) for authentication, database and cloud functions
- I used Chakra UI as a components framework (I wanted to learn something new, other than Material UI)
- Supports authentication via email and password, as well as Google Auth
- Users can add their matches, together with a series of statistics (like goals scored, assists, fouls)
- It has a comprehensive highlights system, in case the user achieved specific events (like scoring a bycicle kick, etc.)
- Users can choose a club they support and upload their own images of the club
- AI coaches and AI journalists provide the user with feedback/analysis after matches, for improved imersion
- I'm using Gemini API for interactive content
- Users can start challenges and competitions in order to win trophies, motivating themselves to perform at their best even though their real life matches might not have a pre-defined stake
- There is a social component, where users can search for the profiles of other users, follow each other and see their peers' performance

Current registered users: 150+
Monthly Active Users: 30+

### *<a href="https://emplicit.app/en" target="_blank">Emplicit - AI Assisted Content Generation App</a> (currently in progress)*

After building various projects, I've always hit the same bottleneck: marketing and promotion. That's how I got the idea for Emplicit, an AI assisted content generation app. The principle is simple, you start with the core identity of your brand, and Emplicit helps you draft content ideas, pick a communication style and create content. You can create a brand strategy, and plan content campaigns. At specific intervals, you can also run brand audits, in order to monitor how your brand strategy evolved.

The app overview:
- Built using the best practices with Next.js, Supabase and ShadCn
- Supports multi-tenancy, via workspaces -> brand hierachies
- Makes use of OpenAI and Google's Gemini APIs for AI generation
- Uses Vercel's AI SDK for managing practices like data streaming
- Uses a credit system for monitoring token usage
- Users are able to use their own API keys, safely stored in Supabase's Vault

### *<a href="https://fitpowerup.com/" target="_blank">fitPowerUp - A Dragon Ball Z Inspired Fitness App</a>*

fitPowerUp represents my first ever full-stack project. Built with React, Typescript and Firebase, I wanted to create an app that combined a wide array of features suitable for a fitness app, as well as a gamification element inspired from Dragon Ball Z series.
The app overview:
- It's a Progressive Web App
- I used Material UI as a UI framework
- Users can save workouts locally via IndexedDb, and sync with Firestore Db
- It provides a comprehensive analytics dashboard built with Recharts
- The user can export their own data to csv

Current registered users: 150+





<!--
**leynadm/leynadm** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>

Here are some ideas to get you started:
- 👯 I’m looking to collaborate on ...
-->
