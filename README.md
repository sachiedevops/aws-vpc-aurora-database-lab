# AWS VPC Aurora Database Lab

## Overview

This lab demonstrates how to create a database layer in an Amazon VPC using Amazon Aurora MySQL.

## AWS Services

- Amazon Aurora MySQL
- Amazon RDS
- Amazon VPC
- Security Groups

## What I Learned

- Created an Aurora MySQL database
- Configured database settings and backups
- Enabled encryption using AWS KMS
- Deployed the database in the AWS VPC environment
- Learned how a database layer fits into a multi-tier AWS architecture

## Architecture

Application Layer
        ↓
Application Load Balancer
        ↓
EC2 Instances
        ↓
Amazon Aurora MySQL
        ↓
Private Database Layer
