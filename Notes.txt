# AZ---204-Guide


# ARM Template-

template.json file to mention the details for resource which needs to be published.
parameters.json file to specify the parameters details to be used in template file.
Four separate sections in template file -
i) Parameters
ii) Variables
iii) Resources
iv) Outputs
Deployment powershell command- 
New-AzResourceGroupDeployment -Name VnetDemo -ResourceGroupName test -TemplateFile path -TemplateParameterFile path 

