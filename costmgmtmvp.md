# Cloud Cost Management Discipline Template
The following is a SAMPLE ONLY for reference. Follow the guidance in the CAF for developing your organization's Cost Management Discipline template.

## Policy Statements
- <b>Future Proof:</b> To ensure current adoption efforts can be effectively governed in the future, all deployments must adhere to the best practices outlined in the [Actionable Journeys section of CAF.](https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/governance/journeys/overview)
- <b>Budget Overrun:</b> Any assets deployed to the cloud must be aligned to a billing unit, with approved budget, and a mechanism for enforcing budgetary limits.
- <b>Overprovisioned Assets:</b> All deployed assets must be registered with a solution that can monitor usage and report on any over provisioned resources.

## Business Risks

| <b>Risk</b> | <b>Description</b> | <b>Indicators</b> | <b>Resolution</b> |
|---------|-----------------|-------------------|----------------|
| Future Proof | Lack of standards will hinder future governance. | Current | Policy statements enforced |
| Budget Overrun | Budget overruns are a potential risk in the future. | Next Major Release | Policy statements drafted but not enforced |
| Over Allocation | Paying too much for unused resources is a potential future risk. |Monthly spend exceeds $1M USD | Policy statements drafted but not enforced |

## Metrics & Indicators
### Metrics
This governance discipline attempts to govern and improve the following key metrics.
- Annual Spend: The total annual cost for services provided by a cloud provider.
- Monthly Spend: The total monthly cost for services provided by a cloud provider.
- Forecast vs Actuals Ratio: The ratio comparing forecasted and actual spend (Monthly or Annual).
- Pace of adoption (MOM) Ratio: The percentage of the delta in cloud costs from month to month.

### Indicators
The following indicators will trigger changes in policy statements based on changes in metrics and other conditions.
- Current: Current state of metrics. Any policy statements listed as current should be actively enforced.
- Release based indicator: Upon the next major release, there will be a sufficient risk of budget overrun to warrant budget controls.
- Monthly spend: When monthly spend exceeds $1M USD, new policy statements will go into effect to better control spending.

## Compliance Process

### Planning, Review, & Reporting
- <i>Initial risk assessment and planning:</i> As part of initial adoption of the Cost Management discipline, the Cloud Governance team will identify core business risks and tolerances related to cloud costs. The team will use This information to discuss budget and cost-related risks with members of business teams and to develop a baseline set of policies for mitigating these risks to establish an initial governance strategy.
- <i>Deployment planning:</i> Before any asset is deployed, the Cloud Governance team will establish a forecasted budget based on expected cloud allocation. As part of this process, the team will document ownership and accounting information for the deployment.
- <i>Annual planning:</i> On an annual basis, the Cloud Governance team will perform a roll-up analysis on all deployed and to-be-deployed assets. The team will align budgets with business units, departments, teams, and other appropriate divisions to empower self-service adoption. This process will ensure that the leader of each billing unit is aware of the budget and how to track spending.<br>
This planning process will also decide on pre-commitments or pre-purchases of cloud services to maximize discounting. These decisions should also align annual budgeting with the cloud vendor's fiscal year to further capitalize on year-end discount options.
- <i>Quarterly planning:</i> On a quarterly basis, the Cloud Governance team will review budgets with each billing unit leader to align forecast and actual spending. If there are changes to the plan or unexpected spending patterns, billing unit leaders will align and reallocate their budget.<br>
The Cloud Governance team will also evaluate the team's current membership for knowledge gaps related to current or future business plans. The team will invite relevant staff and workload owners to participate in reviews and planning as either temporary advisors or permanent members of the team.
- <i>Education and Training:</i> On a bi-monthly basis, the Cloud Governance team will offer training sessions to make sure business and IT staff are up-to-date on the latest Cost Management policy requirements. As part of this process the team will review and update all documentation, guidance, or other training assets to ensure they are in sync with the latest corporate policy statements.
- <i>Monthly reporting:</i> On a monthly basis, the Cloud Governance team will generate actual spending against forecast, and billing leaders notified of any unexpected deviations.

### Ongoing monitoring
IT teams will implement automated systems for monitoring cloud spending and usage for unplanned deviations from expected costs. They will also establish reporting and alerting systems to ensure prompt detection and mitigation of potential policy violations.

### Violation Triggers & Enforcement
- <i>Monthly Budget Deviations:</i> Any deviations in monthly spend exceeding 20% Forecast vs Actuals ratio will be discussed with billing unit leader. Resolutions or changes in forecast will be recorded.
- <i>Pace of Adoption:</i> Any deviation at a subscription level exceeding 20% will trigger a review with billing unit leader. Resolutions or changes in forecast will be recorded.
 
