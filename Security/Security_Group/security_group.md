# Security Group
[TOC]

## Default Rule

inboud
: all close

| Traffic     | Port | Source      | Tag   |
| :---------- | :--- | :---------- | :---- |
|             |      |             |       |


outbound
: all release

| Traffic     | Port | Source      | Tag   |
| :---------- | :--- | :---------- | :---- |
| All Traffic | All  | 0.0.0.0/0   |       |



## APIGW - VPC Lambda connection

* VPC Lambda SG Inbound Rule

| Traffic     | Port | Source      | Tag   |
| :---------- | :--- | :---------- | :---- |
|             |      |             |       |

Ruke無し（all Deny）で問題なく通信できる





