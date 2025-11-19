# 🛡️ Security Integration Lab Documentation

This repository contains my personal 30-day project to build a complete cybersecurity environment using SIEM, SOAR, EDR, XDR, PAM, and Firewall solutions.  
The goal is to learn **Security Solutions Integration** by deploying real tools, collecting logs, detecting attacks, and documenting the process.

---

## 📌 1. Architecture Diagram
%3CmxGraphModel%3E%3Croot%3E%3CmxCell%20id%3D%220%22%2F%3E%3CmxCell%20id%3D%221%22%20parent%3D%220%22%2F%3E%3CmxCell%20id%3D%222%22%20parent%3D%221%22%20style%3D%22whiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22122%22%20width%3D%22182.25%22%20x%3D%2238%22%20y%3D%22117%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%223%22%20parent%3D%221%22%20style%3D%22whiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22134%22%20width%3D%22194%22%20x%3D%22289%22%20y%3D%22237%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%224%22%20parent%3D%221%22%20style%3D%22whiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22142%22%20width%3D%22155%22%20x%3D%22-205%22%20y%3D%22224%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%225%22%20edge%3D%221%22%20parent%3D%221%22%20source%3D%226%22%20style%3D%22edgeStyle%3Dnone%3Bcurved%3D1%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3BfontSize%3D12%3BstartSize%3D8%3BendSize%3D8%3B%22%20target%3D%222%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%226%22%20parent%3D%221%22%20style%3D%22whiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22134%22%20width%3D%22189%22%20x%3D%2234.63%22%20y%3D%22-85%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%227%22%20parent%3D%221%22%20style%3D%22image%3Bhtml%3D1%3Bimage%3Dimg%2Flib%2Fclip_art%2Fcomputers%2FServer_Rack_128x128.png%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2280%22%20width%3D%2280%22%20x%3D%22-148.5%22%20y%3D%22253%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%228%22%20parent%3D%221%22%20style%3D%22image%3Baspect%3Dfixed%3Bperimeter%3DellipsePerimeter%3Bhtml%3D1%3Balign%3Dcenter%3Bshadow%3D0%3Bdashed%3D0%3BspacingTop%3D3%3Bimage%3Dimg%2Flib%2Factive_directory%2Finternet_globe.svg%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2292%22%20width%3D%2292%22%20x%3D%2285.63%22%20y%3D%22-67%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%229%22%20parent%3D%221%22%20style%3D%22points%3D%5B%5B0.13%2C0.02%2C0%5D%2C%5B0.5%2C0%2C0%5D%2C%5B0.87%2C0.02%2C0%5D%2C%5B0.885%2C0.4%2C0%5D%2C%5B0.985%2C0.985%2C0%5D%2C%5B0.5%2C1%2C0%5D%2C%5B0.015%2C0.985%2C0%5D%2C%5B0.115%2C0.4%2C0%5D%5D%3BverticalLabelPosition%3Dbottom%3Bsketch%3D0%3Bhtml%3D1%3BverticalAlign%3Dtop%3Baspect%3Dfixed%3Balign%3Dcenter%3BpointerEvents%3D1%3Bshape%3Dmxgraph.cisco19.secure_endpoints%3BfillColor%3D%23005073%3BstrokeColor%3Dnone%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2278%22%20width%3D%22111.43%22%20x%3D%22306.03999999999996%22%20y%3D%22273%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2210%22%20parent%3D%221%22%20style%3D%22image%3Bhtml%3D1%3Bimage%3Dimg%2Flib%2Fclip_art%2Fnetworking%2FCloud_Rack_Private_128x128.png%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22108%22%20width%3D%22120%22%20x%3D%2240.63%22%20y%3D%22124%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2211%22%20edge%3D%221%22%20parent%3D%221%22%20source%3D%224%22%20style%3D%22edgeStyle%3Dnone%3Bcurved%3D1%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3BexitX%3D1%3BexitY%3D0%3BexitDx%3D0%3BexitDy%3D0%3BfontSize%3D12%3BstartSize%3D8%3BendSize%3D8%3B%22%20target%3D%224%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2212%22%20edge%3D%221%22%20parent%3D%221%22%20source%3D%224%22%20style%3D%22edgeStyle%3Dnone%3Bcurved%3D1%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3BexitX%3D1%3BexitY%3D0.5%3BexitDx%3D0%3BexitDy%3D0%3BfontSize%3D12%3BstartSize%3D8%3BendSize%3D8%3B%22%20target%3D%224%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2213%22%20parent%3D%221%22%20style%3D%22text%3BstrokeColor%3Dnone%3BfillColor%3Dnone%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D16%3B%22%20value%3D%22Internet%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2230%22%20width%3D%2260%22%20x%3D%2240.63%22%20y%3D%22-83%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2214%22%20parent%3D%221%22%20style%3D%22text%3BstrokeColor%3Dnone%3BfillColor%3Dnone%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D16%3B%22%20value%3D%22NAT%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2230%22%20width%3D%2260%22%20x%3D%22122%22%20y%3D%2256%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2215%22%20parent%3D%221%22%20style%3D%22text%3BstrokeColor%3Dnone%3BfillColor%3Dnone%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D16%3B%22%20value%3D%22VirtualBox%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2230%22%20width%3D%2260%22%20x%3D%22153%22%20y%3D%22121%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2216%22%20parent%3D%221%22%20style%3D%22text%3BstrokeColor%3Dnone%3BfillColor%3Dnone%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D16%3B%22%20value%3D%22Ubuntu%20Server%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2230%22%20width%3D%2260%22%20x%3D%22-199%22%20y%3D%22243%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2217%22%20parent%3D%221%22%20style%3D%22text%3BstrokeColor%3Dnone%3BfillColor%3Dnone%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D16%3B%22%20value%3D%22Windows%20Server%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2230%22%20width%3D%2260%22%20x%3D%22413%22%20y%3D%22245%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2218%22%20edge%3D%221%22%20parent%3D%221%22%20style%3D%22edgeStyle%3DsegmentEdgeStyle%3BendArrow%3Dclassic%3Bhtml%3D1%3Bcurved%3D0%3Brounded%3D0%3BendSize%3D8%3BstartSize%3D8%3BfontSize%3D12%3BentryX%3D0.5%3BentryY%3D0%3BentryDx%3D0%3BentryDy%3D0%3B%22%20target%3D%224%22%20value%3D%22%22%3E%3CmxGeometry%20height%3D%2250%22%20relative%3D%221%22%20width%3D%2250%22%20as%3D%22geometry%22%3E%3CmxPoint%20x%3D%2237%22%20y%3D%22165%22%20as%3D%22sourcePoint%22%2F%3E%3CmxPoint%20x%3D%22-13%22%20y%3D%22215%22%20as%3D%22targetPoint%22%2F%3E%3C%2FmxGeometry%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2219%22%20edge%3D%221%22%20parent%3D%221%22%20style%3D%22edgeStyle%3DsegmentEdgeStyle%3BendArrow%3Dclassic%3Bhtml%3D1%3Bcurved%3D0%3Brounded%3D0%3BendSize%3D8%3BstartSize%3D8%3BfontSize%3D12%3BentryX%3D0.5%3BentryY%3D0%3BentryDx%3D0%3BentryDy%3D0%3B%22%20target%3D%223%22%20value%3D%22%22%3E%3CmxGeometry%20height%3D%2250%22%20relative%3D%221%22%20width%3D%2250%22%20as%3D%22geometry%22%3E%3CmxPoint%20x%3D%22219.25000000000003%22%20y%3D%22164%22%20as%3D%22sourcePoint%22%2F%3E%3CmxPoint%20x%3D%22376.25%22%20y%3D%2270%22%20as%3D%22targetPoint%22%2F%3E%3C%2FmxGeometry%3E%3C%2FmxCell%3E%3C%2Froot%3E%3C%2FmxGraphModel%3E

