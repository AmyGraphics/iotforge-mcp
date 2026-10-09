# IoTForge MCP Server 📡⚡🔌

Universal Autonomous IoT & Embedded Development: Device Architecture, Production Firmware, Device-to-Cloud Sync, Power Optimization & Fleet Production Engine MCP Server for **Cursor, Claude Code, Windsurf, and Autonomous AI Agents**.

## 🌟 Core Capabilities:
- 👑 **Master 1-Shot Outcome Engine (`autonomous_iot_architect`):** Ingests the device concept to synthesize a complete IoT blueprint in one call: board decision matrix (ESP32-S3/C3 vs Raspberry Pi Pico W vs STM32 vs Linux Pi), connectivity matrix (WiFi vs BLE vs LoRa/LoRaWAN vs Zigbee/Thread vs LTE-M), power budget with real battery life math, firmware architecture plan, cloud backend plan, and a prototype-to-production roadmap.
- 🔌 **Firmware Generator (`generate_firmware_code`):** Production-grade firmware with the patterns hobby tutorials skip — robust WiFi/MQTT state machines with exponential backoff (no reconnect storms), hardware watchdogs, Last Will & Testament presence, offline buffering, OTA hooks with rollback, and deep sleep integration — for ESP32 (Arduino/ESP-IDF), Pico W (MicroPython), and Raspberry Pi (Python + systemd).
- ☁️ **Device-Cloud Sync Designer (`design_device_cloud_sync`):** MQTT topic hierarchies that scale to 100k devices (with broker ACL isolation), compact telemetry schemas, command/ack patterns with idempotency and expiry, device shadow/digital twin sync for sleeping devices, offline ring buffers with throttled backfill, and broker selection from free tiers to EMQX clusters.
- 🔋 **Power Optimizer (`optimize_power_consumption`):** Battery life engineering from weeks to years: duty-cycle math with concrete numbers, vampire-load hunting (the power LED that costs 40x your sleep budget), deep sleep and ULP coprocessor strategies, radio energy comparison (WiFi vs LoRa vs BLE per message), solar sizing, and why multimeters lie about sleep current.
- 🏭 **Fleet Production Kit (`prepare_device_production`):** A/B OTA with automatic rollback and staged rollouts, per-device identity and secrets provisioning at factory scale, security hardening (TLS pinning, secure boot, flash encryption, revocation drills), manufacturing test jigs, fleet health monitoring, and regulatory notes (modular FCC/CE radio certs, UN38.3 battery shipping).

## 🚀 Server URL
`https://iotforge-api.agentweb-hub.workers.dev/mcp`
