# Ansible Playbook Compatible Testing for EzyAdmin Connectors

## Configuration

| key                | description                                     |
| ------------------ | ------------------------------------------------|
| list :             |                                                 |
|                    | [{                                              |
|                    |     "conn_id" : "***{{ connector id }}***"      |
|                    |     "module" : "***{{ connector module }}***"   |
|                    |     "cmd" : "***{{ command_line }}***"          |
|                    |     "err-msg" : "***{{ error  message  }}***"   |
|                    |     "regex" : "***{{ regular expression }}***"  |
|                    | }]                                              |