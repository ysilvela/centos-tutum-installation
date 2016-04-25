# centos-tutum-installation
HowTo Install CentOs and manage it by tutum

1. First, you need to download the iso file from centos page. Visit https://www.centos.org/download/ and select the minimal ISO distribution and download it from a near site.
2. If you are using Windows, you need Rufus to write the ISO to a USB. Please download rufus from https://rufus.akeo.ie/ and install it.
3. Write the iso file to the usb (You need 4GB usb space) and reboot.
4. Install CentOS minimal ISO
5. Login to your new system
6. Verify that you have ssh enabled and you can access from other external system. Install nano viewer with 'yum install nano'
7. Configure a static ip. You need static ip ir order to configure the router or firewall. http://ask.xmodulo.com/configure-static-ip-address-centos7.html
8. Enable your public RSA key for SSH. Copy your public file into .ssh profile folder
9. Go to cloud.docker.com and bring you own node
10. Paste the curl into you new server

To configure a GIT server please refer to https://github.com/ysilvela/git-create-distribution-server-repository
