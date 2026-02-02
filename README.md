Git Upload and Version Control

All GAT Layer-2 automation scripts, templates, YAML files, and generated configuration outputs are managed in a central GitLab repository hosted in the ESV environment:

https://git.esv.enmp.airservices.gov.au/ntt/gat_l2_network_template.git

This repository acts as the single source of truth for configuration generation across the ESV, PROD, and CSV environments.

Changes are uploaded using standard Git commands. After updating files locally, changes are staged and committed to record a clear versioned history:

git add .
git status
git log
git commit -m "Dec 17 backup"


For initial setup or first-time uploads, the local repository is linked and pushed to GitLab as follows:

cd existing_repo
git remote add origin https://git.esv.enmp.airservices.gov.au/ntt/gat_l2_network_template.git
git branch -M main
git push -uf origin main


Version control ensures that every change is tracked, auditable, and reversible. If required, configurations can be rolled back by reverting to a previous Git commit and regenerating the configuration outputs. Generated configurations for each environment are stored under the .output_builds directory, allowing easy review and comparison before deployment.
