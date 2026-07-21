This repo is not intended to be syncronized to a Fabric Workspace. Instead it contains resources to help you build your own workspace with your own data sources. 
At the same time, though, if you are just investigating, some dummy datasources with a few invalid format, invalid data, duplicates, and referential integrity violations are provided. 

The idea is for you to use the templates to load regular datasources and dimension-like datasources (validating primary key) and build something like this. 

<img width="1863" height="1125" alt="imagen" src="https://github.com/user-attachments/assets/00932dc0-e5d9-4487-a4e5-ee8b9f755bf4" />

If you want to hear the author stumbling in technical issues and explaining a bit more what is it all about, check out the following video
https://www.youtube.com/watch?v=PG5jzlMJr_A link a youtube

the "Dataflow Refresh Monitor.pbix" file just needs 3 parameters to produce a nice report showing how your dataflows refreshed and if there's anything you need to take care of. All KPIs should be always blank. Links to sharepoint will bring you to the files that have some issues. Solution can be removing the file (if it was there by mistake), modify the file if it's manually maintained and it contains wrong data, or modify the ingestion logic so that the values or columns are properly ingested and do not show up as errors.  

<img width="1414" height="795" alt="imagen" src="https://github.com/user-attachments/assets/3e32b906-e0dd-45b7-b9ad-e4c926a9dc93" />


