# Alert-Validation
# Module - Workload Protections

![image](https://github.com/Sismahil/Alert-Validation/assets/121772702/2e291835-8bc6-414c-81fe-b3f5d270d16f)

## Objectives
This exercise shows how to prioritize alerts along with information needed for quick investigation

### Exercise 1: Alert validation

Here let’s cover the new Alert Simulation, which should be out in the first week of December

1.	1.	Go to Microsoft Defender for Cloud, and click the Security Alerts in the sidebar.
2.	Create an alert simulation for VM:
    - On Security alerts page, click on **Sample alerts** button.
    - Select **Azure subscription 1**.
    - On the Workload Protections plans, keep only **Virtual Machines** selected.
    - Click on the **Create sample alerts** button to trigger the alert simulation for VMs.

![image](https://github.com/Sismahil/Alert-Validation/assets/121772702/c670924a-aa3e-45c0-bbcd-79b0601ac5b3)


3.	Sample alerts creation in progress, wait for the process to complete. You can track the progress by opening the notification center or on activity log (this process usually takes 2 minutes to complete)
4.	On the alerts page, you should now see 5 different sample events for a resource named `Sample-VM`. Each alert has the Sample alert banner next to it.

![image](https://github.com/Sismahil/Alert-Validation/assets/121772702/321add30-7d51-40ec-b640-9514995269b0)


5.	Click on the **Digital currency mining related behavior detected alert**.
6.	The details pane opens. Notice the alert properties at the top (severity, status, and time) along with the alerts description and affected resources. At the bottom part, you can see the kill chain intent of the alert based on the MITRE ATT&CK® framework. This specific alert is at the *Execution* phase.
7.	To explore the full details of the alert, click on **View full details**.
8.	Create an alert simulation for Key Vaults:
    - On Security alerts page, click on **Create sample alerts** button.
    - Select **Azure subscription 1**.
    - On the Workload Protections plans, keep only **Key Vaults** selected.
    - Click **Create sample alerts** button to trigger the alert simulation for Key Vaults.
9.	Sample alerts creating in progress, wait for the process to complete. You can track the progress by opening the notification center or on activity log (this process usually takes 2 minutes to complete)
10.	On the alerts page, you should now see 5 different sample events for a resource named `Sample-KV`. Each alert has the `Sample alert` banner next to it.
11.	Click on the **Access from a TOR exit node to a Key Vault** alert.
12.	Click on the **View full details** to see additional information related to the event.
13.	At the top menu, dismiss the alert by changing the status from Active to **Dismiss**.

> Note: You can choose to trigger sample alerts for additional Workload Protections plans.

