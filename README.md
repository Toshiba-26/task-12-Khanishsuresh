# Task-12-Khanishsuresh

## Task 12:

Your production web server (16GB RAM) suddenly slows down during peak hours. free -h shows 95% memory used, with high swap activity causing latency. top reveals user "apache" processes dominate memory usage.

Step-by-step, diagnose the top memory-consuming process under the "apache" user. Provide the exact commands to:

a) Identify apache's highest %MEM process (PID and command)
<img width="1102" height="386" alt="image" src="https://github.com/user-attachments/assets/c5fe8206-ffac-43cf-b1ea-fc303db26a7a" />

b) Check if it's a memory leak or normal load
<img width="912" height="69" alt="image" src="https://github.com/user-attachments/assets/10ea8238-cffe-4eeb-aaaa-930efc7c0a30" />

c) Kill/restart only that process without affecting other apache instances
<br>
<img width="429" height="65" alt="image" src="https://github.com/user-attachments/assets/fa65318b-ef88-4773-b298-558f5edacd09" />

