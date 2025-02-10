---
title: Office deposit for Turkish user (works only in Dev, STG and local env)
excerpt: >-
  On DEV it merely simulates TRY deposit whereas on STG it moves TRY from
  operating account to custody account at VakifBank and adds the deposit to a
  customer
api:
  file: openapi.json
  operationId: simulateVakifBankDeposit
hidden: false
---