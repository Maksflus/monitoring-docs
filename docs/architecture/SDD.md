# Software Design Document (SDD)

## Architecture Style
Мікросервісна архітектура.

## Components

- API Gateway
- Log Service
- Metrics Service
- Alert Service
- Storage Service

## Communication

- REST API (synchronous)
- Message Broker (asynchronous)

## Data Flow

Logs → Log Service → Storage → Analytics → Alerts
