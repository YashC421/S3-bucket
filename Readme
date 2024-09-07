# s3 Docs

## Installing Command

- **yum update all**
- yum install automake fuse fuse-devel gcc-c++ git libcurl-devel libxml2-devel make openssl-devel
- **git clone https://github.com/s3fs-fuse/s3fs-fuse.git**
- 
    
    **cd s3fs-fuse**
    
    **./autogen.sh**
    
    **./configure --prefix=/usr --with-openssl**
    
    **sudo make install**
    
    **which s3fs**
    

**Go to AWS Menu -> Your AWS Account Name -> My Security Credentials.** Here your IAM console will appear.

**You have to go to Users > Your Account name and under the permissions Tab,** check whether you have sufficient access to the S3 bucket. If not, you can manually assign an existing  “S3 Full-Access” policy or create a new policy with sufficient permissions.

**Now go to the Security Credentials Tab and Create an Access Key.** A new Access Key and Secret Key pair will be generated.

**touch /etc/passwd-s3fsvim /etc/passwd-s3fs**

**Your_accesskey:Your_secretkey**

**sudo chmod 640 /etc/passwd-s3fs**

## mount s3 to instance

**mkdir /mys3bucket
s3fs your_bucketname -o use_cache=/tmp -o allow_other -o uid=1001 -o mp_umask=002 -o multireq_max=5 /mys3bucket**
