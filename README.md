# AutocompleteLookupSP2013
Autocomplete Lookup field allows type ahead functionality while entering lookup values in list items.
It uses REST for specifying filters. The WSP file can be downloaded from here: https://github.com/nadeemy/AutocompleteLookupSP2013/releases/download/1.0/NY.Autocomplete.LookupField.wsp

# Deployment steps

**Add Solution using stsadm.exe:**
stsadm.exe -o addsolution -filename C:\NY.ExportVersionHistory.wsp 

**Deploy Solution using stsadm.exe:**
stsadm.exe -o deploysolution -name NY.Autocomplete.LookupField.wsp -immediate -allowgacdeployment

**Add Solution using PowerShell:**
Add-SPSolution -LiteralPath c:\NY.Autocomplete.LookupField.wsp

**Deploy Solution using PowerShell:**
Install-SPSolution -Identity NY.Autocomplete.LookupField.wsp -GACDeployment

For more information please visit http://www.sharepointnadeem.com/2012/03/sharepoint-2010-autocomplete-lookup.html

## WANT TO SHOW APPRECIATION? 

If you find this tool useful and want to show your appreciation, you can go to my blog [SharePoint Learnings](http://www.sharepointnadeem.com/2012/07/export-version-history-of-sharepoint.html) and click the banners on the blog to visit my blog sponsors or you could spread the word about it on social media sites.
