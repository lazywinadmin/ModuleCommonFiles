# Steps

1. Create a project in the CI solution (example Azure Pipelines, Appveyor)
1. Create a pipeline and map it to Github
1. AzureDevops: Create a library group under Pipelines called 'psgallery'
1. Add a variable psgallerykey with the value of your APIKEY from the PowerShell Gallery and click on the LOCK button
1. Update the build.ps1 file variable values in the "# EDIT THIS PART" part
1. generate a new Guid for the psd1 in /src/source.psd1
1. delete todo file
1. delete this file


# Troubleshooting

1. Make sure the CI tool variable, variable groups are matching (case sensitive)
1. Validate Variables usage inside CI Yaml, matching, case sensitive
1. Validate Variables usage inside PSDeploy, matching, case sensitive
1. Make sure the APIKey is valid and not expired
1. Make sure the APIKey is valid to upload new package
1. Make sure the APIKey is valid to upload new package version
1. Make sure the ModuleName is not already used by another module
1. Make sure the GUID is not already used by another module
