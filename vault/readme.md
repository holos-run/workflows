# Vault Audit Logs

Runs ever week.  The audit logs are encrypted to Jeff's GPG key.

Access them with:

```
❯ gpg -d vault.tgz.asc | tar xvzf -
gpg: encrypted with rsa4096 key, ID C0EBC42522ACB4CF, created 2023-04-14
      "Jeff McCune <jeff@openinfrastructure.co>"
x vault/
x vault/audit.log.1725402876.vault-2
x vault/audit.log.1725402876.vault-0
x vault/audit.log.1725402876.vault-1
```
