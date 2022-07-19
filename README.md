# Amazon Linux 2022 - In Preview

**Welcome to Amazon Linux 2022!**

[Amazon Linux 2022](https://aws.amazon.com/linux/amazon-linux-2022) is the next generation of Amazon Linux from [Amazon Web Services](https://aws.amazon.com/) (AWS). It provides a stable, and high-performance execution environment to develop and run cloud applications. With Amazon Linux 2022, you get an application environment that offers long term support with access to the latest innovations in Linux. Using Fedora as the upstream, AL2022 is a stable distribution that has gone through extensive testing to offer package stability and is maintained and managed with all necessary security updates. Amazon Linux 2022 is provided at no additional charge.

**Quick links**
- [Learn how to get started with Amazon Linux 2022](https://github.com/amazonlinux/amazon-linux-2022#how-to-get-started)
- [Review Amazon Linux 2022 documentation](https://docs.aws.amazon.com/linux/al2022/ug/)
- [Review Amazon Linux 2022 FAQs](https://aws.amazon.com/linux/amazon-linux-2022/faqs/)
- [Look at our roadmap to learn of the upcoming features](https://github.com/amazonlinux/amazon-linux-2022/projects/1)
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20211118.0.md) for the AMI released on 2021-11-22
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20211206.0.md) for the AMI released on 2021-12-06
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20211214.0.md) for the AMI released on 2021-12-14
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220105.0.md) for the AMI released on 2022-01-05
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220202.0.md) for the AMI released on 2022-02-07
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220210.0.md) for the AMI released on 2022-02-10
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220308.0.md) for the AMI released on 2022-03-08
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220315.0.md) for the AMI released on 2022-03-15
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220419.0.md) for the AMI released on 2022-04-19
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220504.1.md) for the AMI released on 2022-05-04
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220531.0.md) for the AMI released on 2022-05-31
- [Review the Release Notes](https://github.com/amazonlinux/amazon-linux-2022/blob/main/Release-Notes-Amazon-Linux-2022.0.20220628.0.md) for the AMI released on 2022-06-28


## Contact Us
If you find a security issue, please [contact our security team](https://github.com/amazonlinux/amazon-linux-2022/security/policy) rather than opening an issue.

We use GitHub issues to gather feedback about Amazon Linux 2022, track bug reports and feature requests. You can look at existing [issues](https://github.com/amazonlinux/amazon-linux-2022/issues) to see whether your concern is already known. If not, you can select from a few templates. Contact us with a new issue [here](https://github.com/amazonlinux/amazon-linux-2022/issues/new/choose). We will respond to your request within 48 business hours.

If you just have questions about Amazon Linux 2022, please feel free to start or join a [discussion](https://github.com/amazonlinux/amazon-linux-2022/discussions). Feedback on Amazon Linux 2022 can also be provided through your designated AWS representative or [AWS re:Post](https://repost.aws/). 


## Architectures
Our supported architectures include *x86_64* and *aarch64* (written as arm64 in some contexts). Amazon Linux 2022 does not ship any i686 packages for runtime compatibility with 32bit x86 code.

Please note: Amazon Linux 2022 *does not* support A1 instances. Only instances based on Graviton2 and later generation processors are supported.

## Upcoming changes
During the preview, we're actively seeking your feedback about what to add to and modify in Amazon Linux 2022. We also have a clear [roadmap](https://github.com/amazonlinux/amazon-linux-2022/projects/1) moving forward. If you would like to request a feature, please let us know by submitting a [request](https://github.com/amazonlinux/amazon-linux-2022/issues/new/choose).




## Benefits of Amazon Linux 2022

**Optimized for AWS:**
Amazon Linux 2022 is optimized for Amazon EC2, comes well integrated with latest AWS features, and offers an integrated experience with many of AWS-specific tools.

**Flexible and consistent update experience:**
Based on Fedora, AL2022 provides frequent and flexible quarterly updates. AL2022 also locks to a specific version of the Amazon Linux package repository, giving you control over how and when you absorb updates.

**Easy to plan and manage operating system lifecycle:**
New Amazon Linux major versions will be available every two years and each major version, including AL2022, will come with five years of long term support. 

**High security standard:**
AL2022 has a high security standard and comes with SELinux enabled and enforced by default to help you meet your compliance needs. AL2022 also allows you to set security policies at boot time.

## Notable features of Amazon Linux 2022
**Predictable two-year major release cycle and long-term support:**
Starting with AL2022, a new major version of Amazon Linux releases every two years and comes with five years of long-term support, with each release consisting of standard support (2 years), and maintenance (3 years). This support commitment gives customers the stability they need to manage long project lifecycles.

**Frequent and flexible updates:**
During the standard support phase (2 years), the release receives quarterly minor version updates to provide customers with security updates, bug fixes, and new features. Based on Fedora, this also gives customers access to a wide variety of modern software packages.

**Improved security posture:**
AL2022 includes pre-configured security policies that make it easy for customers to implement common industry guidelines. These policies can be configured at launch time or run time, including setting the system crypto policy to FUTURE or LEGACY, locking down SELinux, and setting SELinux to enforcing or permissive mode.

**Repository locking:**
Amazon Linux 2022 gives customers control over how and when they choose updates and provides the ability to lock major and minor versions as well as specific versions of your Amazon Linux repository. This enables you to ensure consistency of package versions and updates across your environment.

**Kernel hardening:**
Many hardening features are enabled by default. This includes secure-boot related features such as kernel module signing, and making the kernel lockdown feature available.

**Kernel Live Patching:**
Amazon Linux 2022 includes kernel live patching functionality. This enables you to patch critical and important security vulnerabilities in the Linux kernel without reboot or downtime. [Not available in Preview]

## How to get started
### Launching Amazon Linux 2022 via EC2 Management Console
To launch an Amazon Linux 2022 instance from the EC2 Management Console, navigate to **EC2 Dashboard —> Images —> AMIs**, then select **Public images**, and use the search term "al2022-ami". Make sure that *amazon* is listed in the Owner alias column. Select the image from the list, click on the **Launch instance from image** button and follow the instructions.


### Launching latest Amazon Linux 2022 AMI via CloudFormation
To launch the latest Amazon Linux 2022 AMI using CloudFormation, you can use the following template:

```# Use public Systems Manager Parameter
Parameters:
  LatestAmiId:
    Type: 'AWS::SSM::Parameter::Value<AWS::EC2::Image::Id>'
    Default: '/aws/service/ami-amazon-linux-latest/al2022-ami-kernel-5.15-arm64'

Resources:
 Instance:
    Type: 'AWS::EC2::Instance'
    Properties:
      ImageId: !Ref LatestAmiId
```

Make sure to replace the AMI alias section if needed. The following aliases are available:
- *al2022-ami-kernel-5.15-arm64* for arm64 architecture
- *al2022-ami-minimal-kernel-5.15-arm64* for arm64 architecture (minimal AMI)
- *al2022-ami-kernel-5.15-x86_64* for x86_64 architecture
- *al2022-ami-minimal-kernel-5.15-x86_64* for x86_64 architecture (minimal AMI)

### Launching Amazon Linux 2022 using specific AMI ID
You can launch specific Amazon Linux 2022 AMI using its AMI ID. You can determine the needed Amazon Linux 2022 AMI ID by looking at the AMI list in the EC2 Management Console or by using SSM. If you are using SSM, please refer to this [article](https://aws.amazon.com/blogs/compute/query-for-the-latest-amazon-linux-ami-ids-using-aws-systems-manager-parameter-store/) for details and make sure to indicate the AMI aliases from the section above.

### Using the Amazon Linux container image<a name="install-docker"></a>

The Amazon Linux container image is built from the same software components that are included in the Amazon Linux AMI\. It's available for use in any environment as a base image for Docker workloads\. If you're using the Amazon Linux AMI for applications in [Amazon Elastic Compute Cloud](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/) \(Amazon EC2\), you can containerize your applications with the Amazon Linux container image\.

Use the Amazon Linux container image in your local development environment and then push your application to AWS using [Amazon Elastic Container Service](https://docs.aws.amazon.com/AmazonECS/latest/userguide/) \(Amazon ECS\)\. For more information, see [Using Amazon ECR images with Amazon ECS](https://docs.aws.amazon.com/AmazonECR/latest/userguide/ECR_on_ECS.html) in the *Amazon Elastic Container Registry User Guide*\.

The Amazon Linux container image is available on Amazon ECR Public\. Support for the Amazon Linux container image can be found by visiting the [AWS developer forums](https://forums.aws.amazon.com/forum.jspa?forumID=228)\.

**To pull the Amazon Linux container image from Amazon ECR Public**

1. Authenticate your Docker client to the Amazon Linux Public registry\. Authentication tokens are valid for 12 hours\. For more information, see [Private registry authentication](https://docs.aws.amazon.com/AmazonECR/latest/userguide/registry_auth.html) in the *Amazon Elastic Container Registry User Guide*\.
**Note**  
The get\-login\-password command is supported using the latest version of AWS CLI version 2. For more information, see [Installing the AWS Command Line Interface](https://alpha-docs-aws.amazon.com/cli/latest/userguide/getting-started-install.html) in the *AWS Command Line Interface User Guide*\.

   ```
   $ aws ecr-public get-login-password --region us-east-1 | docker login --username AWS --password-stdin public.ecr.aws
   ```

   The output is as follows:

   ```
   Login succeeded
   ```

1. Pull the Amazon Linux container image using the docker pull command\. To view the Amazon Linux container image on the Amazon ECR Public Gallery, see [Amazon ECR Public Gallery \- amazonlinux](https://gallery.ecr.aws/amazonlinux/amazonlinux)\.
**Note**  
To get the latest version of the container image of Amazon Linux 2022, use the tag :2022\. To get a specific version of the container image, you need to use the tag listed in the [Amazon ECR Public Gallery \-amazonlinux](https://gallery.ecr.aws/amazonlinux/amazonlinux), for example :2022\.0\.20211222\.0\. The following examples use the tag :2022 and pull the most recent available container image of Amazon Linux 2022\.

   ```
   # docker pull public.ecr.aws/amazonlinux/amazonlinux:2022
   ```

1. \(Optional\) Run the container locally\.

   ```
   # docker run -it public.ecr.aws/amazonlinux/amazonlinux:2022 /bin/bash
   ```
   **Note**
   If *seccomp* is enabled, you might get an *EPERM* error when using Amazon Linux container images\. To run a container without the default *seccomp* profile, add the following option to the docker command\.

   ```
   --security-opt seccomp=unconfined
   ```

   This is the updated command\.

   ```
   docker run -it --security-opt seccomp=unconfined public.ecr.aws/amazonlinux/amazonlinux:2022 /bin/bash
   ```

**To pull the Amazon Linux container image from Docker Hub**

1. Pull the Amazon Linux container image using the docker pull command\.

   ```
   # docker pull amazonlinux:2022
   ```

1. \(Optional\) Run the container locally\.

   ```
   # docker run -it amazonlinux:2022 /bin/bash
   ```
