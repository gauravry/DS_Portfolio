# Agent Orchestration Scaffold

## Overview
This project scaffolds a multi-agent trading orchestration platform (QuestDB + MT5 + voice/chat supervisor).

## Services
- data_feed_service
- agent_ohlc_stats
- agent_volume_stats
- agent_signal_router
- agent_voice_chat_supervisor
- execution_service_mt5
- monitor_recorder

## Local Development (High-Level)
1. Configure environment variables in `.env.example` and copy to `.env`.
2. Start infrastructure with Docker Compose.
3. Run individual services with your preferred Python runner.

