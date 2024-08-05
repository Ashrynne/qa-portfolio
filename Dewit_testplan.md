Test Plan for "Dewit" To-Do List Web App
1. Introduction
The "Dewit" To-Do List web app is a simple application for managing tasks. It features a Pip-Boy-themed UI and uses localStorage for data persistence. This test plan outlines the testing strategy for the app, ensuring that all functionalities work as expected and the UI is consistent with the design specifications.

2. Objectives
Verify that the core functionality (adding, completing, deleting tasks) works correctly.
Ensure data persistence using localStorage.
Check the UI/UX consistency and responsiveness.
Validate the handling of edge cases and errors.
3. Scope
The test plan covers functional testing, UI testing, and regression testing. It includes both positive and negative test cases.

4. Test Cases
4.1. Functional Testing

Adding Tasks

TC1: Add a task with standard text.
TC2: Add a task with special characters.
TC3: Add a task with a very long text and verify multiline handling.
Completing Tasks

TC4: Mark a task as completed and verify the strikethrough styling.
TC5: Unmark a completed task and verify the removal of strikethrough styling.
Deleting Tasks

TC6: Delete a single task and verify the task is removed.
TC7: Delete multiple tasks and ensure only the selected tasks are removed.
Persistence

TC8: Verify tasks are saved in localStorage.
TC9: Refresh the page and verify that tasks persist.
TC10: Verify that completed status persists across sessions.
4.2. UI Testing

General Layout

TC11: Ensure the header image and title "Dewit" are correctly centered.
TC12: Verify that the task input field and button are centered.
Task Item Layout

TC13: Verify that task text, checkbox, and delete button are aligned horizontally.
TC14: Check the appearance of the checkbox and delete button matches the Fallout Pip-Boy theme.
Responsiveness

TC15: Test the layout on various screen sizes (mobile, tablet, desktop).
TC16: Ensure the app is usable and visually consistent on all supported devices.
4.3. Edge Cases and Error Handling

Empty Input

TC17: Attempt to add an empty task and ensure it is not added.
Input Field Focus

TC18: Verify the input field is focused on app load.
TC19: Check if pressing "Enter" adds a task when the input field is focused.
Task Overflow

TC20: Add a large number of tasks and verify the app handles them without performance issues.
4.4. Regression Testing

Feature Regression

TC21: Ensure that all previously tested features still function correctly after recent changes (removal of border change on task input focus, etc.).
Bug Fix Verification

TC22: Verify the fix for the issue where the delete button text gets a strikethrough.
TC23: Check the task input field is centered and the task text does not overlap with the delete button when long.
5. Environment
Browsers: Test on the latest versions of Chrome, Firefox, Safari, and Edge.
Devices: Test on both desktop and mobile devices (iOS and Android).
6. Out of Scope
Cross-browser testing on outdated or obscure browsers.
Performance testing beyond basic functionality.
7. Test Execution
Tester: The designated QA team member or developer.
Timeline: Estimated completion within one week.
Reporting: Document and report any bugs or issues found during testing.

