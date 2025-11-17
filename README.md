# Exercise 12: Automate an Unattended Robot using Orchestrator

## Aim
Automate an **unattended robot process** using **UiPath Orchestrator**[cite: 329].

## Procedure

### 1. Create a New Project
1.  Open UiPath Studio.
2.  Click on **New Project > Process**.
3.  Name the project: `UnattendedAutomation`.
4.  Choose a location and click **Create**.

### 2. Publish the Process
1.  After creating your workflow, click on the **Publish** button in UiPath Studio.
2.  Select **Orchestrator** as the destination and click **Publish**.

### 3. Connect to Orchestrator
1.  Open **UiPath Assistant**.
2.  Connect to your Orchestrator instance using your Orchestrator URL and machine key.

### 4. Create a Robot in Orchestrator
1.  In Orchestrator, go to the **Robots** section.
2.  Create a new **Unattended Robot**.
3.  Assign the robot to an environment in Orchestrator.

### 5. Schedule the Robot
1.  In Orchestrator, go to **Schedules**.
2.  Create a schedule and assign it to the robot.

### 6. Run the Robot
1.  Once scheduled, the robot will execute the process **automatically** based on the schedule you set.


