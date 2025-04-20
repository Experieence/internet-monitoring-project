# 🌐 Global Academic Network Performace Monitoring 
This project automates the logging of internet perfomance data using 4 global academic targets using Bash scripting, it measures the route stability of the targets, packet loss, route paths and throughput over a week.

## 📁 Project Structure
```
│   LICENSE
│   README.md
│
├───logs
│   ├───ping
│   ├───traceroute
│   └───wget
└───scripts
        ping_logger
        traceroute_logger
        wget_logger
```

## 🎯 Measurement Targets

| Domain             | Country        | Notes                                   |
|--------------------|----------------|------------------------------------------|
| english.hi.is      | Iceland 🇮🇸     | Most stable RTT, reached final hop       |
| www.knust.edu.gh   | Ghana 🇬🇭       | Some route changes, medium latency       |
| www.trentu.ca      | Canada 🇨🇦      | Routed via CANARIE, fast throughput      |
| www.unifr.ch       | Switzerland 🇨🇭 | Final hop firewalled, but trace stable   |
 
