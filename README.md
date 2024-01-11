# NDC Security 2024 - Reviewing NuGet Packages security easily using OpenSSF Scorecard

Several studies shown that round 80% of our applications consist of other people's code because why would you re-create something that's already made by someone else? But with using a NuGet Package that is developed by others, we also put a lot of trust in it, which might result in bigger security problems later. 

Of course, it's always a good idea to get updates of libraries in case of a bug fix related to a functional and/or security issue found. But will that be enough? What about packages that have malicious code inside? Even related to your own supply-chain security, any problem in the package its supply-chain implicitly means your supply-chain is compromised as well!

Would it not be nice if there is a better way to review NuGet packages for security? An easier way to perform an assessment based on certain aspects of the package that will tell you more about the package its software security. With the introduction of Scorecards the Open Source Security Foundation (OpenSSF) exactly tries to achieve that. You could consider a Scorecard being the equivalent of a nutrition labels put on food you buy in a supermarket. It will allow you to see what's inside and determine if you want to eat it or not.

In this session we start out with different area's covered by of OpenSSF Scorecards, like how well it's maintained, does the build have dangerous workflows, and does the project use other security tools to check for problems? We're also going to identify additional area's for NuGet packages in which we could add additional information related to reproducibility, insights on what .NET APIs are used, and security review of the codebase. All combined will give us the ability to assess a NuGet package its security posture more easily and improve our own application security.