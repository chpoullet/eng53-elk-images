# ELK stack images (Packer)

This repository contains the configured Berksfile and packer.json files to create the images for the ELK stack.

### To retrieve the cookbooks, run:

```
berks vendor cookbooks
```

### To create the images, run in the specific directory:

```
packer build packer.json
```

![ELK stack](https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto/gigs/114190066/original/d1ae46a27bd3de1dbafa0521c5943ae2ebd7ea66/setup-elk-stack-on-aws-or-google-cloud.png)
