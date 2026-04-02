Enforcing Data Quality via UI Policies in ServiceNow
​Overview
​This project demonstrates the implementation of a UI Policy on the Incident table to enhance data integrity and process control.
​
Key Features
​Field Behavior Control: Automatically makes the Priority field Read-Only when an incident state transitions to 'In Progress'.
​Deployment Best Practices: All configurations, including UI Policies and related actions, are captured in a single Update Set for controlled migration.
​Instance Migration: Demonstrated the complete lifecycle of configuration management by exporting the Update Set as XML, importing it into a target instance, and committing the changes.

​Technical Implementation
​Target Table: Incident [incident]
​Condition: State is In Progress
​UI Policy Action: Sets Priority field to Read-Only = True.

​How to Verify (Testing Steps)
​Navigate to the Incident table in ServiceNow.
​Open an existing incident or create a new one.
​Change the State to 'In Progress'.
​Observe that the Priority field becomes grayed out and cannot be edited.
​
​Skills Demonstrated
​ServiceNow Administration
​UI Policies & UI Actions
​Update Set Management (Export/Import/Commit)
​Configuration Management Best Practices
