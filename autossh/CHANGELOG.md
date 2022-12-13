# Changelog

## 1.2.0

- Added Local Forwards: Access remote InfluxDB, MQTT Broker and/or use Remote-HomeAssistant on a common host without exposing public ports besides SSHd.

## 1.1.0

Attention: v1.0.9 introduced a change you should pay attention to during an update.
Please set `other_ssh_options` to `-N` or `-N -v` (`N`: no login, just a tunneling connection; `v`: verbose logging)

- Replace "config.json" by "config.yaml"
- Add changelog file

## 1.0.9

- Move ssh argument `-N` to default configurable options so it can be removed (fixes #1)

## 1.0.8

- Switch key type to ed25519 (see #6)

## 1.0.0

- No change. Add-on has been stable for two years
