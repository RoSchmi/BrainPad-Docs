# Docs

This is the repository for all of our docs.

To generate the docs locally:
* Clone/Fork the repo
* Open the command prompt in the documents' root folder ("Run as Administrator" may be necessary)
* Execute docfx --serve
* After executing the above command, a temporary webpage will appear to allow you to view the files in your browser fully rendered in HTML, for example http://localhost:8080.

To install DocFX, please review and download from the following site: https://dotnet.github.io/docfx/. From there, you can go to the [Getting Started](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html) page for instructions on how to install and you can go to [Download Latest](https://github.com/dotnet/docfx/releases) to download the most up to date DocFX files. Please note, you will not need to use the docfx init command as the initial JSON file is already present in our repository.

WK\<html\>TOpdf is required as part of the build process. You will find the needed files at the following address: https://wkhtmltopdf.org/downloads.html. Once downloaded, execute the command to install. Once installed, set PATH to the directory in which WK\<html\>TOpdf was installed.
