# Failed Login Detection

index=main "Failed password"

# Successful Login Detection

index=main "Accepted password"

# SSH Activity

index=main ssh

# Suspicious IP Search

index=main | stats count by src_ip
