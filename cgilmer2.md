# Project Idea - Endpoint Anomaly Monitor

## Summary

The suite of tools proposed by this project will allow for IT administrators and security personnel  
to have better insights into security-relevant events happening on endpoint devices that they manage.

Sensors installed on endpoint devices (Windows, Linux) will collect telemetry and forward the collected data to a centralized repository. 

The repository will be easily accessible via a web interface, which will allow for users to specify and query for events that they might be interested in. 

These events could include new processes being created, network connections being established, files being accessed, etc...

## Problem Being Solved

With the complexity of modern operating systems and software deployments, it can be difficult for system administrators to know about potential indicators  
of a breach before ransomware is deployed on a network or intellectual property is stolen.

This project seeks to give users the power to discover security-critical events before catastrophe.

## Major Features

### Sensor

The sensor will sit on each endpoint device - Windows/Linux laptop, desktop, or server - and monitor process creation, network connections, file access, among other events.  

On a configurable interval, the sensor will forward collected events to the repository.

### Repository

A central database that receives and stores events from all installed sensors. 

### Web Interface

This will allow for users to view trends of certain events over time, enter in custom queries operating over event properties, and  
configure alerts for events.

## Technologies

### Sensor

- Rust
- C
- eBPF
- Windows API
- Windows Driver Kit

### Repository

- Rust
- Axum
- SQL

### Web Interface

- HTML/CSS/Javascript

## Target Audience

The target audience of this project is system administrators managing complex networks that include Windows and Linux machines.