# Mount-Amazon-S3-as-a-virtual-drive-using-NetDrive3


## Scenario
This document guide you the step to mount Amazon S3 cloud storage as a virtual drive by using NetDrive 3 and provide the solution for users with low-capacity SSD-drives.

## Prerequisites
> An AWS account.

> NetDrive License (The license plan: http://www.netdrive.net/store/ ), you can also use 7-day free trial for testing.

> A Facebook, Twitter, Google, or Bdrive account.

## Tutorial
### Install NetDrive
1.1. Download the product from NetDrive website: http://www.netdrive.net .

1.2. Follow the installation steps to install.

### Start your Mounting process
2.1.	Open NetDrive, and sign in with your Facebook, Twitter, or Google account. Or create a free Bdrive account.

![2.1.png](/images/2.1.png)

2.2.	On the NetDrive panel, click **“+”** icon on the right-side bottom.

![2.2.png](/images/2.2.png)

2.3.	In STOGAGE TYPE, choose **S3**.

![2.3.png](/images/2.3.png)

2.4.	Click **Connect**.

![2.4.png](/images/2.4.png)

2.5.	Go to **Amazon Web Services** console and click on the name of your account (it is located in the top right corner of the console). Then, in the expanded drop-down list, select **My Security Credentials**.

![2.5.png](/images/2.5.png)

2.6.	Click **Continue to Security Credentials**.

![2.6.png](/images/2.6.png)

2.7.	Expand the **Access keys (access key ID and secret access key)** option. You will see the list of your active and deleted access keys.

![2.7.png](/images/2.7.png)

2.8.	To generate new access keys, click the **Create New Access Key** button.

2.9.	Click **Show Access Key** to have it displayed on the screen. You can download it to your machine as a file and open it whenever needed. To download it, just click the **Download Key File** button. 

![2.9.png](/images/2.9.png)

***Remember!** If you do not write down the key or download the key file to your computer before you click ”Close”, you will not be able to retrieve the secret key in the future. Then you’ll have to delete the keys which you created and start to create new keys.*

2.10.	Go back to NetDrive, and insert the **Access ID** and **Secret Key**, then click **OK**.

![2.10.png](/images/2.10.png)

2.11.	Click **Browse****.

![2.11.png](/images/2.11.png)

2.12.	Select your bucket, and click **OK**.

![2.12.png](/images/2.12.png)

2.13.	In LABEL, you can change Label Name and Display Color. 

2.14.	In AUTO CONNECT OPTIONS, you can decide whether to automatic mount on login or not.

2.15.	In UPLOAD OPTIONS, suggest to check using background uploading.

2.16.	In READ ONLY OPTIONS, choose for being Writable or Read only.

2.17.	In ADVANCED OPTION, you can decide whether to always retrieve file list from server.

2.18.	Click **OK**.

![2.18.png](/images/2.18.png)

2.19.	The S3 bucket will display on the panel, then click **CONNECT**.

![2.19.png](/images/2.19.png)

2.20.	After processing, you will see the cloud storage has successfully mounted as a virtual device in your finder.

![2.20.png](/images/2.20.png)



## Conclusion

Congratulations! You now have learned how to:
* Find your AWS access key and secret key
* NetDrive mounting solution

