# Azure-arm-templates
I'll try to update this repo regularly to share the ARM templates that i'm working on with everyone.
With using first two templates you can create storage account with blob container named as **"logs"**.
The one that ends with "template" takes a variable as storage account name. I used concat function to create the storage account name with using **"resource group id"** with **"cc"** string. You can choose either use another random string or leave it just with id.
Other (ends with **"nameparameter.json"**) is using storage account name with using parameter that will defined by the one that wants to create storage account with using the template.
Both have **access key** and **connection strings** outputs to use the templates programmatically.

