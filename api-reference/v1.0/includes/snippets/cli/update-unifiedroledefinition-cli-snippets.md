---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc role-management directory role-definitions patch --unified-role-definition-id {unifiedRoleDefinition-id} --body '{\
  "description": "Update basic properties of application registrations",\
  "displayName": "Application Registration Support Administrator",\
  "rolePermissions":\
    [\
        {\
            "allowedResourceActions": \
            [\
                "microsoft.directory/applications/basic/read"\
            ]\
        }\
    ]\
}\
'

```