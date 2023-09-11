# DevOps
This is the main Repository for all material


Design Document

DevOps Dashboard Design Document

Introduction
The DevOps Dashboard is a hub for people using different DevOps tools. It will provide good UI and make it a streamlined system. There will be tools such as alerts, statistics, data visualization, and more.
Storyboard

This is a brief storyboard of the things I would like to incorporate into the dashboard. 
I want to build a lot of this using some WordPress making it a headless system
There will be a visual website for them to sign up on
There will also be the dashboard which is where all the diagnostics and users will interact for the majority of the time.
In the dashboard I want to have as many programs as I can to help the user, may this be the error notifications, uptime alerts, and more.
I will also have data visualization of the uptime, activity, etc. I want to see if this is a possible integration with something similar to Tableau

Functional Requirements
  1. DevOps Employee,
    I want a deployment manager to make sure that all things are deployed well and that I can see the status of them.

  2. DevOps Employee,
    I want to see real-time activity from tools that will inform me of errors, up-and-down time, and more. 
    This would be so I can make sure the systems are running well.

  3. DevOps Employee,
    I want to be aware if there is a sudden alert or necessity, this could be a notification.
    This would be so I can tend to them as soon as possible

  4. DevOps Employee,
    I want to have other technologies like Jenkins and Kubernetes so I can know that all activity is accurate and that the system is reliable.

  Elaboration:
    I am on the dashboard,
    When my deployment fails,
    Then I should receive an alert/notification.
    Given I have the integrated tech.
    When I click on the metrics tab,
    Then I should see a visual representation of all the key metrics.
    
    I am on the dashboard,
    When my deployment succeeded,
    Then I should see the status of it
    Given I have the integrated tech.
    When I click on the status tab,
    Then I should see a visual representation of all the uptimes and downtimes.
    
    I am on the dashboard,
    When my employer asks to see some credibility,
    Then I should see the navigate
    Given I have the integrated tech.
    When I click on the Jenkins tab,
    Then I should see a visual representation of the technologies Jenkins has integrated.

Class Diagram


Class Diagram Description
Dashboard: Represents the main hub, this is where users Interact with multiple different managers to fetch and display statistics and data.
Alert: Alerts and notifications to go to users when something has happened.
MetricsViewer: Gets and displays metrics from various monitoring tools.
IntegrationManager: Integrated with DevOps tools.

JSON Schema
{
    "alert": {
        "id": "string",
        "type": "string",
        "message": "string",
        "timestamp": "datetime"
    },
    "metric": {
        "id": "string",
        "name": "string",
        "value": "number",
        "unit": "string",
        "timestamp": "datetime"
    }
}

Scrum Roles and Responsibilities
Product Owner/Scrum Master/DevOps: Reesë Tuttle
Backend :Reesë Tuttle
UX/UI: Reesë Tuttle

Note: I do not have a group and have not been able to get anyone in a group. I have emailed about it, so as of right now I am still needing 3 to 5 others.

GitHub Project Link
https://github.com/ReeseBessUC/DevOps.git

Scrum/Kanban Board
https://github.com/users/ReeseBessUC/projects/1/views/2

Weekly Meeting Details
Platform: Microsoft Teams
Time: 8:00 PM every Tuesday
Link: Null

