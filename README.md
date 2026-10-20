[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=17&pause=1000&color=53F7AF&repeat=false&width=435&lines=AI+search+Competitor+Pricing+%26+Monitoring)](https://git.io/typing-svg)
## Tech Stack & Badges
![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71?logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-AI%20Analysis-412991?logo=openai&logoColor=white)
![Decodo](https://img.shields.io/badge/Decodo-Web%20Data%20API-6F42C1)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Data%20Storage-34A853?logo=googlesheets&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-Email%20Reports-EA4335?logo=gmail&logoColor=white)
![Status](https://img.shields.io/badge/Status-Prototype-blue)
## Project Description
AI Competitor Pricing Monitoring is an n8n automation prototype that checks competitor pricing pages on a schedule. It uses Decodo to collect web data and OpenAI to compare current prices with previous pricing stored in Google Sheets. The workflow saves the comparison results and sends a consolidated email report through Gmail, helping users track pricing changes with less manual work.
**Schedule → read Google Sheets → collect pricing → AI comparison → update Sheets → generate report → Gmail**
<table>
  <tr>
    <th width="50%">Table of AI price comparison</th>
    <th width="50%">Received report in mail</th>
  </tr>
  <tr>
    <td valign="top">
      <img src="Image Oct 20, 2026, 07_02_10 PM.png" alt="Table of AI price comparison" width="100%">
    </td>
    <td valign="top">
      <img src="Image Oct 20, 2026, 07_01_48 PM.png" alt="Pricing report received in Gmail" width="100%">
    </td>
  </tr>
</table>

> The first run establishes a pricing baseline, and subsequent runs compare current pricing with previously stored data and email a summary of the results. 
  
## Requirements
- An n8n account for workflow
- Decodo and OpenAI API for workflow AI agents
- Google account for Google Sheets
- Gmail access for reports

## Instalation
1. Download the [workflow JSON](AI_Searchtool_price_comp_workflow.json) and import it into n8n.
2. Import Workflow in n8n
3. Configure the OpenAI, Decodo, Google Sheets, and Gmail credentials in n8n
4. create the columns your workflow uses, such as Competitor Name, URL, Previous Pricing, Last updated, and Differences - Summary
5. select the spreadsheet, set the report recipient, and choose the monitoring schedule

> [!WARNING]
> n8n, OpenAI, and Decodo usage may involve costs.
## Usage

➡️ **Add competitors:** Add competitor names and pricing-page URLs to the spreadsheet.

➡️ **Run a manual check:** Click **Execute workflow** in n8n.

➡️ **Review the results:** Review the pricing information and comparison results in Google Sheets.

➡️ **Check your email:** Check Gmail for the consolidated report.

➡️ **Enable scheduled monitoring:** Publish or activate the workflow to run it on the configured schedule.


Last tested: 20.10.2026
