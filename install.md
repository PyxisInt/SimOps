# SimOps Virtual Airline Management Systems Installation Guide

## Introduction

The SimOps Virtual Airline Management System is best installed in your own data centers, whether on-prem or in the cloud. This document will walk you through the steps required for installing the Airline Management System in your own environment.

## Pre-Requisites

In order to install SimOps VAMS, please ensure that you have the met the following pre-requisites.

### MySQL Database

SimOps VAMS relies on a MySQL database. Please ensure that you have MySQL Version 8.0 or above installed and accessible. You can get it from [Oracle MySql](https://www.mysql.com/downloads/). Please ensure that your MySQL installation allows remote connections.

### Authentication

SimOps is designed to work with Auth0 as its authentication provider. All users and roles are managed from within Auth0. It is recommended that you sign up with [Auth0](https://www.auth0.com) for an account for your VA. Auth0 basic plan allows 7000 monthly active users (MAU, at the time of this writing) for free. Once you have signed up for an Auth0 account, please follow the steps outlined below:

* For your organization, create an API Application called `SimOpsService`. In the `General Settings`, ensure that the `Identifier` is the URL of where your SimOps service is installed.
* On the `Permissions` tab of the API, create 2 new permissions called `role:admin` and `role:pilot`


.../to-be-continued
