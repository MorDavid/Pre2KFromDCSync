The script detects machine accounts with Pre-Windows 2000 passwords and outputs the account name, stored NT hash, and potential password.

## Security Impact
Machine accounts with Pre-Windows 2000 passwords are vulnerable to:
- Easy password guessing
- Lateral movement in Active Directory environments
- Potential privilege escalation
- Network resource access exploitation

## Remediation
If vulnerable accounts are found:
1. Reset the machine account passwords
2. Ensure proper machine account password policies are enforced
3. Implement modern security practices for machine authentication
4. Monitor for any unauthorized access attempts

## Disclaimer
This tool is intended for authorized security testing and auditing purposes only. Always ensure proper authorization before conducting security assessments. The author is not responsible for any misuse or damage caused by this tool.
