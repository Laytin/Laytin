<div id="header" align="center">
  <img src="https://i.pinimg.com/originals/ab/dc/be/abdcbe5fdef8ee78bdc312cda2b67df6.gif" width="150"/>
</div>

<div id="badges" align ="center">
  <a href="https://www.linkedin.com/in/ne9ko">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:xpor2002@gmail.com">
    <img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://t.me/ne9ko">
    <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=black" alt="Telegram Badge"/>
  </a>
  <br>
  <img src="https://komarev.com/ghpvc/?username=Laytin&style=flat-square&color=blue" alt=""/ align="center">
</div>

<h2>:man_scientist: About Me :</h2>

I'm Java-Junior from Belarus, have a secondary education in electronics engineering.
<br>
My knowledge of technology: 

- Understanding of OOP and Design Patterns
- Good knowledge of Java (Core, Collections, Threading)
- Spring Frameworks
- Hibernate
- DB: PostgreSQL, MongoDB
- Template engines: Thymeleaf, JSP(?)
- Understanding REST and Microservices structure
- Extras:
  - RabbitMQ
  - JUnit
  - Jackson (serialization)
  - Log4j
  - Testing: Postman

Also: ForgeGradle, GradleShadow(plugin).
I'm using Intelij Idea, maven/gradle.

---
<div align = "center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/spring/spring-original-wordmark.svg" title="Spring" alt="Spring" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSQL"  alt="PostgreSQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tomcat/tomcat-original-wordmark.svg" title="Tomcat"  alt="Tomcat" width="40" height="40"/>&nbsp;
  <img src="https://cdn.worldvectorlogo.com/logos/hibernate.svg" title="Hibernate"  alt="Hibernate" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>

---
<div align = "center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=Laytin&theme=prussian)](https://git.io/streak-stats) 
  
</div>

---

Work is currently underway to create a large monolithic project for the multi-user game Minecraft.
-
**[Project page](https://github.com/Laytin/ExlnProject)**
-
The project consists of a modification part that adds a graphical component, as well as communication with the server side of the modification. 
The server side of the modification is used for injection into the runtime of the Java machine and work with the API of the plugin of the same name, 
which allows you to get full functionality (both the functionality of the bukkit component and Forge), as well as to isolate transactions.
The player only receives response data that is processed by openGL(LWJGL) graphics.
Also, this separation allows you to abandon the graphical component for servers on the Spigot/Bukkit core.

The project's capabilities are extensive:
- Opening cases with animations
- Receiving and previewing kits
- A logging system that allows you to track a player’s multi-accounts (ONLY WITH HIS PERMISSION!I am not responsible for using this function in a real project.
  It is disabled by default.It is presented as educational material) to prevent bypassing bans
- Notification system in Discord, as well as executing console commands using a bot or outputting messages to the game chat and vice versa
- Warp system, public/private, checked by administrator
- In-game store, sync with web-store (in-game items)
NOT RELEASED:
- Daily Rewards
- Some improvements to logging system to prevent WINREG changing
- Tab render with permission level
- Chat and chat formatting

Currently working on a packet system beetwen client<->server.
