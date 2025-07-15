# Nmap Usage Notes

## Common Flags

- `-sS`: SYN scan
- `-sV`: Version detection
- `-O`: OS detection
- `-p-`: Scan all ports
- `-T4`: Faster execution

## Example

```bash
sudo nmap -sS -sV -O -p- -T4 192.168.1.1
```
