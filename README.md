💻 Percruit Platform Test Coverage Project

🎯 Objective

To extend Percruit’s automated test coverage by targeting the most frequently used student paths within the platform, validating both successful flows and failure cases. The project aims to safeguard the student experience and strengthen the development team’s deployment confidence by providing a reliable automated safety net that supports faster iteration and higher platform stability.

💡 Skills Learned

• Exploratory testing  
• Automated testing with Playwright  
• Writing test cases in Gherkin/Cucumber  
• Bug reporting and tracking in JIRA  
• Debugging in Visual Studio Code  

🔧 Tools Used 

• Visual Studio Code  
• GitHub  
• Playwright  
• JIRA  

⚙️ Testing Approach

• Conducted exploratory testing on core student and mentor workflows to identify edge cases and potential issues  
• Developed automated tests using Playwright for critical user flows  
• Wrote structured test cases in Gherkin for Cucumber  
• Logged and tracked bugs in JIRA  
• Debugged test failures and workflow issues using Visual Studio Code  

Steps / QA Process

🕵️ Exploratory Testing 

Explored key student and mentor workflows to identify potential issues and edge cases.

Focused on high-traffic flows, such as login, mentor availability, and the student job board.

Documented any unexpected behavior to create Jira tickets for tracking.

🤖 Automated Testing

Developed automated tests using Playwright for critical user flows to prevent regressions.

Wrote structured test cases in Gherkin for Cucumber to standardize testing scenarios.

Validated both successful and failure scenarios to ensure platform reliability.

🐞Bug Reporting and Tracking

Logged bugs in Jira with clear steps to reproduce, expected results, and observed results.

Examples of issues discovered:

• PER-310: Mentor Account – Blocked dates in date-specific overrides are lost after leaving availability settings
• PER-311: Login – Does not enforce maximum length for email and password fields
• PER-312: Login – Shows unclear email validation message for valid or short emails
• PER-313: System allows users to create overlapping time slots (Mentor Account)
• PER-314: Student Job Board – Job list persists after clearing filters
• PER-315: Student Job Board – Applied jobs not indicated on listings
• PER-316: Student Account – AI Buddle: Cannot create resume without guidance on missing fields

🛠️ Debugging and Verification

Used Visual Studio Code to debug test failures and verify fixes.

Re-ran automated tests and retested workflows after bug resolution to ensure stability.
