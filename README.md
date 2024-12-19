ReactJS Frontend Task
Project Overview
This project demonstrates the creation of a simple HTML page using ReactJS. The page allows users to edit table or div content dynamically, and the edited data is prepared for posting to an API.

Features
Simple HTML + ReactJS Setup:
Uses React and ReactDOM libraries directly via <script> tags from a CDN.
Editable Fields:
All columns in the table (or div structure) are editable.
Data Handling:
On editing, the updated data is prepared and ready to post to an API for database storage.
No Backend Required:
This project focuses solely on the frontend functionality.
Technologies Used
ReactJS (via CDN)
HTML5
JavaScript
Getting Started
How to Run the Project
Clone the repository:
bash
git clone https://github.com/OmChauhan16/VyqdaTask3
Open the index.html file in your browser.
Implementation Details
1. ReactJS Integration
Integrated ReactJS directly into an HTML page using CDN links:
html
<script src="https://unpkg.com/react@18/umd/react.development.js" crossorigin></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js" crossorigin></script>
Followed the official React documentation for this setup.
2. Editable Content
Created a table (or div layout) where all columns are editable.
Used React state to manage and track edited values dynamically.
3. API Data Preparation
Implemented logic to prepare the edited data for API posting in the correct format.
How It Works
Editable Table or Div Layout:
Users can click on any cell or field to edit the content.
Data Handling:
Edited data is stored in a React state object.
Data is displayed dynamically on the page.
API Readiness:
The updated data is displayed in JSON format on the console, ready to be posted to any API.

Demo
<img width="960" alt="Editable Column" src="https://github.com/user-attachments/assets/dca3c1e1-8633-4f1f-b7bb-02e07078cb1c" />
