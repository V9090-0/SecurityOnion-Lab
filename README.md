cat > README.md << 'EOF'
# SecurityOnion-Lab

A home-grown Security Onion SOC lab demonstrating:

- Security Onion setup & configuration  
- Custom Suricata/YARA/Zeek detection rules  
- Python/Bash scripts for log parsing & alert analysis  
- Kibana dashboards & exports  
- Investigation reports & sample PCAPs  

---

## Repository Structure

```text
SecurityOnion-Lab/
├── README.md
├── configs/
│   └── suricata/
│       └── emerging-all.rules       # Full ET rule set (sanitized)
│       └── local.rules               # Custom rules
├── scripts/
│   ├── zeek/                         # Your Zeek scripts
│   └── custom/                       # Python/Bash parsers
├── dashboards/                       # Kibana NDJSON exports
├── reports/                          # Markdown/PDF analysis write-ups
├── samples/                          # Small PCAPs for demos
└── exports/                          # Alert snapshot JSON



