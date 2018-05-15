* How to configure environment within Web.config for IIS?
  
  Set the related value of ASPNETCORE_ENVIRONMENT property in Project.user.csproj so the relevant Web.config file will be available in build.
    - <ASPNETCORE_ENVIRONMENT>**Production**</ASPNETCORE_ENVIRONMENT>
    - <ASPNETCORE_ENVIRONMENT>**Development**</ASPNETCORE_ENVIRONMENT>
