---
layout: post
title: Load Monitoring Web Application (Vue)
---

This web application communicates with a local back-end service at 10-second intervals to retrieve CPU load average information.
It displays the CPU load data for the last 10 minutes on a graph and shows the current CPU load on a card. <br/>
The application also indicates the start and end times of high average load periods and provides alerts for high load conditions or recovery from high load. Thresholds for high load and recovery:<br/>

A CPU is considered under high average load when it has exceeded 1 for 2 minutes or more. <br/>
A CPU is considered recovered from high average load when it drops below 1 for 2 minutes or more. <br/>
[Demo](https://oozd.github.io/load-monitoring-web-application/) <br/>
[Code](https://github.com/oozd/load-monitoring-web-application) <br/>

### Tech Stack

- Vue.js 3
- Node.js
- Vuetify
- Chart.js
- Vitest, Jest
