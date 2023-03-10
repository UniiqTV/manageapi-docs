---
layout: default
title: UNIIQ Management API
has_children: true
has_toc: false
---

# UNIIQ Management API Documentation

Management API is organized around REST API's. Our API has predictable resource-oriented URLs, can accepts both form-encoded request bodies/json payloads, returns JSON-encoded responses, and uses standard HTTP response codes (references) for status codes, JWT authentication, and verbs operations.

## Setup
Pre requisite on using Management API Account:
* UNIIQ Management Account with (Content Provider / Service Provider) access.
* Complete verifications – you need to do this before you start your technical integration. Also ensure you’re compliant with our Terms and Conditions and Acceptable Use Policy. Also make sure two-step log in is set up.

## Table Of Contents
1. [Authentication](authentication.md)
2. [Customer API](customer/index.md)
	1. [Customer List](customer/customer-list.md)
	2. [Customer Detail By Customer ID](customer/customer-by-id.md)
	3. [Customer Detail By Internal Customer ID](customer/customer-by-internal-id.md)
	4. [Create New Customer](customer/customer-create.md) 
3. [Package API](package/index.md)
	1. [Package List](package/package-list.md)
	2. [Assign Package to User](package/assign-package.md)
	3. [Disable Package](package/disable-package.md)
	4. [Remove Package](package/remove-package.md)
4. [Device API](device/index.md)
	1. [Assign Device to User](device/assign-device.md)
	2. [Remove Device from User](device/remove-device.md)
