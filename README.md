<img width="1187" height="816" alt="fastfetchcustom" src="https://github.com/user-attachments/assets/dd708c67-be33-4e6d-a988-08377083d0f4" />
config_colourful_double_outline.jsonc

## **Note:**

The VPN section caches the output from the command "nordvpn status" and assigns it a variable. It then extracts, processes and combines two values from the output. The `awk` function is used to conditionally format the output based on the values returned for the "Status" module.

If you use a different VPN service, you will need to amend lines 136 and 142.
