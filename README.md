# Network-Scanner
This tool help to enumerate subnetwork and internal networks within an organization.
### Usage
# Basic functionality test (should work without errors)
sudo python3 Script2.py --basic

# List available interfaces
sudo python3 Script2.py -l

# Use specific interface
sudo python3 Script2.py -i eth0 --basic

# Save basic results
sudo python3 Script2.py --basic -o basic_results.json
