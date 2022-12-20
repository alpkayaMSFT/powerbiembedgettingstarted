# powerbiembedgettingstarted

Embed a power bi report in a simple web app written in .NET core

Environment set up
1.	You will need to have Admin rights to your PBI tenant. Turn on the service principal option in Power BI Tenant settings
 
2.	Register an application in Azure Portal - capture Azure AD application with client ID, tenant ID, and client secret available

3.	Add application user from previous step (Azure AD application) added as a Member in a Power BI workspace

4.	In Azure Portal - Create an Power BI embed capacity.  Ensure Power BI workspace running on a Power BI Embedded/Premium capacity

5.	Workspace ID of the PBI workspace mentioned in point
 
6.	Report ID of a sample report published in the PBI workspace 
 
7.	Dataset ID of the PBI report 
 
8.	.NET Core 3.1 installed on your computer
9.	Visual Studio 2017 and above (VS) installed on your computer. For VS Code, please refer to steps in Appendix
10.	Basic understanding of how RLS works in PBI service report

