<img style="float: right;" src="./graphics/solutions-microsoft-logo-small.png">

# SQL Server and Azure SQL Labs and Workshops
## (https://aka.ms/sqlworkshops)

This [site](https://lab.github.com/githubtraining/introduction-to-github) is a map of learning content produced by and curated by the SQL Server and Azure SQL teams in Microsoft Engineering. These materials are meant to be instructor-led, but you can work through the materials on a test system on your own if desired. Labs are shorter and Workshops are more comprehensive. You can view all materials directly in this interface, or you can [view the raw github site for this content here](https://github.com/Microsoft/sqlworkshops). 

*See the license information at the bottom of this README.md file*

Find a problem? Spot a bug? [Post an issue here](https://github.com/Microsoft/sqlworkshops/issues), include the page URL, and we'll try and fix it.

## SQL Server Data Platform

- [Workshop: SQL Server Ground to Cloud](https://github.com/microsoft/sqlworkshops/tree/master/SQLGroundToCloud)
- [Workshop: SQL Server 2019 on OpenShift](https://github.com/microsoft/sqlworkshops-sqlonopenshift)
- [Workshop: SQL Server 2019](https://github.com/microsoft/sqlworkshops-sql2019workshop)
- [Workshop: SQL Server 2019 Big Data Clusters - Architecture](https://github.com/Microsoft/sqlworkshops-bdc)
- [Workshop: Kubernetes - From Bare Metal to SQL Server Big Data Clusters](https://github.com/microsoft/sqlworkshops-k8stobdc)
- [Lab: SQL Server 2019](https://github.com/microsoft/sqlworkshops-sql2019lab) 


## Azure SQL 

- [Workshop: SQL Server Ground to Cloud](https://github.com/microsoft/sqlworkshops/tree/master/SQLGroundToCloud)
- [Workshop: Azure SQL [COMING SOON]](https://github.com/IrishSQL/MicrosoftAzureSQL/blob/master/ModernizingDatabase_withAzure_PRECON.pdf)
- [Lab: Microsoft Azure SQL Labs](https://github.com/microsoft/sqlworkshops/tree/master/AzureSQLLabs)

## Programming

- [Lab: Python for Data Professionals](https://github.com/Microsoft/sqlworkshops/tree/master/PythonForDataProfessionals)
- [Workshop: R for Data Professionals](https://github.com/Microsoft/sqlworkshops/tree/master/RForDataProfessionals)

## Machine Learning and AI

- [Workshop: Machine Learning with SQL Server](https://github.com/Microsoft/sqlworkshops/tree/master/SQLServerMLServices)

# Presentation Materials, Code, and References

- [Presentation Materials - *(PowerPoint Decks, etc.)*](https://github.com/Microsoft/sqlworkshops/tree/master/References/README.MD#decks)
- [Example Code](https://github.com/Microsoft/sqlworkshops/tree/master/References/README.MD#code)
- [References and Tools from the Microsoft SQL Team](https://github.com/Microsoft/sqlworkshops/tree/master/References/README.MD#links)

## Learning how to self-learn

Many of these topics are quite deep, and take time to fully absorb. There are several phases of learning:

 - Awareness (You learn a technology exists and what it is used for)
 - Understanding (You learn the components, processes and steps of a technology)
 - Practice (You can perform the steps with the technology by following a process to complete a task)
 - Mastery (You are able to explain the technology to others)


These courses are designed for you to repeat many times to move through these phases. Before you embark on any of these, you may want to complete a "Learning how to Learn" course. <a href="https://www.nytimes.com/2017/08/04/education/edlife/learning-how-to-learn-barbara-oakley.html" target="_blank">You can find more information on that here</a>. 

*Disclaimer*

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### Download all Workshops as a zip file

The entire repository can be [downloaded as a single ZIP file here](https://github.com/Microsoft/sqlworkshops/archive/master.zip). 


### Clone all Workshops using git

You can [clone the entire repository using `git` here](https://github.com/Microsoft/sqlworkshops.git). 

### Get only one Workshop
You can follow the steps below to clone individual files from a git repo using a git client. 

Example:

<pre>
git clone -n https://github.com/Microsoft/sqlworkshops
cd sqlworkshops
git config core.sparsecheckout true
echo workshopname/*| out-file -append -encoding ascii .git/info/sparse-checkout
git checkout
</pre>

For more information about `sparse checkout please` visit [this](https://stackoverflow.com/questions/23289006/on-windows-git-error-sparse-checkout-leaves-no-entry-on-the-working-directory) stackoverflow thread.

### Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### License
Microsoft and any contributors grant you a license to the Microsoft documentation and other content in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode), see [the LICENSE file](https://github.com/MicrosoftDocs/mslearn-tailspin-spacegame-web/blob/master/LICENSE), and grant you a license to any code in the repository under [the MIT License](https://opensource.org/licenses/MIT), see the [LICENSE-CODE file](https://github.com/MicrosoftDocs/mslearn-tailspin-spacegame-web/blob/master/LICENSE-CODE).

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.

### Questions
Email questions to: sqlserversamples@microsoft.com.
