# SRE Agent Policy

`policies/sre-policy.yaml` decides how the Azure SRE Agent responds to incidents:
which rule matches, whether remediation is allowed, and which specialist is assigned.

Edit the file here. The agent reads it from this repo, so a merged change to
`main` changes production behaviour on the next reconcile run.
