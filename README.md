# Grafana Lab Report

## Objective
The goal of this lab was to install Grafana, set up a dashboard, and visualize performance metrics. Due to college restrictions on Azure VM creation, I completed the lab locally on Ubuntu.

## Steps

### Step 1: Install Grafana
- Updated and upgraded Ubuntu.
- Installed Grafana using the official APT repository.
- Started and enabled the Grafana service.

![3](https://github.com/user-attachments/assets/a5e0024f-7d7b-4179-a4d4-adfee32fef5f)


### Step 2: Allow Port 3000

![4](https://github.com/user-attachments/assets/105cc7b1-4d47-45cc-8fb1-cc130931d3d8)



### Step 3: Access Grafana
- Accessed Grafana at `http://localhost:3000`.
- Logged in with default credentials (`admin/admin`).

![image](https://github.com/user-attachments/assets/a71caf27-4e83-41dc-8422-3d871ffd6668)


![5](https://github.com/user-attachments/assets/d4b5354b-9d4f-4a44-b8ac-bd6b944fcb05)

### Step 4: Create a Dashboard
- Created a new dashboard.
- Added a panel using the **TestData DB** data source.
- Visualized dummy metrics (e.g., CPU usage).


![6](https://github.com/user-attachments/assets/45966b9e-4253-4751-ad7f-a6c3752bfeb8)

![7](https://github.com/user-attachments/assets/5315b801-8bd7-4b29-8128-e92cfef83f8d)


## Challenges
- Initially, I forgot my sudo password but reset it using the root user.
- I faced issues with Azure VM creation due to college policies, so I completed the lab locally.

## Conclusion
I successfully installed Grafana, created a dashboard, and visualized metrics locally. This lab helped me understand Grafana's capabilities and how to set it up for monitoring.
