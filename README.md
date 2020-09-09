# Vault Associate Certification Review Guide Checklist
[Vault Associate Certification Review Guide Checklist](https://learn.hashicorp.com/tutorials/vault/certification-vault-associate)

## 1 Compare authentication methods
### 1a Describe authentication methods
- [ ] [Authentication](https://www.vaultproject.io/docs/auth)  
- [ ] [Authentication](https://learn.hashicorp.com/vault/getting-started/authentication)
### 1b	Choose an authentication method based on use case
- [ ] [Authentication](https://www.vaultproject.io/docs/concepts/auth.html)  
- [ ] [AppRole Pull Authentication - Authentication](https://learn.hashicorp.com/vault/identity-access-management/approle#auth-methods)
### 1c	Differentiate human vs. system auth methods
- [ ] [Authentication](https://www.vaultproject.io/docs/concepts/auth.html)  
- [ ] [AppRole Pull Authentication - Authentication](https://learn.hashicorp.com/vault/identity-access-management/approle#auth-methods)

## 2 Create Vault policies
### 2a Illustrate the value of Vault policy
- [ ] [Policies](https://www.vaultproject.io/docs/concepts/policies/)  
- [ ] [Vault Policies](https://learn.hashicorp.com/vault/identity-access-management/iam-policies)
### 2b Describe Vault policy syntax: path
- [ ] [Policy Syntax](https://www.vaultproject.io/docs/concepts/policies.html#policy-syntax)  
- [ ] [Vault Policies– Write ACL policies in HCL format](https://learn.hashicorp.com/vault/identity-access-management/iam-policies#step-1-write-acl-policies-in-hcl-format)
### 2c Describe Vault policy syntax: capabilities
- [ ] [Capabilities](https://www.vaultproject.io/docs/concepts/policies.html#capabilities)  
- [ ] [Vault Policies– Write ACL policies in HCL format](https://learn.hashicorp.com/vault/identity-access-management/iam-policies#step-1-write-acl-policies-in-hcl-format)
### 2d Craft a Vault policy based on requirements
- [ ] [Capabilities](https://www.vaultproject.io/docs/concepts/policies.html#capabilities)  
- [ ] [Vault Policies– Policy requirements](https://learn.hashicorp.com/vault/identity-access-management/iam-policies#policy-requirements-1)

## 3 Assess Vault tokens
### 3a Describe Vault token
- [ ] [Tokens](https://www.vaultproject.io/docs/concepts/tokens.html)  
- [ ] [Tokens](https://learn.hashicorp.com/vault/identity-access-management/tokens)
### 3b Differentiate between service and batch tokens. Choose one based on use case
- [ ] [Tokens](https://www.vaultproject.io/docs/concepts/tokens.html)  
- [ ] [Tokens](https://learn.hashicorp.com/vault/identity-access-management/tokens)
### 3c Describe root token uses and lifecycle
- [ ] [Root Tokens](https://www.vaultproject.io/docs/concepts/tokens.html#root-tokens)
### 3d Define token accessors
- [ ] [Token Accessors](https://www.vaultproject.io/docs/concepts/tokens.html#token-accessors)
### 3e Explain time-to-live
- [ ] [Token Accessors](https://www.vaultproject.io/docs/concepts/tokens.html#token-accessors)  
- [ ] [Service Token Lifecycle](https://learn.hashicorp.com/vault/identity-access-management/tokens#service-token-lifecycle)
### 3f Explain orphaned tokens
- [ ] [Token Hierarchies and Orphan Tokens](https://www.vaultproject.io/docs/concepts/tokens.html#token-hierarchies-and-orphan-tokens)  
- [ ] [Tokens– Orphan tokens](https://learn.hashicorp.com/vault/identity-access-management/tokens#orphan-tokens)
### 3g Create tokens based on need
- [ ] [Tokens](https://learn.hashicorp.com/vault/identity-access-management/tokens)  

## 4 Manage Vault leases
- [ ] 4a Explain the purpose of a lease ID
- [ ] 4b Renew leases
- [ ] 4c Revoke leases
