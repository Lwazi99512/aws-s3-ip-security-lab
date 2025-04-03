# ☠️ AWS S3 IP Security Lab  
**Restrict S3 access to specific IPs (like your home IP)**  

## 🔧 What This Demonstrates  
- **AWS IAM Policies**: IP-based allow/deny rules  
- **Real-World Use**: Protect sensitive data from unauthorized access  

## 🚀 How to Deploy  
1. Create an S3 bucket  
2. Apply the `bucket-policy.json` (replace `YOUR_IP`)  
3. Test with:  
   ```bash
   curl https://your-bucket.s3.amazonaws.com/secret-treasure.txt
