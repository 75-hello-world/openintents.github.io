---
title: Pay Money
action: org.openintents.action.PAY_TO
input: 
    uri: Specifying the receiver of the money
extras: 
  - 
    name: org.openintents.extra.AMOUNT 
    type: float
    sample: 10.00
  - 
    name: org.openintents.extra.CURRENCY 
    type: String
    sample: USD
  - 
    name: android.intent.extra.TEXT 
    type: String
    sample: invoice 123
output:
---
Intent to pay some one a specified amount of money.

The receiver of the money could be specified by an email address (mailto://) or through content like "content://com.visa/savedreceivers/1", or mime type "text/x-bancAccount" or by additional information of a contact.