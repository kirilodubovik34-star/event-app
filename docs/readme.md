# Event App

Mobile application for organizing events.

## Features

- Create events
- Manage participants

## Setup Instructions

1. Clone the repository: git clone https://github.com/kirilodubovik34-star/event-app.git
2. Open the event-app folder in Visual Studio Code.
3. Open src/index.html in a browser to see the start page.

## Remote Synchronization

Remote changes are downloaded with Fetch first (asynchronous, no merge), checked in the Graph view and only then applied with Pull.

## Project Structure

- src/index.html - start page of the application
- docs/readme.md - project documentation
- commits.txt - exported commit history

## Git Workflow in VS Code

1. Create a branch in the status bar (feature-style, feature-docs).
2. Stage files with + and commit with the Commit button.
3. Publish or Push the branch to GitHub.
4. Fetch, review incoming commits in the Graph, then Pull.
5. Merge branches and resolve conflicts in the Merge Editor.

Alternative path: revert to restore previous state. If a commit breaks the page, Revert Commit creates a new commit that undoes it without rewriting history.