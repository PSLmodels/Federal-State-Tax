# Federal-State Tax Project

The Federal-State Tax Project develops open source tools for analyzing the impacts of federal tax reforms by state. These impacts vary widely across states due to differences in tax-relevant factors such as the income distribution; relative importance of wage, business, and retirement income; and family size and structure. Understanding the state-specific impacts of a reform is important to state and federal policymakers, among others.

+----------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------+
| Recent project news                                                                                                                          | Type                                       |
+==============================================================================================================================================+============================================+
| [Repealing the SALT Cap - State by State Impact](https://www.aei.org/research-products/report/repealing-the-salt-cap-state-by-state-impact/) | Publication (AEI & Rockefeller College)    |
+----------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------+
| [Constructing Tax Data for the 50 States](https://blog.pslmodels.org/demo-day-14-constructing-tax-data-for-the-50-states)                    | Presentation (PSL Demo Days)               |
+----------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------+
| Detailed 50-state tables on SALT-cap repeal \[LINK TK\]                                                                                      | Resource for states, paid (PSL Foundation) |
+----------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------+

## Project Goals

-   Construct state weights for the Tax-Calculator-ready Public Use File (puf.csv), such that:

    -   Weighted summaries by state are consistent with published or forecasted summary data for the state, and;
    -   State weights on each record sum to the record's national weight, ensuring that the state result equals the national result.

-   Produce 50-state distributional tables, rankings, and other useful results for important policy proposals and legislation.

## Tools under development

-   Weighting repo - A python repo with tools for microdata files to (1) construct initial weights or reweight existing weights so that the microdata file, when weighted, hits or approximates targeted values, and (2) apportion national weights to geographic areas in a manner that hits or approximates targeted values for each region while ensuring that geographic weights for each record sum to the record's national weights.
-   puf_analysis repo - A python repo with tools and programs that construct state weights for the microdata file puf.csv.

## Other essential tools this project uses

-   Tax-Calculator -- We use the Tax-Calculator microsimulation model for estimating federal individual income and payroll tax liabilities under baseline and reform policy scenarios.
-   Tax Data -- We use TaxData to construct an initial set of national microdata for use with Tax-Calculator, which we then modify and augment.

## Other resources this project offers

-   Repealing the SALT Cap: State by State Impact -- [Report](https://www.aei.org/research-products/report/repealing-the-salt-cap-state-by-state-impact/) using the tools developed by the project to estimate the impact of repealing the TCJA's SALT cap in 2021 on the 50 states.
-   Constructing Tax Data for the 50 States -- [Technical presentation](https://blog.pslmodels.org/demo-day-14-constructing-tax-data-for-the-50-states) for Policy Simulation Library's Demo Days series on how to produce a state-weighted data file.
-   Detailed state by state tables on the impact of SALT cap repeal -- Subscription for in-depth data access. \[LINK TK\]

## Contacts

**Donald Boyd** Co-director, State and Local Government Finance Project, Rockefeller College of Public Affairs and Policy at the University at Albany; Principal, Boyd Research, LLC [linkedin](https://www.linkedin.com/in/donald-boyd-2443276b/) [donboyd5\@gmail.com](mailto:donboyd5@gmail.com){.email}

**Matt Jensen** Director, Open Source Policy Center, American Enterprise Institute [matthjensen\@gmail.com](mailto:matthjensen@gmail.com){.email}
