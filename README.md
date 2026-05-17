# JMeter AIOps CI/CD Pipeline

## Overview
Automated performance testing pipeline combining:
- Apache JMeter — load testing
- Jenkins — CI/CD automation
- Datadog — real-time monitoring and AIOps

## Pipeline Flow
JMeter Script → GitHub → Jenkins → Execute Tests → Datadog Monitoring

## Test Scenarios
- Flask API performance test (50 users)
- 4 endpoints: home, users, orders, slow
- Monitors: response time, error rate, throughput

## Author
Phaneendra Adluri | 8+ Years Performance Testing + AIOps
