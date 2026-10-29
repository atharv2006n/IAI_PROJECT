# AI Sales Report Analyzer

## Project Description
AI Sales Report Analyzer is an AI-powered project that automates sales data analysis using n8n, Google Sheets, an AI Agent, and Gmail. It helps users understand sales performance and generate reports with less manual effort.

## Objectives
- Automate sales data analysis.
- Generate meaningful sales insights.
- Reduce manual work and save time.
- Display reports through a chat interface.
- Send sales reports through Gmail.

## Technologies Used
- **n8n:** Workflow automation
- **OpenAI Chat Model:** AI-based analysis
- **AI Agent:** Processes sales data and generates insights
- **Google Sheets:** Stores and provides sales data
- **Gmail:** Sends generated reports

## Workflow Process
1. The user submits a Google Sheets URL through the chat interface.
2. The n8n Chat Trigger receives the request.
3. The Google Sheets tool retrieves the available sales data.
4. The AI Agent analyzes the data using the OpenAI Chat Model.
5. The analysis is displayed in the chat interface.
6. Gmail sends the generated sales report.

## Features
- Chat-based interaction
- Automated sales data analysis
- Sales performance summaries
- AI-generated insights
- Automated email reporting

## Requirements
- Internet connection
- n8n account
- OpenAI API credentials
- Google account with access to the spreadsheet
- Gmail credentials connected to n8n

## How to Use
1. Open the project's chat interface.
2. Enter a valid Google Sheets URL.
3. Submit the request for sales analysis.
4. View the generated analysis in chat.
5. Check Gmail for the sales report.

## Future Scope
- Generate PDF reports.
- Add charts and graphs.
- Support Excel and CSV files.
- Provide advanced sales trend analysis.

## References
- n8n Documentation: https://docs.n8n.io/
- OpenAI Documentation: https://platform.openai.com/docs/
- Google Sheets API: https://developers.google.com/sheets/api
- Gmail API: https://developers.google.com/gmail/api
