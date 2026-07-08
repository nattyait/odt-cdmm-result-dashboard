# Sample Prompts for odt-cdmm-result-dashboard Skill

## Example 1: Mode A (Single Team)

```
I want to analyze a single team's CDMM assessment.

Organization: 7Solutions
Mode: A (Single Team)
Team Name: Backend Platform Team
Assessment URL: https://cdmm.odt.co.th/group-assessment/abc123def456/report

Please create a CDMM dashboard with fact-based analysis of this team's maturity level.
```

## Example 2: Mode B (Multiple Teams)

```
I need to compare CDMM maturity across our organization.

Organization: Global Tech Corp
Dashboard Title: Global Tech Corp CDMM Assessment Q3 2026
Mode: B (Multiple Teams)

Teams:
1. Frontend Platform Team | https://cdmm.odt.co.th/group-assessment/front001/report
2. Backend Platform Team | https://cdmm.odt.co.th/group-assessment/back002/report
3. Infrastructure Team | https://cdmm.odt.co.th/group-assessment/infra003/report
4. Quality Assurance Team | https://cdmm.odt.co.th/group-assessment/qa004/report

Create a comparative dashboard with all teams and an overview tab.
```

## Example 3: Mode C (Add to Existing)

```
I need to add a new team to our existing CDMM dashboard.

Organization: 7Solutions
Mode: C (Add to Existing)
Existing Dashboard: 7Solutions_CDMM_Complete_Dashboard.html
New Team Name: Security Team
New Assessment URL: https://cdmm.odt.co.th/group-assessment/security789/report

Add this team's analysis to the existing dashboard.
```

## Example 4: Mode B with Executive Summary

```
I need an executive-level CDMM dashboard for our leadership team.

Organization: Digital Financial Services
Dashboard Title: DFS CDMM Maturity Report 2026
Mode: B (Multiple Teams)

Teams:
1. Payment Systems | https://cdmm.odt.co.th/group-assessment/pay001/report
2. Risk Management | https://cdmm.odt.co.th/group-assessment/risk002/report
3. Customer Platform | https://cdmm.odt.co.th/group-assessment/cust003/report

Include:
- Executive summary of key findings
- Observable data with precise counts
- P1/P2/P3 priority recommendations with ODT training courses
- Fact-based analysis without assumptions
```

## Key Points

- Always provide the exact assessment URL format: `https://cdmm.odt.co.th/group-assessment/[ID]/report`
- Mode B requires "Dashboard Title"
- Mode C requires the existing dashboard filename
- Tab names will use actual team names from your input
- All recommendations will reference courses from https://training.odt.co.th/
- Analysis is strictly fact-based with observable data counts

See SKILL.md for complete documentation.
