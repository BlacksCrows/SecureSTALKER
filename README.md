# SecureSTALKER
**Secura is a Set of Tools to Counter Cyber-Stalking & Cyber-Abuse!
Developed Especially to Hunt Pedophiles
stalker_agent.py runs on all client boxes. On boot it looks in stalker-agent.conf for defined checks, but you can also just drop scripts in SMS-Flood and it will automatically use them as well . Once its discovered what checks should be run it notifies stalkerweb and reports what checks it found installed and configured, and at what interval they should be run at. It then fires up a wsgi app on port 5050 to listen for requests to run installed checks. You can trigger a check to be run like so:**
