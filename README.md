
# AltCloud Landing Page Project

This is a dynamic landing page project hosted on AWS EC2, built for the AltSchool of Engineering Tinyuka Second Semester (Cloud) submission.

## 🔧 Technologies Used

* Ubuntu 22.04 (AWS EC2)
* Nginx Web Server
* CSS
* HTML5
* JavaScript
* Cloudflare
* Namecheap

## 🌐 Live Preview

**Public IP Address:** [http://13.48.44.160](http://13.48.44.160)
**Domain Names:**

* [https://www.kayhub.xyz](https://www.kayhub.xyz)
* [https://kayhub.xyz](https://kayhub.xyz)

![AltCloud Landing Page Screenshot](Screenshot.png)

## 🛠️ Steps Taken

### 1. Server Provisioning (AWS EC2)

* Launched a `t2.micro` Ubuntu 22.04 instance on AWS EC2.
* Created and downloaded a key pair `altcloud-key.pem`.
* Configured AWS security group to allow HTTP (port 80), HTTPS (port 443), and SSH (port 22) access.

### 2. Web Server Setup

* Installed and started Nginx on the EC2 server.
* Opened port 80 in the AWS security group to allow HTTP traffic.

### 3. Dynamic Landing Page

* Replaced the default Nginx welcome page with a custom HTML file.
* Used CSS (Cascading Style Sheets.) for styling.
* Added interactive elements using JavaScript.
* Page includes:

  * Name: Karabo Malatji
  * Role: Lead Cloud Engineer
  * Title: The Future of Cloud-Powered Solutions
  * Pitch and Professional Bio

### 4. Buying a Domain (Namecheap)

* Purchased the domain `kayhub.xyz` via Namecheap.

### 5. Linking to Cloudflare

* Added domain to Cloudflare for DNS and security management.
* Updated Namecheap nameservers to point to Cloudflare.
* Configured DNS records to link domain to EC2 public IP.
* **Enabled SSL/TLS encryption via Cloudflare** to secure the domain with HTTPS.

### 6. Deployment

* Deployed the HTML page to the EC2 instance.
* Configured Nginx to serve the landing page.
* **Tested SSL certificate functionality** to ensure secure HTTPS access to the site.
* Verified that both IP address and domain load the project.

### 7. README File

* Created a step-by-step README to explain the setup process.
* Documented technologies used, live preview, and all steps clearly.

### 8. Git Pushing

* Initialized a Git repository.
* Added and committed project files.
* Pushed code to a remote repository for version control and sharing.

## 👨‍💻 Author

**Karabo Malatji**
Cloud Engineering Student, AltSchool of Engineering

