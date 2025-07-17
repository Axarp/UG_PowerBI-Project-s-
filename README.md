# Home Loan Analytics Dashboard – Power BI

This repository showcases an interactive **Power BI dashboard** developed for analyzing **Home Loan disbursement performance** across different branches and channels.

## Objective

To build a fully functional Power BI report that helps business stakeholders answer key questions such as:

- Where is the highest volume of loans applied and disbursed?
- Which channels contribute the most to loan distribution?
- What is the recovery percentage across regions?
- How do trends change over time?

### 🔍 Data Modelling
- Applied Power Query transformations
- Created **calculated columns** (`Applied Loan Amount > 10L`)
- Built **calculated tables** for target-based date comparisons
- Added **DAX measures** for:
  - `SUM(Applied Loan Amount)`
  - `SUM(Sanction Amount)`
  - `SUM(Disbursed Amount)`
  - `SUM(Recovered Amount)`

### 📊 Visuals & Pages
- Loan funnel: From application to recovery
- Monthly trends (line chart)
- Channel distribution (pie chart)
- Top product analysis (bar chart)
- Branch-wise AGC map for spatial insights
- AI visuals like:
  - **Decomposition Tree**
  - **Q&A Visual**
- Interactive **Bookmarks** for toggling insights on Decomposition Tree & Q&A Visual

## 🌐 Publishing & Sharing
- Report published to **Power BI Service Workspace**
- Created App Called UpGrad
- Set up **Scheduled Refresh** for real-time data sync

[First report](https://github.com/user-attachments/assets/ac1b1075-8976-4101-a8ac-e3ad338e5d7c)


