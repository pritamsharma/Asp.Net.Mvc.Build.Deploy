# Asp.Net.Mvc.Build.Deploy
 Build and deploy ASP.NET MVC project. .NET framework 4.8.

Pre-requisite:
1. Jenkins is installed and has atleaset two nodes. We will use one to build the solution. The other to deploy the solution.
    1.1. Build Node : Should have Visual Studio installed.
    1.2. Deploy Node: Should have IIS.
2. Shared folder to copy build from Build Node to Deployment Node.
3. Following plugins to be added in Build Node.
    1. Git Plugin
    2. Pipeline Utility Steps
    3. MSBuild