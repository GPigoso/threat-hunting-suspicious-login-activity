# Threat Hunting Investigation Notes

## Objective

Identify suspicious login behavior that may indicate malicious activity.

## Log Source

Authentication logs

## Suspicious Indicators

IP Address: 185.220.101.45

## Timeline

10 failed login attempts within 3 minutes

## Investigation Steps

• Reviewed login attempts
• Filtered external IP addresses
• Identified repeated failed attempts
• Checked for successful compromise

## Findings

This activity is consistent with brute force attack behavior.

## Conclusion

Potential attack detected and should be mitigated.

## Recommendation

• Block IP address
• Enable account lockout policy
• Continue monitoring
