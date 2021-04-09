# DeployHub action

This [DeployHub](https://www.deployhub.com/) deployment step container deploys an
application to an environment.  And adds/replaces a component version with attributes
for an application version.

## Specifications

| Setting | Data type | Description | Default | Required |
|---------|---------------|-----------|-------------|---------|
| `action` | string | Action to preform (deploy,updatecomp) | None | True |
| `dhurl` | string | DeployHub Server Url | None | True |
| `dhuser` | string | DeployHub User Id | None | True |
| `dhpass` | string | DeployHub Password | None | True |
| `appname` | string | Application Name to deploy or update | None | True |
| `appversion` | string | Application Version | None | False |
| `deployenv` | string | Environment to deploy to | None | False |
| `compname` | string | Component Name | None | True (for updatecomp action) |
| `compvariant` | string | Component Variant | None | False |
| `compversion` | string | Application Version | None | False |
| `docker` | boolean | Docker Component Item Type | None | False |
| `file` | boolean | File Component Item Type | None | False |
| `compattr` | string | Component Attribute | None | False |
| `envs` | string | Environment to associate Application to | None | False |
