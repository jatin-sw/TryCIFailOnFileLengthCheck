# TryCIFailOnFileLengthCheck
A CI Pipeline to check for max file name length on commit and fail when length exceeds max.
The pipeline will fail if there is direct commit to main branch. It will work only when there's a PR to main.
Also the pipeline is set for a repo in Azure DevOps only. So it always fails here.
