<!-- region Generated -->
# Microsoft.Graph.Identity.Governance
This directory contains the PowerShell module for the IdentityGovernance service.

---
## Status
[![Microsoft.Graph.Identity.Governance](https://img.shields.io/powershellgallery/v/Microsoft.Graph.Identity.Governance.svg?style=flat-square&label=Microsoft.Graph.Identity.Governance "Microsoft.Graph.Identity.Governance")](https://www.powershellgallery.com/packages/Microsoft.Graph.Identity.Governance/)

## Info
- Modifiable: yes
- Generated: all
- Committed: yes
- Packaged: yes

---
## Detail
This module was primarily generated via [AutoRest](https://github.com/Azure/autorest) using the [PowerShell](https://github.com/Azure/autorest.powershell) extension.

## Development
For information on how to develop for `Microsoft.Graph.Identity.Governance`, see [how-to.md](how-to.md).
<!-- endregion -->

### AutoRest Configuration

> see https://aka.ms/autorest

``` yaml
require:
  - $(this-folder)/../../readme.graph.md
  - $(this-folder)/../../../profiles/$(title)/readme.md
title: $(service-name)
subject-prefix: ''
```

### Directives

> see https://github.com/Azure/autorest/blob/master/docs/powershell/directives.md

``` yaml
directive:
  - remove-path-by-operation: ^identityGovernance_(Get|Create|Update|Set|Delete)EntitlementManagement$|^identityGovernance\.entitlementManagement(_.*AccessPackageResourceRoleScopes|\.accessPackageResourceRoleScopes.*|\.accessPackageAssignmentPolicies\..*|\.accessPackageAssignmentRequests\..*|\.accessPackageAssignmentResourceRoles\..*|\.accessPackageAssignments\..*|\.accessPackageCatalogs\..*|\.accessPackageResourceRequests\..*|\.accessPackageResources\..*|\.accessPackages\..*)|^identityGovernance\.accessReviews\.definitions\.instances\.decisions\.(instance_.*)|^identityGovernance\.accessReviews\.definitions\.instances\.stages\.decisions.*$
# Remove cmdlets
  - where:
      verb: Get
      subject: ^AgreementFile$
      variant: ^Get1|Get3|GetViaIdentity1|GetViaIdentity3$
    remove: true
  - where:
      verb: Update
      subject: ^AgreementFile$
      variant: ^Update1|Update3|UpdateExpanded1|UpdateExpanded3|UpdateViaIdentity1|UpdateViaIdentity3|UpdateViaIdentityExpanded1|UpdateViaIdentityExpanded3$
    remove: true
  - where:
      verb: Remove
      subject: ^AgreementFile$
      variant: ^Delete1|Delete3|DeleteViaIdentity1|DeleteViaIdentity3$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AccessPackageRefAccessPackageCatalog$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AccessPackageGraphRefCatalog$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentAccessPackage$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AssignmentGraphRefAccessPackage$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AssignmentAccessPackage
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentAccessPackageAssignmentPolicy$
    remove: true
  - where:
      verb: Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentAccessPackageAssignmentRequest$
    remove: true
  - where:
      verb: Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentAccessPackageAssignmentResourceRole$
    remove: true
  - where:
      verb: Get|New
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentApproval$
    remove: true
  - where:
      verb: Get|New
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentApprovalStep$
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentPolicyAccessPackage$
    remove: true
  - where:
      verb: Get|Set|Remove
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentPolicyRefAccessPackage$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentPolicyAccessPackageCatalog$
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentRequestAccessPackage$
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)AssignmentRequestAccessPackage
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentRequestAccessPackageAssignment$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AssignmentRequestAssignment$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentRequestRefAccessPackage$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AssignmentRequestGraphRefAccessPackage$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AssignmentRequestGraphRefAssignment$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AssignmentRequestGraphRefRequestor$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentRequestRequestor$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AssignmentRequestRequestor$
    remove: true
  - where:
      verb: Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentResourceRoleAccessPackageAssignment$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentResourceRoleAccessPackageResourceRole$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentResourceRoleAccessPackageResourceScope$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentResourceRoleAccessPackageSubject$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentTarget$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AssignmentTarget$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AssignmentGraphRefTarget$
    remove: true
  - where:
      verb: Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageCatalogAccessPackage$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)CatalogGraphRefAccessPackage
    remove: true
  - where:
      verb: Get|New|Remove|Update|Set
      subject: (.*)(EntitlementManagement)CatalogAccessPackage
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)CatalogAccessPackageCatalog$
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)AccessPackageResourceAccessPackageResourceEnvironment$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AccessPackageResourceRefAccessPackageResourceEnvironment$
    remove: true
  - where:
      verb: Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageResourceAccessPackageResourceRole$
    remove: true
  - where:
      verb: Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageResourceAccessPackageResourceScope$
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)AccessPackageResourceEnvironmentAccessPackageResource$
    remove: true
  - where:
      verb: Get|New
      subject: (.*)(EntitlementManagement)AccessPackageResourceEnvironmentRefAccessPackageResource$
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)AccessPackageResourceRequestAccessPackageResource$
    remove: true
  - where:
      verb: Get|Remove|Set
      subject: (.*)(EntitlementManagement)AccessPackageResourceRequestRefAccessPackageResource$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageResourceRequestRequestor$
    remove: true
  - where:
      verb: Get
      subject: (.*)(EntitlementManagement)AccessPackageResourceRoleScope$
    remove: true
  - where:
      verb: New
      subject: (.*)(EntitlementManagement)AccessPackageAssignment$
    remove: true
  - where:
      verb: New|Invoke|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentResourceRole$
    remove: true
  - where:
      verb: New|Remove|Update|Get
      subject: (.*)(EntitlementManagement)AccessPackageCatalogAccessPackageResourceRole$
      variant: (Create.*|Delete.*|Update.*|Get.*) # Removes all variants except List.*
    remove: true
  - where:
      verb: New|Remove|Update|Get
      subject: (.*)(EntitlementManagement)AccessPackageCatalogAccessPackageResourceScope$
      variant: (Create.*|Delete.*|Update.*|Get.*)
    remove: true
  - where:
      verb: New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageResource$
    remove: true
  - where:
      verb: New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageResourceEnvironment$
    remove: true
  - where:
      verb: Search
      subject: (.*)(EntitlementManagement)AccessPackage$
    remove: true
  - where:
      verb: Search|Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageCatalog$
      variant: ^(Search.*|Get1|List1|GetViaIdentity1|Create1|CreateExpanded1|CreateViaIdentity|CreateViaIdentityExpanded|Update1|UpdateExpanded1|UpdateViaIdentity1|UpdateViaIdentityExpanded1|Delete1|DeleteViaIdentity1)$
    remove: true
  - where:
      verb: New|Remove|Update|Get
      subject: (.*)(EntitlementManagement)AccessPackageCatalogAccessPackageResource$
      variant: (Create.*|Delete.*|Update.*|Get.*)
    remove: true
  - where:
      verb: Get|New|Remove|Update
      subject: (.*)(EntitlementManagement)AccessPackageAssignmentPolicy$
      variant: ^(Get1|List1|GetViaIdentity1|Create1|CreateExpanded1|CreateViaIdentity|CreateViaIdentityExpanded|Update1|UpdateExpanded1|UpdateViaIdentity1|UpdateViaIdentityExpanded1|Delete1|DeleteViaIdentity1)$
    remove: true
  - where:
      verb: Remove
      subject: (.*)(EntitlementManagement)Setting$
    remove: true
  - where:
      verb: Get|Update
      subject: (.*)(IdentityGovernance)$
    remove: true
  - where:
      verb: Get|Remove|Update
      subject: (.*)(IdentityGovernance)AccessReview$
    remove: true
  - where:
      verb: New|Remove|Update|Get|Add|Invoke|Reset|Send|Set|Stop
      subject: (.*)(IdentityGovernance)(AccessReviewDefinition|AccessReviewHistoryDefinition|AccessReviewPolicy)(.*)$
    remove: true
  - where:
      verb: New|Remove|Update|Get
      subject: ^(.*)(IdentityGovernance)Term$
    remove: true
  - where:
      verb: New|Remove|Update|Get|Invoke
      subject: (.*)(IdentityGovernance)AppConsent
    remove: true
# Rename cmdlets with duplicates in their name.
  - where:
      subject: ^(BusinessFlowTemplate)(\1)+
    set:
      subject: $1
  - where:
      subject: ^(ProgramControlType)(\1)+
    set:
      subject: $1
  - where:
      subject: ^(PrivilegedRoleAssignment)(\1)+
    set:
      subject: $1
  - where:
      subject: ^(PrivilegedRoleAssignmentRequest)(\1)+
    set:
      subject: $1
  - where:
      subject: ^(PrivilegedOperationEvent)(\1)+
    set:
      subject: $1
# Rename cmdlets
  - where:
      verb: Get
      subject: ^(PrivilegedRole)(Assignment)$
    set:
      subject: $1Role$2
  - where:
      subject: (.*)(IdentityGovernance)(EntitlementManagement)(.*)$
    set:
      subject: $1$3$4
```
### Versioning

``` yaml
module-version: 1.9.4
release-notes: See https://aka.ms/GraphPowerShell-Release.
```