**Architecture:**




---

## 🖥️ 2. Virtual Machine Specifications

### **Ubuntu SIEM VM**
- **OS:** Ubuntu Server 22.04 LTS  
- **RAM:** 4 GB  
- **CPU:** 2 vCPUs  
- **Disk:** 40 GB  
- **Network:**
  - NAT (Internet access)
  - Host-only (Internal lab)
- **Roles:**
  - SIEM (ELK Stack)
  - Log processing (Filebeat/Logstash)
  - Future SOAR/EDR integrations

---

### **Windows 10 Endpoint VM**
- **OS:** Windows 10 Pro 22H2  
- **RAM:** 4 GB  
- **CPU:** 2 vCPUs  
- **Disk:** 50 GB
- **Network:**
  - NAT
  - Host-only
- **Roles:**
  - Sysmon telemetry
  - Winlogbeat/Filebeat agent
  - Attack simulation using TryHackMe labs

---

## 🧩 3. OS & Software Versions

- **Ubuntu Server:** 22.04.4 LTS  
- **Windows 10 Pro:** Version 22H2  
- **VirtualBox:** 7.x  

---

## 🎯 4. Goal of the Lab

The purpose of this lab is to build a complete cybersecurity monitoring environment that covers:

- SIEM integration (Elastic, Security Onion)
- Endpoint telemetry (Sysmon, Beats)
- EDR/XDR deployment
- SOAR orchestration
- Firewall setup and log forwarding
- Incident detection & attack simulation
- Documentation for professional Security Engineering/Integration roles

The ultimate goal is to understand **how security solutions integrate together** and produce a real portfolio for cybersecurity job applications.

---
