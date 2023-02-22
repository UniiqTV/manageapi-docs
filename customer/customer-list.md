---
layout: default
title: Customer List
nav_order: 1
parent: Customer API
grand_parent: UNIIQ Management API
---

# Customer List

manage api use to get customer-list from uniiq service by username authentication

```
GET https://manageapi.uniiq.id/api/customer/list
Authorization: Bearer {{token}}
```

**Response** :
```json
[
    {
        "id": "21577bdc-a7d7-4993-b1e9-bd711bc15854",
        "name": "Test Platinum SBY",
        "phone": "",
        "email": "",
        "address": "",
        "customerId": ""
    },
    {
        "id": "5df778d8-cbcb-43d8-b983-7b17327c87c6",
        "name": "Milenium City 60CH + Daai",
        "phone": "1234567890",
        "email": "",
        "address": "",
        "customerId": "Milenium_60CH+DAAITV"
    },
    {
        "id": "59695283-e8c8-49fb-aca3-f543e6a3b542",
        "name": "OWNER TPM",
        "phone": "123456845",
        "email": "OWNERTPM@TEST.COM",
        "address": "",
        "customerId": ""
    },
    {
        "id": "93f64a17-2912-4227-816e-4fefb339a668",
        "name": "Milenium City 60CH",
        "phone": "",
        "email": "tbg@sp",
        "address": "",
        "customerId": "Milenium_60CH"
    },
    {
        "id": "3822a8af-6647-4484-81c0-9b05d65ef3a7",
        "name": "Channel World Cup",
        "phone": "1234567890",
        "email": "",
        "address": "",
        "customerId": "test ch world cup"
    },
    {
        "id": "009dc41b-0cfe-444d-a841-de8a55086e11",
        "name": "Bandara City 60CH",
        "phone": "",
        "email": "tbg@sp",
        "address": "",
        "customerId": "Bandaracity_60CH"
    },
    {
        "id": "63101eb3-ccb8-4692-a40e-8ed0da854c37",
        "name": "Anandamaya 60CH",
        "phone": "",
        "email": "tbg@sp",
        "address": "",
        "customerId": "Anandamaya_60CH"
    },
    {
        "id": "889a777d-652f-45bd-9c37-a5e731459e19",
        "name": "Test Cyberplus",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "Test Cyberplus"
    },
    {
        "id": "20ed1b74-8bfc-4931-b2db-d4994744bd82",
        "name": "KUNCIT 60 CH",
        "phone": "",
        "email": "",
        "address": "",
        "customerId": "Kuningan City 60CH"
    },
    {
        "id": "7006ebf7-41d2-4530-bc1e-7a0c3b7629b6",
        "name": "Developer Uniiq",
        "phone": "081111111000",
        "email": "dev@uniiq.id",
        "address": "",
        "customerId": ""
    },
    {
        "id": "f649acaa-e22b-494f-8871-9fddd3a94aaf",
        "name": "Test Siaran UIN JAMBI",
        "phone": "123456677",
        "email": "",
        "address": "",
        "customerId": "Demo TV UIN JAMBI"
    },
    {
        "id": "91f22acc-a48d-46ff-86cd-d78e700fa3ef",
        "name": "CDNNetCitiTest-COMP-KINGS",
        "phone": "123456789",
        "email": "KINGS@KINGS.NET.ID",
        "address": "",
        "customerId": ""
    },
    {
        "id": "6ccbba02-15ec-4253-acf1-c7c2126abe20",
        "name": "Remala 50 CH",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "Remala_Abadi_50CH"
    },
    {
        "id": "1f637923-a03f-4287-b61e-e880ad732d99",
        "name": "V-NET INDONESIA",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "Trial IPTV V-NET"
    },
    {
        "id": "27d7fa19-ad90-437f-8dca-f22a97242bca",
        "name": "Eko Priyono",
        "phone": "08112345678",
        "email": "echo@kings.net.id",
        "address": "M101",
        "customerId": null
    },
    {
        "id": "5838611a-4534-4cfb-8ca9-96be217698a2",
        "name": "TPM + WorldCup",
        "phone": "123456789",
        "email": "",
        "address": "",
        "customerId": "Worldcup Menteng"
    },
    {
        "id": "ed7f4071-559a-46ac-b195-9ad5952723bc",
        "name": "The Nest 40 CH",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "The Nest 40 CH"
    },
    {
        "id": "232b27e2-0644-46eb-8820-f0bd25192183",
        "name": "Bandara City 40CH",
        "phone": "",
        "email": "tbg@sp",
        "address": "",
        "customerId": "Bandaracity_40CH"
    },
    {
        "id": "a0e34bf1-5d64-43f1-9d81-e44bc4a1af5d",
        "name": "SATU8 40 CH",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "SATU8 40 CH"
    },
    {
        "id": "80cf3fc1-566c-4401-9fb1-7c5d0f4afc1e",
        "name": "Sunvone Test",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "Sunvone_Test"
    },
    {
        "id": "3622355d-8202-462f-b2c9-cc579a5d226c",
        "name": "GCA 40 CH",
        "phone": "",
        "email": "",
        "address": "",
        "customerId": "GCA 40 CH"
    },
    {
        "id": "3810f14b-e80e-46c4-ac62-f6cce2de4c66",
        "name": "Anandamaya 40CH",
        "phone": "",
        "email": "tbg@sp",
        "address": "",
        "customerId": "anandamaya_40CH"
    },
    {
        "id": "178effdf-b77b-4fb5-8603-f79537e61ae2",
        "name": "Milenium City 40CH",
        "phone": "",
        "email": "tbg@sp",
        "address": "",
        "customerId": "Milenium_40CH"
    },
    {
        "id": "b25f0431-19cd-4fde-b30e-6f2e406226be",
        "name": "DEMO UNIIQ TV",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "Demo UNIIQ TV"
    },
    {
        "id": "e903ff2f-5438-4f7d-82b8-b5eb5a78408b",
        "name": "Test D8 Kings",
        "phone": "",
        "email": "C_one@CP",
        "address": "",
        "customerId": "Test_D8_Kings"
    },
    {
        "id": "5244c0b6-5e58-4243-b56e-ba7cd7f75267",
        "name": "Remala 40 CH",
        "phone": "",
        "email": "Remala@sp",
        "address": "",
        "customerId": "Remala_Abadi_40CH"
    },
    {
        "id": "fd2e7d2c-8c50-4025-b7d3-c4eb9d0b1d71",
        "name": "Bitsnet 40 CH",
        "phone": "12345678",
        "email": "",
        "address": "",
        "customerId": "Bitsnet 40 CH"
    },
    {
        "id": "bd9def3c-09db-4f4f-b64a-8e936d0af813",
        "name": "Joandi Leonardus",
        "phone": "0812345678",
        "email": "joandi@kings.net.id",
        "address": "M102",
        "customerId": ""
    },
    {
        "id": "b346b204-d6d7-4761-aeb1-728fc3916e0b",
        "name": "Hikaru",
        "phone": "",
        "email": "hikaru@kings.net.id",
        "address": "Indonesia",
        "customerId": ""
    },
    {
        "id": "b77143a4-eacc-45af-ab8b-667d203ad179",
        "name": "Developer",
        "phone": "11111",
        "email": "dev@kings.id",
        "address": "bekasi",
        "customerId": "12313123"
    }
]
```
- *id* : this is id from customer
- *name* : this is name from customer
- *phone* : this is phone from customer
- *email* : this is email from customer
- *address* : this is address from customer
- *customerId* : this is CustomerId from customer