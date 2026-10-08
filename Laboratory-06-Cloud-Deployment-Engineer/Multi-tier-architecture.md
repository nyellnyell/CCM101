# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A Two-Tier Architecture is an application structure where the system is divided into two main parts: the Web/Application Tier and the Database Tier. In this mission, Nextcloud is the Web/Application Tier and MariaDB is the Database Tier.

## The Web/Application Tier

The Web/Application Tier is responsible for serving the user interface and handling HTTP requests from users. In this mission, the Nextcloud container provides the web application that users access through a browser.

## The Database Tier

The Database Tier is responsible for storing persistent data, user accounts, and other information needed by the application. In this mission, MariaDB is used as the database container for Nextcloud.

## Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage and maintain. Each container has a specific role, and the application can communicate with the database through the Docker network.
