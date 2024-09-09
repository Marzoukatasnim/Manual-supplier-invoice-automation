This project aims at automation of manual supplier invoice module of IFS. To create multiple manual supplier invoices at once, it is convenient to upload data
through external file(excel file).A new procedure named Start_Ext_MSI is written inside C_Customization_API package to do this job.
Input file format=> colA=Account, colB=Unit, colC=Costcent, colD=Department, colE=Inventory gross current amount, colF=Text, colG=Supplier name, colH=Invoice no
To insert the input file(MSI_input.csv) go to "external file assistant", type file template name and upload the input file
