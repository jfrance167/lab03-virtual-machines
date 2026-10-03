# Cloud Computing Architecture Lab 3 Virtual Machines

This repository preserves work from my **Cloud Computing Architecture** course. The lab was intended to develop practical experience with Azure virtual machines and exported infrastructure-as-code artifacts.

## Intended lab focus

- Planning Azure virtual-machine resources.
- Connecting compute resources to virtual networks and subnets.
- Working with deployment parameters and ARM templates.
- Exporting Azure resource configurations into source control.
- Building on the storage and networking concepts from earlier labs.

## Repository status

This is an incomplete course archive. The committed `template.json` contains only the Azure export placeholder `Generating template...`, and `parameters.json` is empty. No deployable infrastructure definition or credentials are present.

I am keeping this repository as part of the course collection because it shows the progression of my cloud-computing coursework, including an attempted export that was not completed.

These files should not be used for deployment without recreating and validating the missing ARM template and parameters.

## Local review and safe reuse

Clone this repository and inspect the Markdown and JSON files locally; no cloud
subscription or deployment is needed to review the coursework. These exports are
historical evidence. Empty parameter files and export placeholders, where noted
above, are not deployable templates and are deliberately preserved.

Use only an isolated subscription you own or are authorized to administer, with
a cost limit and teardown plan, for any future exercise. Review actual network
access, identities, credentials, names and API versions before deploying. Never
commit local credentials or production resource exports. See [SECURITY.md](SECURITY.md).

## Repository map

```text
lab03-virtual-machines/
|-- .gitignore
|-- README.md
|-- SECURITY.md
|-- parameters.json
`-- template.json
```

Follow the setup and safety boundaries above before running or deploying any code.
